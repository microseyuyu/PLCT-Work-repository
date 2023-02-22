# node-api

tools/test.py test/node-api

```
[root@openEuler-riscv64 ~]# cd rpmbuild/BUILD/node-v16.14.2 ; tools/test.py test/node-api
=== release test ===                   
Path: node-api/test_general/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_general'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_general/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.resolve (node:internal/modules/cjs/helpers:108:19)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_general/test.js:4:26)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_general/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_general/test.js
=== release test ===                   
Path: node-api/test_fatal/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_fatal'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal/test.js:5:20)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal/test.js
=== release test ===                   
Path: node-api/test_threadsafe_function/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_threadsafe_function/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_threadsafe_function/test.js:5:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_threadsafe_function/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_threadsafe_function/test.js
=== release test ===                   
Path: node-api/test_uv_loop/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_uv_loop'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_uv_loop/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_uv_loop/test.js:3:26)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_uv_loop/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_uv_loop/test.js
=== release test ===                   
Path: node-api/test_async_context/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async_context/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async_context/test.js:11:5)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async_context/test.js'
  ]
}
Command: out/Release/node --gc-interval=100 --gc-global /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async_context/test.js
=== release test ===                   
Path: node-api/test_null_init/test
node:assert:749
    throw err;
    ^

AssertionError [ERR_ASSERTION]: The input did not match the regular expression /Module has no declared entry point[.]/. Input:

"Error: Cannot find module './build/Release/test_null_init'\n" +
  'Require stack:\n' +
  '- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_null_init/test.js'

    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_null_init/test.js:5:8)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: Error: Cannot find module './build/Release/test_null_init'
  Require stack:
  - /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_null_init/test.js
      at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
      at Function.Module._load (node:internal/modules/cjs/loader:778:27)
      at Module.require (node:internal/modules/cjs/loader:1005:19)
      at require (node:internal/modules/cjs/helpers:102:18)
      at /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_null_init/test.js:6:9
      at getActual (node:assert:756:5)
      at Function.throws (node:assert:902:24)
      at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_null_init/test.js:5:8)
      at Module._compile (node:internal/modules/cjs/loader:1103:14)
      at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10) {
    code: 'MODULE_NOT_FOUND',
    requireStack: [
      '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_null_init/test.js'
    ]
  },
  expected: /Module has no declared entry point[.]/,
  operator: 'throws'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_null_init/test.js
=== release test ===                   
Path: node-api/test_async/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_async'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async/test.js:5:20)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async/test.js
=== release test ===                   
Path: node-api/test_env_teardown_gc/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_env_teardown_gc/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_env_teardown_gc/test.js:7:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_env_teardown_gc/test.js'
  ]
}
Command: out/Release/node --expose-gc /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_env_teardown_gc/test.js
=== release test ===                   
Path: node-api/test_instance_data/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_instance_data'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_instance_data/test.js
- /root/rpmbuild/BUILD/node-v16.14.2/test/common/require-as.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_instance_data/test.js:9:5)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Module.require (node:internal/modules/cjs/loader:1005:19) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_instance_data/test.js',
    '/root/rpmbuild/BUILD/node-v16.14.2/test/common/require-as.js'
  ]
}

node:internal/event_target:916
  process.nextTick(() => { throw err; });
                           ^
Error: Cannot find module './build/Release/test_instance_data'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_instance_data/test.js
- /root/rpmbuild/BUILD/node-v16.14.2/test/common/require-as.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_instance_data/test.js:9:5)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
Emitted 'error' event on Worker instance at:
    at Worker.[kOnErrorMessage] (node:internal/worker:289:10)
    at Worker.[kOnMessage] (node:internal/worker:300:37)
    at MessagePort.<anonymous> (node:internal/worker:201:57)
    at MessagePort.[nodejs.internal.kHybridDispatch] (node:internal/event_target:647:20)
    at MessagePort.exports.emitMessage (node:internal/per_context/messageport:23:28) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_instance_data/test.js',
    '/root/rpmbuild/BUILD/node-v16.14.2/test/common/require-as.js'
  ]
}
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_ref_then_set'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_instance_data/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.resolve (node:internal/modules/cjs/helpers:108:19)
    at testProcessExit (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_instance_data/test.js:42:8)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_instance_data/test.js:53:3)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_instance_data/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_instance_data/test.js
=== release test ===                   
Path: node-api/test_make_callback/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_make_callback/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_make_callback/test.js:6:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_make_callback/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_make_callback/test.js
=== release test ===                   
Path: node-api/test_callback_scope/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_callback_scope/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_callback_scope/test.js:5:32)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_callback_scope/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_callback_scope/test.js
=== release test ===                   
Path: node-api/test_exception/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_exception'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_exception/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_exception/test.js:6:24)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_exception/test.js'
  ]
}
Command: out/Release/node --expose-gc /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_exception/test.js
=== release test ===                   
Path: node-api/1_hello_world/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/1_hello_world/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.resolve (node:internal/modules/cjs/helpers:108:19)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/1_hello_world/test.js:6:29)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/1_hello_world/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/1_hello_world/test.js
=== release test ===                   
Path: node-api/test_worker_buffer_callback/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_buffer_callback/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_buffer_callback/test.js:5:20)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_buffer_callback/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_buffer_callback/test.js
=== release test ===                   
Path: node-api/test_buffer/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_buffer'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_buffer/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_buffer/test.js:5:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_buffer/test.js'
  ]
}
Command: out/Release/node --expose-gc --no-concurrent-array-buffer-sweeping /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_buffer/test.js
=== release test ===                   
Path: node-api/test_make_callback_recurse/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_make_callback_recurse/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_make_callback_recurse/test.js:6:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_make_callback_recurse/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_make_callback_recurse/test.js
=== release test ===                   
Path: node-api/test_worker_terminate_finalization/test
node:internal/event_target:916
  process.nextTick(() => { throw err; });
                           ^

AssertionError [ERR_ASSERTION]: function should not have been called at /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_terminate_finalization/test.js:12
called with arguments: Error: Cannot find module './build/Release/test_worker_terminate_finalization'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_terminate_finalization/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_terminate_finalization/test.js:15:5)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_terminate_finalization/test.js'
  ]
}
    at Worker.mustNotCall (/root/rpmbuild/BUILD/node-v16.14.2/test/common/index.js:472:12)
    at Worker.emit (node:events:526:28)
    at Worker.[kOnErrorMessage] (node:internal/worker:289:10)
    at Worker.[kOnMessage] (node:internal/worker:300:37)
    at MessagePort.<anonymous> (node:internal/worker:201:57)
    at MessagePort.[nodejs.internal.kHybridDispatch] (node:internal/event_target:647:20)
    at MessagePort.exports.emitMessage (node:internal/per_context/messageport:23:28) {
  generatedMessage: false,
  code: 'ERR_ASSERTION',
  actual: undefined,
  expected: undefined,
  operator: 'fail'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_terminate_finalization/test.js
=== release test ===                   
Path: node-api/test_fatal_exception/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_fatal_exception'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal_exception/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal_exception/test.js:4:20)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal_exception/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal_exception/test.js
=== release test ===                   
Path: node-api/test_cleanup_hook/test
node:assert:123
  throw new AssertionError(obj);
  ^

AssertionError [ERR_ASSERTION]: Expected values to be strictly equal:
+ actual - expected

+ ''
- 'cleanup(42)'
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_cleanup_hook/test.js:11:10)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: '',
  expected: 'cleanup(42)',
  operator: 'strictEqual'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_cleanup_hook/test.js
=== release test ===                   
Path: node-api/test_async_cleanup_hook/test
node:internal/event_target:916
  process.nextTick(() => { throw err; });
                           ^
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async_cleanup_hook/build/Release/binding'
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
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async_cleanup_hook/test.js
=== release test ===                   
Path: node-api/test_worker_terminate/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_worker_terminate'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_terminate/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_terminate/test.js:10:3)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_terminate/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_terminate/test.js
=== release test-async-hooks ===                   
Path: node-api/test_async/test-async-hooks
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_async'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async/test-async-hooks.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async/test-async-hooks.js:5:20)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async/test-async-hooks.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async/test-async-hooks.js
=== release test-async-hooks ===                   
Path: node-api/test_make_callback/test-async-hooks
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_make_callback/test-async-hooks.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_make_callback/test-async-hooks.js:6:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_make_callback/test-async-hooks.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_make_callback/test-async-hooks.js
=== release test-async-hooks ===                   
Path: node-api/test_callback_scope/test-async-hooks
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_callback_scope/test-async-hooks.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_callback_scope/test-async-hooks.js:13:32)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_callback_scope/test-async-hooks.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_callback_scope/test-async-hooks.js
=== release test-external-buffer ===                   
Path: node-api/test_buffer/test-external-buffer
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_buffer'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_buffer/test-external-buffer.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_buffer/test-external-buffer.js:4:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_buffer/test-external-buffer.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_buffer/test-external-buffer.js
=== release test-free-called ===                       
Path: node-api/test_worker_buffer_callback/test-free-called
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_buffer_callback/build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_buffer_callback/test-free-called.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_buffer_callback/test-free-called.js:7:30)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_buffer_callback/test-free-called.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_worker_buffer_callback/test-free-called.js
=== release test-gcable ===                        
Path: node-api/test_async_context/test-gcable
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async_context/test-gcable.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async_context/test-gcable.js:7:33)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async_context/test-gcable.js'
  ]
}
Command: out/Release/node --gc-interval=100 --gc-global /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async_context/test-gcable.js
=== release test-gcable-callback ===                   
Path: node-api/test_async_context/test-gcable-callback
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async_context/test-gcable-callback.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async_context/test-gcable-callback.js:11:5)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async_context/test-gcable-callback.js'
  ]
}
Command: out/Release/node --gc-interval=100 --gc-global /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async_context/test-gcable-callback.js
=== release test-loop ===                              
Path: node-api/test_async/test-loop
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_async'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async/test-loop.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async/test-loop.js:4:20)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async/test-loop.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async/test-loop.js
=== release test-resolve-async ===                   
Path: node-api/test_callback_scope/test-resolve-async
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_callback_scope/test-resolve-async.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_callback_scope/test-resolve-async.js:4:30)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_callback_scope/test-resolve-async.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_callback_scope/test-resolve-async.js
=== release test-uncaught ===                        
Path: node-api/test_async/test-uncaught
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_async'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async/test-uncaught.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async/test-uncaught.js:4:20)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async/test-uncaught.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_async/test-uncaught.js
=== release test2 ===                           
Path: node-api/test_fatal/test2
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_fatal'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal/test2.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal/test2.js:5:20)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal/test2.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal/test2.js
=== release test_policy ===                   
Path: node-api/test_policy/test_policy
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/binding.node'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_policy/test_policy.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.resolve (node:internal/modules/cjs/helpers:108:19)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_policy/test_policy.js:24:29)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_policy/test_policy.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_policy/test_policy.js
=== release test_threads ===                   
Path: node-api/test_fatal/test_threads
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_fatal'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal/test_threads.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal/test_threads.js:5:20)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal/test_threads.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal/test_threads.js
=== release test_threads_report ===                   
Path: node-api/test_fatal/test_threads_report
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_fatal'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal/test_threads_report.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal/test_threads_report.js:8:20)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal/test_threads_report.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/node-api/test_fatal/test_threads_report.js
[01:21|% 100|+   0|-  35]: Done                       
```

