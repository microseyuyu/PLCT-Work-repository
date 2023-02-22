# parallel

tools/test.py test/parallel

```
[root@openEuler-riscv64 node-v16.14.2]# tools/test.py test/parallel
=== release test-child-process-stdio-overlapped ===                           
Path: parallel/test-child-process-stdio-overlapped
node:events:504
      throw er; // Unhandled 'error' event
      ^

Error: spawn /usr/bin/overlapped-checker ENOENT
    at Process.ChildProcess._handle.onexit (node:internal/child_process:283:19)
    at onErrorNT (node:internal/child_process:478:16)
    at processTicksAndRejections (node:internal/process/task_queues:83:21)
Emitted 'error' event on ChildProcess instance at:
    at Process.ChildProcess._handle.onexit (node:internal/child_process:289:12)
    at onErrorNT (node:internal/child_process:478:16)
    at processTicksAndRejections (node:internal/process/task_queues:83:21) {
  errno: -2,
  code: 'ENOENT',
  syscall: 'spawn /usr/bin/overlapped-checker',
  path: '/usr/bin/overlapped-checker',
  spawnargs: []
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-child-process-stdio-overlapped.js
=== release test-child-process-windows-hide ===                     
Path: parallel/test-child-process-windows-hide
Command: out/Release/node --expose-internals /root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-child-process-windows-hide.js
--- TIMEOUT ---
=== release test-cli-eval ===                                
Path: parallel/test-cli-eval
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-cli-eval.js
--- TIMEOUT ---
=== release test-cli-node-options ===                         
Path: parallel/test-cli-node-options
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-cli-node-options.js
--- TIMEOUT ---
=== release test-cli-node-print-help ===                              
Path: parallel/test-cli-node-print-help
Command: out/Release/node --expose-internals /root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-cli-node-print-help.js
--- TIMEOUT ---
=== release test-cli-options-negation ===                             
Path: parallel/test-cli-options-negation
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-cli-options-negation.js
--- TIMEOUT ---
=== release test-cli-options-precedence ===                         
Path: parallel/test-cli-options-precedence
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-cli-options-precedence.js
--- TIMEOUT ---
=== release test-debugger-address ===                                         
Path: parallel/test-debugger-address
node:internal/process/promises:279
            triggerUncaughtException(err, true /* fromPromise */);
            ^

AssertionError [ERR_ASSERTION]: ifError got unwanted exception: Timeout (5000) while waiting for />\s+$/; found: 
    at cleanup (/root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-debugger-address.js:53:12)
    at Timeout.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/common/debugger.js:84:18)
    at listOnTimeout (node:internal/timers:559:17)
    at processTimers (node:internal/timers:502:7) {
  generatedMessage: false,
  code: 'ERR_ASSERTION',
  actual: Error: Timeout (5000) while waiting for />\s+$/; found: 
      at Timeout.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/common/debugger.js:84:18)
      at listOnTimeout (node:internal/timers:559:17)
      at processTimers (node:internal/timers:502:7),
  expected: null,
  operator: 'ifError'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-debugger-address.js
=== release test-http-outgoing-end-cork ===                                   
Path: parallel/test-http-outgoing-end-cork
Sending req no 1
node:assert:170
  throw err;
  ^

AssertionError [ERR_ASSERTION]: () => {
    reject(new Error('Request timed out'));
  } at /root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-http-outgoing-end-cork.js:53
    at Timeout.mustNotCall [as _onTimeout] (/root/rpmbuild/BUILD/node-v16.14.2/test/common/index.js:472:12)
    at listOnTimeout (node:internal/timers:559:17)
    at processTimers (node:internal/timers:502:7) {
  generatedMessage: false,
  code: 'ERR_ASSERTION',
  actual: undefined,
  expected: undefined,
  operator: 'fail'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-http-outgoing-end-cork.js
=== release test-http2-forget-closed-streams ===                              
Path: parallel/test-http2-forget-closed-streams
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-http2-forget-closed-streams.js
--- TIMEOUT ---
=== release test-perf-hooks-histogram ===                                     
Path: parallel/test-perf-hooks-histogram
node:internal/event_target:916
  process.nextTick(() => { throw err; });
                           ^

AssertionError [ERR_ASSERTION]: The expression evaluated to a falsy value:

  ok(data.count > 0)

    at MessagePort.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-perf-hooks-histogram.js:87:5)
    at MessagePort.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/common/index.js:394:15)
    at MessagePort.eventHandler (node:internal/event_target:926:12)
    at MessagePort.[nodejs.internal.kHybridDispatch] (node:internal/event_target:647:20)
    at MessagePort.exports.emitMessage (node:internal/per_context/messageport:23:28) {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: false,
  expected: true,
  operator: '=='
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-perf-hooks-histogram.js
=== release test-process-config ===                                           
Path: parallel/test-process-config
config: {
  target_defaults: {
    cflags: [],
    default_configuration: 'Release',
    defines: [ 'NODE_OPENSSL_CERT_STORE' ],
    include_dirs: [],
    libraries: [
      '-lz',
      '-luv',
      '-lbrotlidec',
      '-lbrotlienc',
      '-lnghttp2',
      '-lcrypto',
      '-lssl'
    ]
  },
  variables: {
    asan: 0,
    coverage: false,
    dcheck_always_on: 0,
    debug_nghttp2: 1,
    debug_node: false,
    enable_lto: false,
    enable_pgo_generate: false,
    enable_pgo_use: false,
    error_on_warn: false,
    force_dynamic_crt: 1,
    host_arch: 'riscv64',
    icu_data_in: '../../deps/icu-tmp/icudt70l.dat',
    icu_default_data: '/usr/share/nodejs/icudata',
    icu_endianness: 'l',
    icu_gyp_path: 'tools/icu/icu-generic.gyp',
    icu_locales: 'root,en',
    icu_path: 'deps/icu-small',
    icu_small: true,
    icu_ver_major: '70',
    is_debug: 0,
    libdir: 'lib64',
    llvm_version: '0.0',
    napi_build_version: '8',
    node_byteorder: 'little',
    node_debug_lib: false,
    node_enable_d8: false,
    node_install_corepack: true,
    node_install_npm: true,
    node_library_files: [
      'lib/_stream_passthrough.js',
      'lib/sys.js',
      'lib/timers.js',
      'lib/module.js',
      'lib/perf_hooks.js',
      'lib/_http_common.js',
      'lib/domain.js',
      'lib/events.js',
      'lib/punycode.js',
      'lib/trace_events.js',
      'lib/vm.js',
      'lib/querystring.js',
      'lib/os.js',
      'lib/readline.js',
      'lib/child_process.js',
      'lib/_stream_wrap.js',
      'lib/_tls_common.js',
      'lib/https.js',
      'lib/diagnostics_channel.js',
      'lib/_stream_transform.js',
      'lib/_tls_wrap.js',
      'lib/_http_agent.js',
      'lib/assert.js',
      'lib/worker_threads.js',
      'lib/stream.js',
      'lib/v8.js',
      'lib/dns.js',
      'lib/cluster.js',
      'lib/string_decoder.js',
      'lib/fs.js',
      'lib/tty.js',
      'lib/path.js',
      'lib/_stream_writable.js',
      'lib/process.js',
      'lib/_stream_readable.js',
      'lib/buffer.js',
      'lib/net.js',
      'lib/util.js',
      'lib/dgram.js',
      'lib/inspector.js',
      'lib/constants.js',
      'lib/_http_client.js',
      'lib/http.js',
      'lib/_http_incoming.js',
      'lib/console.js',
      'lib/tls.js',
      'lib/_http_server.js',
      'lib/_stream_duplex.js',
      'lib/repl.js',
      'lib/url.js',
      'lib/zlib.js',
      'lib/crypto.js',
      'lib/_http_outgoing.js',
      'lib/http2.js',
      'lib/wasi.js',
      'lib/async_hooks.js',
      'lib/internal/linkedlist.js',
      'lib/internal/socket_list.js',
      'lib/internal/timers.js',
      'lib/internal/js_stream_socket.js',
      'lib/internal/worker.js',
      'lib/internal/idna.js',
      'lib/internal/blob.js',
      'lib/internal/abort_controller.js',
      'lib/internal/inspector_async_hook.js',
      'lib/internal/dtrace.js',
      'lib/internal/querystring.js',
      'lib/internal/validators.js',
      'lib/internal/error_serdes.js',
      'lib/internal/child_process.js',
      'lib/internal/watchdog.js',
      'lib/internal/freeze_intrinsics.js',
      'lib/internal/assert.js',
      'lib/internal/promise_hooks.js',
      'lib/internal/stream_base_commons.js',
      'lib/internal/tty.js',
      'lib/internal/fixed_queue.js',
      'lib/internal/options.js',
      'lib/internal/buffer.js',
      'lib/internal/socketaddress.js',
      'lib/internal/freelist.js',
      'lib/internal/net.js',
      'lib/internal/errors.js',
      'lib/internal/histogram.js',
      'lib/internal/util.js',
      'lib/internal/dgram.js',
      'lib/internal/constants.js',
      'lib/internal/blocklist.js',
      'lib/internal/priority_queue.js',
      'lib/internal/http.js',
      'lib/internal/v8_prof_processor.js',
      'lib/internal/event_target.js',
      'lib/internal/repl.js',
      'lib/internal/url.js',
      'lib/internal/cli_table.js',
      'lib/internal/encoding.js',
      'lib/internal/v8_prof_polyfill.js',
      'lib/internal/heap_utils.js',
      'lib/internal/async_hooks.js',
      'lib/internal/trace_events_async_hooks.js',
      ... 167 more items
    ],
    node_module_version: 93,
    node_no_browser_globals: false,
    node_prefix: '/usr',
    node_release_urlbase: '',
    node_shared: true,
    node_shared_brotli: true,
    node_shared_cares: false,
    node_shared_http_parser: false,
    node_shared_libuv: true,
    node_shared_nghttp2: true,
    node_shared_nghttp3: false,
    node_shared_ngtcp2: false,
    node_shared_openssl: true,
    node_shared_zlib: true,
    node_tag: '',
    node_target_type: 'shared_library',
    node_use_bundled_v8: true,
    node_use_dtrace: true,
    node_use_etw: false,
    node_use_node_code_cache: false,
    node_use_node_snapshot: false,
    node_use_openssl: true,
    node_use_v8_platform: true,
    node_with_ltcg: false,
    node_without_node_options: false,
    openssl_fips: '',
    openssl_is_fips: false,
    openssl_quic: false,
    ossfuzz: false,
    shlib_suffix: 'so.93',
    target_arch: 'riscv64',
    v8_enable_31bit_smis_on_64bit_arch: 0,
    v8_enable_gdbjit: 0,
    v8_enable_i18n_support: 1,
    v8_enable_inspector: 1,
    v8_enable_lite_mode: 0,
    v8_enable_object_print: 1,
    v8_enable_pointer_compression: 0,
    v8_enable_webassembly: 1,
    v8_no_strict_aliasing: 1,
    v8_optimized_debug: 1,
    v8_promise_internal_field_count: 1,
    v8_random_seed: 0,
    v8_trace_maps: 0,
    v8_use_siphash: 1,
    want_separate_host_toolset: 0
  }
}
process.config: {
  target_defaults: {
    cflags: [],
    default_configuration: 'Release',
    defines: [ 'NODE_OPENSSL_CERT_STORE' ],
    include_dirs: [],
    libraries: [
      '-lz',
      '-luv',
      '-lbrotlidec',
      '-lbrotlienc',
      '-lnghttp2',
      '-lcrypto',
      '-lssl'
    ]
  },
  variables: {
    asan: 0,
    coverage: false,
    dcheck_always_on: 0,
    debug_nghttp2: 1,
    debug_node: false,
    enable_lto: false,
    enable_pgo_generate: false,
    enable_pgo_use: false,
    error_on_warn: false,
    force_dynamic_crt: 1,
    host_arch: 'riscv64',
    icu_data_in: '../../deps/icu-tmp/icudt70l.dat',
    icu_default_data: '/usr/share/nodejs/icudata',
    icu_endianness: 'l',
    icu_gyp_path: 'tools/icu/icu-generic.gyp',
    icu_locales: 'root,en',
    icu_path: 'deps/icu-small',
    icu_small: true,
    icu_ver_major: '70',
    is_debug: 0,
    libdir: 'lib64',
    llvm_version: '0.0',
    napi_build_version: '8',
    node_byteorder: 'little',
    node_debug_lib: false,
    node_enable_d8: false,
    node_install_corepack: true,
    node_install_npm: true,
    node_library_files: [
      'lib/crypto.js',
      'lib/v8.js',
      'lib/net.js',
      'lib/assert.js',
      'lib/querystring.js',
      'lib/_http_outgoing.js',
      'lib/_stream_writable.js',
      'lib/_stream_passthrough.js',
      'lib/punycode.js',
      'lib/_http_server.js',
      'lib/trace_events.js',
      'lib/os.js',
      'lib/sys.js',
      'lib/child_process.js',
      'lib/tls.js',
      'lib/inspector.js',
      'lib/http.js',
      'lib/_tls_common.js',
      'lib/wasi.js',
      'lib/zlib.js',
      'lib/cluster.js',
      'lib/timers.js',
      'lib/tty.js',
      'lib/_tls_wrap.js',
      'lib/buffer.js',
      'lib/_http_common.js',
      'lib/dns.js',
      'lib/process.js',
      'lib/_stream_transform.js',
      'lib/constants.js',
      'lib/path.js',
      'lib/vm.js',
      'lib/stream.js',
      'lib/_http_client.js',
      'lib/_stream_wrap.js',
      'lib/async_hooks.js',
      'lib/domain.js',
      'lib/string_decoder.js',
      'lib/console.js',
      'lib/util.js',
      'lib/_stream_readable.js',
      'lib/_http_agent.js',
      'lib/fs.js',
      'lib/_http_incoming.js',
      'lib/https.js',
      'lib/worker_threads.js',
      'lib/events.js',
      'lib/http2.js',
      'lib/module.js',
      'lib/repl.js',
      'lib/_stream_duplex.js',
      'lib/url.js',
      'lib/diagnostics_channel.js',
      'lib/dgram.js',
      'lib/perf_hooks.js',
      'lib/readline.js',
      'lib/internal/net.js',
      'lib/internal/assert.js',
      'lib/internal/querystring.js',
      'lib/internal/blob.js',
      'lib/internal/socket_list.js',
      'lib/internal/inspector_async_hook.js',
      'lib/internal/stream_base_commons.js',
      'lib/internal/child_process.js',
      'lib/internal/event_target.js',
      'lib/internal/idna.js',
      'lib/internal/v8_prof_polyfill.js',
      'lib/internal/linkedlist.js',
      'lib/internal/http.js',
      'lib/internal/trace_events_async_hooks.js',
      'lib/internal/cli_table.js',
      'lib/internal/js_stream_socket.js',
      'lib/internal/timers.js',
      'lib/internal/tty.js',
      'lib/internal/validators.js',
      'lib/internal/buffer.js',
      'lib/internal/watchdog.js',
      'lib/internal/worker.js',
      'lib/internal/priority_queue.js',
      'lib/internal/constants.js',
      'lib/internal/heap_utils.js',
      'lib/internal/async_hooks.js',
      'lib/internal/options.js',
      'lib/internal/encoding.js',
      'lib/internal/freeze_intrinsics.js',
      'lib/internal/error_serdes.js',
      'lib/internal/util.js',
      'lib/internal/histogram.js',
      'lib/internal/fixed_queue.js',
      'lib/internal/freelist.js',
      'lib/internal/blocklist.js',
      'lib/internal/dtrace.js',
      'lib/internal/abort_controller.js',
      'lib/internal/promise_hooks.js',
      'lib/internal/errors.js',
      'lib/internal/socketaddress.js',
      'lib/internal/repl.js',
      'lib/internal/url.js',
      'lib/internal/v8_prof_processor.js',
      'lib/internal/dgram.js',
      ... 167 more items
    ],
    node_module_version: 93,
    node_no_browser_globals: false,
    node_prefix: '/usr',
    node_release_urlbase: '',
    node_shared: true,
    node_shared_brotli: true,
    node_shared_cares: false,
    node_shared_http_parser: false,
    node_shared_libuv: true,
    node_shared_nghttp2: true,
    node_shared_nghttp3: false,
    node_shared_ngtcp2: false,
    node_shared_openssl: true,
    node_shared_zlib: true,
    node_tag: '',
    node_target_type: 'shared_library',
    node_use_bundled_v8: true,
    node_use_dtrace: true,
    node_use_etw: false,
    node_use_node_code_cache: false,
    node_use_node_snapshot: false,
    node_use_openssl: true,
    node_use_v8_platform: true,
    node_with_ltcg: false,
    node_without_node_options: false,
    openssl_fips: '',
    openssl_is_fips: false,
    openssl_quic: false,
    ossfuzz: false,
    shlib_suffix: 'so.93',
    target_arch: 'riscv64',
    v8_enable_31bit_smis_on_64bit_arch: 0,
    v8_enable_gdbjit: 0,
    v8_enable_i18n_support: 1,
    v8_enable_inspector: 1,
    v8_enable_lite_mode: 0,
    v8_enable_object_print: 1,
    v8_enable_pointer_compression: 0,
    v8_enable_webassembly: 1,
    v8_no_strict_aliasing: 1,
    v8_optimized_debug: 1,
    v8_promise_internal_field_count: 1,
    v8_random_seed: 0,
    v8_trace_maps: 0,
    v8_use_siphash: 1,
    want_separate_host_toolset: 0
  }
}
/root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-process-config.js:65
  throw e;
  ^

AssertionError [ERR_ASSERTION]: Expected values to be strictly deep-equal:
+ actual - expected ... Lines skipped

  {
    target_defaults: {
...
      node_install_npm: true,
      node_library_files: [
+       'lib/_stream_passthrough.js',
+       'lib/sys.js',
+       'lib/timers.js',
+       'lib/module.js',
+       'lib/perf_hooks.js',
+       'lib/_http_common.js',
+       'lib/domain.js',
+       'lib/events.js',
-       'lib/crypto.js',
-       'lib/v8.js',
-       'lib/net.js',
-       'lib/assert.js',
-       'lib/querystring.js',
-       'lib/_http_outgoing.js',
-       'lib/_stream_writable.js',
-       'lib/_stream_passthrough.js',
        'lib/punycode.js',
+       'lib/trace_events.js',
+       'lib/vm.js',
+       'lib/querystring.js',
+       'lib/os.js',
+       'lib/readline.js',
+       'lib/child_process.js',
+       'lib/_stream_wrap.js',
+       'lib/_tls_common.js',
+       'lib/https.js',
+       'lib/diagnostics_channel.js',
+       'lib/_stream_transform.js',
+       'lib/_tls_wrap.js',
+       'lib/_http_agent.js',
+       'lib/assert.js',
+       'lib/worker_threads.js',
...
-       'lib/_http_server.js',
-       'lib/trace_events.js',
-       'lib/os.js',
-       'lib/sys.js',
-       'lib/child_process.js',
-       'lib/tls.js',
-       'lib/inspector.js',
-       'lib/http.js',
-       'lib/_tls_common.js',
-       'lib/wasi.js',
-       'lib/zlib.js',
-       'lib/cluster.js',
-       'lib/timers.js',
-       'lib/tty.js',
-       'lib/_tls_wrap.js',
...
    at Object.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-process-config.js:58:10)
    at Module._compile (node:internal/modules/cjs/loader:1103:14)
    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1157:10)
    at Module.load (node:internal/modules/cjs/loader:981:32)
    at Function.Module._load (node:internal/modules/cjs/loader:822:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:77:12)
    at node:internal/main/run_main_module:17:47 {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: {
    target_defaults: {
      cflags: [],
      default_configuration: 'Release',
      defines: [ 'NODE_OPENSSL_CERT_STORE' ],
      include_dirs: [],
      libraries: [
        '-lz',
        '-luv',
        '-lbrotlidec',
        '-lbrotlienc',
        '-lnghttp2',
        '-lcrypto',
        '-lssl'
      ]
    },
    variables: {
      asan: 0,
      coverage: false,
      dcheck_always_on: 0,
      debug_nghttp2: 1,
      debug_node: false,
      enable_lto: false,
      enable_pgo_generate: false,
      enable_pgo_use: false,
      error_on_warn: false,
      force_dynamic_crt: 1,
      host_arch: 'riscv64',
      icu_data_in: '../../deps/icu-tmp/icudt70l.dat',
      icu_default_data: '/usr/share/nodejs/icudata',
      icu_endianness: 'l',
      icu_gyp_path: 'tools/icu/icu-generic.gyp',
      icu_locales: 'root,en',
      icu_path: 'deps/icu-small',
      icu_small: true,
      icu_ver_major: '70',
      is_debug: 0,
      libdir: 'lib64',
      llvm_version: '0.0',
      napi_build_version: '8',
      node_byteorder: 'little',
      node_debug_lib: false,
      node_enable_d8: false,
      node_install_corepack: true,
      node_install_npm: true,
      node_library_files: [
        'lib/_stream_passthrough.js',
        'lib/sys.js',
        'lib/timers.js',
        'lib/module.js',
        'lib/perf_hooks.js',
        'lib/_http_common.js',
        'lib/domain.js',
        'lib/events.js',
        'lib/punycode.js',
        'lib/trace_events.js',
        'lib/vm.js',
        'lib/querystring.js',
        'lib/os.js',
        'lib/readline.js',
        'lib/child_process.js',
        'lib/_stream_wrap.js',
        'lib/_tls_common.js',
        'lib/https.js',
        'lib/diagnostics_channel.js',
        'lib/_stream_transform.js',
        'lib/_tls_wrap.js',
        'lib/_http_agent.js',
        'lib/assert.js',
        'lib/worker_threads.js',
        'lib/stream.js',
        'lib/v8.js',
        'lib/dns.js',
        'lib/cluster.js',
        'lib/string_decoder.js',
        'lib/fs.js',
        'lib/tty.js',
        'lib/path.js',
        'lib/_stream_writable.js',
        'lib/process.js',
        'lib/_stream_readable.js',
        'lib/buffer.js',
        'lib/net.js',
        'lib/util.js',
        'lib/dgram.js',
        'lib/inspector.js',
        'lib/constants.js',
        'lib/_http_client.js',
        'lib/http.js',
        'lib/_http_incoming.js',
        'lib/console.js',
        'lib/tls.js',
        'lib/_http_server.js',
        'lib/_stream_duplex.js',
        'lib/repl.js',
        'lib/url.js',
        'lib/zlib.js',
        'lib/crypto.js',
        'lib/_http_outgoing.js',
        'lib/http2.js',
        'lib/wasi.js',
        'lib/async_hooks.js',
        'lib/internal/linkedlist.js',
        'lib/internal/socket_list.js',
        'lib/internal/timers.js',
        'lib/internal/js_stream_socket.js',
        'lib/internal/worker.js',
        'lib/internal/idna.js',
        'lib/internal/blob.js',
        'lib/internal/abort_controller.js',
        'lib/internal/inspector_async_hook.js',
        'lib/internal/dtrace.js',
        'lib/internal/querystring.js',
        'lib/internal/validators.js',
        'lib/internal/error_serdes.js',
        'lib/internal/child_process.js',
        'lib/internal/watchdog.js',
        'lib/internal/freeze_intrinsics.js',
        'lib/internal/assert.js',
        'lib/internal/promise_hooks.js',
        'lib/internal/stream_base_commons.js',
        'lib/internal/tty.js',
        'lib/internal/fixed_queue.js',
        'lib/internal/options.js',
        'lib/internal/buffer.js',
        'lib/internal/socketaddress.js',
        'lib/internal/freelist.js',
        'lib/internal/net.js',
        'lib/internal/errors.js',
        'lib/internal/histogram.js',
        'lib/internal/util.js',
        'lib/internal/dgram.js',
        'lib/internal/constants.js',
        'lib/internal/blocklist.js',
        'lib/internal/priority_queue.js',
        'lib/internal/http.js',
        'lib/internal/v8_prof_processor.js',
        'lib/internal/event_target.js',
        'lib/internal/repl.js',
        'lib/internal/url.js',
        'lib/internal/cli_table.js',
        'lib/internal/encoding.js',
        'lib/internal/v8_prof_polyfill.js',
        'lib/internal/heap_utils.js',
        'lib/internal/async_hooks.js',
        'lib/internal/trace_events_async_hooks.js',
        ... 167 more items
      ],
      node_module_version: 93,
      node_no_browser_globals: false,
      node_prefix: '/usr',
      node_release_urlbase: '',
      node_shared: true,
      node_shared_brotli: true,
      node_shared_cares: false,
      node_shared_http_parser: false,
      node_shared_libuv: true,
      node_shared_nghttp2: true,
      node_shared_nghttp3: false,
      node_shared_ngtcp2: false,
      node_shared_openssl: true,
      node_shared_zlib: true,
      node_tag: '',
      node_target_type: 'shared_library',
      node_use_bundled_v8: true,
      node_use_dtrace: true,
      node_use_etw: false,
      node_use_node_code_cache: false,
      node_use_node_snapshot: false,
      node_use_openssl: true,
      node_use_v8_platform: true,
      node_with_ltcg: false,
      node_without_node_options: false,
      openssl_fips: '',
      openssl_is_fips: false,
      openssl_quic: false,
      ossfuzz: false,
      shlib_suffix: 'so.93',
      target_arch: 'riscv64',
      v8_enable_31bit_smis_on_64bit_arch: 0,
      v8_enable_gdbjit: 0,
      v8_enable_i18n_support: 1,
      v8_enable_inspector: 1,
      v8_enable_lite_mode: 0,
      v8_enable_object_print: 1,
      v8_enable_pointer_compression: 0,
      v8_enable_webassembly: 1,
      v8_no_strict_aliasing: 1,
      v8_optimized_debug: 1,
      v8_promise_internal_field_count: 1,
      v8_random_seed: 0,
      v8_trace_maps: 0,
      v8_use_siphash: 1,
      want_separate_host_toolset: 0
    }
  },
  expected: {
    target_defaults: {
      cflags: [],
      default_configuration: 'Release',
      defines: [ 'NODE_OPENSSL_CERT_STORE' ],
      include_dirs: [],
      libraries: [
        '-lz',
        '-luv',
        '-lbrotlidec',
        '-lbrotlienc',
        '-lnghttp2',
        '-lcrypto',
        '-lssl'
      ]
    },
    variables: {
      asan: 0,
      coverage: false,
      dcheck_always_on: 0,
      debug_nghttp2: 1,
      debug_node: false,
      enable_lto: false,
      enable_pgo_generate: false,
      enable_pgo_use: false,
      error_on_warn: false,
      force_dynamic_crt: 1,
      host_arch: 'riscv64',
      icu_data_in: '../../deps/icu-tmp/icudt70l.dat',
      icu_default_data: '/usr/share/nodejs/icudata',
      icu_endianness: 'l',
      icu_gyp_path: 'tools/icu/icu-generic.gyp',
      icu_locales: 'root,en',
      icu_path: 'deps/icu-small',
      icu_small: true,
      icu_ver_major: '70',
      is_debug: 0,
      libdir: 'lib64',
      llvm_version: '0.0',
      napi_build_version: '8',
      node_byteorder: 'little',
      node_debug_lib: false,
      node_enable_d8: false,
      node_install_corepack: true,
      node_install_npm: true,
      node_library_files: [
        'lib/crypto.js',
        'lib/v8.js',
        'lib/net.js',
        'lib/assert.js',
        'lib/querystring.js',
        'lib/_http_outgoing.js',
        'lib/_stream_writable.js',
        'lib/_stream_passthrough.js',
        'lib/punycode.js',
        'lib/_http_server.js',
        'lib/trace_events.js',
        'lib/os.js',
        'lib/sys.js',
        'lib/child_process.js',
        'lib/tls.js',
        'lib/inspector.js',
        'lib/http.js',
        'lib/_tls_common.js',
        'lib/wasi.js',
        'lib/zlib.js',
        'lib/cluster.js',
        'lib/timers.js',
        'lib/tty.js',
        'lib/_tls_wrap.js',
        'lib/buffer.js',
        'lib/_http_common.js',
        'lib/dns.js',
        'lib/process.js',
        'lib/_stream_transform.js',
        'lib/constants.js',
        'lib/path.js',
        'lib/vm.js',
        'lib/stream.js',
        'lib/_http_client.js',
        'lib/_stream_wrap.js',
        'lib/async_hooks.js',
        'lib/domain.js',
        'lib/string_decoder.js',
        'lib/console.js',
        'lib/util.js',
        'lib/_stream_readable.js',
        'lib/_http_agent.js',
        'lib/fs.js',
        'lib/_http_incoming.js',
        'lib/https.js',
        'lib/worker_threads.js',
        'lib/events.js',
        'lib/http2.js',
        'lib/module.js',
        'lib/repl.js',
        'lib/_stream_duplex.js',
        'lib/url.js',
        'lib/diagnostics_channel.js',
        'lib/dgram.js',
        'lib/perf_hooks.js',
        'lib/readline.js',
        'lib/internal/net.js',
        'lib/internal/assert.js',
        'lib/internal/querystring.js',
        'lib/internal/blob.js',
        'lib/internal/socket_list.js',
        'lib/internal/inspector_async_hook.js',
        'lib/internal/stream_base_commons.js',
        'lib/internal/child_process.js',
        'lib/internal/event_target.js',
        'lib/internal/idna.js',
        'lib/internal/v8_prof_polyfill.js',
        'lib/internal/linkedlist.js',
        'lib/internal/http.js',
        'lib/internal/trace_events_async_hooks.js',
        'lib/internal/cli_table.js',
        'lib/internal/js_stream_socket.js',
        'lib/internal/timers.js',
        'lib/internal/tty.js',
        'lib/internal/validators.js',
        'lib/internal/buffer.js',
        'lib/internal/watchdog.js',
        'lib/internal/worker.js',
        'lib/internal/priority_queue.js',
        'lib/internal/constants.js',
        'lib/internal/heap_utils.js',
        'lib/internal/async_hooks.js',
        'lib/internal/options.js',
        'lib/internal/encoding.js',
        'lib/internal/freeze_intrinsics.js',
        'lib/internal/error_serdes.js',
        'lib/internal/util.js',
        'lib/internal/histogram.js',
        'lib/internal/fixed_queue.js',
        'lib/internal/freelist.js',
        'lib/internal/blocklist.js',
        'lib/internal/dtrace.js',
        'lib/internal/abort_controller.js',
        'lib/internal/promise_hooks.js',
        'lib/internal/errors.js',
        'lib/internal/socketaddress.js',
        'lib/internal/repl.js',
        'lib/internal/url.js',
        'lib/internal/v8_prof_processor.js',
        'lib/internal/dgram.js',
        ... 167 more items
      ],
      node_module_version: 93,
      node_no_browser_globals: false,
      node_prefix: '/usr',
      node_release_urlbase: '',
      node_shared: true,
      node_shared_brotli: true,
      node_shared_cares: false,
      node_shared_http_parser: false,
      node_shared_libuv: true,
      node_shared_nghttp2: true,
      node_shared_nghttp3: false,
      node_shared_ngtcp2: false,
      node_shared_openssl: true,
      node_shared_zlib: true,
      node_tag: '',
      node_target_type: 'shared_library',
      node_use_bundled_v8: true,
      node_use_dtrace: true,
      node_use_etw: false,
      node_use_node_code_cache: false,
      node_use_node_snapshot: false,
      node_use_openssl: true,
      node_use_v8_platform: true,
      node_with_ltcg: false,
      node_without_node_options: false,
      openssl_fips: '',
      openssl_is_fips: false,
      openssl_quic: false,
      ossfuzz: false,
      shlib_suffix: 'so.93',
      target_arch: 'riscv64',
      v8_enable_31bit_smis_on_64bit_arch: 0,
      v8_enable_gdbjit: 0,
      v8_enable_i18n_support: 1,
      v8_enable_inspector: 1,
      v8_enable_lite_mode: 0,
      v8_enable_object_print: 1,
      v8_enable_pointer_compression: 0,
      v8_enable_webassembly: 1,
      v8_no_strict_aliasing: 1,
      v8_optimized_debug: 1,
      v8_promise_internal_field_count: 1,
      v8_random_seed: 0,
      v8_trace_maps: 0,
      v8_use_siphash: 1,
      want_separate_host_toolset: 0
    }
  },
  operator: 'deepStrictEqual'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-process-config.js
=== release test-stream-filter ===                                            
Path: parallel/test-stream-filter
node:assert:123
  throw new AssertionError(obj);
  ^

AssertionError [ERR_ASSERTION]: Expected values to be strictly equal:

4 !== 2

    at Immediate._onImmediate (/root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-stream-filter.js:69:12)
    at processImmediate (node:internal/timers:466:21) {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: 4,
  expected: 2,
  operator: 'strictEqual'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-stream-filter.js
=== release test-stream-map ===                                               
Path: parallel/test-stream-map
undefined
undefined
node:assert:123
  throw new AssertionError(obj);
  ^

AssertionError [ERR_ASSERTION]: Expected values to be strictly equal:

4 !== 2

    at Immediate._onImmediate (/root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-stream-map.js:68:12)
    at processImmediate (node:internal/timers:466:21) {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: 4,
  expected: 2,
  operator: 'strictEqual'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-stream-map.js
=== release test-tls-no-sslv3 ===                                             
Path: parallel/test-tls-no-sslv3
CONNECTED(00000003)
---
no peer certificate available
---
No client certificate CA names sent
---
SSL handshake has read 7 bytes and written 58 bytes
Verification: OK
---
New, (NONE), Cipher is (NONE)
Secure Renegotiation IS NOT supported
Compression: NONE
Expansion: NONE
No ALPN negotiated
SSL-Session:
    Protocol  : SSLv3
    Cipher    : 0000
    Session-ID: 
    Session-ID-ctx: 
    Master-Key: 
    PSK identity: None
    PSK identity hint: None
    SRP username: None
    Start Time: 1677078112
    Timeout   : 7200 (sec)
    Verify return code: 0 (ok)
    Extended master secret: no
---
274044867616:error:14094410:SSL routines:ssl3_read_bytes:sslv3 alert handshake failure:ssl/record/rec_layer_s3.c:1543:SSL alert number 40
node:assert:399
    throw err;
    ^

AssertionError [ERR_ASSERTION]: The expression evaluated to a falsy value:

  assert(/:wrong version number/.test(errors[0].message) ||
         /:version too low/.test(errors[0].message))

    at process.<anonymous> (/root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-tls-no-sslv3.js:46:5)
    at process.emit (node:events:538:35) {
  generatedMessage: true,
  code: 'ERR_ASSERTION',
  actual: false,
  expected: true,
  operator: '=='
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-tls-no-sslv3.js
=== release test-trace-events-fs-sync ===                                     
Path: parallel/test-trace-events-fs-sync
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/parallel/test-trace-events-fs-sync.js
--- TIMEOUT ---
[52:13|% 100|+ 2844|-  16]: Done                                              
```

