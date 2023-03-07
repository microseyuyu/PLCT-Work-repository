# Test_coverage

```
openkylin@openkylin:~/python3.8/Lib$ python3.8 -m test --coverage -D .
== CPython 3.8.2 (default, Jun 3 2022, 08:49:21) [GCC 9.3.0]
== Linux-5.11.0-1030-generic-riscv64-with-glibc2.28 little-endian
== cwd: /tmp/test_python_4441
== CPU count: 8
== encodings: locale=UTF-8, FS=utf-8
0:00:00 load avg: 0.66 Run tests sequentially
0:00:00 load avg: 0.66 [  1/423] test_grammar
0:00:03 load avg: 0.69 [  2/423] test_opcodes
0:00:04 load avg: 0.69 [  3/423] test_dict
0:00:17 load avg: 0.76 [  4/423] test_builtin
0:00:30 load avg: 0.79 [  5/423] test_exceptions
0:00:46 load avg: 0.84 [  6/423] test_types
0:00:50 load avg: 0.85 [  7/423] test_unittest
Executing <Task pending name='Task-39' coro=<IsolatedAsyncioTestCase._asyncioLoopRunner() running at /home/openkylin/python3.8/Lib/unittest/async_case.py:96> wait_for=<Future pending cb=[<TaskWakeupMethWrapper object at 0x3ff2123eb0>()] created at /home/openkylin/python3.8/Lib/asyncio/base_events.py:422> created at /home/openkylin/python3.8/Lib/unittest/async_case.py:118> took 0.164 seconds
Executing <Task pending name='Task-41' coro=<IsolatedAsyncioTestCase._asyncioLoopRunner() running at /home/openkylin/python3.8/Lib/unittest/async_case.py:96> wait_for=<Future pending cb=[<TaskWakeupMethWrapper object at 0x3ff2068fd0>()] created at /home/openkylin/python3.8/Lib/asyncio/base_events.py:422> created at /home/openkylin/python3.8/Lib/unittest/async_case.py:118> took 0.156 seconds
Executing <Task pending name='Task-43' coro=<IsolatedAsyncioTestCase._asyncioLoopRunner() running at /home/openkylin/python3.8/Lib/unittest/async_case.py:96> wait_for=<Future pending cb=[<TaskWakeupMethWrapper object at 0x3ff20ec310>()] created at /home/openkylin/python3.8/Lib/asyncio/base_events.py:422> created at /home/openkylin/python3.8/Lib/unittest/async_case.py:118> took 0.167 seconds
Executing <Task pending name='Task-45' coro=<IsolatedAsyncioTestCase._asyncioLoopRunner() running at /home/openkylin/python3.8/Lib/unittest/async_case.py:96> wait_for=<Future pending cb=[<TaskWakeupMethWrapper object at 0x3ff210a5e0>()] created at /home/openkylin/python3.8/Lib/asyncio/base_events.py:422> created at /home/openkylin/python3.8/Lib/unittest/async_case.py:118> took 0.145 seconds
Executing <Task pending name='Task-47' coro=<IsolatedAsyncioTestCase._asyncioLoopRunner() running at /home/openkylin/python3.8/Lib/unittest/async_case.py:96> wait_for=<Future pending cb=[<TaskWakeupMethWrapper object at 0x3ff2123d90>()] created at /home/openkylin/python3.8/Lib/asyncio/base_events.py:422> created at /home/openkylin/python3.8/Lib/unittest/async_case.py:118> took 0.152 seconds
Executing <Task pending name='Task-49' coro=<IsolatedAsyncioTestCase._asyncioLoopRunner() running at /home/openkylin/python3.8/Lib/unittest/async_case.py:96> wait_for=<Future pending cb=[<TaskWakeupMethWrapper object at 0x3ff20ec910>()] created at /home/openkylin/python3.8/Lib/asyncio/base_events.py:422> created at /home/openkylin/python3.8/Lib/unittest/async_case.py:118> took 0.142 seconds
Executing <Task pending name='Task-51' coro=<IsolatedAsyncioTestCase._asyncioLoopRunner() running at /home/openkylin/python3.8/Lib/unittest/async_case.py:96> wait_for=<Future pending cb=[<TaskWakeupMethWrapper object at 0x3ff2100610>()] created at /home/openkylin/python3.8/Lib/asyncio/base_events.py:422> created at /home/openkylin/python3.8/Lib/unittest/async_case.py:118> took 0.228 seconds
Executing <Task pending name='Task-53' coro=<IsolatedAsyncioTestCase._asyncioLoopRunner() running at /home/openkylin/python3.8/Lib/unittest/async_case.py:96> wait_for=<Future pending cb=[<TaskWakeupMethWrapper object at 0x3ff2121cd0>()] created at /home/openkylin/python3.8/Lib/asyncio/base_events.py:422> created at /home/openkylin/python3.8/Lib/unittest/async_case.py:118> took 0.185 seconds
Executing <Task pending name='Task-55' coro=<IsolatedAsyncioTestCase._asyncioLoopRunner() running at /home/openkylin/python3.8/Lib/unittest/async_case.py:96> wait_for=<Future pending cb=[<TaskWakeupMethWrapper object at 0x3ff2068280>()] created at /home/openkylin/python3.8/Lib/asyncio/base_events.py:422> created at /home/openkylin/python3.8/Lib/unittest/async_case.py:118> took 0.181 seconds
Executing <Task pending name='Task-57' coro=<IsolatedAsyncioTestCase._asyncioLoopRunner() running at /home/openkylin/python3.8/Lib/unittest/async_case.py:96> wait_for=<Future pending cb=[<TaskWakeupMethWrapper object at 0x3ff2068c10>()] created at /home/openkylin/python3.8/Lib/asyncio/base_events.py:422> created at /home/openkylin/python3.8/Lib/unittest/async_case.py:118> took 0.239 seconds
Executing <Task pending name='Task-59' coro=<IsolatedAsyncioTestCase._asyncioLoopRunner() running at /home/openkylin/python3.8/Lib/unittest/async_case.py:96> wait_for=<Future pending cb=[<TaskWakeupMethWrapper object at 0x3ff2102760>()] created at /home/openkylin/python3.8/Lib/asyncio/base_events.py:422> created at /home/openkylin/python3.8/Lib/unittest/async_case.py:118> took 0.179 seconds
Executing <Task pending name='Task-61' coro=<IsolatedAsyncioTestCase._asyncioLoopRunner() running at /home/openkylin/python3.8/Lib/unittest/async_case.py:96> wait_for=<Future pending cb=[<TaskWakeupMethWrapper object at 0x3ff2177b80>()] created at /home/openkylin/python3.8/Lib/asyncio/base_events.py:422> created at /home/openkylin/python3.8/Lib/unittest/async_case.py:118> took 0.140 seconds
Warning -- sys.gettrace was modified by test_unittest
  Before: <bound method Trace.globaltrace_lt of <trace.Trace object at 0x3ff37b8640>>
  After:  None 
test test_unittest failed -- multiple errors occurred; run in verbose mode for details
0:04:32 load avg: 1.00 [  8/423/1] test_doctest -- test_unittest failed in 3 min 41 sec
0:05:09 load avg: 1.13 [  9/423/1] test_doctest2 -- test_doctest passed in 36.8 sec
0:05:10 load avg: 1.13 [ 10/423/1] test_support
0:06:15 load avg: 1.04 [ 11/423/1] test___all__ -- test_support passed in 1 min 4 sec
0:06:39 load avg: 1.03 [ 12/423/1] test___future__
0:06:40 load avg: 1.03 [ 13/423/1] test__locale
0:06:41 load avg: 1.03 [ 14/423/1] test__opcode
0:06:44 load avg: 1.02 [ 15/423/1] test__osx_support
0:06:45 load avg: 1.02 [ 16/423/1] test__xxsubinterpreters
0:07:06 load avg: 1.02 [ 17/423/1] test_abc
0:07:07 load avg: 1.02 [ 18/423/1] test_abstract_numbers
0:07:08 load avg: 1.02 [ 19/423/1] test_aifc
0:07:14 load avg: 1.01 [ 20/423/1] test_argparse
0:12:08 load avg: 1.00 [ 21/423/1] test_array -- test_argparse passed in 4 min 54 sec
test test_array failed -- multiple errors occurred; run in verbose mode for details
0:12:44 load avg: 1.00 [ 22/423/2] test_asdl_parser -- test_array failed in 35.8 sec
test_asdl_parser skipped -- test irrelevant for an installed Python
0:12:44 load avg: 1.00 [ 23/423/2] test_ast -- test_asdl_parser skipped
0:13:03 load avg: 1.00 [ 24/423/2] test_asyncgen
0:13:07 load avg: 1.00 [ 25/423/2] test_asynchat
0:13:12 load avg: 0.92 [ 26/423/2] test_asyncio
0:23:46 load avg: 1.02 [ 27/423/2] test_asyncore -- test_asyncio passed in 10 min 33 sec
0:23:52 load avg: 0.94 [ 28/423/2] test_atexit
0:23:55 load avg: 0.95 [ 29/423/2] test_audioop
0:23:57 load avg: 0.95 [ 30/423/2] test_audit
0:24:19 load avg: 0.97 [ 31/423/2] test_augassign
0:24:21 load avg: 0.97 [ 32/423/2] test_base64
0:24:28 load avg: 0.97 [ 33/423/2] test_baseexception
0:24:29 load avg: 0.97 [ 34/423/2] test_bdb
0:24:32 load avg: 0.97 [ 35/423/2] test_bigaddrspace
0:24:33 load avg: 0.97 [ 36/423/2] test_bigmem
0:24:37 load avg: 0.97 [ 37/423/2] test_binascii
0:24:39 load avg: 0.98 [ 38/423/2] test_binhex
0:24:40 load avg: 0.98 [ 39/423/2] test_binop
0:24:42 load avg: 0.98 [ 40/423/2] test_bisect
0:24:47 load avg: 0.98 [ 41/423/2] test_bool
0:24:49 load avg: 0.98 [ 42/423/2] test_buffer
0:50:17 load avg: 1.00 [ 43/423/2] test_bufio -- test_buffer passed in 25 min 27 sec
0:50:39 load avg: 1.00 [ 44/423/2] test_bytes
0:54:08 load avg: 1.00 [ 45/423/2] test_bz2 -- test_bytes passed in 3 min 29 sec
0:54:36 load avg: 1.00 [ 46/423/2] test_c_locale_coercion
0:55:10 load avg: 1.00 [ 47/423/2] test_calendar -- test_c_locale_coercion passed in 33.8 sec
0:55:42 load avg: 1.05 [ 48/423/2] test_call -- test_calendar passed in 31.9 sec
0:55:46 load avg: 1.04 [ 49/423/2] test_capi
0:56:04 load avg: 1.03 [ 50/423/2] test_cgi
0:56:07 load avg: 1.03 [ 51/423/2] test_cgitb
0:56:19 load avg: 1.02 [ 52/423/2] test_charmapcodec
0:56:20 load avg: 1.02 [ 53/423/2] test_class
0:56:22 load avg: 1.02 [ 54/423/2] test_clinic
0:56:35 load avg: 1.02 [ 55/423/2] test_cmath
0:56:41 load avg: 1.02 [ 56/423/2] test_cmd
0:56:43 load avg: 1.02 [ 57/423/2] test_cmd_line
0:57:26 load avg: 1.01 [ 58/423/2] test_cmd_line_script -- test_cmd_line passed in 43.3 sec
test test_cmd_line_script failed -- multiple errors occurred; run in verbose mode for details
0:58:20 load avg: 1.00 [ 59/423/3] test_code -- test_cmd_line_script failed in 53.8 sec
0:58:22 load avg: 1.00 [ 60/423/3] test_code_module
Warning -- warnings.filters was modified by test_code_module
  Before: (274668417920, [('default', None, <class 'DeprecationWarning'>, '__main__', 0), ('ignore', None, <class 'DeprecationWarning'>, None, 0), ('ignore', None, <class 'PendingDeprecationWarning'>, None, 0), ('ignore', None, <class 'ImportWarning'>, None, 0), ('ignore', None, <class 'ResourceWarning'>, None, 0)], [('default', None, <class 'DeprecationWarning'>, '__main__', 0), ('ignore', None, <class 'DeprecationWarning'>, None, 0), ('ignore', None, <class 'PendingDeprecationWarning'>, None, 0), ('ignore', None, <class 'ImportWarning'>, None, 0), ('ignore', None, <class 'ResourceWarning'>, None, 0)])
  After:  (274668417920, [('default', None, <class 'DeprecationWarning'>, '__main__', 0), ('ignore', None, <class 'DeprecationWarning'>, None, 0), ('ignore', None, <class 'PendingDeprecationWarning'>, None, 0), ('ignore', None, <class 'ImportWarning'>, None, 0), ('ignore', None, <class 'ResourceWarning'>, None, 0)], [('ignore', re.compile('apt API not stable yet', re.IGNORECASE), <class 'FutureWarning'>, None, 0), ('default', None, <class 'DeprecationWarning'>, '__main__', 0), ('ignore', None, <class 'DeprecationWarning'>, None, 0), ('ignore', None, <class 'PendingDeprecationWarning'>, None, 0), ('ignore', None, <class 'ImportWarning'>, None, 0), ('ignore', None, <class 'ResourceWarning'>, None, 0)]) 
test test_code_module failed -- multiple errors occurred; run in verbose mode for details
0:58:31 load avg: 1.00 [ 61/423/4] test_codeccallbacks -- test_code_module failed
0:58:33 load avg: 1.00 [ 62/423/4] test_codecencodings_cn
0:58:55 load avg: 1.00 [ 63/423/4] test_codecencodings_hk
0:58:57 load avg: 1.00 [ 64/423/4] test_codecencodings_iso2022
0:59:18 load avg: 1.00 [ 65/423/4] test_codecencodings_jp
1:00:16 load avg: 1.06 [ 66/423/4] test_codecencodings_kr -- test_codecencodings_jp passed in 57.4 sec
1:00:29 load avg: 1.05 [ 67/423/4] test_codecencodings_tw
1:00:35 load avg: 1.05 [ 68/423/4] test_codecmaps_cn
1:00:36 load avg: 1.04 [ 69/423/4] test_codecmaps_hk
1:00:38 load avg: 1.04 [ 70/423/4] test_codecmaps_jp
1:00:39 load avg: 1.04 [ 71/423/4] test_codecmaps_kr
1:00:40 load avg: 1.04 [ 72/423/4] test_codecmaps_tw
1:00:41 load avg: 1.04 [ 73/423/4] test_codecs
1:03:11 load avg: 1.00 [ 74/423/4] test_codeop -- test_codecs passed in 2 min 29 sec
1:03:12 load avg: 1.00 [ 75/423/4] test_collections
1:04:15 load avg: 1.04 [ 76/423/4] test_colorsys -- test_collections passed in 1 min 3 sec
1:04:18 load avg: 1.04 [ 77/423/4] test_compare
1:04:19 load avg: 1.04 [ 78/423/4] test_compile
1:04:38 load avg: 1.02 [ 79/423/4] test_compileall
1:05:38 load avg: 1.29 [ 80/423/4] test_complex -- test_compileall passed in 59.8 sec
1:06:04 load avg: 1.19 [ 81/423/4] test_concurrent_futures
test test_concurrent_futures failed -- multiple errors occurred; run in verbose mode for details
1:10:56 load avg: 1.43 [ 82/423/5] test_configparser -- test_concurrent_futures failed in 4 min 52 sec
1:11:44 load avg: 1.20 [ 83/423/5] test_contains -- test_configparser passed in 48.1 sec
1:11:46 load avg: 1.18 [ 84/423/5] test_context
1:14:00 load avg: 1.02 [ 85/423/5] test_contextlib -- test_context passed in 2 min 13 sec
1:14:07 load avg: 1.02 [ 86/423/5] test_contextlib_async
Task was destroyed but it is pending!
task: <Task pending name='Task-3884' coro=<<async_generator_athrow without __name__>()>>
Task was destroyed but it is pending!
task: <Task pending name='Task-3886' coro=<<async_generator_athrow without __name__>()>>
Task was destroyed but it is pending!
task: <Task pending name='Task-3891' coro=<<async_generator_athrow without __name__>()>>
1:14:15 load avg: 1.01 [ 87/423/5] test_copy
1:14:18 load avg: 1.01 [ 88/423/5] test_copyreg
1:14:19 load avg: 1.01 [ 89/423/5] test_coroutines
1:14:29 load avg: 1.01 [ 90/423/5] test_cprofile
1:14:40 load avg: 1.01 [ 91/423/5] test_crashers
1:14:42 load avg: 1.01 [ 92/423/5] test_crypt
1:14:50 load avg: 1.01 [ 93/423/5] test_csv
1:14:56 load avg: 1.01 [ 94/423/5] test_ctypes
1:15:18 load avg: 1.00 [ 95/423/5] test_curses
test_curses skipped -- Use of the 'curses' resource not enabled
1:15:19 load avg: 1.00 [ 96/423/5] test_dataclasses -- test_curses skipped (resource denied)
1:15:36 load avg: 1.00 [ 97/423/5] test_datetime
1:24:06 load avg: 1.00 [ 98/423/5] test_dbm -- test_datetime passed in 8 min 29 sec
BDB0004 fop_read_meta: @test_4441_tmp_ndbm.db: unexpected file type or format
1:24:09 load avg: 1.00 [ 99/423/5] test_dbm_dumb
1:24:13 load avg: 1.00 [100/423/5] test_dbm_gnu
test_dbm_gnu skipped -- No module named '_gdbm', please install the python3-gdbm package
1:24:14 load avg: 1.00 [101/423/5] test_dbm_ndbm -- test_dbm_gnu skipped
BDB0111 DB->del: attempt to modify a read-only database
BDB0111 DB->del: attempt to modify a read-only database
BDB0111 DB->put: attempt to modify a read-only database
1:24:16 load avg: 1.00 [102/423/5] test_decimal
1:31:42 load avg: 1.00 [103/423/5] test_decorators -- test_decimal passed in 7 min 26 sec
1:31:44 load avg: 1.00 [104/423/5] test_defaultdict
1:31:45 load avg: 1.00 [105/423/5] test_deque
1:34:29 load avg: 1.03 [106/423/5] test_descr -- test_deque passed in 2 min 43 sec
test test_descr failed -- Traceback (most recent call last):
  File "/home/openkylin/python3.8/Lib/test/test_descr.py", line 1276, in test_slots
    self.assertEqual(orig_objects, new_objects)
AssertionError: 94338 != 94342

1:35:36 load avg: 1.01 [107/423/6] test_descrtut -- test_descr failed in 1 min 7 sec
1:35:39 load avg: 1.01 [108/423/6] test_devpoll
test_devpoll skipped -- test works only on Solaris OS family
1:35:40 load avg: 1.01 [109/423/6] test_dict_version -- test_devpoll skipped
1:35:41 load avg: 1.01 [110/423/6] test_dictcomps
1:35:43 load avg: 1.01 [111/423/6] test_dictviews
1:35:45 load avg: 1.01 [112/423/6] test_difflib
1:38:26 load avg: 1.00 [113/423/6] test_dis -- test_difflib passed in 2 min 41 sec
1:39:15 load avg: 1.00 [114/423/6] test_distutils -- test_dis passed in 48.8 sec
test test_distutils failed -- multiple errors occurred; run in verbose mode for details
1:39:49 load avg: 1.00 [115/423/7] test_docxmlrpc -- test_distutils failed in 34.3 sec
1:39:57 load avg: 0.92 [116/423/7] test_dtrace
1:39:59 load avg: 0.93 [117/423/7] test_dummy_thread
1:40:01 load avg: 0.93 [118/423/7] test_dummy_threading
1:40:03 load avg: 0.93 [119/423/7] test_dynamic
1:40:05 load avg: 0.93 [120/423/7] test_dynamicclassattribute
1:40:07 load avg: 0.93 [121/423/7] test_eintr
1:40:25 load avg: 1.09 [122/423/7] test_email
1:44:05 load avg: 1.01 [123/423/7] test_embed -- test_email passed in 3 min 39 sec
1:44:07 load avg: 1.01 [124/423/7] test_ensurepip
test test_ensurepip crashed -- Traceback (most recent call last):
  File "/home/openkylin/python3.8/Lib/test/libregrtest/runtest.py", line 270, in _runtest_inner
    refleak = _runtest_inner2(ns, test_name)
  File "/home/openkylin/python3.8/Lib/test/libregrtest/runtest.py", line 221, in _runtest_inner2
    the_module = importlib.import_module(abstest)
  File "/home/openkylin/python3.8/Lib/importlib/__init__.py", line 127, in import_module
    return _bootstrap._gcd_import(name[level:], package, level)
  File "<frozen importlib._bootstrap>", line 1014, in _gcd_import
  File "<frozen importlib._bootstrap>", line 991, in _find_and_load
  File "<frozen importlib._bootstrap>", line 975, in _find_and_load_unlocked
  File "<frozen importlib._bootstrap>", line 671, in _load_unlocked
  File "<frozen importlib._bootstrap_external>", line 783, in exec_module
  File "<frozen importlib._bootstrap>", line 219, in _call_with_frames_removed
  File "/home/openkylin/python3.8/Lib/test/test_ensurepip.py", line 150, in <module>
    def fake_pip(version=ensurepip._PIP_VERSION):
AttributeError: module 'ensurepip' has no attribute '_PIP_VERSION'

1:44:08 load avg: 1.01 [125/423/8] test_enum -- test_ensurepip failed
1:46:54 load avg: 1.23 [126/423/8] test_enumerate -- test_enum passed in 2 min 46 sec
1:46:59 load avg: 1.29 [127/423/8] test_eof
1:47:04 load avg: 1.27 [128/423/8] test_epoll
1:47:09 load avg: 1.24 [129/423/8] test_errno
1:47:10 load avg: 1.24 [130/423/8] test_exception_hierarchy
1:47:12 load avg: 1.24 [131/423/8] test_exception_variations
1:47:14 load avg: 1.22 [132/423/8] test_extcall
1:47:17 load avg: 1.22 [133/423/8] test_faulthandler
1:47:57 load avg: 0.95 [134/423/8] test_fcntl -- test_faulthandler passed in 39.5 sec
1:47:59 load avg: 0.96 [135/423/8] test_file
1:48:16 load avg: 0.97 [136/423/8] test_file_eintr
1:48:30 load avg: 0.97 [137/423/8] test_filecmp
1:48:33 load avg: 0.98 [138/423/8] test_fileinput
1:48:36 load avg: 0.98 [139/423/8] test_fileio
Warning -- sys.gettrace was modified by test_fileio
  Before: <bound method Trace.globaltrace_lt of <trace.Trace object at 0x3ff37b8640>>
  After:  None 
1:48:38 load avg: 0.98 [140/423/9] test_finalization -- test_fileio failed (env changed)
1:48:50 load avg: 0.98 [141/423/9] test_float
1:49:10 load avg: 0.99 [142/423/9] test_flufl
1:49:12 load avg: 0.99 [143/423/9] test_fnmatch
1:49:15 load avg: 0.99 [144/423/9] test_fork1
1:49:25 load avg: 0.84 [145/423/9] test_format
1:49:27 load avg: 0.84 [146/423/9] test_fractions
1:49:30 load avg: 0.85 [147/423/9] test_frame
test test_frame failed -- multiple errors occurred; run in verbose mode for details
1:49:33 load avg: 0.86 [148/423/10] test_frozen -- test_frame failed
1:49:34 load avg: 0.86 [149/423/10] test_fstring
1:49:42 load avg: 0.87 [150/423/10] test_ftplib
1:50:10 load avg: 0.79 [151/423/10] test_funcattrs
1:50:12 load avg: 0.79 [152/423/10] test_functools
Warning -- sys.gettrace was modified by test_functools
  Before: <bound method Trace.globaltrace_lt of <trace.Trace object at 0x3ff37b8640>>
  After:  None 
1:50:21 load avg: 0.82 [153/423/11] test_future -- test_functools failed (env changed)
1:50:24 load avg: 0.83 [154/423/11] test_future3
1:50:26 load avg: 0.83 [155/423/11] test_future4
1:50:28 load avg: 0.85 [156/423/11] test_future5
1:50:29 load avg: 0.85 [157/423/11] test_gc
test test_gc failed -- Traceback (most recent call last):
  File "/home/openkylin/python3.8/Lib/test/test_gc.py", line 817, in test_get_objects_arguments
    self.assertEqual(len(gc.get_objects()),
AssertionError: 103344 != 103345

1:51:12 load avg: 0.92 [158/423/12] test_gdb -- test_gc failed in 42.9 sec
test_gdb skipped -- Couldn't find gdb on the path
1:51:14 load avg: 0.93 [159/423/12] test_generator_stop -- test_gdb skipped
1:51:16 load avg: 0.93 [160/423/12] test_generators
Warning -- sys.gettrace was modified by test_generators
  Before: <bound method Trace.globaltrace_lt of <trace.Trace object at 0x3ff37b8640>>
  After:  None 
test test_generators failed -- Traceback (most recent call last):
  File "/home/openkylin/python3.8/Lib/test/test_generators.py", line 40, in test_raise_and_yield_from
    _testcapi.raise_SIGINT_then_send_None(gen)
AssertionError: <class 'KeyboardInterrupt'> is not <class 'StopIteration'>

1:51:19 load avg: 0.94 [161/423/13] test_genericclass -- test_generators failed
1:51:21 load avg: 0.94 [162/423/13] test_genericpath
1:51:23 load avg: 0.94 [163/423/13] test_genexps
1:51:25 load avg: 0.94 [164/423/13] test_getargs2
1:51:31 load avg: 0.95 [165/423/13] test_getopt
1:51:33 load avg: 0.95 [166/423/13] test_getpass
1:51:42 load avg: 0.95 [167/423/13] test_gettext
1:51:49 load avg: 0.96 [168/423/13] test_glob
1:52:28 load avg: 0.98 [169/423/13] test_global -- test_glob passed in 39.0 sec
1:52:30 load avg: 0.98 [170/423/13] test_grp
1:52:33 load avg: 0.98 [171/423/13] test_gzip
1:52:45 load avg: 0.99 [172/423/13] test_hash
1:52:58 load avg: 0.99 [173/423/13] test_hashlib
1:53:32 load avg: 1.15 [174/423/13] test_heapq -- test_hashlib passed in 34.1 sec
1:55:20 load avg: 1.07 [175/423/13] test_hmac -- test_heapq passed in 1 min 48 sec
1:55:22 load avg: 1.07 [176/423/13] test_html
1:55:25 load avg: 1.06 [177/423/13] test_htmlparser
1:55:35 load avg: 1.05 [178/423/13] test_http_cookiejar
1:55:48 load avg: 1.04 [179/423/13] test_http_cookies
1:55:52 load avg: 1.04 [180/423/13] test_httplib
1:55:57 load avg: 1.04 [181/423/13] test_httpservers
1:56:17 load avg: 1.10 [182/423/13] test_idle
test_idle skipped -- No module named '_tkinter', please install the python3-tk package
1:56:18 load avg: 1.10 [183/423/13] test_imaplib -- test_idle skipped
1:56:37 load avg: 1.07 [184/423/13] test_imghdr
1:56:40 load avg: 1.07 [185/423/13] test_imp
1:56:44 load avg: 1.06 [186/423/13] test_import
1:57:08 load avg: 1.04 [187/423/13] test_importlib
1:58:16 load avg: 1.01 [188/423/13] test_index -- test_importlib passed in 1 min 8 sec
1:58:19 load avg: 1.01 [189/423/13] test_inspect
test test_inspect failed -- Traceback (most recent call last):
  File "/home/openkylin/python3.8/Lib/test/test_inspect.py", line 3936, in test_details
    self.assertIn(module.__file__, output)
AssertionError: '/home/openkylin/python3.8/Lib/unittest/__init__.py' not found in "Target: unittest\nOrigin: /usr/lib/python3.8/unittest/__init__.py\nCached: /usr/lib/python3.8/unittest/__pycache__/__init__.cpython-38.pyc\nLoader: <_frozen_importlib_external.SourceFileLoader object at 0x3fef0cc0d0>\nSubmodule search path: ['/usr/lib/python3.8/unittest']\n\n\n"

1:58:55 load avg: 1.00 [190/423/14] test_int -- test_inspect failed in 36.3 sec
1:58:59 load avg: 1.00 [191/423/14] test_int_literal
1:59:01 load avg: 1.00 [192/423/14] test_io
Warning -- sys.gettrace was modified by test_io
  Before: <bound method Trace.globaltrace_lt of <trace.Trace object at 0x3ff37b8640>>
  After:  None 
2:00:48 load avg: 0.81 [193/423/15] test_ioctl -- test_io failed (env changed) in 1 min 46 sec
2:00:50 load avg: 0.83 [194/423/15] test_ipaddress
2:01:13 load avg: 0.88 [195/423/15] test_isinstance
2:01:16 load avg: 0.89 [196/423/15] test_iter
2:01:20 load avg: 0.90 [197/423/15] test_iterlen
2:01:23 load avg: 0.90 [198/423/15] test_itertools
2:12:30 load avg: 1.01 [199/423/15] test_json -- test_itertools passed in 11 min 7 sec
Warning -- sys.gettrace was modified by test_json
  Before: <bound method Trace.globaltrace_lt of <trace.Trace object at 0x3ff37b8640>>
  After:  None 
2:12:55 load avg: 1.00 [200/423/16] test_keyword -- test_json failed (env changed)
2:12:58 load avg: 1.00 [201/423/16] test_keywordonlyarg
2:13:01 load avg: 1.00 [202/423/16] test_kqueue
test_kqueue skipped -- test works only on BSD
2:13:02 load avg: 1.00 [203/423/16] test_largefile -- test_kqueue skipped
2:13:05 load avg: 1.00 [204/423/16] test_lib2to3
2:45:11 load avg: 1.01 [205/423/16] test_linecache -- test_lib2to3 passed in 32 min 5 sec
2:45:14 load avg: 1.01 [206/423/16] test_list
2:45:21 load avg: 1.01 [207/423/16] test_listcomps
2:45:24 load avg: 1.01 [208/423/16] test_lltrace
2:45:28 load avg: 1.01 [209/423/16] test_locale
2:45:34 load avg: 1.01 [210/423/16] test_logging
2:46:21 load avg: 0.79 [211/423/16] test_long -- test_logging passed in 47.2 sec
2:51:24 load avg: 1.01 [212/423/16] test_longexp -- test_long passed in 5 min 3 sec
2:51:28 load avg: 1.01 [213/423/16] test_lzma
2:51:49 load avg: 1.00 [214/423/16] test_mailbox
2:52:47 load avg: 1.03 [215/423/16] test_mailcap -- test_mailbox passed in 58.1 sec
2:52:53 load avg: 1.03 [216/423/16] test_marshal
2:52:59 load avg: 1.03 [217/423/16] test_math
2:59:04 load avg: 1.02 [218/423/16] test_memoryio -- test_math passed in 6 min 5 sec
2:59:12 load avg: 1.02 [219/423/16] test_memoryview
2:59:25 load avg: 1.01 [220/423/16] test_metaclass
2:59:27 load avg: 1.01 [221/423/16] test_mimetypes
2:59:31 load avg: 1.01 [222/423/16] test_minidom
2:59:37 load avg: 1.01 [223/423/16] test_mmap
2:59:45 load avg: 1.01 [224/423/16] test_module
test test_module failed -- Traceback (most recent call last):
  File "/home/openkylin/python3.8/Lib/test/test_module.py", line 272, in test_module_finalization_at_shutdown
    rc, out, err = assert_python_ok("-c", "from test import final_a")
  File "/home/openkylin/python3.8/Lib/test/support/script_helper.py", line 157, in assert_python_ok
    return _assert_python(True, *args, **env_vars)
  File "/home/openkylin/python3.8/Lib/test/support/script_helper.py", line 143, in _assert_python
    res.fail(cmd_line)
  File "/home/openkylin/python3.8/Lib/test/support/script_helper.py", line 70, in fail
    raise AssertionError("Process return code is %d\n"
AssertionError: Process return code is 1
command line: ['/usr/bin/python3.8', '-X', 'faulthandler', '-I', '-c', 'from test import final_a']

stdout:
---

---

stderr:
---
Traceback (most recent call last):
  File "<string>", line 1, in <module>
ImportError: cannot import name 'final_a' from 'test' (/usr/lib/python3.8/test/__init__.py)
---

2:59:51 load avg: 1.01 [225/423/17] test_modulefinder -- test_module failed
3:00:25 load avg: 1.08 [226/423/17] test_msilib -- test_modulefinder passed in 34.2 sec
test_msilib skipped -- No module named '_msi'
3:00:27 load avg: 1.07 [227/423/17] test_multibytecodec -- test_msilib skipped
3:01:02 load avg: 1.04 [228/423/17] test_multiprocessing_fork -- test_multibytecodec passed in 34.9 sec
Traceback (most recent call last):
  File "<string>", line 1, in <module>
ModuleNotFoundError: No module named 'test._test_multiprocessing'
Traceback (most recent call last):
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 278, in main
    code = _serve_one(child_r, fds,
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 317, in _serve_one
    code = spawn._main(child_r, parent_sentinel)
  File "/usr/lib/python3.8/multiprocessing/spawn.py", line 126, in _main
    self = reduction.pickle.load(from_parent)
ModuleNotFoundError: No module named 'test.test_multiprocessing_fork'
Traceback (most recent call last):
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 278, in main
    code = _serve_one(child_r, fds,
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 317, in _serve_one
    code = spawn._main(child_r, parent_sentinel)
  File "/usr/lib/python3.8/multiprocessing/spawn.py", line 126, in _main
    self = reduction.pickle.load(from_parent)
ModuleNotFoundError: No module named 'test.test_multiprocessing_fork'
/usr/lib/python3.8/multiprocessing/resource_tracker.py:216: UserWarning: resource_tracker: There appear to be 1 leaked shared_memory objects to clean up at shutdown
  warnings.warn('resource_tracker: There appear to be %d '
/usr/lib/python3.8/multiprocessing/resource_tracker.py:229: UserWarning: resource_tracker: '/psm_82e1c515': [Errno 2] No such file or directory: '/psm_82e1c515'
  warnings.warn('resource_tracker: %r: %s' % (name, e))
test test_multiprocessing_fork failed -- multiple errors occurred; run in verbose mode for details
3:07:49 load avg: 2.52 [229/423/18] test_multiprocessing_forkserver -- test_multiprocessing_fork failed in 6 min 47 sec
Traceback (most recent call last):
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 278, in main
    code = _serve_one(child_r, fds,
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 317, in _serve_one
    code = spawn._main(child_r, parent_sentinel)
  File "/usr/lib/python3.8/multiprocessing/spawn.py", line 126, in _main
    self = reduction.pickle.load(from_parent)
ModuleNotFoundError: No module named 'test.test_multiprocessing_forkserver'
Traceback (most recent call last):
  File "<string>", line 1, in <module>
ModuleNotFoundError: No module named 'test._test_multiprocessing'
Traceback (most recent call last):
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 278, in main
    code = _serve_one(child_r, fds,
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 317, in _serve_one
    code = spawn._main(child_r, parent_sentinel)
  File "/usr/lib/python3.8/multiprocessing/spawn.py", line 126, in _main
    self = reduction.pickle.load(from_parent)
ModuleNotFoundError: No module named 'test.test_multiprocessing_forkserver'
Traceback (most recent call last):
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 278, in main
    code = _serve_one(child_r, fds,
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 317, in _serve_one
    code = spawn._main(child_r, parent_sentinel)
  File "/usr/lib/python3.8/multiprocessing/spawn.py", line 126, in _main
    self = reduction.pickle.load(from_parent)
ModuleNotFoundError: No module named 'test.test_multiprocessing_forkserver'
Traceback (most recent call last):
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 278, in main
    code = _serve_one(child_r, fds,
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 317, in _serve_one
    code = spawn._main(child_r, parent_sentinel)
  File "/usr/lib/python3.8/multiprocessing/spawn.py", line 126, in _main
    self = reduction.pickle.load(from_parent)
ModuleNotFoundError: No module named 'test.test_multiprocessing_forkserver'
Traceback (most recent call last):
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 278, in main
    code = _serve_one(child_r, fds,
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 317, in _serve_one
    code = spawn._main(child_r, parent_sentinel)
  File "/usr/lib/python3.8/multiprocessing/spawn.py", line 126, in _main
    self = reduction.pickle.load(from_parent)
ModuleNotFoundError: No module named 'test._test_multiprocessing'
Traceback (most recent call last):
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 278, in main
    code = _serve_one(child_r, fds,
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 317, in _serve_one
    code = spawn._main(child_r, parent_sentinel)
  File "/usr/lib/python3.8/multiprocessing/spawn.py", line 126, in _main
    self = reduction.pickle.load(from_parent)
ModuleNotFoundError: No module named 'test._test_multiprocessing'
Traceback (most recent call last):
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 278, in main
    code = _serve_one(child_r, fds,
  File "/usr/lib/python3.8/multiprocessing/forkserver.py", line 317, in _serve_one
    code = spawn._main(child_r, parent_sentinel)
  File "/usr/lib/python3.8/multiprocessing/spawn.py", line 126, in _main
    self = reduction.pickle.load(from_parent)
ModuleNotFoundError: No module named 'test._test_multiprocessing'
```

```
^C
Warning -- multiprocessing.process._dangling was modified by test_multiprocessing_forkserver
  Before: set()
  After:  {<weakref at 0x3fd33c2d10; to 'Process' at 0x3fd2299370>} 

test_multiprocessing_fork failed in 6 min 47 sec

== Tests result: FAILURE, INTERRUPTED ==
Test suite interrupted by signal SIGINT.

195 tests omitted:
    test_multiprocessing_forkserver test_multiprocessing_main_handling
    test_multiprocessing_spawn test_named_expressions test_netrc
    test_nis test_nntplib test_normalization test_ntpath
    test_numeric_tower test_openpty test_operator test_optparse
    test_ordered_dict test_os test_ossaudiodev test_osx_env
    test_parser test_pathlib test_pdb test_peepholer test_pickle
    test_picklebuffer test_pickletools test_pipes test_pkg
    test_pkgimport test_pkgutil test_platform test_plistlib test_poll
    test_popen test_poplib test_positional_only_arg test_posix
    test_posixpath test_pow test_pprint test_print test_profile
    test_property test_pstats test_pty test_pulldom test_pwd
    test_py_compile test_pyclbr test_pydoc test_pyexpat test_queue
    test_quopri test_raise test_random test_range test_re
    test_readline test_regrtest test_repl test_reprlib test_resource
    test_richcmp test_rlcompleter test_robotparser test_runpy test_sax
    test_sched test_scope test_script_helper test_secrets test_select
    test_selectors test_set test_setcomps test_shelve test_shlex
    test_shutil test_signal test_site test_slice test_smtpd
    test_smtplib test_smtpnet test_sndhdr test_socket
    test_socketserver test_sort test_source_encoding test_spwd
    test_sqlite test_ssl test_startfile test_stat test_statistics
    test_strftime test_string test_string_literals test_stringprep
    test_strptime test_strtod test_struct test_structmembers
    test_structseq test_subclassinit test_subprocess test_sunau
    test_sundry test_super test_symbol test_symtable test_syntax
    test_sys test_sys_setprofile test_sys_settrace test_sysconfig
    test_syslog test_tabnanny test_tarfile test_tcl test_telnetlib
    test_tempfile test_textwrap test_thread test_threaded_import
    test_threadedtempfile test_threading test_threading_local
    test_threadsignals test_time test_timeit test_timeout test_tix
    test_tk test_tokenize test_tools test_trace test_traceback
    test_tracemalloc test_ttk_guionly test_ttk_textonly test_tuple
    test_turtle test_type_comments test_typechecks test_typing
    test_ucn test_unary test_unicode test_unicode_file
    test_unicode_file_functions test_unicode_identifiers
    test_unicodedata test_univnewlines test_unpack test_unpack_ex
    test_urllib test_urllib2 test_urllib2_localnet test_urllib2net
    test_urllib_response test_urllibnet test_urlparse test_userdict
    test_userlist test_userstring test_utf8_mode test_utf8source
    test_uu test_uuid test_venv test_wait3 test_wait4 test_warnings
    test_wave test_weakref test_weakset test_webbrowser
    test_winconsoleio test_winreg test_winsound test_with test_wsgiref
    test_xdrlib test_xml_dom_minicompat test_xml_etree
    test_xml_etree_c test_xmlrpc test_xmlrpc_net test_xxtestfuzz
    test_yield_from test_zipapp test_zipfile test_zipfile64
    test_zipimport test_zipimport_support test_zlib

202 tests OK.

14 tests failed:
    test_array test_cmd_line_script test_code_module
    test_concurrent_futures test_descr test_distutils test_ensurepip
    test_frame test_gc test_generators test_inspect test_module
    test_multiprocessing_fork test_unittest

4 tests altered the execution environment:
    test_fileio test_functools test_io test_json

8 tests skipped:
    test_asdl_parser test_curses test_dbm_gnu test_devpoll test_gdb
    test_idle test_kqueue test_msilib
```

