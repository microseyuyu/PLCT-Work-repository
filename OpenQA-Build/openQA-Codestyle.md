# openQA 测试编写准则

## 测试命名

所有测试都存放在 `/var/lib/openqa/share/tests/DISTRI_NAME/tests` 下
（如 `/var/lib/openqa/share/tests/openeuler/tests`），且必须位于二级目录中
（如 `/var/lib/openqa/share/tests/openeuler/tests/xfce`）。

考虑到测试位于二级子目录下，单个测试的命名中则不再需要包含所测试的程序名，只需要
包含测试项目的描述性信息。

```
gimp/gimp_start		:( BAD
gimp/start		:) GOOD
```

如果一个程序包含多个组件（如 `xfce` 包含 `panel` `application finder` 等），我们
需要将组件名称附加在模块名开头。

```
xfce/fold_unfold				:( BAD, WHO KNOWS WHAT IT IS FOR
xfce/appfinder_fold_unfold			:) GOOD
```

要注意，在 Schedule 文件中引用测试时不需要带 `.pm` 后缀名（因为 openQA 将测试作
为 Perl 模块加载，Perl 中加载模块的 `use` 语句引用一个模块时不需要后缀名），这
也就意味着所说的 `gimp/start` 测试对应的文件是
`/var/lib/openqa/share/tests/openeuler/tests/gimp/start.pm`。不作额外说明，我们
一般用前者代指一个测试。

```
Who coded /var/lib/openqa/share/tests/openeuler/tests/gimp/start.pm?
						:| NOT VERY GOOD, TOO LONG
Who coded gimp/start				:) GOOD
```

要注意，Perl 模块命名中不能包含连字符，只能使用下划线。

```
xfce/appfinder-run				:( BAD AND WRONG
xfce/appfinder_run				:) GOOD
```

## needles 命名

首先，必须注意，`assert_screen` 等 API 的参数为 needle 的 tag，而非 needle 名字
，意味着只要有一个带有该 tag 的 needle 与屏幕匹配，该检查就成功。一般的，我们总
是保持 needle 名称与其 tag 一致。

```
NeedleName: xfce_application_finder-list-showed-20230324
NeedleTag:  what_a_fucking_tag					:| NOT VERY GOOD

NeedleName: xfce_application_finder-list-showed-20230324
NeedleTag:  xfce_application_finder-list-showed-20230324	:) GOOD
```

同一个发行版中的不同测试使用的 needle 共享名字空间，这意味着如果
`installation/open_window` 和 `xfce/application_finder` 都用到了 needle
`check-window-poped`，在编辑 needle 时就会发生冲突而相互覆盖的情况。

因此，我们希望 needle 的命名遵循以下规则（needle 名字应当与 tag 一致，此处不再赘
述）：

- Needle 名称总是以使用它的测试作为名字的开头，其中斜线被替换为下划线。

```
# Used by xfce/application_finder_fold_unfold
list-showed-20230324							:( BAD
xfce_application_finder_fold_unfold-list-showed-20230324		:) GOOD
```

特例：如果一个 needle 被测试同一个组件/软件的不同测试所使用，其可以以使用之的最
小共同分类作为名字的开头，而不需要创建多个 needle。e.g.
`xfce/application_finder_*` 可能有多个测试需要检查 `Preference` 窗口是否正确弹
出，`gimp/*` 可能有多个测试需要检查工具栏是否位置正确。

```
xfce_application_finder_a-preference-poped-20230324
xfce_application_finder_b-preference-poped-20230324
...
xfce_application_finder_z-preference-poped-20230324			:( BAD
xfce_application_finder-preference-poped-20230324			:) GOOD
```

```
gimp_draw_xxx-toolbar-poped-20230326
gimp_select_xxx-toolbar-poped-20230326
...
gimp_clear_xxx-toolbar-poped-20230326					:( BAD
gimp-toolbar-poped-20230326						:) GOOD
```

如果有一些 needle 被许多分类的测试共同使用，需与其他开发者讨论后再新增在全局范围
内的 needle（e.g. `desktop-title-20230326`）

- Needle 应该包含描述性的文本描述此 needle 匹配什么样子的屏幕

```
xfce_application_finder_run-dsfafdaf-20230324
							:( BAD, POINTLESS
xfce_application_finder_run-it-is-sunny-20230324
							:( BAD, OUT OF TOPIC
xfce_application_finder_run-window-poped-20230324
							:) GOOD
```

- Needle 应该给出一个创建时间

```
xfce_application_finder_run-window-poped		:( BAD
xfce_application_finder_run-window-poped-20230324	:) GOOD
```

- 要使用 `assert_and_click()` 的 needle（即需要点击的 needle) ***可以***在描述性
文本中包含 `click` 字样。

```
xfce_application_finder_fold_unfold-fold-list-20230324		:) OKAY
xfce_application_finder_fold_click-then-fold-list-20230324	:) BETTER
```
