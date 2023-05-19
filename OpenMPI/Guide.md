# OpenMPI 运行指南

## 安装

OpenMPI 软件包已经包含在 openEuler RISC-V 23.03 源内，可使用 `dnf` 直接安装

```
dnf install openmpi openmpi-devel
```

## 运行实例代码

[hello.c](./hello.c) 是一个包含在 OpenMPI 项目中的官方示例代码。

编译源代码

```
/usr/lib64/openmpi/bin/mpicc hello.c
```

运行输出文件

```
/usr/lib64/openmpi/bin/mpirun --allow-run-as-root -t --oversubscribe a.out
```

如果输出类似

```
Hello, world. I am 0 of 1, (OpenMPI v4.1.4, package: Open MPI abuild@oerv-obs-worker
```

则 OpenMPI 运行正常
