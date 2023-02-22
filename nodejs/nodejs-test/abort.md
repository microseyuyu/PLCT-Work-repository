# abort

tools/test.py test/abort

```
[root@openEuler-riscv64 node-v16.14.2]# tools/test.py test/abort
=== release test-abort-backtrace ===                   
Path: abort/test-abort-backtrace
node:assert:170
  throw err;
  ^

AssertionError [ERR_ASSERTION]: Some frames should include the binary name:
 1: 0x3fe27bea7c node::Abort() [/usr/lib64/libnode.so.93]
 2: 0x3fe2843c78  [/usr/lib64/libnode.so.93]
 3: 0x3fe2eb6ac4  [/usr/lib64/libnode.so.93]
 4: 0x3fe2eb7624 v8::internal::Builtin_HandleApiCall(int, unsigned long*, v8::internal::Isolate*) [/usr/lib64/libnode.so.93]
 5: 0x3fe2a66adc  [/usr/lib64/libnode.so.93]

    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/abort/test-abort-backtrace.js:24:16)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  generatedMessage: false,
  code: 'ERR_ASSERTION',
  actual: undefined,
  expected: undefined,
  operator: 'fail'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/abort/test-abort-backtrace.js
[00:43|% 100|+   9|-   1]: Done  
```

