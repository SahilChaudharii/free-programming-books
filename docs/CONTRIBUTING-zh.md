*[阅读本文的其他语言版本](README.md#nslations)*


## 贡献者许可协议

请遵循此[许可协议](../LICENSE)参与贡献。


## 贡献者行为准则

请同意并遵循此[行为准则](CODE_OF_CONDUCT.md)参与贡献。([translations](README.md#nslations))


## 概要

1. "轻松下载图书的链接 "并不一定是免费图书的链接。请只提供免费内容。确保是免费的。我们不接受需要工作电子邮件地址来获取书籍的页面链接，但我们欢迎要求提供电子邮件地址的列表。

2.您不一定要懂 Git：如果您发现了一些感兴趣的内容，而本版本库中还没有，请打开一个 Issue，提出您的链接建议。

3.如果您了解 Git，请叉入 repo 并发送 Pull Requests (PR)。
我们有 6 种列表。请选择合适的一种：

•	书籍：PDF、HTML、ePub、基于 gitbook.io 的网站、Git 仓库等。
•	课程：课程是一种学习材料，它不是一本书 [This is a course](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-              algorithms-fall-2011/)。
•	*Interactive Tutorials* ：互动网站，让用户输入代码或命令，并对结果进行评估（"评估 "不是指 "评分"）。：[Try Haskell](http://tryhaskell.org)[Try GitHub](http://try.github.io)。

•	Playgrounds : 在线互动网站、游戏或桌面软件，用于学习编程。可以编写、编译（或运行）和共享代码片段。游戏场通常允许你分叉，并通过玩代码弄脏自己的手。
•	播客和截屏： 播客和截屏。
•	Problem Sets & Competitive Programming（问题集与竞技编程）：一个网站或软件，让您通过解决简单或复杂的问题来评估自己的编程技能，无论是否进行代码审查，                    也无论是否与其他用户比较结果

4. 确保按照(#基本准则)，并尊重 [Markdown规定格式](#规定格式)。

5. GitHub Actions 将运行测试，以确保你的列表是 **按字母顺序排列** 的，并 **遵循格式化规则**。请 **确保** 你的更改通过了该测试。
   

### 基本准则

- 确保一本书是免费的。如有需要，请再三确认。如果您在 PR 中评论为什么您认为该书是免费的，会对管理员有所帮助。
- 我们不接受托管在 Google Drive、Dropbox、Mega、Scribd、Isusuu 和其他类似文件上传平台上的文件。
- 按字母顺序插入链接，如下所述。(#alphabetical-order).
- 使用最权威来源的链接（即作者的网站优于编辑的网站，编辑的网站优于第三方网站）
- 不使用文件托管服务（包括（但不限于）Dropbox 和 Google Drive 链接）

* 优先选择使用 `https` 链接，而不是 `http` 链接 -- 只要它们位于相同的域并提供相同的内容。
* 在根域上，去掉末尾的斜杠：使用 `http://example.com` 代替 `http://example.com/`。
* 总是选择最短的链接：使用 `http://example.com/dir/` 比使用 `http://example.com/dir/index.html` 更好。
    * 不要提供短链接
* 优先选择使用 "current" 链接代替有 "version" 链接：使用 `http://example.com/dir/book/current/` 比使用 `http://example.com/dir/book/v1.0.0/index.html` 更好。
* 如果一个链接存在过期的证书/自签名证书/SSL问题的任何其他类型：
    1. *replace it* ：如果可能的话，将其 *替换* 为对应的`http`(因为在移动设备上接受异常可能比较复杂)。
    2. *leave it* ：如果没有`http`版本，但仍然可以通过`https`访问链接，则在浏览器中添加异常或忽略警告。
    3. *remove it* ：上述以外删除掉它。
* 如果一个链接以多种格式存在，请添加一个单独的链接，并注明每种格式。
* 如果一个资源存在于Internet上的不同位置
    * 使用最权威来源的链接(意思是原始作者的网站比编辑的网站好，比第三方网站好)。
    * 如果它们链接到不同的版本，你认为这些版本差异很大，值得保留，那么添加一个单独的链接，并对每个版本做一个说明(参见[Issue #2353](https://github.com/EbookFoundation/free-programming-books/issues/2353)有助于格式化问题的讨论)。
* 相较一个比较大的提交，我们更倾向于原子提交(通过添加/删除/修改进行一次提交)。在提交PR之前没有必要压缩你的提交。(我们永远不会执行这个规则，因为这只是维护人员的方便)。
* 如果一本书比较旧，请在书名中注明出版日期。
* 包含作者的名字或适当的名字。中文版本可以用 “`等`” (“`et al.`”) 缩短作者列表。
* 如果一本书还没有完成，并且仍在编写中，则需添加 “`in process`” 符号，参见[下文](#in_process)所述。
- if a resource is restored using the [*Internet Archive's Wayback Machine*](https://web.archive.org) (or similar), add the "`archived`" notation, as described [below](#archived). The best versions to use are recent and complete.
* 如果在开始下载之前需要电子邮件地址或帐户设置，请在括号中添加合适的语言描述，例如：`(*需要*电子邮件，但不是必须的)`。


### 规定格式

* 所有列表都是`.md`文件。试着学习[Markdown](https://guides.github.com/features/mastering-markdown/)语法。它很容易上手！
* 所有的列表都以索引开始。它的作用是列出并链接所有的sections(章节/段落)或subsections(子段落/子章节)。务必遵循字母顺序排列。
* Sections(章节/段落)使用3级标题(`###`)，subsections(子段落/子章节)使用4级标题 (`####`)。

整体思想为：

* `2` ：新添加的Section与末尾链接间必须留有`2`个空行
* `1` ：标题和第一个链接之间必须留有`1`个空行的空行
* `0` ：任何两个链接之间不能留有任何空行
* `1` ：每个`.md`文件末尾必须留有`1`个空行

举例：

```text
[...]
* [一本很有用的书](http://example.com/example.html)
                                (空行)
                                (空行)
### 电子书种类标题
                                (空行)
* [Another 很有用的书](http://example.com/book.html)
* [Other 有用的书](http://example.com/other.html)
```

* 在 `]` 和 `(` 之间不要留有空格：

    ```text
    错误：* [一本很有用的书] (http://example.com/book.html)
    正确：* [一本很有用的书](http://example.com/book.html)
    ```

* 如果包括作者，请使用' - '(由单个空格(英文半角)包围的破折号)：

    ```text
    错误：* [一本很有用的书](http://example.com/book.html)- 张显宗
    正确：* [一本很有用的书](http://example.com/book.html) - 张显宗
    ```

* 在链接和电子书格式之间放一个空格：

    ```text
    错误：* [一本很有用的书](https://example.org/book.pdf)(PDF)
    正确：* [一本很有用的书](https://example.org/book.pdf) (PDF)
    ```

* 如需备注或注解，请使用英文半角括号`( )`：

    ```text
    错误：* [一本很有用的书](https://example.org/book.pdf) （繁体中文）
    正确：* [一本很有用的书](https://example.org/book.pdf) (繁体中文)
    ```

* 作者在电子书格式之前：

    ```text
    错误：* [一本很有用的书](https://example.org/book.pdf)- (PDF) 张显宗
    正确：* [一本很有用的书](https://example.org/book.pdf) - 张显宗 (PDF)
    ```

* 多重格式：

    ```text
    错误：* [一本很有用的书](http://example.com/)- 张显宗 (HTML)
    错误：* [一本很有用的书](https://downloads.example.org/book.html)- 张显宗 (download site)
    正确：* [一本很有用的书](http://example.com/) - 张显宗 (HTML) [(PDF, EPUB)](https://downloads.example.org/book.html)
    ```

* 多作者，多译者时，请使用中文 `、` 进行分隔，在译者名字后请使用英文半角括号包围的 `(翻译)`，可以用 “等” 缩短作者列表：

    ```text
    错误：* [一本很有用的书](https://example.org/book.pdf) - 张显宗，岳绮罗
    正确：* [一本很有用的书](https://example.org/book.pdf) - 张显宗、岳绮罗(翻译)
    正确：* [一本很有用的书](https://example.org/book.pdf) - 张显宗、岳绮罗、顾玄武、出尘子 等
    ```

* 在旧书的标题中包括出版年份：

    ```text
    错误：* [一本很有用的书](https://example.org/book.html) - 张显宗 - 1970
    正确：* [一本很有用的书 (1970)](https://example.org/book.html) - 张显宗
    ```

* <a id="in_process"></a>编写(翻译)中的书籍：

    ```text
    正确：* [马上出版的一本书](http://example.com/book2.html) - 张显宗 (HTML) (:construction: *编写中*)
    正确：* [马上出版的一本书](http://example.com/book2.html) - 张显宗 (HTML) (:construction: *翻译中*)
    ```

- <a id="archived"></a>存档链接：

    ```text
    正确: * [A Way-backed Interesting Book](https://web.archive.org/web/20211016123456/http://example.com/) - John Doe (HTML) *(:card_file_box: archived)*
    ```

### 按字母顺序排列

- 当有多个标题以相同字母开头时，按第二个字母顺序排列，以此类推。例如: `aa` 先于 `ab`.
- `one two` 先于  `onetwo`

如果发现链接错位，请查看链接器的错误信息，了解哪些行应该互换。


### 注意事项

虽然基础知识相对简单，但我们列出的资源却多种多样。下面是我们如何处理这种多样性的一些说明。


#### 元数据

我们的列表提供了一套最基本的元数据：标题、URL、创建者、平台和访问说明。


##### 标题

- 没有杜撰的标题。我们尽量使用资源本身的标题；我们告诫投稿人不要编造标题，如果可以避免的话，也不要在编辑时使用标题。但较早的作品例外；如果这些作品主要是历史性的，则在标题后的括号中加上年份，以帮助用户了解这些作品是否值得关注。
- 不使用 ALLCAPS 标题。通常标题大小写是合适的，但如果有疑问，请使用来源的大写字母。
- 不使用表情符号。


##### 网址

- 我们不允许缩短 URL。
- 必须删除 URL 中的跟踪代码。
- 国际网址应转义。浏览器栏通常会将其转换为 Unicode，但请使用复制和粘贴。
- 在已实施 HTTPS 的情况下，安全 (`https`)URL 始终优于非安全 (`http`)URL。
- 我们不喜欢指向不包含所列资源、而是指向其他地方的网页的 URL。


##### 创建者

- 我们希望在适当的地方注明免费资源创建者的姓名，包括翻译者！
- 对于翻译作品，应注明原作者。我们建议使用[MARC relators](https://loc.gov/marc/relators/relaterm.html)来标明作者以外的创作者，如本示例：

    ``标记
    * [一本翻译过的书](http://example.com/book-zh.html) - 无名氏，"翻译 "迈克
    ```

    在这里，注释 `trl.:` 使用 MARC 中的 "translator".
- 使用逗号", "来分隔作者列表中的每个项目。
- 您可以使用"`et al.`"缩短作者列表。
- 我们不允许链接 "创作者"。
- 对于汇编或混音作品，"创作者 "可能需要说明。例如，"GoalKicker "或 "RIP Tutorial "书籍的作者署名为"`根据 StackOverflow 文档编译`"。

##### 平台和访问说明

- 课程。特别是对于我们的课程列表而言，平台是资源描述的重要组成部分。这是因为课程平台有不同的承受能力和访问模式。虽然我们通常不会列出需要注册的书籍，但许多课程平台都有没有某种账户就无法使用的功能。例如，课程平台包括 Coursera、EdX、Udacity 和 Udemy。当课程依赖于某个平台时，应在括号中列出平台名称。
- YouTube。我们有许多课程由 YouTube 播放列表组成。我们不会将 YouTube 列为一个平台，我们会尽量列出 YouTube 的创建者，这通常是一个子平台。
- YouTube 视频。我们通常不会链接到单个 YouTube 视频，除非这些视频长度超过一小时，结构类似于课程或教程。
- Leanpub。Leanpub 提供多种访问模式的图书。有时，一本书无需注册即可阅读；有时，一本书需要一个 Leanpub 账户才能免费阅读。考虑到图书的质量以及 Leanpub 访问模式的混合性和流动性，我们允许列出后者，并附带 "*"访问说明。(Leanpub account or valid email requested)*`.


#### 类型

决定一个资源属于哪个列表的首要原则是看该资源是如何描述自己的。如果它自称是一本书，那么它可能就是一本书。


##### 我们没有列出的类型

由于互联网浩瀚无边，我们不将以下资源列入列表：

- 博客
- 博文
- 文章
- 网站（除了那些包含大量我们列出的项目的网站）。
- 非课程或截屏的视频。
- 书籍章节
- 书中的预告样本
- IRC 或 Telegram 频道
- Slacks 或邮件列表

我们的竞争性编程列表对这些排除项的要求并不严格。repo 的范围由社区决定；如果您想对范围提出修改或补充建议，请使用问题来提出建议。


##### 图书与其他内容

我们对书籍的性质并不那么挑剔。以下是表明资源是图书的一些属性：

- 有 ISBN（国际标准书号）
- 有目录
- 提供可下载版本，尤其是 ePub 文件。
- 有版本
- 不依赖互动内容或视频
- 试图全面涵盖一个主题
- 自成一体

我们列出的很多书籍都不具备这些属性；这可能取决于具体情况。


##### 图书与课程

有时这两者很难区分！

课程通常有相关的教科书，我们会将其列在书籍列表中。课程有讲座、练习、测试、笔记或其他教学辅助材料。单个讲座或视频本身不是一门课程。Powerpoint 也不是一门课程。


##### 互动教程与其他内容

如果可以打印出来并保留其精髓，那就不是互动教程。


###自动化

- 通过 [GitHub 操作] 自动执行格式化规则(https://github.com/features/actions) 使用 [fpb-lint](https://github.com/vhf/free-programming-books-lint) (see [`.github/workflows/fpb-lint.yml`](../.github/workflows/fpb-lint.yml))
- URL 验证使用 [awesome_bot](https://github.com/dkhamsing/awesome_bot)
- 要触发 URL 验证，请推送包含提交信息的提交，信息中应包含 `check_urls=file_to_check`:

    ```属性
    check_urls=free-programming-books.md free-programming-books-zh.md
    ```

- 您可以指定多个要检查的文件，每个条目之间用一个空格隔开。
- 如果您指定了多个文件，构建结果将基于最后检查的文件的结果。因此，请务必点击 "显示所有检查"->"详细信息"，在拉动请求的最后检查构建日志。
