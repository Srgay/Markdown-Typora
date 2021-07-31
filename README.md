[toc]

# 1. Markdown历史

在日常工作和互联网写作中, Markdown几乎随处可见,并且扮演着越来越重要的角色。不管你是不是程序员,只要关乎写作,都离不开 Markdown。知乎、简书、CSDN、 GitHub、 WordPress印象笔记、有道笔记等都支持 Markdown, Markdown俨然已成为最流行的“写作语言”。

据 GitHub Flavored Markdown(GFM)官方文档介绍, Markdown是由约翰·格鲁伯( John Gruber)在亚伦·斯沃茨( Aaron Swartz)的帮助下开发,并在2004年发布的标记语言。

其设计灵感主要来源于纯文本电子邮件的格式,目标是让人们能够使用易读、易写的纯文本格式编写文档,而且这些文档可以转换为HTML( Hyper Text MarkupLanguage,超文本标记语言)文档。

起初 Markdown主要用于网络写作,后来人们希望 Markdown能够应用到更多的领域,如写书、记笔记、写文档、写幻灯片等。
由于 Markdown本身功能有限,一些特定的需求和场景无法被满足,因此产生了许多扩展语法,这些语法在基础语法之上新增了如表格、任务列表、围栏代码块等功能。

## 1.1  Markdown演进史
* 2006年, Pandoc's Markdown发布,作者是 John MacFarlane此版本对 Markdown语法有额外的扩充和些许修正,这使 Markdown可以转换为更多的文件格式, Pando堪称文件转换领域的“瑞士军刀”
* 2011年, MultiMarkdown(简称MMD)发布,作者是 Fletcher T. Penney此版本让 Markdown可以转换为更多的文件格式,包括HTML/ XHTML、OpenDocument, OPML( Outline Processor Markup Language,大纲处理标记语言)
* 2013年, Markdown Extra发布,作者是 Michel fortin。此版本最初使用PHP语言实现,新增了围栏代码块、具有 id/class属性的元素、表格、任务列表、脚注、缩写等功能。
* 2014年, Common Mark规范发布,主要作者是 Jeff Atwood和JohrMacFarlaneCommonAl旨在为人们提供一个标准的 Markdown语法规范和参考实现。Markdown标准化工作开始于2012年,2014年9月,由于 John Gruber反对在这一工作中继续使用“ Markdown”这个名字,其被更名为 Common Mark
* 2017年, GitHub发布了 GitHub Flavored Markdown,即GFM此版本遵循 CommonMark规范,新增了围栏代码块、表格、删除线、自动接、 Emoji表情和任务列表等功能,是目前使用最广泛的版本。

## 1.2 标准语法 Common Mark
由于不同版本的扩展语法太多, John Gruber对 Markdown语法也没有指定明确的规范,在非正式规范中也存在一些含糊不清的地方,一些扩展语法慢慢偏离了最初的参考实现方式。另外,用户的写作习惯和编辑器的解析规则也不尽相同,这就导致 Markdown文本在不同编辑器上解析时可能会出现一些问题。

这些问题促使一些机构和开发人员努力对 Markdown语法进行标准化CommonMark(http://commonmark.org/)就是这样一个产物。它为 Markdown t提出了一个标准的、明确的语法规范,以及一套全面的测试,根据此规范可以验证Markdown的实现结果, GitHub Flavored Markdown(GFM)遵循的就是CommonMark规范

## 1.3 最流行的扩展语法CFM

目前最流行的扩展语法是 GitHub Flavored Markdown,简称GFM,毕竟Github是全球最大的程序员“交友”网站.

# 2. Markdown使用场景

当你对文章的排版没什么特殊需求,且不想花太多时间在排版上时,就可以使用 Markdown。因为编辑器或平台会通过 Markdown标记对文章进行渲染,最终的版效果会非常简洁、漂亮。众多“专职”的 Markdown编辑器(如 Typora、熊掌记、 Ulysses)也提供了对 Markdown的支持。

Markdown并不是万能的,它只适用于对排版要求不高的场景,如果你对字号段落、图片、表格等方面的排版要求较高,还是需要使用Word这类专业的编辑软件的。
小提示: Markdown文件可以很方便地转换为Word文件,如果有一些需要特殊处理的格式,可以两者结合使用。

# 3. Markdown使用流程

Markdown的工作流程很简单,首先要挑一款好用的编辑器进行写作,内容使用 Markdown进行标记,然后通过编辑器的功能将文章进行渲染、发布或导出。
所以如果想让 Markdown发挥最大的作用,语法和编辑器都是要好好学习的。

## 3.1 语法学习
1. 学习基础语法
Markdown的基础语法是指 John Gruber最初发布的 Markdown版本,大多扩展语法都是基于此版本开发的,因此基础语法是需要学会的。
2. 学习扩展语法
在众多扩展语法中,GEM无疑是目前最流行的。它扩展了包括表格、任务列表、删除线、围栏代码、Emoj等在内的语法,功能非常全面,是笔者重点推荐学习的扩展语法。
3. 学习写作规范
人们在使用 Markdown的过程中逐渐总结出了一些最佳实践方案,并且制定了写作规范,学习这些规范可以让我们养成良好的写作习惯,避免重复“踩坑”。另外,遵循这些规范也可以让源码(没有渲染过的文本)有更强的可读性、可移植性(一处编写,随处使用)和可维护性(有统一的认知)。
## 3.2 编辑器简介
正所谓“好马配好鞍”,好的编辑工具可以让写作事半功倍。在市面上也有很多流行的 Markdown编辑器,免费的、收费的都有,可谓各有千秋。本文挑选了比较有代表性的工具Typora来介绍。

比较流行的Markdown编辑器列表

| 编辑器       | Markdown语法 | 跨平台 | 移动端 | 免费 | 推荐指数 | 适宜人群 |
| :------------: | :------------: | :------: | :------: | :----: | :--------: | :--------: |
| Typora       | GFM | ✔️ | ❎ | ✔️ | ⭐⭐⭐⭐⭐ | 所有人 |
| VS Code      | GFM | ✔️ | ❎ | ✔️ | ⭐⭐⭐⭐⭐ | 技术写作人员 |
| Gitbook      | GFM | ✔️ | ❎ | ✔️ | ⭐⭐⭐⭐ | 热爱开源的人 |
| 印象笔记     | GFM | ✔️ | ❎ | ✔️(内购) | ⭐⭐⭐⭐⭐ | 印象笔记用户 |
| 有道笔记     | GFM | ✔️ | ✔️ | ✔️(内购) | ⭐⭐⭐⭐ | 有道笔记用户 |
| 熊掌记       | 简化并兼容标准语法 | ❎(macOS) | ✔️(iOS) | ✔️(内购) | ⭐⭐⭐⭐⭐ | 文艺青年 |
| Ulysses      | GFM | ❎(macOS) | ✔️(iOS) | ❎ | ⭐⭐⭐⭐ | 重度文字工作者 |
| MWeb         | GFM | ❎(macOS) | ✔️(iOS) | ❎ | ⭐⭐⭐⭐ | 技术写作人员 |
| MarkdownPad  | GFM | ❎(Windows) | ❎ | ✔️(内购) | ⭐⭐⭐ | Windows用户 |
| CMD Markdown | GFM | ✔️ | ❎ | ✔️(内购) | ⭐⭐⭐⭐⭐ | 所有人 |

本文示例演示使用的是Typora + VS Code。

# 4. MarkDown语法

## 4.1 基础语法

### 4.1.1 字体

#### 4.1.1.1 标题

* 使用# 语法表示标题

`# + 空格 + 标题内容`

* 语法说明

    1. 在行首插入#可标记出标题

    2. \#的个数表示标题等级

    3. 建议在#之后加一个空格

    4. Markdown最多支持六级标题

* 示例演示

![image-20210602233706829](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-02-153707.png)

建议标题写在一行的开头，结尾不要有空格和标点符号，如句号，都好，冒号，分号等。

建议标题要尽量简短，这样方便引用，特别是当生成目录时。如果原拟的标题是一个长句，可以从长句中提取标题，并将长句作为标题下的内容。

#### 4.1.1.2 粗体和斜体

在Markdown中，粗体由两个 * 或者两个 _ 包裹，斜体由一个 * 或者一个 _ 包裹

* 使用* 的加粗语法

`**加粗内容**`

* 使用_ 的加粗语法

`__加粗内容__`

* 使用* 的斜体语法

`*加粗内容*`

* 使用_ 的斜体语法

`_加粗内容_`

* 示例演示

![image-20210603001344569](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-02-161344.png)

### 4.1.2 段落与换行

Markdown支持有序列表和无序列表

有序列表使用数字序号 + 加英文句号 + 空格 + 列表内容来标记

无序列表由*/+/- + 空格 + 列表内容来标记。

#### 4.1.2.1 有序列表

* 有序列表语法如下

    `数字序号 + 英文句号 + 空格 —+ 列表内容`

* 示例演示

![image-20210603001814484](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-02-161814.png)

#### 4.1.2.2 无序列表

* 无序列表语法如下

`*/+/- + 空格 + 列表内容`

建议使用-来标记无序列表，因为* 容易跟粗体和斜体混淆,而+不流行

* 示例演示

![image-20210603002534732](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-02-162535.png)

#### 4.1.2.3 嵌套列表

* 嵌套列表语法

`+ 第一层列表`

`TAB + 第二层列表`

`TAB + TAB + 第三层列表`

* 示例演示

![image-20210603004437012](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-02-164437.png)

#### 4.1.2.4 分割线

在Markdown中，分割线由三个以上的*/-/_来标记。

* 分割线语法

`***`

`---`

`___`

==注意，在行内不要有其他的字符==

* 示例演示

![image-20210603223346746](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-03-143347.png)

### 4.1.3 图片:framed_picture:

* 插入图片的语法如下

`![图片代表文字](图片地址)`

* 语法说明

    1. 图片替代问题在图片无法正常显示时比较有用，正常情况下可以为空

    2. 图片地址是本地图片也可以是网络图片
    3. 本地图片支持相对路径和绝对路径

* 示例演示

![image-20210605145346541](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-05-065347.png)

![image-20210605145109936](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-05-065110.png)

![image-20210605145223049](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-05-065223.png)

![image-20210605145309429](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-05-065310.png)

### 4.1.4 链接 :link:

#### 4.1.4.1文字链接

文字链接就是把链接地址写在文本里。语法是用方括号包裹链接文字，后面紧跟着括号包裹的链接地址。

`[链接文字](链接地址)`

* 示例演示

![image-20210605150610474](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-05-070611.png)

![image-20210605150925108](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-05-070925.png)

相较之下，第二种写法将链接地址放在某个地方统一定义好，然后在正文中通过**变量**来引用，可读性更好一些，这种方法叫引用链接。

#### 4.1.4.3网址链接

在Markdown中，将网络地址或邮箱地址使用<>包裹起来就会被自动转换为超链接。

* 网络链接语法

`<URL或邮箱地址>`

* 示例演示

![image-20210605152121436](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-05-072121.png)

==注意 自动链接要以http/https 开头==

### 4.1.5 代码

#### 4.1.5.1 行内代码

在Markdown中，行内代码引用使用两个`包裹

* 示例演示

![image-20210605153117858](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-05-073117.png)

#### 4.1.5.2 代码块

在Markdown中，代码块以tab键或者四个空格开头

* 示例演示

![image-20210605153554490](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-05-073554.png)

因为代码块使用tab后者四个空格开头的效果不够直观，很多扩展语法如GFM提供了***围栏代码块***功能，并且支持语法高亮，详见4.2.5。

### 4.1.6 引用

在Markdown中，引用由 > + 引用内容来标记

* 引用语法

`> 引用内容`

* 语法说明

    1. 多行引用也可以在没一行的开头都插入> 。
    2. 在引用中可以嵌套引用
    3. 在引用中可以嵌套其他的Markdown语法
    4. 段落与换行的格式在引用中也是适用的。

* 示例演示

![image-20210605165843595](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-05-085844.png)

### 4.1.7 转义

当我们在Markdown文件中插入一些标记，但是又不想这些符号被渲染时，可以使用\进行转义

* 转义语法

`\特殊符号`

可被转义的字符

```markdown
\   反斜线
`   反引号
*   星号
_   底线
{}  花括号
[]  方括号
()  括弧
#   井字号
+   加号
-   减号
.   英文句点
!   惊叹号
```

* 示例演示

![image-20210605170717467](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-05-090717.png)

## 4.2 扩展语法

在众多Markdown扩展语法中，Github Flavored Markdown（简称 GFM）无疑是最流行的，它提供了包括表格，任务列表，围栏代码块，蔚蓝代码，emoji表情等在内的标记语法。

### 4.2.1 删除线

* 删除线语法

`~~被删除文字~~`

* 示例演示

![image-20210605171920271](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-05-091921.png)

### 4.2.2 表情符号:dog:

使用：包裹表情代码即可

* 表情符号与法

`:表情代码:`

* 示例演示

![image-20210605172850754](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-05-092851.png)

更多表情符号，请查阅<https://emoji.svend.cc/>

### 4.2.3 表格

* 表格语法

```markdown
| 表头1 | 表头2 | 表头2 |
| ---- | ---- | ---- |
| 内容1 | 内容2 | 内容3 |
| 内容1 | 内容2 | 内容3 |
```

* 语法说明

    1. 单元格之间使用|来分割，为了阅读清晰，建议前和后都使用|
    2. 表头和其他行使用----来分割
    3. 表格对齐方式
        1. 左对齐(默认) `:----`
        2. 右对齐 `----:`
        3. 居中对齐 `:----:`

    4. 块级元素（代码区域，引用区块）不能插入表格

* 示例演示

![image-20210605175509710](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-05-095510.png)

### 4.2.4 任务列表

* 任务列表语法

```markd
- [ ] 未勾选
- [x] 未勾选
```

* 语法说明

    1. 任务列表以-或者+开头，然后加[ 空格 / + ]
    2. x可以小写也可以大写，推荐使用小写x
    3. 方括号中的符号为空格时，复选框是未选中状态，为x时是选中状态

* 示例演示

![image-20210605181432884](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-05-101433.png)

### 4.2.5 围栏代码块

* 围栏代码语法

```markdown
​```
代码块
​```
或者
~~~
代码块
~~~

语法高亮

​```编程语言的名称
代码块
​```
```

* 语法说明

围栏代码使用三个`或者~包裹，支持语法高亮并可以加上编程语言的名称

* 示例演示

![image-20210605182516976](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-05-102517.png)

### 4.2.6 目录

* 生成目录的语法

~~~markdown
[toc]
~~~

* 示例演示

![image-20210605184138034](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-05-104138.png)



## 4.3 排版建议

* 英文标点符号（如,.;:?）与后面的字符之间需要加空格，与前面的字符不需要加空格

* 当在中文，或者英文中使用>标识路径是，两边加空格

    例如 偏好设置 →通用 →高级设置

* 数字和百分号之间不需要添加空格

* 数字和单位符号之间不需要添加空格

* 货币符号后不加空格

* 中文排版中，使用全角标点符号

* 英文排版中，使用半角标点符号

* 正确使用英文大小写

# 5. Typora编辑器使用

## 5.1 软件安装

Typora是目前最受欢迎的Markdown编辑器之一，主要特性如下

1. 实时预览：传统的Markdown编辑器都有两个窗口，左边是源码，右边是渲染后的结果。Typora 独辟蹊径，把源码编辑和预览效果合二为一，实现了真正的所见即所得。
2. 扩展语法：Typora不仅支持GFM，还扩展数学公式，流程图等功能
3. 快捷操作：Typora对几乎所有的Markdown标记都提供了快捷操作方式，使用起来非常高效。
4. 界面漂亮：默认支持6种主题，可自定义，好看又好用
5. 文件转换：支持多种文件格式通过导入/导出功能跟.md格式相互转换
6. 支持中文，可以帮助大家更好的理解各项功能
7. 视图模式：支持大纲和文档列表视图，方便在不同段落和不同文件之间进行切换
8. 跨平台：支持macOS，windows和Linux系统
9. 目前免费：真香

下载地址：<https://www.typora.io/>

## 5.2 界面介绍

在默认情况下，Typora会使用操作系统的语言，如果需要自定义语言，可以在Typora编辑器上执行如下操作：偏好设置 →通用 →语言 ，选择语言后，重启Typora即可生效。

Typora编辑器的界面

![image-20210606191009446](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-06-111009.png)

默认鼠标放到状态栏才会显示字数统计，如果我们想让字数一直显示，则需要在**偏好设置**中设置，操作步骤：文件→ 偏好设置 → 外观 → 字数统计 → 勾选 **总是显示字数统计**

Typora编辑器最具特色的功能就是实时预览，当输入Markdown标记后，按回车键或者定位到别的段落就可以看到预览效果。之前介绍的Markdown语法，Typora都支持

```markdown
## 常用标记
**粗体** ，*斜体*，==高亮==，~~删除线~~，<u>下划线</u>，我是^上标^，我是~下标~，[超链接](http://www.baidu.com)
![图片](https://wx1.sinaimg.cn/large/008egyxIly1gqh131whhfj30u010yagf.jpg)
无序列表
- 无序列表1
- 无序列表2
1. 有序列表
2. 有序列表
任务列表
-[ ] 看电影
-[ ] 听音乐
```

渲染后的效果

![image-20210620234753126](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-20-154753.png)

## 5.3 高效使用Typora

Typora支持GFM，还扩展了很多其他的功能（如支持的数学公式，上标，下标，高亮，各种图表），它几乎为每个标记提供了快捷的操作方式，这使得我们的写作变得轻松。

### 5.3.1 基础语法和GFM语法

#### 5.3.1.1 编辑样式

在Typora中通过执行：菜单栏 → **格式** → 加粗/斜体/代码/图像/超链接 ，可以添加或移除关于文字样式的的标记符号。如果没有选中文字，则只会添件标记符号；如果选中了文字，则会为选中的文字添加或移除标记符号

格式快捷键

Format

| 操作     | Windows | macOS        |
| :-----------: | :---------------------: | :---------------------: |
| 加粗       | Ctrl + B               | Command + B           |
| 斜体     | Ctrl + I               | Command + I           |
| 下划线 | Ctrl + U               | Command + U           |
| 行内代码       | Ctrl + Shift + \` |Control + \`|
| 删除线       | Alt + Shift + 5        | Control + Shift + `   |
| 超链接 | Ctrl + K               | Command + K           |
| 图片      | Ctrl + Shift + I       | Command + Control + I |
| 清除格式 | Ctrl + \               | Command + \           |
| 源代码模式/预览模式切换 | Ctrl + / | Command + / |

#### 5.3.1.2 编辑段落

在Typora中通过执行：菜单栏 → **段落** → 段落/引用/表格/代码块/分割线/有序列表/无序列表/任务列表，可以添加或删除关于段落的标记符号

1. 段落的快捷键

| 操作         | Windows                | macOS                     |
| :-----------: | :---------------------: | :-------------------------: |
| 标题1-6      | Ctrl + 1/2/3/4/5/6     | Command + 1/2/3/4/5/6     |
| 正文         | Ctrl + 0               | Command + 0               |
| 提升标题级别 | Ctrl + =               | Command + =               |
| 降低标题级别 | Ctrl + -               | Command + -               |
| 添加有序列表 | Ctrl + Shift + [       | Command + Option + O      |
| 添加无序列表 | Ctrl + Shift + ]       | Command + Option + U      |
| 减少缩进   | Ctrl + [         | Command + [         |
| 增加缩进    | Ctrl + ] | Command + ] |
| 添加任务状态 | 无                     | Option + Command + X      |
| 切换任务状态 | 无                     | Control + X               |

**注意**:secret:

* 当光标放在任务列表上时，任务状态被激活，这时才可以切换任务状态

* *列表*和*代码块*都可以使用**增加缩进**和**减少缩进**

2. 引用和水平分割线

与引用和水平分割线对应的快捷键

| 操作     | Windows            | macOS                 |
| :-------: | :-----------------: | :---------------------: |
| 添加引用 | Ctrl + Shift + Q | Option + Command + Q |
| 添加水平分割线 | 无         | Option + Command + - |

3. 表格

如果想创建一个表格，可以执行菜单栏 → **段落** → 表格 → 输入列数和行数 → 单击确定按钮。

创建表格的快捷键

|   操作   | Windows          |          macOS           |
| :------: | :---------------: | :----------------------: |
| 创建表格 | Ctrl + Shift + T |   Option + Command + T   |
| 增加一行 | Ctrl + Enter     |     Command + Enter      |
| 删除一行 | Ctrl + Backspace | Command + Shift + Delete |

对于表格的增加，删除，复制和格式化操作，可以在表格中单击鼠标右键，选择**表格**，通过其列出的操作选项对表格进行操作。如图

![image-20210606204601224](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-06-124601.png)

快速调整表格

如果想快速调整表格的行数，列数，对齐方式，可以将光标放在表格中，表格左上方和右下方都会显示操作菜单，直接进行操作即可。==但是不太建议用这种方式调整对齐方式，否则整个文档粘贴到博客当中之后，可能还是调整前的状态，建议直接修改源代码，用:来调整==

![image-20210606205215428](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-06-125215.png)

如果想调整表格中行或列的顺序，可将光标放在行的最左边或列的最上边，当光标变成双向箭头后拖动即可调整顺序。

![Jietu20210606-210513-HD](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-06-130634.gif)

4. 围栏代码块

如果想添加或删除围栏代码块的标记，可以执行菜单栏 → 段落 → 代码块。如果想把某段内容使用围栏代码块包裹，需要首先选中该内容，然后执行上述操作。

围栏代码块快捷键

|  操作  | Windows          |        macOS         |
| :----: | :---------------: | :------------------: |
| 代码块 | Ctrl + Shift + K | Option + Command + C |



代码块默认是不显示行数的，如果想显示行数，则需要执行文件 → 偏好设置 → markdown →代码块 → 勾选显示行数。

在代码块中，如果代码过长，默认是会自动换行的。如果不希望代码自动换行，可以执行，文件 → 偏好设置 → markdown → 代码块 → 不勾选代码块自动换行。

### 5.3.2 Typora扩展语法1

Typora扩展了下划线，数学公式，目录，脚注，上标和下标，图表操作等功能，并且支持很多HTML标签，使排版样式更加齐全。

#### 5.3.2.1 下划线

在Typora中，下划线是通过HTML的<u>标签来实现的，语法如下

`<u>这段文字下面有下划线</u>`，效果就是这样，<u>这段文字下面有下划线</u>

下划线快捷键

|  操作  | Windows  |   macOS    |
| :----: | :-------: | :--------: |
| 下划线 | Ctrl + U | Command +U |

#### 5.2.2.2 高亮

如果想使用高亮，需要首先激活偏好设置 → Markdown → Markdown扩展语法 → 勾选高亮→ 重启Typora。

Typora的语法

`==高亮内容==`

* 语法说明

    1. 使用两个等号（=）把想要高亮的内容包裹起来

    2. 设置的高亮的内容是显示为黄色

* 示例演示

```markdown
==我醉欲眠卿且去==，明朝有意抱琴来
```

渲染后的效果

==我醉欲眠卿且去==，明朝有意抱琴来

还可以执行：菜单栏 → 格式 → 高亮，插入高亮的语法标记

#### 5.2.2.3 注释

如果想添加注释，可以执行：菜单栏 → 格式 → 注释，在编辑和预览时，注释的内容会被显示；在导出PDF和word时，则会被隐藏

设置注释的语法

```markdown
<!--我是注释-->
```

设置注释的快捷键

| 操作 | Windows |    macOS    |
| :--: | :------: | :---------: |
| 注释 | 无      | Control + - |

#### 5.2.2.4 清除格式

如果想快速清除样式，可以执行：菜单栏 → 格式 → 清除样式

清除样式的快捷键

| 操作 | Windows  |    macOS    |
| :--: | :-------: | :---------: |
| 清除样式 | Ctrl + \ | Control + \ |

### 5.3.3 Typora扩展语法2

#### 5.3.3.1 上标和下标

如果想使用上标和下标，需要首先激活偏好设置 → Markdown → Markdown扩展语法 → 勾选下标/上标 → 重启Typora。上标和下标的语法

`~下标内容~`

`^上标内容^`

* 语法说明

1. 使用~把下标内容包裹起来
2. 使用^把上标内容包裹起来

* 示例演示

```Markdown
下标：H~2~O

上标：x^2^ + Y^2^
```

渲染后的效果

下标：H~2~O

上标：x^2^ + Y^2^

还可以执行：菜单栏 → 格式 → 上标/下标，插入上标/下标的语法标记

#### 5.3.3.2 内联数学公式

如果想使用内联数学公式，需要首先激活偏好设置 → Markdown → Markdown扩展语法 → 勾选内联公式 → 重启Typora。内联数学公式的语法是使用$把数学公式包裹起来

`$数学公式$`

* 示例演示

```markdown
分数：$f(x,y) = \frac{x^2}{y^3}$
开根号：$f(x,y) = \sqrt[n]{{x^2}{y^3}}$
省略号：$f(x~1~,x~2~，\ldots,x~n~) = x~1~ + x~2~ + + \cdots x~n~$
```

渲染后的效果

分数：$f(x,y) = \frac{x^2}{y^3}$
开根号：$f(x,y) = \sqrt[n]{{x^2}{y^3}}$
省略号：$f(x~1~,x~2~，\ldots,x~n~) = x~1~ + x~2~ + + \cdots x~n~$

还可以执行：菜单栏 → 格式  →  内嵌公式 ，插入内联数学公式。

设置插入内联数学公式的快捷方式

|     操作     | Windows |    macOS    |
| :----------: | :-----: | :---------: |
| 内联数学公式 |   无    | Control + M |

#### 5.2.3.3 数学公式块

专业的写作离不开数学公式。其语法是使用两个$包裹数学公式

```markdown
$$
数学公式
$$
```

为某段内容添加或删除公式块，需要先选中该内容，然后执行：菜单栏 → 段落 → 公式块，如果不选中任何内容，直接执行：菜单栏 → 段落 → 公式块，则会插入公式块标记。

公式块快捷键

|  操作  |     Windows      |        macOS         |
| :----: | :--------------: | :------------------: |
| 公式块 | Ctrl + Shift + M | Option + Command + M |

### 5.3.4 Typora扩展语法3

如果想使用图表功能,需要先激活:文件→偏好设置 → Markdown →Markdown扩展语法 →勾选 图表→重启 Typora
注意

1. 图表是 Typora的扩展语法,标准的 Markdown语法、 CommonMark和GFM都不支持这一语法。
2. 如果想要把图表使用到更多的地方,推荐直接插入图片,不推荐在 Typora中进行绘制
3. 在 Typora中,图表在导出 HTML/PDF/ePub/dox等格式的文件时会被正常显示,但是其他的 Markdown编辑器不一定支持此语法。

#### 5.2.4.1  序列图

序列图( Sequence Diagram)也被称为循序图,是一种UML( Unified Modeling Language,统一建模语言)行为图,它通过描述对象之间发送消息的时间顺序显示多个对象之间的动态协作。
Typora提供的序列图语法标记功能是基于开源项目发的

* 语法

```markdown
​```sequence
js-sequence-diagrames语法
​```
```

* 语法说明
    1. 使用3个 \` +  sequence包裹js-quence-diagrams语法。
    2. js-sequence-diagrams语法参考<http://bramp.githu.io/js-sequence-diagrams/>。

* 示例演示

```markdown
​```sequence
interface->CanTp:CanTp_Transmit
CanTp->CanTp:Check input
CanTp->CanTp:Active a Tx task
CanTp-->interface:
CanTp->interface:PduR_CanTpCopyTxData
interface->interface:copy segment data
interface-->CanTp:
CanTp->CanIf:CanIf_Transmit
CanIf-->CanTp:
CanIf->CanTp:CanTp_TxConfirmation
CanTp-->CanIf:
CanTp->interface:PduR_CanTpTxConfirmation
interface-->CanTp:
​```
```

* 渲染效果

![image-20210620233726718](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-20-153727.png)

#### 5.2.4.2 流程图

流程图是以图像的方式表示过程，算法和流程的，Typora提供的流程图语法标记是基于开源项目(flowchart.js)开发的

flowchart.js语法参考<http://flowchaer.js.org/>。

#### 5.2.4.3 甘特图

## 5.4 自定义Typora主题

如果想更换Typora主题，可以执行：菜单栏 → 主题→ 选择中意的主题

Typora软件安装后，就有五种主题可选择，如果感觉不太满意，可以去[官网主题](https://theme.typora.io/)下载。

也可以在github上下载[Typora主题](https://github.com/luxihua201010028/Typora-theme),然后放在主题文件夹下即可。

如果不知道安装目录，可以执行：菜单栏 → 偏好设置 → 外观→ 打开主题文件夹，就可以打开主题文件夹，重启Typora即可看到下载的主题，选择即可。

![image-20210608215821717](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-135821.png)

## 5.5 Typora自动上传图片至阿里云图床

Typora + ipic + 阿里云OSS

### 5.5.1 阿里云图床环境搭建

1. [注册阿里云账号](https://account.aliyun.com/register/register.htm?spm=5176.12901015.yrepazatz.1.3ec5525covwkoT&oauth_callback=https%3A%2F%2Fwww.aliyun.com%3Fspm%3D5176.12901015.0.i12901015.3ec5525covwkoT)，手机号注册即可

![image-20210608220913086](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-140913.png)

2. 阿里云控制台 → 产品与服务 → 对象存储OSS → Bucket列表 → 创建Bucket

![image-20210608221058065](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-141058.png)

![image-20210608221238617](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-141239.png)

![image-20210608221615157](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-141615.png)

3. 设置Bucket

注意：==Bucket名称只允许小写字母、数字、短横线（-），且不能以短横线开头或结尾==

参考配置如下

![image-20210608222628067](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-142628.png)

![image-20210608222702498](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-142703.png)

几点注意事项

* Bucket名称 （配置iPic需要用到）

* Endpoint的地址（配置IPic需要用到）

* 选择公共读

* 存储类型和空间，按需购买设置

4. 创建子用户 AccessKey

控制台 → AccessKey管理 →  开始使用子用户AccessKey

![image-20210608223424628](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-143424.png)

![image-20210608223531105](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-143531.png)

![image-20210608223714196](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-143714.png)

![image-20210608224031312](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-144033.png)

注意：==创建成功后，弹出下图信息，这里的AccessKey Secret只显示一次，自己备份下来==

![image-20210608224320023](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-144320.png)

如果一不小心手抖了，将网页切走了，可以到 控制台 → AccessKey管理 → 继续使用AccessKey  → 继续使用子用户 → 输入手机号 → 复制AccessKeyId和AccessKey

![image-20210608225751486](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-145752.png)

5. 给刚创建的用户添加管理OSS权限

![image-20210608224612077](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-144612.png)

![image-20210608224737786](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-144738.png)

如此，阿里云OSS准备工作完成。

### 5.5.2 iPic添加阿里云Oss

前往商店下载IPic即可，这里主要说下如何设置阿里云OSS

iPic → 偏好设置 → 图床 → + → 选择阿里云OSS

![image-20210608230359850](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-150400.png)

* Bucket 就是我们设置Bucket名称
* AccessKey 就是上面得到的AccessID
* Secret Key 就是上面得到的AccessKey Secret
* 网址前缀设置如下，点击==验证==即可检验信息是否填写正确

![image-20210608231346370](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-151346.png)

### 5.5.3 Typora设置图片上传位置

偏好设置 → 图像 → 插入图片时上传图片

![image-20210608231745977](https://luxihua201010028.oss-cn-hangzhou.aliyuncs.com/2021-06-08-151746.png)

注意:point_right:

* 勾选 对于网络位置/本地位置的图片应用上述规则，即上传
* 头癣允许根据YAML设置自动上传图片
* 选择使用iPic上传

如此，Typora就会将图片自动上传至阿里云

