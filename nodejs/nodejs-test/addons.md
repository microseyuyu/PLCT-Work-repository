# addons

tools/test.py test/addons

```
[root@openEuler-riscv64 node-v16.14.2]# tools/test.py test/addons
=== release test ===                        
Path: addons/errno-exception/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/errno-exception/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/errno-exception/test.js:9:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/errno-exception/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/errno-exception/test.js
=== release test ===                   
Path: addons/hello-world/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/hello-world/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.resolve (node:internal/modules/cjs/helpers:108:19)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/hello-world/test.js:4:29)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/hello-world/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/hello-world/test.js
=== release test ===                   
Path: addons/dlopen-ping-pong/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/dlopen-ping-pong/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.resolve (node:internal/modules/cjs/helpers:108:19)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/dlopen-ping-pong/test.js:11:29)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/dlopen-ping-pong/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/dlopen-ping-pong/test.js
=== release test ===                   
Path: addons/no-addons/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/no-addons/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.resolve (node:internal/modules/cjs/helpers:108:19)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/no-addons/test.js:8:29)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/no-addons/test.js'
  ]
}
Command: out/Release/node --no-addons /root/rpmbuild/BUILD/node-v16.14.2/test/addons/no-addons/test.js
=== release test ===                   
Path: addons/worker-addon/test
spawning test worker
node:internal/event_target:916
  process.nextTick(() => { throw err; });
                           ^
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/worker-addon/build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/[worker eval]
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at [worker eval]:1:1
    at Script.runInThisContext (node:vm:129:12)
    at Object.runInThisContext (node:vm:305:38)
    at node:internal/process/execution:76:19
    at [worker eval]-wrapper:6:22
    at evalScript (node:internal/process/execution:75:60)
Emitted 'error' event on Worker instance at:
    at Worker.[kOnErrorMessage] (node:internal/worker:289:10)
    at Worker.[kOnMessage] (node:internal/worker:300:37)
    at MessagePort.<anonymous> (node:internal/worker:201:57)
    at MessagePort.[nodejs.internal.kHybridDispatch] (node:internal/event_target:647:20)
    at MessagePort.exports.emitMessage (node:internal/per_context/messageport:23:28) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [ '/root/rpmbuild/BUILD/node-v16.14.2/[worker eval]' ]
}
node:assert:123
  throw new AssertionError(obj);
  ^

AssertionError [ERR_ASSERTION]: Expected values to be strictly equal:
+ actual - expected

+ '\n' +
+   'node:internal/event_target:916\n' +
+   '  process.nextTick(() => { throw err; });\n' +
+   '                           ^\n' +
+   'node:internal/modules/cjs/loader:936\n' +
+   '  throw err;\n' +
+   '  ^\n' +
+   '\n' +
+   "Error: Cannot find module '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/worker-addon/build/Release/binding'\n" +
+   'Require stack:\n' +
+   '- /root/rpmbuild/BUILD/node-v16.14.2/[worker eval]\n' +
+   '    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)\n' +
+   '    at Function.Module._load (node:internal/modules/cjs/loader:778:27)\n' +
+   '    at Module.require (node:internal/modules/cjs/loader:1005:19)\n' +
+   '    at require (node:internal/modules/cjs/helpers:102:18)\n' +
+   '    at [worker eval]:1:1\n' +
+   '    at Script.runInThisContext (node:vm:129:12)\n' +
+   '    at Object.runInThisContext (node:vm:305:38)\n' +
+   '    at node:internal/process/execution:76:19\n' +
+   '    at [worker eval]-wrapper:6:22\n' +
+   '    at evalScript (node:internal/process/execution:75:60)\n' +
+   "Emitted 'error' event on Worker instance at:\n" +
+   '    at Worker.[kOnErrorMessage] (node:internal/worker:289:10)\n' +
+   '    at Worker.[kOnMessage] (node:internal/worker:300:37)\n' +
+   '    at MessagePort.<anonymous> (node:internal/worker:201:57)\n' +
+   '    at MessagePort.[nodejs.internal.kHybridDispatch] (node:internal/event_target:647:20)\n' +
+   '    at MessagePort.exports.emitMessage (node:internal/per_context/messageport:23:28) {\n' +
+   "  code: 'MODULE_NOT_FOUND',\n" +
+   "  requireStack: [ '/root/rpmbuild/BUILD/node-v16.14.2/[worker eval]' ]\n" +
+   '}\n'
- ''
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/worker-addon/test.js:64:10)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: '\n' +
    'node:internal/event_target:916\n' +
    '  process.nextTick(() => { throw err; });\n' +
    '                           ^\n' +
    'node:internal/modules/cjs/loader:936\n' +
    '  throw err;\n' +
    '  ^\n' +
    '\n' +
    "Error: Cannot find module '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/worker-addon/build/Release/binding'\n" +
    'Require stack:\n' +
    '- /root/rpmbuild/BUILD/node-v16.14.2/[worker eval]\n' +
    '    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)\n' +
    '    at Function.Module._load (node:internal/modules/cjs/loader:778:27)\n' +
    '    at Module.require (node:internal/modules/cjs/loader:1005:19)\n' +
    '    at require (node:internal/modules/cjs/helpers:102:18)\n' +
    '    at [worker eval]:1:1\n' +
    '    at Script.runInThisContext (node:vm:129:12)\n' +
    '    at Object.runInThisContext (node:vm:305:38)\n' +
    '    at node:internal/process/execution:76:19\n' +
    '    at [worker eval]-wrapper:6:22\n' +
    '    at evalScript (node:internal/process/execution:75:60)\n' +
    "Emitted 'error' event on Worker instance at:\n" +
    '    at Worker.[kOnErrorMessage] (node:internal/worker:289:10)\n' +
    '    at Worker.[kOnMessage] (node:internal/worker:300:37)\n' +
    '    at MessagePort.<anonymous> (node:internal/worker:201:57)\n' +
    '    at MessagePort.[nodejs.internal.kHybridDispatch] (node:internal/event_target:647:20)\n' +
    '    at MessagePort.exports.emitMessage (node:internal/per_context/messageport:23:28) {\n' +
    "  code: 'MODULE_NOT_FOUND',\n" +
    "  requireStack: [ '/root/rpmbuild/BUILD/node-v16.14.2/[worker eval]' ]\n" +
    '}\n',
  expected: '',
  operator: 'strictEqual'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/worker-addon/test.js
=== release test ===                   
Path: addons/async-hooks-id/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/async-hooks-id/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/async-hooks-id/test.js:5:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/async-hooks-id/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/async-hooks-id/test.js
=== release test ===                   
Path: addons/new-target/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/new-target/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/new-target/test.js:5:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/new-target/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/new-target/test.js
=== release test ===                   
Path: addons/node-module-version/test
node:assert:749
    throw err;
    ^

AssertionError [ERR_ASSERTION]: The input did not match the regular expression /^Error: The module '.+'\nwas compiled against a different Node\.js version using\nNODE_MODULE_VERSION 42\. This version of Node\.js requires\nNODE_MODULE_VERSION 93\. Please try re-compiling or re-installing\nthe module \(for instance, using `npm rebuild` or `npm install`\)\.$/. Input:

"Error: Cannot find module './build/Release/binding'\n" +
  'Require stack:\n' +
  '- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/node-module-version/test.js'

    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/node-module-version/test.js:14:8)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: Error: Cannot find module './build/Release/binding'
  Require stack:
  - /root/rpmbuild/BUILD/node-v16.14.2/test/addons/node-module-version/test.js
      at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
      at Function.Module._load (node:internal/modules/cjs/loader:778:27)
      at Module.require (node:internal/modules/cjs/loader:1005:19)
      at require (node:internal/modules/cjs/helpers:102:18)
      at /root/rpmbuild/BUILD/node-v16.14.2/test/addons/node-module-version/test.js:14:21
      at getActual (node:assert:756:5)
      at Function.throws (node:assert:902:24)
      at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/node-module-version/test.js:14:8)
      at Module._compile (node:internal/modules/cjs/loader:1103:14)
      at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10) {
    code: 'MODULE_NOT_FOUND',
    requireStack: [
      '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/node-module-version/test.js'
    ]
  },
  expected: /^Error: The module '.+'\nwas compiled against a different Node\.js version using\nNODE_MODULE_VERSION 42\. This version of Node\.js requires\nNODE_MODULE_VERSION 93\. Please try re-compiling or re-installing\nthe module \(for instance, using `npm rebuild` or `npm install`\)\.$/,
  operator: 'throws'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/node-module-version/test.js
=== release test ===                   
Path: addons/not-a-binding/test
node:assert:749
    throw err;
    ^

AssertionError [ERR_ASSERTION]: The input did not match the regular expression /^Error: Module did not self-register: '.*[\\/]binding\.node'\.$/. Input:

"Error: Cannot find module './build/Release/binding'\n" +
  'Require stack:\n' +
  '- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/not-a-binding/test.js'

    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/not-a-binding/test.js:6:8)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: Error: Cannot find module './build/Release/binding'
  Require stack:
  - /root/rpmbuild/BUILD/node-v16.14.2/test/addons/not-a-binding/test.js
      at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
      at Function.Module._load (node:internal/modules/cjs/loader:778:27)
      at Module.require (node:internal/modules/cjs/loader:1005:19)
      at require (node:internal/modules/cjs/helpers:102:18)
      at /root/rpmbuild/BUILD/node-v16.14.2/test/addons/not-a-binding/test.js:6:21
      at getActual (node:assert:756:5)
      at Function.throws (node:assert:902:24)
      at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/not-a-binding/test.js:6:8)
      at Module._compile (node:internal/modules/cjs/loader:1103:14)
      at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10) {
    code: 'MODULE_NOT_FOUND',
    requireStack: [
      '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/not-a-binding/test.js'
    ]
  },
  expected: /^Error: Module did not self-register: '.*[\\/]binding\.node'\.$/,
  operator: 'throws'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/not-a-binding/test.js
=== release test ===                   
Path: addons/worker-buffer-callback/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/worker-buffer-callback/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/worker-buffer-callback/test.js:5:20)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/worker-buffer-callback/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/worker-buffer-callback/test.js
=== release test ===                   
Path: addons/parse-encoding/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/parse-encoding/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/parse-encoding/test.js:5:27)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/parse-encoding/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/parse-encoding/test.js
=== release test ===                   
Path: addons/load-long-path/test
node:internal/fs/utils:344
    throw err;
    ^

Error: ENOENT: no such file or directory, open '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/load-long-path/build/Release/binding.node'
    at Object.openSync (node:fs:585:3)
    at Object.readFileSync (node:fs:453:35)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/load-long-path/test.js:46:21)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  errno: -2,
  syscall: 'open',
  code: 'ENOENT',
  path: '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/load-long-path/build/Release/binding.node'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/load-long-path/test.js
=== release test ===                   
Path: addons/null-buffer-neuter/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/null-buffer-neuter/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/null-buffer-neuter/test.js:5:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/null-buffer-neuter/test.js'
  ]
}
Command: out/Release/node --expose-gc /root/rpmbuild/BUILD/node-v16.14.2/test/addons/null-buffer-neuter/test.js
=== release test ===                   
Path: addons/repl-domain-abort/test
node:assert:399
    throw err;
    ^

AssertionError [ERR_ASSERTION]: The expression evaluated to a falsy value:

  assert(cb_ran)

    at process.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/repl-domain-abort/test.js:35:3)
    at process.emit (node:events:538:35)
    at process.emit (node:domain:475:12)
    at process.topLevelDomainCallback (node:domain:152:15)
    at process.callbackTrampoline (node:internal/async_hooks:128:24) {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: false,
  expected: true,
  operator: '=='
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/repl-domain-abort/test.js
=== release test ===                   
Path: addons/make-callback/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/make-callback/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/make-callback/test.js:6:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/make-callback/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/make-callback/test.js
=== release test ===                   
Path: addons/make-callback-domain-warning/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/make-callback-domain-warning/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/make-callback-domain-warning/test.js:6:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/make-callback-domain-warning/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/make-callback-domain-warning/test.js
=== release test ===                   
Path: addons/buffer-free-callback/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/buffer-free-callback/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/buffer-free-callback/test.js:5:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/buffer-free-callback/test.js'
  ]
}
Command: out/Release/node --expose-gc /root/rpmbuild/BUILD/node-v16.14.2/test/addons/buffer-free-callback/test.js
=== release test ===                   
Path: addons/zlib-binding/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/zlib-binding/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/zlib-binding/test.js:8:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/zlib-binding/test.js'
  ]
}
Command: out/Release/node --force-context-aware /root/rpmbuild/BUILD/node-v16.14.2/test/addons/zlib-binding/test.js
=== release test ===                   
Path: addons/symlinked-module/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/symlinked-module/build/Release/binding.node'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/symlinked-module/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at /root/rpmbuild/BUILD/node-v16.14.2/test/addons/symlinked-module/test.js:30:15
    at Array.forEach (<anonymous>)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/symlinked-module/test.js:29:24)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/symlinked-module/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/symlinked-module/test.js
=== release test ===                   
Path: addons/make-callback-recurse/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/make-callback-recurse/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/make-callback-recurse/test.js:6:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/make-callback-recurse/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/make-callback-recurse/test.js
=== release test ===                   
Path: addons/callback-scope/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/callback-scope/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/callback-scope/test.js:5:32)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/callback-scope/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/callback-scope/test.js
=== release test ===                   
Path: addons/uv-handle-leak/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/uv-handle-leak/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.resolve (node:internal/modules/cjs/helpers:108:19)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/uv-handle-leak/test.js:3:29)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/uv-handle-leak/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/uv-handle-leak/test.js
=== release test ===                   
Path: addons/hello-world-function-export/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/hello-world-function-export/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/hello-world-function-export/test.js:4:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/hello-world-function-export/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/hello-world-function-export/test.js
=== release test ===                   
Path: addons/heap-profiler/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/heap-profiler/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/heap-profiler/test.js:5:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/heap-profiler/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/heap-profiler/test.js
=== release test ===                   
Path: addons/force-context-aware/test
node:assert:749
    throw err;
    ^

AssertionError [ERR_ASSERTION]: The input did not match the regular expression /^Error: Loading non context-aware native modules has been disabled$/. Input:

"Error: Cannot find module './build/Release/binding'\n" +
  'Require stack:\n' +
  '- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/force-context-aware/test.js'

    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/force-context-aware/test.js:6:8)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: Error: Cannot find module './build/Release/binding'
  Require stack:
  - /root/rpmbuild/BUILD/node-v16.14.2/test/addons/force-context-aware/test.js
      at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
      at Function.Module._load (node:internal/modules/cjs/loader:778:27)
      at Module.require (node:internal/modules/cjs/loader:1005:19)
      at require (node:internal/modules/cjs/helpers:102:18)
      at /root/rpmbuild/BUILD/node-v16.14.2/test/addons/force-context-aware/test.js:7:3
      at getActual (node:assert:756:5)
      at Function.throws (node:assert:902:24)
      at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/force-context-aware/test.js:6:8)
      at Module._compile (node:internal/modules/cjs/loader:1103:14)
      at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10) {
    code: 'MODULE_NOT_FOUND',
    requireStack: [
      '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/force-context-aware/test.js'
    ]
  },
  expected: /^Error: Loading non context-aware native modules has been disabled$/,
  operator: 'throws'
}
Command: out/Release/node --force-context-aware /root/rpmbuild/BUILD/node-v16.14.2/test/addons/force-context-aware/test.js
=== release test ===                   
Path: addons/async-resource/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/async-resource/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/async-resource/test.js:5:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/async-resource/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/async-resource/test.js
=== release test-async-hooks ===                   
Path: addons/callback-scope/test-async-hooks
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/callback-scope/test-async-hooks.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/callback-scope/test-async-hooks.js:6:32)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/callback-scope/test-async-hooks.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/callback-scope/test-async-hooks.js
=== release test-free-called ===                   
Path: addons/worker-buffer-callback/test-free-called
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/worker-buffer-callback/build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/worker-buffer-callback/test-free-called.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/worker-buffer-callback/test-free-called.js:7:30)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/worker-buffer-callback/test-free-called.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/worker-buffer-callback/test-free-called.js
=== release test-resolve-async ===                           
Path: addons/callback-scope/test-resolve-async
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/callback-scope/test-resolve-async.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/callback-scope/test-resolve-async.js:5:30)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/callback-scope/test-resolve-async.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/callback-scope/test-resolve-async.js
=== release test-stringbytes-external-at-max ===                   
Path: addons/stringbytes-external-exceed-max/test-stringbytes-external-at-max
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-at-max.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-at-max.js:8:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-at-max.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-at-max.js
=== release test-stringbytes-external-exceed-max ===                   
Path: addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max.js:9:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max.js
=== release test-stringbytes-external-exceed-max-by-1-ascii ===               
Path: addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-ascii
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-ascii.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-ascii.js:9:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-ascii.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-ascii.js
=== release test-stringbytes-external-exceed-max-by-1-base64 ===              
Path: addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-base64
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-base64.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-base64.js:9:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-base64.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-base64.js
=== release test-stringbytes-external-exceed-max-by-1-binary ===              
Path: addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-binary
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-binary.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-binary.js:9:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-binary.js'
  ]
}
Command: out/Release/node --expose-gc /root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-binary.js
=== release test-stringbytes-external-exceed-max-by-1-hex ===                 
Path: addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-hex
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-hex.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-hex.js:9:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-hex.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-hex.js
=== release test-stringbytes-external-exceed-max-by-1-utf8 ===                
Path: addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-utf8
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-utf8.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-utf8.js:8:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-utf8.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-1-utf8.js
=== release test-stringbytes-external-exceed-max-by-2 ===                     
Path: addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-2
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-2.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-2.js:8:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-2.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/stringbytes-external-exceed-max/test-stringbytes-external-exceed-max-by-2.js
=== release test-worker ===                                                   
Path: addons/hello-world/test-worker
node:internal/event_target:916
  process.nextTick(() => { throw err; });
                           ^
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/hello-world/build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/[worker eval]
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at [worker eval]:3:3
    at Script.runInThisContext (node:vm:129:12)
    at Object.runInThisContext (node:vm:305:38)
    at node:internal/process/execution:76:19
    at [worker eval]-wrapper:6:22
    at evalScript (node:internal/process/execution:75:60)
Emitted 'error' event on Worker instance at:
    at Worker.[kOnErrorMessage] (node:internal/worker:289:10)
    at Worker.[kOnMessage] (node:internal/worker:300:37)
    at MessagePort.<anonymous> (node:internal/worker:201:57)
    at MessagePort.[nodejs.internal.kHybridDispatch] (node:internal/event_target:647:20)
    at MessagePort.exports.emitMessage (node:internal/per_context/messageport:23:28) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [ '/root/rpmbuild/BUILD/node-v16.14.2/[worker eval]' ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/hello-world/test-worker.js
=== release test-worker ===                   
Path: addons/dlopen-ping-pong/test-worker
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/addons/dlopen-ping-pong/test-worker.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.resolve (node:internal/modules/cjs/helpers:108:19)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/dlopen-ping-pong/test-worker.js:13:29)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/addons/dlopen-ping-pong/test-worker.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/addons/dlopen-ping-pong/test-worker.js
=== release test-worker ===                   
Path: addons/no-addons/test-worker
node:internal/event_target:916
  process.nextTick(() => { throw err; });
                           ^

AssertionError [ERR_ASSERTION]: Expected values to be strictly equal:
+ actual - expected

+ 'MODULE_NOT_FOUND'
- 'ERR_DLOPEN_DISABLED'
    at Worker.assertError (/root/rpmbuild/BUILD/node-v16.14.2/test/addons/no-addons/test-worker.js:13:10)
    at Worker.assertError (/root/rpmbuild/BUILD/node-v16.14.2/test/common/index.js:394:15)
    at Worker.emit (node:events:526:28)
    at Worker.[kOnErrorMessage] (node:internal/worker:289:10)
    at Worker.[kOnMessage] (node:internal/worker:300:37)
    at MessagePort.<anonymous> (node:internal/worker:201:57)
    at MessagePort.[nodejs.internal.kHybridDispatch] (node:internal/event_target:647:20)
    at MessagePort.exports.emitMessage (node:internal/per_context/messageport:23:28) {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: 'MODULE_NOT_FOUND',
  expected: 'ERR_DLOPEN_DISABLED',
  operator: 'strictEqual'
}
Command: out/Release/node --no-addons /root/rpmbuild/BUILD/node-v16.14.2/test/addons/no-addons/test-worker.js
[01:44|% 100|+  10|-  40]: Done               
```

