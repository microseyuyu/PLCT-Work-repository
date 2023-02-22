# doctool

tools/test.py test/doctool

```
[root@openEuler-riscv64 node-v16.14.2]# tools/test.py test/doctool
=== release test-doctool-html ===                   
Path: doctool/test-doctool-html
node:internal/errors:464
    ErrorCaptureStackTrace(err);
    ^

Error [ERR_MODULE_NOT_FOUND]: Cannot find package 'highlight.js' imported from /root/rpmbuild/BUILD/node-v16.14.2/tools/doc/html.mjs
    at new NodeError (node:internal/errors:371:5)
    at packageResolve (node:internal/modules/esm/resolve:932:9)
    at moduleResolve (node:internal/modules/esm/resolve:978:18)
    at defaultResolve (node:internal/modules/esm/resolve:1080:11)
    at ESMLoader.resolve (node:internal/modules/esm/loader:530:30)
    at ESMLoader.getModuleJob (node:internal/modules/esm/loader:251:18)
    at ModuleWrap.<anonymous> (node:internal/modules/esm/module_job:79:40)
    at link (node:internal/modules/esm/module_job:78:36) {
  code: 'ERR_MODULE_NOT_FOUND'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/doctool/test-doctool-html.mjs
=== release test-doctool-json ===                   
Path: doctool/test-doctool-json
node:internal/errors:464
    ErrorCaptureStackTrace(err);
    ^

Error [ERR_MODULE_NOT_FOUND]: Cannot find package 'remark-html' imported from /root/rpmbuild/BUILD/node-v16.14.2/tools/doc/json.mjs
    at new NodeError (node:internal/errors:371:5)
    at packageResolve (node:internal/modules/esm/resolve:932:9)
    at moduleResolve (node:internal/modules/esm/resolve:978:18)
    at defaultResolve (node:internal/modules/esm/resolve:1080:11)
    at ESMLoader.resolve (node:internal/modules/esm/loader:530:30)
    at ESMLoader.getModuleJob (node:internal/modules/esm/loader:251:18)
    at ModuleWrap.<anonymous> (node:internal/modules/esm/module_job:79:40)
    at link (node:internal/modules/esm/module_job:78:36) {
  code: 'ERR_MODULE_NOT_FOUND'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/doctool/test-doctool-json.mjs
=== release test-doctool-versions ===                   
Path: doctool/test-doctool-versions
node:internal/process/esm_loader:94
    internalBinding('errors').triggerUncaughtException(
                              ^

AssertionError [ERR_ASSERTION]: Expected values to be strictly equal:

1 !== 0

    at file:///root/rpmbuild/BUILD/node-v16.14.2/test/doctool/test-doctool-versions.mjs:40:8
    at ModuleJob.run (node:internal/modules/esm/module_job:197:25)
    at async Promise.all (index 0)
    at async ESMLoader.import (node:internal/modules/esm/loader:337:24)
    at async loadESM (node:internal/process/esm_loader:88:5)
    at async handleMainPromise (node:internal/modules/run_main:61:12) {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: 1,
  expected: 0,
  operator: 'strictEqual'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/doctool/test-doctool-versions.mjs
=== release test-local-md-file-reference-regex ===                   
Path: doctool/test-local-md-file-reference-regex
node:internal/errors:464
    ErrorCaptureStackTrace(err);
    ^

Error [ERR_MODULE_NOT_FOUND]: Cannot find package 'unist-util-visit' imported from /root/rpmbuild/BUILD/node-v16.14.2/tools/doc/markdown.mjs
    at new NodeError (node:internal/errors:371:5)
    at packageResolve (node:internal/modules/esm/resolve:932:9)
    at moduleResolve (node:internal/modules/esm/resolve:978:18)
    at defaultResolve (node:internal/modules/esm/resolve:1080:11)
    at ESMLoader.resolve (node:internal/modules/esm/loader:530:30)
    at ESMLoader.getModuleJob (node:internal/modules/esm/loader:251:18)
    at ModuleWrap.<anonymous> (node:internal/modules/esm/module_job:79:40)
    at link (node:internal/modules/esm/module_job:78:36) {
  code: 'ERR_MODULE_NOT_FOUND'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/doctool/test-local-md-file-reference-regex.mjs
=== release test-make-doc ===                                        
Path: doctool/test-make-doc
node:fs:1392
  handleErrorFromBinding(ctx);
  ^

Error: ENOENT: no such file or directory, scandir '/root/rpmbuild/BUILD/node-v16.14.2/out/doc/api/'
    at Object.readdirSync (node:fs:1392:3)
    at file:///root/rpmbuild/BUILD/node-v16.14.2/test/doctool/test-make-doc.mjs:17:20
    at ModuleJob.run (node:internal/modules/esm/module_job:197:25)
    at async Promise.all (index 0)
    at async ESMLoader.import (node:internal/modules/esm/loader:337:24)
    at async loadESM (node:internal/process/esm_loader:88:5)
    at async handleMainPromise (node:internal/modules/run_main:61:12) {
  errno: -2,
  syscall: 'scandir',
  code: 'ENOENT',
  path: '/root/rpmbuild/BUILD/node-v16.14.2/out/doc/api/'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/doctool/test-make-doc.mjs
[00:34|% 100|+   1|-   5]: Done      
```

