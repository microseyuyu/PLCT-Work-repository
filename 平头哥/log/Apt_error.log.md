# Apt_error.log

```
WARNING: apt does not have a stable CLI interface. Use with caution in scripts.

Reading package lists...
Building dependency tree...
Reading state information...
The following additional packages will be installed:
  gcc-13
Suggested packages:
  gcc-multilib autoconf automake libtool flex bison gdb gcc-doc gcc-13-doc
  gcc-13-locales
The following NEW packages will be installed:
  gcc gcc-13
0 upgraded, 2 newly installed, 0 to remove and 0 not upgraded.
Need to get 0 B/65.0 MB of archives.
After this operation, 271 MB of additional disk space will be used.
(Reading database ... 
(Reading database ... 5%
(Reading database ... 10%
(Reading database ... 15%
(Reading database ... 20%
(Reading database ... 25%
(Reading database ... 30%
(Reading database ... 35%
(Reading database ... 40%
(Reading database ... 45%
(Reading database ... 50%
(Reading database ... 55%
(Reading database ... 60%
(Reading database ... 65%
(Reading database ... 70%
(Reading database ... 75%
(Reading database ... 80%
(Reading database ... 85%
(Reading database ... 90%
(Reading database ... 95%
(Reading database ... 100%
(Reading database ... 57867 files and directories currently installed.)
Preparing to unpack .../gcc-13_13-20230320-1_riscv64.deb ...
Unpacking gcc-13 (13-20230320-1) ...
dpkg-deb (subprocess): decompressing archive '/var/cache/apt/archives/gcc-13_13-20230320-1_riscv64.deb' (size=65007844) member 'data.tar': lzma error: compressed data is corrupt
dpkg-deb: error: <decompress> subprocess returned error exit status 2
dpkg: error processing archive /var/cache/apt/archives/gcc-13_13-20230320-1_riscv64.deb (--unpack):
 cannot copy extracted data for './usr/bin/riscv64-linux-gnu-lto-dump-13' to '/usr/bin/riscv64-linux-gnu-lto-dump-13.dpkg-new': unexpected end of file or stream
Selecting previously unselected package gcc.
Preparing to unpack .../gcc_4%3a13.0.1-1revyos1_riscv64.deb ...
Unpacking gcc (4:13.0.1-1revyos1) ...
Errors were encountered while processing:
 /var/cache/apt/archives/gcc-13_13-20230320-1_riscv64.deb
E: Sub-process /usr/bin/dpkg returned an error code (1)
```

