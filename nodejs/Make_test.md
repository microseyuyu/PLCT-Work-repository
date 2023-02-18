# Make_test

## 日志

[log](https://github.com/microseyuyu/PLCT-Work-repository/blob/main/nodejs/make_test)

## 结果

```
Ran 6 tests in 0.030s

OK
make -s test-doc

added 121 packages, and audited 122 packages in 17s

95 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
npm notice 
npm notice New major version of npm available! 8.5.0 -> 9.5.0
npm notice Changelog: https://github.com/npm/cli/releases/tag/v9.5.0
npm notice Run npm install -g npm@9.5.0 to update!
npm notice 
Error: connect ECONNREFUSED 0.0.0.0:443
    at TCPConnectWrap.afterConnect [as oncomplete] (node:net:1157:16) {
  errno: -111,
  code: 'ECONNREFUSED',
  syscall: 'connect',
  address: '0.0.0.0',
  port: 443
}
make[2]: *** [Makefile:770: out/previous-doc-versions.json] Error 1
make[1]: *** [Makefile:728: doc-only] Error 2
make: *** [Makefile:306: test] Error 2
```

## 其他说明

其中以下代码是因为电脑自动休眠而导致的报错：

```
[12058.139701] watchdog: BUG: soft lockup - CPU#7 stuck for 248s! [cc1plus:30857]
[12058.139867] watchdog: BUG: soft lockup - CPU#1 stuck for 248s! [cc1plus:30917]
[12058.139884] watchdog: BUG: soft lockup - CPU#3 stuck for 248s! [cc1plus:30897]
[12058.170641] watchdog: BUG: soft lockup - CPU#6 stuck for 248s! [cc1plus:30937]
[12058.178895] watchdog: BUG: soft lockup - CPU#2 stuck for 248s! [cc1plus:30837]
[12058.178920] watchdog: BUG: soft lockup - CPU#4 stuck for 248s! [cc1plus:30797]
[12058.205652] watchdog: BUG: soft lockup - CPU#0 stuck for 248s! [cc1plus:30877]
[12058.206362] watchdog: BUG: soft lockup - CPU#5 stuck for 248s! [cc1plus:30817]
```

