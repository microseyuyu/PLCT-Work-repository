# js-native-api	

tools/test.py test/js-native-api	

```
[root@openEuler-riscv64 ~]# cd rpmbuild/BUILD/node-v16.14.2 ; tools/test.py test/js-native-api
=== release test ===                   
Path: js-native-api/5_function_factory/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/5_function_factory'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/5_function_factory/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/5_function_factory/test.js:4:15)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/5_function_factory/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/5_function_factory/test.js
=== release test ===                   
Path: js-native-api/test_handle_scope/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_handle_scope'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_handle_scope/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_handle_scope/test.js:7:5)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_handle_scope/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_handle_scope/test.js
=== release test ===                   
Path: js-native-api/test_object/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_object'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_object/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_object/test.js:6:21)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_object/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_object/test.js
=== release test ===                   
Path: js-native-api/4_object_factory/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/4_object_factory'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/4_object_factory/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/4_object_factory/test.js:4:15)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/4_object_factory/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/4_object_factory/test.js
=== release test ===                   
Path: js-native-api/test_typedarray/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_typedarray'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_typedarray/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_typedarray/test.js:6:25)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_typedarray/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_typedarray/test.js
=== release test ===                   
Path: js-native-api/test_array/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_array'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_array/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_array/test.js:6:20)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_array/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_array/test.js
=== release test ===                   
Path: js-native-api/test_number/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_number'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_number/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_number/test.js:4:21)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_number/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_number/test.js
=== release test ===                   
Path: js-native-api/test_general/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_general'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/test.js:5:22)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/test.js'
  ]
}
Command: out/Release/node --expose-gc /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/test.js
=== release test ===                   
Path: js-native-api/test_promise/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_promise'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_promise/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_promise/test.js:8:22)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_promise/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_promise/test.js
=== release test ===                   
Path: js-native-api/test_dataview/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_dataview'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_dataview/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_dataview/test.js:6:23)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_dataview/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_dataview/test.js
=== release test ===                   
Path: js-native-api/test_function/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_function'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_function/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_function/test.js:8:23)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_function/test.js'
  ]
}
Command: out/Release/node --expose-gc /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_function/test.js
=== release test ===                   
Path: js-native-api/8_passing_wrapped/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/8_passing_wrapped'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/8_passing_wrapped/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/8_passing_wrapped/test.js:6:15)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/8_passing_wrapped/test.js'
  ]
}
Command: out/Release/node --expose-gc /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/8_passing_wrapped/test.js
=== release test ===                   
Path: js-native-api/test_instance_data/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_instance_data'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_instance_data/test.js
- /root/rpmbuild/BUILD/node-v16.14.2/test/common/require-as.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_instance_data/test.js:10:5)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Module.require (node:internal/modules/cjs/loader:1005:19) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_instance_data/test.js',
    '/root/rpmbuild/BUILD/node-v16.14.2/test/common/require-as.js'
  ]
}
node:assert:123
  throw new AssertionError(obj);
  ^

AssertionError [ERR_ASSERTION]: Expected values to be strictly equal:

1 !== 0

    at checkOutput (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_instance_data/test.js:29:12)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_instance_data/test.js:36:3)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: 1,
  expected: 0,
  operator: 'strictEqual'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_instance_data/test.js
=== release test ===                   
Path: js-native-api/test_error/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_error'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_error/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_error/test.js:4:20)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_error/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_error/test.js
=== release test ===                   
Path: js-native-api/2_function_arguments/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/2_function_arguments'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/2_function_arguments/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/2_function_arguments/test.js:4:15)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/2_function_arguments/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/2_function_arguments/test.js
=== release test ===                   
Path: js-native-api/test_properties/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_properties'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_properties/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_properties/test.js:10:21)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_properties/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_properties/test.js
=== release test ===                   
Path: js-native-api/6_object_wrap/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/6_object_wrap'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/6_object_wrap/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/6_object_wrap/test.js:4:15)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/6_object_wrap/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/6_object_wrap/test.js
=== release test ===                   
Path: js-native-api/test_exception/test
node:assert:123
  throw new AssertionError(obj);
  ^

AssertionError [ERR_ASSERTION]: Expected values to be strictly equal:
+ actual - expected

+ "Cannot find module './build/Release/test_exception'\n" +
+   'Require stack:\n' +
+   '- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_exception/test.js'
- 'Error during Init'
    at /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_exception/test.js:20:10
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_exception/test.js:22:3)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: "Cannot find module './build/Release/test_exception'\n" +
    'Require stack:\n' +
    '- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_exception/test.js',
  expected: 'Error during Init',
  operator: 'strictEqual'
}
Command: out/Release/node --expose-gc /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_exception/test.js
=== release test ===                   
Path: js-native-api/7_factory_wrap/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/7_factory_wrap'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/7_factory_wrap/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/7_factory_wrap/test.js:6:14)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/7_factory_wrap/test.js'
  ]
}
Command: out/Release/node --expose-gc /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/7_factory_wrap/test.js
=== release test ===                   
Path: js-native-api/test_conversions/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_conversions'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_conversions/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_conversions/test.js:4:14)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_conversions/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_conversions/test.js
=== release test ===                   
Path: js-native-api/test_reference_double_free/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_reference_double_free'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_reference_double_free/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_reference_double_free/test.js:8:15)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_reference_double_free/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_reference_double_free/test.js
=== release test ===                   
Path: js-native-api/test_string/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_string'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_string/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_string/test.js:6:21)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_string/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_string/test.js
=== release test ===                   
Path: js-native-api/test_reference/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_reference'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_reference/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_reference/test.js:7:24)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_reference/test.js'
  ]
}
Command: out/Release/node --expose-gc /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_reference/test.js
=== release test ===                   
Path: js-native-api/test_new_target/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_new_target'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_new_target/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_new_target/test.js:5:17)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_new_target/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_new_target/test.js
=== release test ===                   
Path: js-native-api/test_bigint/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_bigint'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_bigint/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_bigint/test.js:11:5)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_bigint/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_bigint/test.js
=== release test ===                   
Path: js-native-api/test_date/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_date'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_date/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_date/test.js:8:19)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_date/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_date/test.js
=== release test ===                   
Path: js-native-api/test_constructor/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_constructor'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_constructor/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_constructor/test.js:9:25)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_constructor/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_constructor/test.js
=== release test ===                   
Path: js-native-api/3_callbacks/test
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/3_callbacks'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/3_callbacks/test.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/3_callbacks/test.js:4:15)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/3_callbacks/test.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/3_callbacks/test.js
=== release test1 ===                   
Path: js-native-api/test_symbol/test1
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_symbol'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_symbol/test1.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_symbol/test1.js:6:21)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_symbol/test1.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_symbol/test1.js
=== release test2 ===                   
Path: js-native-api/test_constructor/test2
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_constructor'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_constructor/test2.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_constructor/test2.js:7:5)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_constructor/test2.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_constructor/test2.js
=== release test2 ===                   
Path: js-native-api/test_symbol/test2
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_symbol'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_symbol/test2.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_symbol/test2.js:6:21)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_symbol/test2.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_symbol/test2.js
=== release test3 ===                   
Path: js-native-api/test_symbol/test3
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_symbol'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_symbol/test3.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_symbol/test3.js:6:21)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_symbol/test3.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_symbol/test3.js
=== release testEnvCleanup ===                   
Path: js-native-api/test_general/testEnvCleanup
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_general'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testEnvCleanup.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testEnvCleanup.js:5:24)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testEnvCleanup.js'
  ]
}
node:assert:123
  throw new AssertionError(obj);
  ^

AssertionError [ERR_ASSERTION]: Expected values to be strictly deep-equal:
+ actual - expected

+ {}
- {
-   'finalize at env cleanup for second wrap': true,
-   'finalize at env cleanup for simple wrap': true
- }
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testEnvCleanup.js:48:10)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: {},
  expected: {
    'finalize at env cleanup for simple wrap': true,
    'finalize at env cleanup for second wrap': true
  },
  operator: 'deepStrictEqual'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testEnvCleanup.js
=== release testFinalizer ===                    
Path: js-native-api/test_general/testFinalizer
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_general'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testFinalizer.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testFinalizer.js:5:22)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testFinalizer.js'
  ]
}
Command: out/Release/node --expose-gc /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testFinalizer.js
=== release testFinalizerException ===                   
Path: js-native-api/test_exception/testFinalizerException
node:assert:1026
    throw err;
    ^

AssertionError [ERR_ASSERTION]: The input did not match the regular expression /Error during Finalize/. Input:

'/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_exception/testFinalizerException.js:10\n' +
  '    anException.binding.createExternal();\n' +
  '                        ^\n' +
  '\n' +
  "TypeError: Cannot read properties of undefined (reading 'createExternal')\n" +
  '    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_exception/testFinalizerException.js:10:25)\n' +
  '    at Module._compile (node:internal/modules/cjs/loader:1103:14)\n' +
  '    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)\n' +
  '    at Module.load (node:internal/modules/cjs/loader:981:32)\n' +
  '    at Function.Module._load (node:internal/modules/cjs/loader:822:12)\n' +
  '    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)\n' +
  '    at node:internal/main/run_main_module:17:47\n'

    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_exception/testFinalizerException.js:32:8)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_exception/testFinalizerException.js:10\n' +
    '    anException.binding.createExternal();\n' +
    '                        ^\n' +
    '\n' +
    "TypeError: Cannot read properties of undefined (reading 'createExternal')\n" +
    '    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_exception/testFinalizerException.js:10:25)\n' +
    '    at Module._compile (node:internal/modules/cjs/loader:1103:14)\n' +
    '    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)\n' +
    '    at Module.load (node:internal/modules/cjs/loader:981:32)\n' +
    '    at Function.Module._load (node:internal/modules/cjs/loader:822:12)\n' +
    '    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)\n' +
    '    at node:internal/main/run_main_module:17:47\n',
  expected: /Error during Finalize/,
  operator: 'match'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_exception/testFinalizerException.js
=== release testGlobals ===                              
Path: js-native-api/test_general/testGlobals
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_general'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testGlobals.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testGlobals.js:5:22)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testGlobals.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testGlobals.js
=== release testInstanceOf ===                   
Path: js-native-api/test_general/testInstanceOf
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_general'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testInstanceOf.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testInstanceOf.js:7:15)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testInstanceOf.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testInstanceOf.js
=== release testNapiRun ===                      
Path: js-native-api/test_general/testNapiRun
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_general'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testNapiRun.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testNapiRun.js:7:15)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testNapiRun.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testNapiRun.js
=== release testNapiStatus ===                   
Path: js-native-api/test_general/testNapiStatus
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_general'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testNapiStatus.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testNapiStatus.js:4:15)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testNapiStatus.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_general/testNapiStatus.js
=== release test_null ===                        
Path: js-native-api/test_object/test_null
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_object'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_object/test_null.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_object/test_null.js:6:22)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_object/test_null.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_object/test_null.js
=== release test_null ===                   
Path: js-native-api/test_string/test_null
node:internal/modules/cjs/loader:936
  throw err;
  ^

Error: Cannot find module './build/Release/test_string'
Require stack:
- /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_string/test_null.js
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Module.require (node:internal/modules/cjs/loader:1005:19)
    at require (node:internal/modules/cjs/helpers:102:18)
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_string/test_null.js:6:22)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12) {
  code: 'MODULE_NOT_FOUND',
  requireStack: [
    '/root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_string/test_null.js'
  ]
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/js-native-api/test_string/test_null.js
[01:30|% 100|+   0|-  41]: Done             
```

