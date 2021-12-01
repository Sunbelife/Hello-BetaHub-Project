# Hello-BetaHub-Project

首先，感谢您参与 Hello BetaHub 项目。

让全世界的用户都有机会成为如您一样热爱探索的尝鲜派。

为了大家翻译工作的高效。

请在翻译前参考本指南：

# 开始之前

### 语法和工具

工欲善其事，必先利其器。

在一切工作开始之前，先向你介绍一下我们使用的翻译工具。

一共有两种，一个是基于 Markdown 的文档，用来撰写升级教程等图文内容。

另一个是 .po 格式的翻译文件，用来翻译网站按钮等文字内容。

另外为了大家协作起来更方便，使用了 Github 这个平台。

如果以上内容有不明白的，不用担心，需要时学习就可以，它们都很简单。

### 目录结构和流程

接着向你介绍一下翻译的整个流程。

首先你需要把项目 Clone 到本地。

接着你会发现，项目中有「Web Content」和「Article Content」两个文件夹。

其中「Web Content」存放了有关网站主程序的翻译内容，是 .po 格式的翻译文件。

这些内容是用户与之操作，和网站的框架性内容。

![][Main Program]

而「Article Content」存放了升级教程等图文内容，比如升级教程，关于等页面。

![][Article Content]

下面分别介绍这两个流程。

#### Web Content 翻译流程

这部分我们使用的翻译工具是：「Poedit」，您可以在网上免费下载到：

> https://poedit.net/

文件夹内除了包含了各个语言的翻译文件夹之外，

还包含了一份名为「Keywords.md」的关键词对照表：

![][Web Content Folder]

1. 开始之前，请新建一个文件夹，名称任意：

![][Web Content New Folder]

2. 打开 Poedit，选择「新建」，选择您希望翻译的源语言，并选择翻译的目标语言。

![][Web Content Target Language]

3. 接着立即保存至刚才新建的文件夹中，此时它会生成一个此语言名称的文件名，例如「ja_JP」，把这个文件名保存下来，并更改为「app」。

最终的路径规则应该如下：

> 1. 文件夹名称：语言名称
> 2. 语言名称的文件夹内有且仅包含一个文件夹，名为：LC_MESSAGES
> 3. LC_MESSAGES 中储存名为 app.po 的翻译文件

![][Web Content Path]

4. 接着就只需要打开 app.po，选择上方的文本，在下方的翻译区逐一翻译并保存即可。

![][Web Content Translate]

5. 需要注意的是，部分词汇请参考 Keywords.md 中的翻译规则：

![][Web Content Keywords]

6. 最后，请一定记得保存！

#### Article Content

这部分我们对使用的工具没有限制。

Typora、CodeRunner、Taio 都可以使用。

1. 在开始之前，请新建一个文件夹，名称为上一步时保存的文件夹名称。

![][Article Content New Folder]

2. 选择您希望翻译的源语言文件夹，复制全部内容到你刚才新建的文件夹中：

![][Article Content All Content]

3. 接着将每个 .md 文件逐个翻译即可：

![][Article Content MD]

4. 需要注意的是，其中「ItemName.md」为其他 .md 文件的文章名称，其中只需翻译「Now =>」部分，如图所示：

![][Article Content ItemName]

5. 最后，还是一定要记得保存！

# 最后一步，提交

如果您完成了翻译，请提交 Pull Request 到这个项目中。

如果您不知道如何提交，也可以邮件发送至 i@Sunbelife.com，有遇到什么其他问题也可以随时联系。

# 最后的最后

最后的最后，恭喜和感谢您成为尝鲜派的志愿者们之一。

通过您的工作，可以让更多人遇见尝鲜派。

也可以让我们遇到更多热爱尝鲜的人们。

尝鲜派目前仍然是非盈利组织，它的发展离不开每位用户和志愿者们的支持。

我们会在相应的位置标注您的署名，以及对您身份的永久承认。

感谢大家，辛苦了！

尝鲜派创始人 Sunbelife

[Main Program]: https://tva1.sinaimg.cn/large/008i3skNgy1gwsp92fvmzj30w90u0gnz.jpg
[Article Content]: https://tva1.sinaimg.cn/large/008i3skNgy1gwspg1nlfaj30w90u041r.jpg
[Web Content Folder]: https://tva1.sinaimg.cn/large/008i3skNgy1gwspsivn2qj316g0u0wgn.jpg
[Web Content New Folder]: https://tva1.sinaimg.cn/large/008i3skNgy1gwwfc0y7llj31ew0u0dig.jpg
[Web Content Target Language]: https://tva1.sinaimg.cn/large/008i3skNgy1gwwff5ks5ij30u011zdiy.jpg
[Web Content Translate]: https://tva1.sinaimg.cn/large/008i3skNgy1gwspzltf13j316h0u0djv.jpg
[Web Content Path]: https://tva1.sinaimg.cn/large/008i3skNgy1gwwflgrucaj31ew0u0q5w.jpg
[Web Content Keywords]: https://tva1.sinaimg.cn/large/008i3skNgy1gwwfud3carj31ew0u0jum.jpg
[Article Content New Folder]: https://tva1.sinaimg.cn/large/008i3skNgy1gwwfxf42vaj31ew0u0q5i.jpg
[Article Content All Content]: https://tva1.sinaimg.cn/large/008i3skNgy1gwwfz9ome4j31ew0u0tcb.jpg
[Article Content MD]: https://tva1.sinaimg.cn/large/008i3skNgy1gwwg3bqfu8j31ge0u0jw7.jpg
[Article Content ItemName]: https://tva1.sinaimg.cn/large/008i3skNgy1gwwg98m1lxj32630u079p.jpg