# embedding

tools/test.py test/embedding

```
[root@openEuler-riscv64 node-v16.14.2]# tools/test.py test/embedding
=== release test-embedding ===                   
Path: embedding/test-embedding
/root/rpmbuild/BUILD/node-v16.14.2/test/embedding/test-embedding.js:18
    .stdout.toString().trim(),
           ^

TypeError: Cannot read properties of null (reading 'toString')
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/embedding/test-embedding.js:18:12)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/embedding/test-embedding.js
[00:02|% 100|+   0|-   1]: Done   
```

