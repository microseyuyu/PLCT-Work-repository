# openQA 测试用例编写

openQA 中的测试以 `.pm` （Perl Module）的形式组织，换而言之，每一个测试都是一个
独立加载的 Perl 模块，使用 Perl 的语法和语义，同时能够访问 openQA 的 API。在测试
过程中需要对比结果（屏幕显示内容）的，可以通过创建 needle 并调用 API 进行比对实
现。

## 测试运行顺序

当通过 `openqa-cli` 激活测试后，在 Job Group 中配置的各个 Testsuite 会同时被运行
（当Worker 不足时会排队等待），而各个 Testsuite 被执行时会自上而下顺序运行每一个
Test。

## 创建 needle

我们可以在 openQA Web 端从执行过的 Job 的截图中创建 needle。打开一个 Job，选中一
幕屏幕，点击 Create New Needle，从图像中选中区域并创建 needle。如果需要使用
`assert_and_click` API 可以同时对某个选区应用 Add click coordinates for
`assert_and_click`。

## 编写测试的 Perl Module

下面是一个测试的基本框架。

```Perl
use strict;
use Mojo::Base "basetest";
use warnings;
use testapi;
use utils;

sub
run {
}

sub
test_flags {
	return { fatal => 1, milestone => 1 };
}

1;
```

`use warnings` 与 `use strict` 使能了 Perl 的严格模式和警告，减少出错的几率。
`Mojo::Base "basetest"` `testapi` `utils` 为 openQA 的测试 API 及预制的辅助库
。

Perl 中的每条语句必须以分号 `;` 结束。

Perl 中没有函数，而是概念***子例程(subroutine)***，使用 `sub` 关键字可以定义一
个子例程。`test_flags` 子例程会返回该测试使用的设置（失败后是否继续测试等）。
`run` 子例程会在测试执行时被调用。对子例程的调用可以省略括号，但必须保证不出现
歧义。

要注意，Perl 中如果省略 `return` 语句，最后一行语句的返回值即子例程的返回值；
而 Perl Module 要求在被加载完毕后返回一个真值，所以最后一行 `1;` 是不可省略的
（Perl 中非零值都为真，0 为假）

test_flags 的含义见下：

- `fatal`: The whole test suite is aborted if the test module fails. The overall state is set to failed.
- `ignore_failure`: If this module fails, it will not affect the overall result at all.
- `milestone`: After this test succeeds, update the 'lastgood' snapshot.
- `no_rollback`: Don’t roll back to the 'lastgood' snapshot if the test module fails.
- `always_rollback`: Roll back to the 'lastgood' snapshot even if test was successful.

在 `run` 子例程中，我们可以调用 openQA 的 API 进行测试。部分 API 如下（方括号内
为可选参数）：


### Needle 检查

- `assert_screen $tag [, $timeout]`: 检查屏幕与带有 tag `$tag` 的 needle 是否匹
配，最多等待 `$timeout` 秒
- `assert_and_click $tag [, $timeout, $button]`: 同 `assert_screen`，不同的是在
匹配后按照 `$button` （默认 "left"）用鼠标点击设置的区域
- `wait_still_screen`: 等待直到屏幕停止变化

### 键盘

- `send_key $key [,$wait_screen_change]`: 按下按键，当 `$wait_screen_change` 为
真时阻塞至屏幕变化。特殊按键包括
```
'esc', 'down', 'right', 'up', 'left', 'equal', 'spc',  'minus', 'shift', 'ctrl'
'caps', 'meta', 'alt', 'ret', 'tab', 'backspace', 'end', 'delete', 'home', 'insert'
'pgup', 'pgdn', 'sysrq', 'super'`
```
- `hold_key $key`: 按住一个按键
- `release_key $key`: 松开一个按键
- `send_key_until_needlematch $tag, $key`: 一直重复按键直到匹配
- `type_string $str` 与 `type_string_slow`, `type_string_very_slow`: 输入字符串，
后两个子例程降低了输入速度
- `type_password [$password]`: 输入密码，同 `type_string`，但日志中不包含输入内
容。如果不指定 `$password` 则使用 `$testapi::password`
- `enter_cmd $string`: 输入 `string` 并回车

### 鼠标

- `mouse_set $x, $y`: 将鼠标设置到 x, y 位置
- `mouse_click [$button, $holdtime]`: 点击鼠标的 `$button` 键（"left" 或 "right"
, 默认 "left"），其中按住时间为 `$holdtime`

### 辅助子例程

- `x11_start_program $program`: 在 X 系统下启动程序 `$program`，部分发行版下不可
用。（经测试可能在 openEuler 22.03 QEMU 下无效）

完整的 API 列表可见[此文档](http://open.qa/api/testapi)

## 触发测试

测试可以在 openQA 的 Web 界面通过重启一个此前的测试而被触发，此类型的任务会包含
一个 restarted 标志。

更普遍的方法是使用 `openqa-cli` 触发测试。一般的用例类似：
```
openqa-cli api -X POST isos async=0 DISTRI=xxx FLAVOR=xx ARCH=xx VERSION=xxx
```

其中 DISTRI，FALVOR，ARCH，VERSION 即为在 Job Template 中的对应配置。
