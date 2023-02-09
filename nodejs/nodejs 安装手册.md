# nodejs 安装手册

## 基本信息

系统：openEuler 22.03 RISC-V V2

nodejs 版本：1:16.14.2-1.oe2203

qemu 版本：QEMU emulator version 7.2.0

## 通过 DNF 安装 nodejs

输入以下之指令安装 nodejs：

```
dnf install nodejs
```

当系统询问```Is this ok [y/N]```时，输入 y ，回车以安装。

## 测试 nodejs 是否安装成功

通过查看版本来检测 nodejs 是否安装成功，输入以下指令查看：

```
node -v
```

输出结果：

```
[root@openEuler-riscv64 ~]# node -v
v16.14.2
```

