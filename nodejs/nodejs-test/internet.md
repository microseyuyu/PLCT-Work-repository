# internet

tools/test.py test/internet

```
[root@openEuler-riscv64 node-v16.14.2]# tools/test.py test/internet
=== release test-dns ===                                                   
Path: internet/test-dns
test_reverse_bogus
test_resolve4_ttl
looking up nodejs.org..
test_resolve6_ttl
nodejs.org = 104.20.23.46,104.20.22.46
test_resolveMx
test_resolveMx_failure
test_resolveNs
test_resolveNs_failure
test_resolveSrv
6 tests completed
(node:9834) internal/test/binding: These APIs are for internal testing only. Do not use them.
(Use `node --trace-warnings ...` to show where the warning was created)
node:internal/errors:464
    ErrorCaptureStackTrace(err);
    ^

Error: querySrv ENOTFOUND _jabber._tcp.google.com
    at QueryReqWrap.onresolve [as oncomplete] (node:internal/dns/promises:173:17) {
  errno: undefined,
  code: 'ENOTFOUND',
  syscall: 'querySrv',
  hostname: '_jabber._tcp.google.com'
}
Command: out/Release/node --expose-internals /root/rpmbuild/BUILD/node-v16.14.2/test/internet/test-dns.js
=== release test-dns-any ===                   
Path: internet/test-dns-any
node:internal/errors:464
    ErrorCaptureStackTrace(err);
    ^

Error: queryAny ENOTFOUND _jabber._tcp.google.com
    at QueryReqWrap.onresolve [as oncomplete] (node:internal/dns/promises:173:17) {
  errno: undefined,
  code: 'ENOTFOUND',
  syscall: 'queryAny',
  hostname: '_jabber._tcp.google.com'
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/internet/test-dns-any.js
=== release test-http2-issue-32922 ===                                        
Path: internet/test-http2-issue-32922
node:events:504
      throw er; // Unhandled 'error' event
      ^

Error: connect ECONNREFUSED 142.251.43.14:443
    at TCPConnectWrap.afterConnect [as oncomplete] (node:net:1157:16)
Emitted 'error' event on ClientHttp2Session instance at:
    at emitClose (node:internal/http2/core:1075:10)
    at processTicksAndRejections (node:internal/process/task_queues:83:21) {
  errno: -111,
  code: 'ECONNREFUSED',
  syscall: 'connect',
  address: '142.251.43.14',
  port: 443
}
Command: out/Release/node /root/rpmbuild/BUILD/node-v16.14.2/test/internet/test-http2-issue-32922.js
[04:01|% 100|+  25|-   3]: Done  
```

