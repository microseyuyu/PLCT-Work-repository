# benchmark

tools/test.py test/benchmark

```
[root@openEuler-riscv64 node-v16.14.2]# tools/test.py test/benchmark
=== release test-benchmark-napi ===                            
Path: benchmark/test-benchmark-napi
/root/rpmbuild/BUILD/node-v16.14.2/benchmark/napi/function_args/index.js: V8 Binding failed to load
misc/function_call.js Binding failed to load
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/addon'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/benchmark/napi/ref/index.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/benchmark/napi/ref/index.js:3:15)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [ '/root/rpmbuild/BUILD/node-v16.14.2/benchmark/napi/ref/index.js' ]
}
node:assert:123
  throw new AssertionError(obj);
  ^

AssertionError [ERR_ASSERTION]: Expected values to be strictly equal:

1 !== 0

    at ChildProcess.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/common/benchmark.js:28:12)
    at ChildProcess.emit (node:events:526:28)
    at Process.ChildProcess._handle.onexit (node:internal/child_process:291:12) {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: 1,
  expected: 0,
  operator: 'strictEqual'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/benchmark/test-benchmark-napi.js
[20:23|% 100|+  33|-   1]: Done
```

