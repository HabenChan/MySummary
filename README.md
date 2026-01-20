# Kenneth Lee的工作和生活总结

本工程原本是知乎上的三个专栏，为了更好维护和备份，迁移为一个git工程，用
python3-sphinx管理。

sphinx基于reStructured Markdown语言(rst)写成，和markdown格式一样，它也是文本文
件，所以可以直接用文本编辑器打开阅读。在git托管网站上，甚至可以解释其中部分的格
式。但如果文档之间有相互引用，或者文档中使用了数学公式，用这种方法阅读都是看不
到的。我为此申请了readthedocs的自动生成服务，读者可以直接在这里阅读生成后的版本：
[MySummary](https://mysummary.readthedocs.io/zh/latest/index.html)。

但如果要得到完整的格式支持，需要通过：

```bash
make html
make epub
```

等方式编译成html或者epub等格式。

项目原来包含一个道德经翻译的子目录。2020底，我开始这个翻译转化为一本书，项目在
这里：

* [道德经直译@github](https://github.com/Kenneth-Lee-2012/daodejing_translation)

所以，本项目的“道德经直译”目录中翻译的部分不再进行内容修正，但我仍会使用该目录
补充我关于《道德经》的一些建模心得。

这个项目最初有gitee和github两个托管服务，但gitee后来无条件把项目设置成私有的了。
所以，这个项目现在只有github一个git服务：

* git@github.com:Kenneth-Lee/MySummary.git

要获得最新的源代码，请跟踪这个位置。
