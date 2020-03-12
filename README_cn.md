# ultimate（终极） macOS


forked from [Vonng/Capslock](https://github.com/Vonng/Capslock/) : *让 <kbd>CapsLock</kbd> 更 NB！* 

[![openIssues](https://img.shields.io/github/issues-raw/suliveevil/Capslock.svg)](https://github.com/suliveevil/Capslock/issues/new) [![pullRequests](https://img.shields.io/github/issues-pr/suliveevil/Capslock.svg)](https://github.com/suliveevil/Capslock/compare)   [![star this repo](http://githubbadges.com/star.svg?user=suliveevil&repo=capslock&style=flat)](https://github.com/suliveevil/capslock) [![fork this repo](http://githubbadges.com/fork.svg?user=suliveevil&repo=capslock&style=flat)](https://github.com/suliveevil/capslock/fork)[![Downloads](https://img.shields.io/github/downloads/suliveevil/Capslock/total.svg)]() [![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu)

![](images/function-overview.png)


## 为什么用 CapsLock 键

### 让 Capslock 成为一个 *Hyper* 键, 极大提高效率!

* 功能强大: 把 <kbd>Capslock</kbd> 变成一个新的修饰键: **<kbd>Hyper(✱)</kbd>**.。
* 精心设计: 在键盘热区高频率使用的按键. 带来很多有用的功能。
* 兼容性: 和其他修饰键、应用、设备一起为你提高效率。
* 轻量级:  仅一个小脚本, 随处使用 !
* [设计文档](design.md)


### 平台

<details>
<summary>details</summary>

- [CapsLock(macOS)](mac/) 使用   [Karabiner-Elements](https://pqrs.org/osx/karabiner/)
  - macOS Mojave (10.14)
  - macOS High Sierra (10.13)
  - macOS Sierra (10.12)
  - macOS EI Capitan (10.11)

</details>


### 安装 (macOS)

1. 下载 [Karabiner-Elements](https://pqrs.org/osx/karabiner/) 并安装

2. 拷贝下面的链接到浏览器 (**在 Safari 中打开**)来导入配置文件。

```bash
karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/Vonng/Capslock/master/mac/capslock.json
```

或者在 Karabiner-Elements 官方网站导入配置文件

```bash
https://pqrs.org/osx/karabiner/complex_modifications/#ultimate_macOS
```

3. 打开 Karabiner, 找到 "ComplexModification", 点击 "Add Item", 开始自定义配置。

4. 默认配置文件的路径是  `$HOME/.config/karabiner/assets/complex_modifications`。你可以自行修改。

5. 开启 **CapsLock** 功能: `[App] karabiner-elements -> [Tab] Complex Modification -> Add Item`

## 符号说明

<details>
<summary>修饰键:  macOS</summary>

| Sym  | Key     |
| :----: | ------- |
| <kbd>✱</kbd>    | Hyper   |
| <kbd>⌃</kbd>    | Control |
| <kbd>⌥</kbd>    | Option  |
| <kbd>⇧</kbd>    | Shift   |
| <kbd>⌘</kbd>    | Command |

</details>


<details>
<summary>修饰键: ⊞ Windows</summary>

| Sym  | Key     |
| :----: | ------- |
| <kbd>✱</kbd>    | Hyper   |
| <kbd>⌃</kbd>    | Control |
| <kbd>⊞</kbd>    | Windows |
| <kbd>⇧</kbd>    | Shift   |
| <kbd>⎇</kbd>    | Alter   |

</details>


<details>
<summary>常用键</summary>

| GLYPH   | NAME                                   |
| :-------: | -------------------------------------- |
| <kbd></kbd>       | Apple                                  |
| <kbd>⌘</kbd>       | Command, Cmd, Clover, (formerly) Apple |
| <kbd>⌃</kbd>       | Control, Ctl, Ctrl                     |
| <kbd>⌥</kbd>       | Option, Opt, (Windows) Alt             |
| <kbd>⎇</kbd>       | Alt                                   |
| <kbd>⇧</kbd>       | Shift                                  |
| <kbd>⇪</kbd>       | 大写锁定键(Caps Lock)                    |
| <kbd>⏏</kbd>       | Eject                                  |
| <kbd>↩</kbd>, <kbd>↵</kbd>, <kbd>⏎</kbd> | 返回键, 回车键(Return, Carriage Return) |
| <kbd>⌤</kbd>       | Enter                                  |
| <kbd>⌫</kbd>       | Delete, Backspace                      |
| <kbd>⌦</kbd>       | Forward Delete                         |
| <kbd>⎋</kbd>       | 退出(Escape, Esc)                       |
| <kbd>→</kbd>       | 右箭头                                  |
| <kbd>←</kbd>       | Left arrow                             |
| <kbd>↑</kbd>       | Up arrow                               |
| <kbd>↓</kbd>       | Down arrow                             |
| <kbd>⇞</kbd>       | Page Up, PgUp                          |
| <kbd>⇟</kbd>       | Page Down, PgDn                        |
| <kbd>↖</kbd>       | Home                                   |
| <kbd>↘</kbd>       | End                                    |
| <kbd>⌧</kbd>       | Clear                                  |
| <kbd>⇥</kbd>       | Tab, Tab Right, Horizontal Tab         |
| <kbd>⇤</kbd>       | Shift Tab, Tab Left, Back-tab          |
| <kbd>␢</kbd>       | 空格键(Space, Blank)                    |
| <kbd>␣</kbd>       | 空格键(Space, Blank)                    |
| <kbd>❘⃝</kbd>      | 电源键                                  |
| <kbd>⇭</kbd>       | Num lock                               |
| <kbd>?⃝</kbd>      | Help                                   |
| <kbd></kbd>      | Context menu                           |

</details>






## 用法 (mac)

![](images/keyboard.png)

### 基础用法

<kbd>✱</kbd> Hyper 键实际上映射为 <kbd>⌃</kbd> <kbd>⌥</kbd> <kbd>⇧</kbd> <kbd>⌘</kbd> (右边所有的修饰键) , 它和左边的修饰键能够一起工作，并且兼容大多数应用程序。 

按住(Hold) <kbd>CapsLock</kbd> 并按下(Press)其他键来触发 <kbd>Hyper</kbd> 功能，而单独按下 <kbd>CapsLock</kbd> 作为 <kbd>Escape</kbd> 键。

| 键盘上的键 | Maps to    | 备注                       |
| :------: | ---------- | -------------------------- |
| <kbd>⇪</kbd> 按下  | <kbd>⎋</kbd> Escape | 单独按下，成为 <kbd>escape</kbd>  |
| <kbd>⇪</kbd> 按住   | <kbd>✱</kbd>  Hyper | 开启 Hyper 功能 |

### 浏览

<details>
<summary>details</summary>

- 按住  <kbd>✱</kbd> Hyper 开始浏览
- 再按住一个<kbd>⌘</kbd> 来 **选择** . ( 就像按住 <kbd>⇧</kbd> 来进行大写字母输入那样)
- 再按住一个<kbd>⌥</kbd>  和 <kbd>H</kbd> <kbd>J</kbd> <kbd>K</kbd> <kbd>L</kbd> 进行 **鼠标移动**
- 再按住一个<kbd>⇧</kbd>  和 <kbd>H</kbd> <kbd>J</kbd> <kbd>K</kbd> <kbd>L</kbd> 进行 **标签页/app切换**
- 再按住一个<kbd>⌃</kbd>  和 <kbd>H</kbd> <kbd>J</kbd> <kbd>K</kbd> <kbd>L</kbd> 进行 **桌面管理** . (就像按下 <kbd>⌃</kbd> 和 <kbd>↑</kbd> <kbd>↓</kbd> <kbd>←</kbd> <kbd>→</kbd> 一样)

| Origin | Maps to        | Comment                  |
| ------: | -------------- | ------------------------ |
| <kbd>⌘</kbd> <kbd>0</kbd>    | <kbd>⌘</kbd><kbd>←</kbd> 左箭头  | 光标移动到行首         |
| <kbd>⌘</kbd> <kbd>4($)</kbd>    | <kbd>⌘</kbd> <kbd>→</kbd> 下箭头  | 光标移动到行末          |
| <kbd>H</kbd>    | <kbd>←</kbd> 左箭头  | 光标左移         |
| <kbd>J</kbd>    | <kbd>↓</kbd> 下箭头  | 光标下移          |
| <kbd>K</kbd>    | <kbd>↑</kbd> 上箭头    | 光标上移        |
| <kbd>L</kbd>    | <kbd>→</kbd> 右箭头 | 光标右移           |
| <kbd>⌘</kbd> <kbd>H</kbd>    | <kbd>⇧</kbd><kbd>←</kbd> 左箭头  | 光标左移并选择         |
| <kbd>⌘</kbd> <kbd>J</kbd>    | <kbd>⇧</kbd> <kbd>↓</kbd> 下箭头  | 光标下移并选择          |
| <kbd>⌘</kbd> <kbd>K</kbd>    | <kbd>⇧</kbd> <kbd>↑</kbd> 上箭头    | 光标上移并选择        |
| <kbd>⌘</kbd> <kbd>L</kbd>    | <kbd>⇧</kbd> <kbd>→</kbd> 右箭头 | 光标右移并选择          |
|  <kbd>⌥</kbd> <kbd>H</kbd>    | <kbd>←</kbd> 左箭头  | <kbd>⌥</kbd> <kbd>←</kbd> |
|  <kbd>⌥</kbd> <kbd>J</kbd>    | <kbd>↓</kbd> 下箭头  | <kbd>⌥</kbd> <kbd>↓</kbd> |
|  <kbd>⌥</kbd> <kbd>K</kbd>    | <kbd>↑</kbd> 上箭头    | <kbd>⌥</kbd> <kbd>↑</kbd> |
|  <kbd>⌥</kbd> <kbd>L</kbd>    | <kbd>→</kbd> 右箭头 | <kbd>⌥</kbd> <kbd>→</kbd> |
|  <kbd>⌃</kbd> <kbd>H</kbd>    | <kbd>⌃</kbd> <kbd>←</kbd> 左箭头  | expose all      |
|  <kbd>⌃</kbd> <kbd>J</kbd>    | <kbd>⌃</kbd> <kbd>↓</kbd> 下箭头  | 应用程序窗口 ~~show desktops~~  |
|  <kbd>⌃</kbd> <kbd>K</kbd>    | <kbd>⌃</kbd> <kbd>↑</kbd> 上箭头    | 转到上一桌面    |
|  <kbd>⌃</kbd> <kbd>L</kbd>    | <kbd>⌃</kbd> <kbd>→</kbd> 右箭头 | 转到下一桌面   |
| <kbd>U</kbd>    | <kbd>⇞</kbd> PageUp     | 光标向上翻页   |
| <kbd>I</kbd>    | <kbd>↖</kbd> Home       | 光标移动到行首 |
| <kbd>O</kbd>    | <kbd>↘</kbd>  End       | 光标移动到行末 |
| <kbd>P</kbd>    | <kbd>⇟</kbd> PageDn     | 光标向下翻页   |
| <kbd>⌘</kbd><kbd>U</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌘</kbd><kbd>I</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌘</kbd><kbd>O</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌘</kbd><kbd>P</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌥</kbd><kbd>U</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌥</kbd><kbd>I</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌥</kbd><kbd>O</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌥</kbd><kbd>P</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌃</kbd><kbd>U</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌃</kbd><kbd>I</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌃</kbd><kbd>O</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |
| <kbd>⌃</kbd><kbd>P</kbd>   | <kbd>X</kbd><kbd>X</kbd>       | leave to other apps |

</details>


### 鼠标键

<details>
<summary>details</summary>

* 用键盘模拟鼠标

| Origin | Maps to        | Comment                  |
| ------: | -------------- | ------------------------ |
| <kbd>←</kbd>    | 鼠标左移    | 鼠标光标向左移动               |
| <kbd>↓</kbd>    | 鼠标下移    | 鼠标光标向右移动               |
| <kbd>↑</kbd>    | 鼠标上移    | 鼠标光标向上移动               |
| <kbd>→</kbd>    | 鼠标右移    | 鼠标光标向右移动               |
| <kbd>↩</kbd>    | 鼠标左键    | 鼠标左键点击                  |
| <kbd>⌥</kbd> <kbd>↩</kbd>    | 鼠标中键点击    | 鼠标左键点击  |
| <kbd>⌘</kbd> <kbd>↩</kbd>    | 鼠标右键点击    | 鼠标右键点击  |

</details>


### 删除 

<details>
<summary>details</summary>

这个模块与 vim 的 delete 不同，需要改进

| Origin    | Maps to                            | Comment             |
| --------: | ---------------------------------- | ------------------- |
| <kbd>N</kbd>       | <kbd>⌥</kbd> <kbd>⌫</kbd>  Option + ForwardDelete       | 删除光标前面的一个单词 |
| <kbd>M</kbd>       | <kbd>⌫</kbd>  ForwardDelete       | 删除光标前面的一个字符 |
| <kbd>,</kbd>       | <kbd>⌦</kbd>  Delete      | 删除光标后面的一个字符 |
| <kbd>.</kbd>       | <kbd>⌥</kbd> <kbd>⌦</kbd>  Option + Delete       | 删除光标后面的一个单词 |
| <kbd>⌘</kbd> <kbd>M</kbd> + <kbd>⌘</kbd> <kbd>N</kbd> | <kbd>⌘</kbd> <kbd>⌥</kbd> <kbd>⌫</kbd> Command+Option+ForwardDelete | 删除到行首 |

</details>



### 窗口管理

<details>
<summary>details</summary>

| Origin           | Maps to                 | Comment                                  |
| ---------------: | ----------------------- | ---------------------------------------- |
| <kbd>⇥</kbd> Tab          | <kbd>⌘</kbd> <kbd>⇥</kbd> Command+Tab | 切换窗口                        |
| <kbd>⌘</kbd><kbd>⇥</kbd> Command+Tab | <kbd>⌘</kbd><kbd>⇧</kbd><kbd>⇥</kbd> Command+Shift+Tab | 反向切换窗口              |
| <kbd>Q</kbd>              | <kbd>⌘</kbd> <kbd>Q</kbd>                   | 关闭窗口                             |
| <kbd>W</kbd>              | <kbd>⌘</kbd> <kbd>W</kbd>                   | Close Tab                                |
| <kbd>A</kbd>              | <kbd>⌃</kbd> <kbd>⌥</kbd> <kbd>⇧</kbd> <kbd>⌘</kbd> <kbd>A</kbd>               | [Moom*](https://manytricks.com/moom/) 专用。※ 一个窗口管理 app |
| <kbd>⌘</kbd><kbd>A</kbd>             | <kbd>⌃</kbd> <kbd>↑</kbd>  Ctrl+UpArrow      | 应用 Expose                  |
| <kbd>S</kbd>             | <kbd>⌃</kbd> <kbd>⇥</kbd>  Ctrl+Tab          | 切换标签页                                |
| <kbd>⌘</kbd><kbd>S</kbd>             | <kbd>⌃</kbd> <kbd>⇧</kbd> <kbd>⇥</kbd> Ctrl+Shift+Tab    | 反向切换标签页     |
| <kbd>⌥</kbd><kbd>D</kbd>             | <kbd>F11</kbd>                   | Show Desktop                             |


</details>


### Bash

<details>
<summary>details</summary>

- 常用 bash 工具: EOF, SIGINT, SIGTSTP, VIM/Tmux Prefix

| Origin | Maps to     | Comment                                      |
| -----: | ----------- | -------------------------------------------- |
| <kbd>Z</kbd>   | <kbd>⌃</kbd> <kbd>Z</kbd> | 暂停进程 SIGTSTP                                 |
| <kbd>X</kbd>   | <kbd>⌃</kbd> <kbd>R</kbd> | 运行 IDE                                   |
| <kbd>C</kbd>   | <kbd>⌃</kbd> <kbd>C</kbd> | 终止进程 SIGINT                                  |
| <kbd>V</kbd>   | <kbd>⌃</kbd> <kbd>V</kbd> | Vim Prefix                                   |
| <kbd>B</kbd>   | <kbd>⌃</kbd> <kbd>B</kbd> | [Tmux](http://tmux.github.io) Default Prefix |
| <kbd>D</kbd>   | <kbd>⌃</kbd> <kbd>D</kbd> | 文件结束 EOF                                     |



</details>


### 应用程序

<details>
<summary>details</summary>

- 以下设置可以被重写为你喜欢的 app。

| Origin | Maps to          | Comment                       |
| -----: | ------------     | ----------------------------- |
| <kbd>E</kbd>              | 打开访达 | 打开文件浏览器  |
| <kbd>⌘</kbd> <kbd>E</kbd> | 打开 Safari | 打开网页浏览器  |
| <kbd>R</kbd>              | 打开 iTerm2  | macOS 上一个很棒的终端 app (`Run`) |
| <kbd>⌘</kbd> <kbd>R</kbd> | 打开 Webstorm | Webstorm |
| <kbd>T</kbd>              | 打开 Visual Studio Code | 文本编辑器: Visual Studio Code                 |
| <kbd>⌘</kbd> <kbd>T</kbd> | 打开 Notion  | The all-in-one workspace for your notes,tasks,wikis,and databeses. |
| <kbd>Y</kbd>              | 打开 Siri |                 |
| <kbd>⌘</kbd> <kbd>D</kbd> | 打开词典        | 查询单词 |
| <kbd>F</kbd>              | 打开 Alfred            |               |
| <kbd>⌘</kbd> <kbd>F</kbd> | 打开 Dash      | 查询 API 文档      |
| <kbd>G</kbd>              | add held down hyper g to fn | fn                |
| <kbd>⌘</kbd><kbd>G</kbd>  | 打开 Chrome             | Google Chrome   |
| <kbd>⌘</kbd><kbd>B</kbd>  | 打开 BBEdit             | BBEdit        |
</details>


### 功能键

<details>
<summary>details</summary>

- 使用 1…9、0、-、= 作为标准功能键（F1-F12）.


| Origin            | Maps to              | Comment                          |
| ----------------: | -------------------- | -------------------------------- |
| <kbd>⌥</kbd><kbd>1</kbd>              | <kbd>BrightnessDown</kbd>     |                                  |
| <kbd>⌥</kbd><kbd>2</kbd>              | <kbd>BrightnessUp</kbd>       |                                  |
| <kbd>⌥</kbd><kbd>3</kbd>              | <kbd>ExposeAll</kbd>          |                                  |
| <kbd>⌥</kbd><kbd>4</kbd>              | <kbd>LaunchPad</kbd>         |                                  |
| <kbd>⌥</kbd><kbd>5</kbd>              | <kbd>KeyboardLightDown</kbd>  |                                  |
| <kbd>⌥</kbd><kbd>6</kbd>              | <kbd>KeyboardLightUp</kbd>    |                                  |
| <kbd>⌥</kbd><kbd>7</kbd>              | <kbd>MusicPrev</kbd>          |                                  |
| <kbd>⌥</kbd><kbd>8</kbd>              | <kbd>MusicPlay</kbd>          |                                  |
| <kbd>⌥</kbd><kbd>9</kbd>              | <kbd>MusicNext</kbd>          |                                  |
| <kbd>⌥</kbd><kbd>0</kbd>              | <kbd>Mute</kbd>               |                                  |
| <kbd>⌥</kbd><kbd>-</kbd>              | <kbd>VolumeDown</kbd>         |                                  |
| <kbd>⌥</kbd><kbd>=</kbd>              | <kbd>VolumeUp</kbd>           |                                  |
| <kbd>F13</kbd> <kbd>PrintScreen</kbd> | <kbd>MusicPrev</kbd>          |                                  |
| <kbd>F14</kbd> <kbd>ScrollLock</kbd>  | <kbd>MusicNext</kbd>          |                                  |
| <kbd>F15</kbd> Pause       | <kbd>MusicPlay</kbd>                     | Just as it shows                 |
| <kbd>Insert</kbd>          | <kbd>⌥</kbd><kbd>BrightnessUp</kbd>      | Fine grained brightness up       |
| <kbd>Delete</kbd>          | <kbd>⌥</kbd><kbd>BrightnessDown</kbd>    | Fine grained brightness down     |
| <kbd>Home</kbd>            | <kbd>⌥</kbd><kbd>KeyboardLightUp</kbd>   | Fine grained keyboard light up   |
| <kbd>End</kbd>             | <kbd>⌥</kbd><kbd>KeyboardLightDown</kbd> | Fine grained keyboard light down |
| <kbd>PgUp</kbd>            | <kbd>⌥</kbd><kbd>VolumeUp</kbd>          | Fine grained volume up           |
| <kbd>PgDn</kbd>            | <kbd>⌥</kbd><kbd>VolumeDown</kbd>        | Fine grained volume down         |

</details>


### Shifter

<details>
<summary>details</summary>

- 更方便的 <kbd>shift</kbd>
- 分号<kbd> ;</kbd> 引号  <kbd>'</kbd> 被特殊处理， 使得输入 <kbd>!=</kbd> 和 <kbd>:=</kbd>  更方便

| Origin             | Maps to | Comment                  |
| -----------------: | ------- | ------------------------ |
| <kbd>1</kbd>                | <kbd>!</kbd>     | 感叹号                           |
| <kbd>2</kbd>                | <kbd>@</kbd>     | At                       |
| <kbd>3</kbd>                | <kbd>#</kbd>     | Sharp                    |
| <kbd>4</kbd>                | <kbd>$</kbd>     | Dollar                   |
| <kbd>5</kbd>                | <kbd>%</kbd>     | 百分号                  |
| <kbd>6</kbd>                | <kbd>^</kbd>     | 脱字符 Caret                |
| <kbd>7</kbd>                | <kbd>&</kbd>     | Ampersand                |
| <kbd>8</kbd>                | <kbd>*</kbd>     | 星号                     |
| <kbd>9</kbd>                | <kbd>(</kbd>     | 左括号       |
| <kbd>0</kbd>                | <kbd>)</kbd>     | 右括号   |
| <kbd>-</kbd> Minus          | <kbd>_</kbd>     | Hyphen                   |
| <kbd>=</kbd> Equal          | <kbd>+</kbd>     | Plus                     |
| <kbd>[</kbd> Left Bracket              | <kbd>{</kbd>     | 左花括号 <kbd>⇧</kbd> <kbd>{[</kbd>  |
| <kbd>]</kbd>  Right Bracket            | <kbd>}</kbd>     | 右花括号 <kbd>⇧</kbd> <kbd>}]</kbd>  |
| <kbd>;</kbd> Semicolon      | <kbd>!</kbd>     | Exclamation              |
| <kbd>'</kbd> Single Quote   | <kbd>=</kbd>     | EqualSign                |
| <kbd>⌘</kbd> <kbd>;</kbd> Semicolon     | <kbd>!</kbd>     | Colon                    |
| <kbd>⌘</kbd> <kbd>'</kbd> Single Quote  | <kbd>=</kbd>     | EqualSign                |


</details>


### Misc

<details>
<summary>details</summary>

| Origin                 | Maps to             | Comment                                        |
| ---------------------: | ------------------- | ---------------------------------------------- |
| <kbd>⎋</kbd> Escape             | <kbd>⇪</kbd>  CapsLock       | Bug: Difficult to turn capslock off after emit |
| <kbd>~</kbd> BackQuote          | <kbd>⌃</kbd><kbd>⇧</kbd><kbd>⌘4</kbd><kbd>4</kbd>             | macOS 区域截图并保存到桌面 |
| <kbd>⌘</kbd><kbd>~</kbd> Command+BackQuote | <kbd>⌃</kbd><kbd>⇧</kbd><kbd>4</kbd>               | macOS 区域截图并保存到剪切板   |
| <kbd>⌫</kbd> Backspace          | <kbd>⌘</kbd><kbd>⌫</kbd>                | macOS 删除文件                 |
| <kbd>/</kbd> Slash              | <kbd>⌘</kbd><kbd>/</kbd> Command+Slash  | IDE 注释                      |
| <kbd>`\`</kbd> Backslash        | <kbd>⌘</kbd><kbd>/</kbd> Command+Slash  | IDE 注释                      |
| <kbd>␢</kbd> Spacebar           | <kbd>⌃</kbd><kbd>␢</kbd>  Ctrl+Spacebar | 切换输入法                     |


</details>




## 问答

- Q： 为什么使用 <kbd>✱</kbd> 作为 hyper 键的符号？

  A：因为星号的 ascii 码是 42, 是生命、宇宙、一切的答案!  并且它也可以被理解为一颗星星。 :star: <kbd>✱</kbd> (加粗的星号) 比 <kbd> * </kbd> (星号) 更好看. 如果 Github 能够正确显示的话，其实我更愿意使用 <kbd>☯</kbd>。

- Q：为什么没有 Linux 版本？

  A：因为我用 Mac, 在终端使用 Linux。

- Q:  为什么 macOS 版 和 Windows 版有些键盘绑定不一样?

  A:   我现在已经不用 Windows 了,  Windows 版已不再维护，欢迎你来完善它。

- Q:  为什么这儿还有一个旧的 Mac 版本?

  A:  Apple 真的是很反复(ren)无常(xing)。 macOS Sierra 改变了内核架构, 所以老版本的 Karabiner 不兼容 10.12 以后的 macOS。 但现在有了新版本的 karabiner 并被取名为 Karabiner-Elements。 Karabiner-Elements 使用 JSON 格式配置文件而不是原来的 XML 格式。 请使用新版本。

  

## About

作者：suliveevil（suliveevil@outlook.com）

License： [![WTFPL](https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/WTFPL_logo.svg/50px-WTFPL_logo.svg.png)]()

```
Do What The Fuck you want to Public License

Version 1.0
Copyright (C) 2018 Feng Ruohang (Vonng).
Everyone is permitted to copy and distribute verbatim copies
of this license document, but changing it is not allowed.

Ok, the purpose of this license is simple
and you just

DO WHAT THE FUCK YOU WANT TO.
```