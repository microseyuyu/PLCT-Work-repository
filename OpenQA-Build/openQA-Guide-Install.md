# openQA 教程

## 安装

参考 [吕老师的笔记](https://gitee.com/lvxiaoqian/memo/blob/master/deploy-openQA-for-riscv.md)
。

### 安装 openSUSE

openQA 为 openSUSE 团队开发，在 openSUSE 发行版上支持较为完善。首先安装
openSUSE Tumbleweed 版本。

### 安装 openQA 本体

openSUSE 上包管理器为 `zypper`，使用以下命令安装 openQA 本体：

```shell
zypper in openQA-bootstrap
cd /usr/share/openqa/script
./openqa-bootstrap
```

该脚本会默认下载 openSUSE 的 needles，此处我们不需要，Ctrl-C 终止脚本后
修改 `fetchneedles` 脚本如下以下载 openEuler 已有的 needles。

```
: "${dist_name:=${dist:-"openEuler"}}" # the display name, for the help message
: "${dist:="openeuler"}"
: "${giturl:="https://gitee.com/lvxiaoqian/os-autoinst-distri-openeuler.git"}"
: "${branch:="master"}"
: "${email:="openqa@$HOST"}"
: "${username:="openQA web UI"}"
: "${product:="$dist"}"

: "${git_lfs:="0"}"
: "${needles_separate:="1"}"
: "${needles_giturl:="https://gitee.com/lvxiaoqian/os-autoinst-needles-openeuler.git"}"
: "${needles_branch:="master"}"
```

再次运行 `openqa-bootstrap` 脚本。

### 下载 openEuler RISC-V 测试

```
cd /var/lib/openqa/share/tests
mkdir openeuler && cd openeuler
git clone -b master https://gitee.com/lvxiaoqian/os-autoinst-distri-openeuler.git --depth=1
cd products/openeuler
mkdir needles && cd needles
git clone -b master https://gitee.com/lvxiaoqian/os-autoinst-needles-openeuler.git --depth=1
```

### 对 openQA 应用补丁

为支持 RISC-V 64 架构， 对 openQA 应用（的组件 `os-autoinst`）补丁，否则会出现对
QEMU 的调用包含无效参数等情况。

[补丁](https://gitee.com/lvxiaoqian/os-autoinst/commit/c2c580265330c7bab82e2efe61ebd8612671a0eb.patch)
需要手动下载，Gitee 不允许未登录状态下直接下载文件。

使用 `zypper` 安装 `patch`（`zypper in patch`），将补丁拷贝到
`/usr/lib/os-autoinst`。应用补丁：

```shell
patch -p1 < PATH/TO/PATCH
```

此时 openQA Web 前端已经部署完成，可以访问 `http://localhost/` 查看效果，默认使
用 `Fake` 方式登陆，点击 `Login` 可以直接以管理员身份登陆。

### 配置 openQA RISC-V QEMU Worker

openQA 使用 QEMU 作为虚拟化后端，使用 `zypper` 安装之。

```shell
zypper in qemu-extra
```

修改 `/etc/openqa/workers.ini`，添加以下内容：

```INI
[NUM]
WORKER_CLASS=qemu_riscv64
QEMU_NO_KVM=1
QEMUCPU=rv64
QEMUMACHINE=virt,usb=off
```

其中 `NUM` 为 worker 编号。

启动 worker

```shell
systemctl enable --now openqa-worker@NUM
```

刷新 openQA Web 端，即可在 Worker 页面看到新增的 worker。

### 配置 Medium 和 Machines

这两个选项卡和 worker 选项卡同级。

Medium 配置为：

- Distri: openeuler
- Version: 22.03
- Flavor: v2
- Arch: riscv64

Machines 配置为：

- Name: RISCV64_VM
- Backend: qemu
- Setting:

```
APPEND=root=/dev/vda1
BIOS=none
CDMODEL=virtio-blk-device
HDDMODEL=virtio-blk-device
HDD_1=openEuler-22.03-V2-xfce-qemu-testing.qcow2
KERNEL=fw_payload_oe_qemuvirt.elf
NOAUTOLOGIN=1
NUMDISKS=1
PASSWORD=openEuler12#$
QEMU=riscv64
QEMUCPU=rv64
QEMUCPUS=4
QEMUMACHINE=virt,accel=kvm,usb=off,dump-guest-core=off,gic-version=3
QEMURAM=4096
ROOTONLY=1
SERIALDEV=ttyS0
TIMEOUT_SCALE=2
VGA=std
VIRTIO_CONSOLE=1
WORKER_CLASS=qemu_riscv64
```

对 Setting 的解释：

- `APPEND`: 对应 QEMU `-append` 参数，给内核的附加参数
- `QEMU`: 使用的 QEMU 模拟器，即使用 `qemu-system-${QEMU}`
- `HDD_1`: 指定使用的虚拟磁盘，该文件需放在 `/var/lib/openqa/factory/hdd`
  目录下
- `KERNEL`: 指定要引导的内核（此处为固件，`BIOS=none` 禁用了默认固件），该文件
  必须在 `/var/lib/openqa/factory/other` 目录下

### 创建 Testsuite, 配置 Job Groups 并触发测试

Test Suites 选项卡和 Worker, Medium, Machine 同级。创建名为 `install_testsuite`
的 testsuite，Settings 为

```
DESKTOP=xfce
HDDSIZEGB=100
INSTALL=1
NICTYPE=user
YAML_SCHEDULE=schedule/install_testsuite.yaml
```

其中 `YAML_SCHEDULE` 指定了通过 schedule 配置测试内容。该配置使用的的 schedule
文件（YAML 格式）位于 `/var/lib/openqa/share/tests/openeuler/schedule/install_testsuite.yaml`。

创建 Job Group，编辑 Job Template，该文件为 YAML 格式，内容类似：

```yaml
defaults:
  riscv64:
    machine: RISCV64_VM
    priority: 50

products:
  openeuler-v2-riscv64-22.03:
     distri: openeuler
     flavor: v2
     version: 22.03
scenarios:
  riscv64:
     openeuler-v2-riscv64-22.03:
        - install_testsuite
```

字段解释：

- `machine`: 运行 Job 的 Machine，对应配置 Machine 时的 `Name` 字段
- `products`: 测试的 Medium，配置 Medium 时的 `Distri` 字段

配置 `openqa-cli`。从 openQA Web 端 `Manage API Keys` 生成 secret/key 对。编辑
`/etc/openqa/client.ini`，在其中填入

```
[localhost]
key = YOUR_API_KEY
secret = YOUR_API_SECRET
```

通过 `openqa-cli` 触发测试：

```
openqa-cli api -X POST isos async=0 DISTRI=openeuler FLAVOR=v2 ARCH=riscv64 VERSION=22.03
```

### 配置 OAuth2 验证

默认的 openQA Web 使用 Fake 验证，该验证方式不需要密码，适用于测试时。当 openQA
实例暴露在公网下时会造成重大的安全隐患。可以通过接入 GitHub 的 OAuth2 服务来进行
用户认证及鉴权。

在 GitHub Settings/Developer Settings 中找到 OAuth Apps, 新建一 OAuth 应用。
Authorization callback URL 设置为 `DOMAIN/login`，其中 `DOMAIN` 为 openQA 实例的
域名。注意 Callback URL 和 openQA 实例在调用接口时给出的 callback URL 必须一致，
如果带有“callback URL 不一致”的错误请检查该之（包括协议种类（HTTP/HTTPS）也必须
一致。）

为该 OAuth App 生成 key/secret 对。

编辑 `/etc/openqa/openqa.ini`，内容如下

```ini
[auth]
method = OAuth2		# 修改，大小写敏感，原为 method = Fake

[oauth2]
provider = github
key = YOUR_KEY
secret = YOUR_SECRET
```

更改配置后重启 openQA Web 端

```shell
systemctl restart openqa-webui
```

此时 OAuth2 配置已经生效，可以通过 GitHub 账号验证并登陆 openQA 实例。然而新登陆
的账号仅有 User 权限，这是因为 openQA 会对第一个登陆的用户赋予 Administrator
权限，而我们的第一个账号是使用 Fake 模式时创建的 Demo 用户。为了提权，使用
OAuth2 登陆 openQA 后暂时关闭 OAuth2 验证，并再次使用 Fake 模式下的 Demo 用户为
新创建的用户提权，再重新配置 OAuth2 验证。完成后在新的用户下将 Demo 用户的权限设
置为 User。

---
至此，openQA 服务已经部署完成。
