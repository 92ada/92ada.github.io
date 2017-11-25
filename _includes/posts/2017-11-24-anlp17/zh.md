> red n. the color of blood or a ruby.<br>
> blood n. the red liquid that circulates in the heart, arteries and veins of animals.<br><br>
> 这是 American Heritage Dictionary 中对于 red 和 blood 的定义。像这样的循环定义，出现在词典各种各样的角落里。人可以意会出这些词的含义，但如果我们需要为计算机造一个词典库来做机器翻译，这样的递归可不是什么好主意。

WordNet 也是一个词典，但它是为机器翻译而生的词典。它根据词条的意义将单词分组，每一个具有相同意义的字条组称为一个 synset（同义词集合）。WordNet 为每一个 synset 提供了简短，概要的定义，并记录不同 synset 之间的语义关系。

### 同义词、反义词、下义词、Meronymy、Holonym

同义词和反义词看似好理解，但其实需要仔细想一想。严格意义上的同义词，是词义与词义的关系，而不是词与词的。当我们说“巨”和“大”是同义词的时候，并不代表我们可以回家把“大姐”叫成“巨姐”。“巨”和“大”只在某些情景的词义中可替换，所以说相同的是他们的部分词义，而不是他们本身。

反义词呢，乍看之下是指完全相反的一对词，但其实，虽然反义词在一个方面完全不同（规模／方向／情感等），但是在其他方面非常相似，几乎分享了所有其他方面的意义。黑和白都是颜色，远和近都是距离，爱和恨都是情感。

“下义词”“上位语”表示抽象-具体关系。芒果是水果的下义词，水果是芒果的上位语。

Meronymy 和 Holonym 描述整体-部分关系。轮子是车的 Meronymy，车是轮子的 Holonym。

### WordNet

> {\\(chump^1,\\; fool^2,\\; gull^1,\\; mark^9,\\; patsy^1,\\; all\\;guy^1,\\; sucker^1,\\; soft\\;touch^1,\\; mug^2\\)}

这是 WordNet 中同义词集合的一个例子，可以猜到它的含义是“容易受骗的人”。

前面描述的各种词义关系都存储在 WordNet 之中：

![](/img/in-post/post-wordnet-example.png)

如果你从任意一个词开始向上溯源，你最终会到达 WordNet 的 root（也叫 *unique beginner*），那里只有11个抽象的基本概念。

### 应用

WordNet 的一个应用是整合机器学习进行 Word Sense Disambiguation (词义消歧)。


---

### 总结

这一章主要都是介绍概念，看着晦涩但没有什么难点。<br>
以上，*Chapter 17, Speech and Language Processing, Daniel Jurafsky & James H. Martin.*
