# DDE 桌面环境测试

在 openEuler QEMU 上测试 DDE 桌面。

## 安装

使用 `dnf install dde` 安装 DDE 桌面环境，安装成功。
[日志见此](openEuler-2303-0404-install.log)

## 启动

重启虚拟机后 lightdm 会自动启动，待登陆界面初始化完成后使用 root 账户及
对应密码登陆，提示选择 Session 时，点击 New Session 或 Continue 都会导致
崩溃（收到 11 号信号，SIGSEGV）

dmesg [见此](openEuler-2303-0404-dmesg.log)。
