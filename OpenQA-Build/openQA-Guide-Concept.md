# openQA 概念和 Web 端操作讲解

openQA 是一个由 openSUSE 发行版开发的自动化测试平台，使用 OpenCV 和 QEMU 等技术
实现对界面类程序的自动化测试。

## 目录

- Test
- Needle
- Testsuite
- Medium
- API Key

## Test

Test 即测试，是一项对软件功能的检查。openQA 使用 Perl 语言编写测试对虚拟机进行操
作，其存储在 `/var/lib/openqa/share/tests/DISTRI_NAME/tests` 下。

## Needle

Needle 代表着虚拟机的一个状态，作为测试的一个检查点（checkpoint）。Test 在执行一
系列操作后，可以通过将 needle 与当前屏幕/串口等的状态进行匹配来检查当前虚拟机的
状态是否达到了预期。

## Needle 的构成

Needle 中可以包含三种区域

- Regular Area，普通区域：这种区域中的内容将会通过 OpenCV 进行相似度匹配
- OCR Area，文字识别区域：这种区域中的内容将会通过 OpenCV 进行 OCR 之后与预期文
  本检查是否匹配。
- Exclude Area，不关心的区域：这种区域中的内容与 needle 是否匹配成功无关。

同时，needle 的一个区域可以被添加点击坐标，这样在 test 中使用
`assert_and_click()` API 与该 needle 匹配时，若匹配成功会对该区域进行点击。

### Needle 的储存形式

一个 needle 实际上由一个 `png` 图片和 `JSON` 配置文件构成，`png` 文件中包含了屏
幕的截图，而 `JSON` 文件则包含要匹配的区域的信息。

### 创建/修改 Needle

needle 可以手动编写，但更加方便的方式是从已有的截图中派生。在 openQA Web 界面打
开一个测试，选中其中的一幕截图，点击 `Create new needle` 即可创建新的 needle。
如果新的 needle 名称与其他 needle 相同，则该 needle 会被覆盖。

如果 `Needle based on` 不为 None，则该 needle 会继承所基于 needle 的所有区域。

### Needle 的 Tag

在使用相关 API 匹配 needle 时，向 API 传入的并非 needle 名称，而是 needle 对应的
tag。而多个 needle 可以具有同一个 tag，使得当使用该 tag 进行匹配时只需有一个
包含该 tag 的 needle 匹配成功，该次匹配即成功。

## Test Suite（或 Testsuite）

一个 testsuite 是一系列 test 的集合，其规定了测试的内容和各个 test 的运行顺序。

### 配置 Test Suite

在 openQA Web 界面的对应选项卡中可以很容易得创建新的 Testsuite，其中 Settings 指
定了此 Test Suite 中测试运行时需要设置的测试变量，编写的 test 可以根据它们更改自
己的行为。

常用的测试变量包括

- `DESKTOP`: `gnome`, `xfce` 等，影响 X11 相关测试的行为。
- `HDDSIZEGB`: 硬盘的大小
- `YAML_SCHEDULE`: 该 testsuite 使用的 YAML Schedule 文件。

### Schedule 文件

通常存放在 `/var/lib/opeqa/share/tests/DISTRI_NAME/schedule` 下，其中使用 YAML
格式描述了需要运行的 test，在该 Test Suite 被执行时会按顺序执行。

其格式类似
```YAML
name: SCHEDULE_NAME
schedule:
  - xxx/xxx
  - xxx/xxx
```

## Medium

Medium 即介质，给出了操作系统的详细种类。其包括以下内容

- `Distri`: 该 medium 包含的发行版
- `Version`: 该 medium 的版本
- `Arch`: 该 medium 的目标架构
- `Flavor`: 该 medium 的“口味”，即包含的软件套件类型（`KDE`/`xfce`，`netinst`/
  `dvd` 等）

Medium 可以在 openQA Web 界面创建和修改。

## Machine

Machine 即机器，给出了一种运行操作系统的虚拟化配置。其包括

- `Name`
- `Backend`: 使用的虚拟化后端，一般为 `qemu`
- `Settings`: 细化的配置内容

`Settings` 的配置项不完全列表包括：

- `APPEND`, `BIOS`, `KERNEL`, `QEMURAM`, `QEMUCPU`, `QEMUCPUS`: 对应 QEMU 的同名
  /同义选项。
- `HDD_n`: 虚拟机第 n 个磁盘的镜像文件
- `TIMEOUT_SCALE`: 所有的测试在此 machine 运行时，timeout 会乘上该因子
- `WORKER_CLASS`: 该 machine 所属的 worker 类别
- `password`: 默认密码，可能被一些库使用
- `NUMDISKS`: 磁盘数

## Job Group

Job Group 被用来自动化测试任务的创建，其本身可以在 openQA Web 界面创建。

Job Group 中需要使用一个 job template 控制测试人物的创建，其内容大致如下：

```YAML
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
      - testsuite_a
```

`defaults` 中指定了运行该测试使用的 machine，其需要和对应的 machine name 一致。
`products` 中指定了产品与 medium 的对应关系，scenarios 指定了某一个产品在某种配
置下需运行的 testsuite。

## API Key

openQA 的命令行管理工具 `openqa-cli` 在与 openQA 实例进行交互时使用 API Key 进行
身份验证，所以在配置 `openqa-cli` 时必须从 `Manage API Keys` 中生成一个 API Key
。
