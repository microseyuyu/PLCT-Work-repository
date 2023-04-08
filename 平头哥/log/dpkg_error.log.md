# dpkg_error.log

```
(Reading database ... 57898 files and directories currently installed.)
Preparing to unpack gcc-13_13-20230320-1_riscv64.deb ...
Unpacking gcc-13 (13-20230320-1) ...
dpkg-deb (subprocess): decompressing archive 'gcc-13_13-20230320-1_riscv64.deb' (size=65007844) member 'data.tar': lzma error: compressed data is corrupt
dpkg-deb: error: <decompress> subprocess returned error exit status 2
dpkg: error processing archive gcc-13_13-20230320-1_riscv64.deb (--install):
 cannot copy extracted data for './usr/libexec/gcc/riscv64-linux-gnu/13/lto1' to '/usr/libexec/gcc/riscv64-linux-gnu/13/lto1.dpkg-new': unexpected end of file or stream
Errors were encountered while processing:
 gcc-13_13-20230320-1_riscv64.deb
```