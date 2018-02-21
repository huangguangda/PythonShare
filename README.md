# PythonShare

PythonShare初学者书籍、视频、资料、社区推荐

Github 欢迎 Star、Fork，欢迎大家 Star、Pull Request 中提交推荐。

## 推荐阅读文章

 [《如何用好Google搜索引擎？》](http://www.zhihu.com/question/20161362) 

 [《十大高明的Google搜索技巧》](http://www.williamlong.info/archives/728.html)
 
 [《提问的智慧》](http://wiki.woodpecker.org.cn/moin/AskForHelp) 
 
 
1. 推荐[《Python基础教程》](http://book.douban.com/subject/4866934/)

2. 推荐 [《Python编程实践》] (http://book.douban.com/subject/7059900/)

3.  推荐 [《Python进阶》（Intermediate Python 中文版）](https://github.com/eastlakeside/interpy-zh)

4.  推荐  [Python快速教程](http://www.cnblogs.com/vamei/archive/2012/09/13/2682778.html) 

# 认识Python

>人生苦短，我用Python--Life is short,you need Python

Python的起源
为什么要用Python?
Python的特点
Python的优缺点

## Python的起源

Python的创始人为吉多范罗苏姆（Gudio van Rossum）

1.1989年的圣诞节期间，吉多范罗苏姆为了在阿姆斯特丹打发时间，决心开发一个新的解释程序，作为ABC语言的一种继承（感觉下什么叫牛人）

2.ABC是由吉多范罗苏姆参加设计的一种教学语言，就吉多范罗苏姆本人看来，ABC这种语言非常优美和强大，是专门为非专业程序员设计的。但是ABC语言并没有成功，究其原因，吉多范罗苏姆认为是非开放造成的。吉多范罗苏姆决心在Python中避免这一错误，并获取了非常好的效果

3.之所以选中Python（蟒蛇）作为程序的名字，是因为他是BBC电视剧的某马戏团的爱好者

4.1991年，第一个Python解释器诞生，它是用C语言实现的，并能够调用C语言的库文件

### 在Python社区，吉多范罗苏姆被称为“仁慈的独裁者”

# 为什么选择Python?
代码量少，同一样问题，用不同的语言解决，代码量差距还是很多的，一般情况下Python是Java的1/5,所以说 人生苦短，我用Python

## Python特点

### Python是完全面向对象的语言
>函数，模块，数字，字符串 都是对象，在Python中一切皆对象
>完全支持继承，重载，多重继承
>支持重在运算符，也支持泛型设计

1.Python 拥有一个强大的标准库， Python语言的核心只包含数字，字符串，列表，字典，文件等常见类型和函数，而由Python标准库提供了系统管理，网络通信，文本处理，数据库接口，图形系统，XML处理等额外的功能
2.Python社区提供了 大量的第三方模块， 使用 方式与标准库类似。它们的功能覆盖科学计算，人工智能，机器学习，Web开发，数据库接口，图形系统多个领域

#### 面向对象的思维方式
>面向对象是一种思维方式，也是一门程序设计技术
>要解决一个问题前，首先考虑 由谁 来做，怎么做 事情是谁的职责，最后把事情做好就行！

>对象 就是 谁
>要解决复杂的问题，就可以找 多个不同的对象，各司其职， 共同实现，最终完成需求

# Python发展历史
### 起源
1.Python的作者，Guido von Rossum,荷兰人。1982年，Guido从阿姆斯特丹大学获得了数学和计算机硕士学位，然而，尽管他算得上是一位数学家，但他更加享受计算机带来的乐趣，用他的话说，尽管拥有数学和计算机双料资质，他总趋向于做计算机相关的工作，并热衷于做任何和编程相关的活儿。

2.在那个时候，Guido接触并使用过诸如Pascal,C,Fortran等语言。这些语言的基本设计原则是让机器能更快运行。在80年代，虽然IBM和苹果已经掀起了个人电脑浪潮，但这些个人电脑的配置很低。比如早期的Macintosh，只有8MHz的CPU主频和128KB的RAM，一个大的数组就能占满内存。所有的编译器的核心是做优化，以便让程序能够运行。为了增进效率，语言也迫使程序员像计算机一样思考，以便能写出更符合机器口味的程序。在那个时代，程序员恨不得用手榨取计算机每一寸的能力。有人甚至认为C语言的指针是在浪费内存。至于动态类型，内存自动管理，面向对象。。。别想了，那会让你的电脑陷入瘫痪。

3.这种编程方式让Guido感到苦恼。Guido知道如何用C语言写出一个功能，但整个编写过程需要耗费大量的时间，即使他已经准确的知道了如何实现。他的另一个选择是shell,Bourne Shell作为UNX系统的解释器已经长期存在。UNIX的管理员们常常用shell去写一些简单的脚本，以进行一些系统维护的工作，比如定期备份，文件系统管理等等。shell可以像胶水一样，将UNIX下的许多功能连接在一起，许多C语言下上百行的程序，在shell下只用几行就可以完成。然而，shell的本质是调用命令。它并不是一个真正的语言。比如说，shell没有数值型的数据类型，加法运算都是复杂。总之，shell不能全面的调动计算机的功能。

4.Guido希望有一种语言，这种语言能够像C语言那样，能够全面调用计算机的功能接口，又可以像shell那样，可以轻松的编程。ABC语言让Gudio看到希望，ABC是由荷兰的数学和计算机研究所开发的。Guido在该研究所工作，并参与到ABC语言的开发。ABC语言以教学为目的。与当时的大部分语言不同，ABC语言的目标是“让用户感觉更好”。ABC语言希望让语言变得容易阅读，容易使用，容易记忆，容易学习，并以此来激发人们学习编程的兴趣。比如下面是一段来自Wikipedia的ABC程序，这个程序用于统计文本中出现的词的总数：

### 一门语言的诞生
>1991年，第一个Python编译器诞生。它是用C语言实现的，并能够调用C语言的库文件。从一出生，Python已经具有了：类，函数，异常处理，包含表和词典在内的核心数据类型，以及模块为基础的拓展系统。Python语法很多来自C，但又受到ABC语言的强烈影响。来自ABC语言的一些规定直到今天还富有争议，比如强制缩进。但这些语法规定让Python容易读。另一方面，Python聪明的选择服从一些惯例，特别是C语言的惯例，比如回归等号赋值。Guido认为，如果“常识”上确立的东西，没有必要过度纠结。Python从一开始就特别在意可拓展性。Python可以在多个层次上拓展。从高层上，你可以直接引入.py文件。在底层，你可以引用C语言的库。Python程序员可以快速的使用Python写.py文件作为拓展模块。但当性能是考虑的重要因素时，Python程序员可以深入底层，写C程序，编译为.so文件引入到Python中使用。Python就好像是使用钢构建房一样，先规定好大的框架。而程序员 可以在此框架下相当自由的拓展或更改。最初的Python完全由Guido本人开发。Python得到Guido同事的欢迎。他们迅速的反馈使用意见，并参与到Python的改进。Guido和一些同事构成Python的核心团队。他们将自己大部分的业余时间用于hack Python,随后，Python拓展到研究所之外。Python将许多机器层面上的细节隐藏，交给编译器处理，并凸显出逻辑层面的编程思考。Python程序员可以花更多的时间用于思考程序的逻辑，而不是具体的实现细节。这一特征吸引了广大的程序员。Python开始流行

## Python崇尚优美，清晰，简单，是一个优秀并广泛使用的语言。它是Google的第三大开发语言，Dropbox的基础语言，豆瓣的服务器语言。

## Python优缺点
1.优点：
    简单---Python是一种代表简单主义思想的语言。阅读一个良好的Python程序就感觉像是在读英语一样，尽管这个英语的要求非常严格！Python的这种伪代码本质是它最大的优点之一。它使你能够专注于解决问题而不是去搞明白语言本身。

   易学---就如同你即将看到的一样，Python极其容易上手。
     
   免费，开源---Python是FLOSS（自由/开放源码软件）之一。简单地说，你可以自由地发布这个软件的拷贝，阅读它的源代码，对它做改动，把它的一部分用于新的自由软件中。FLOSS是基于一个团体分享知识的概念。这是为什么Python如此优秀的原因之一---它是由一群希望看到一个更加优秀的Python的人创造并经常改进着的。

   高层语言---当你用Python语言编程程序的时候，你无需考虑如何管理你的程序使用的内存一类的底层细节。

   可移植性---由于它的开源本质，Python已经被移植在许多平台上（经过改动使它能够工作在不同平台上）。如果你小心地避免使用依赖于系统的特性，那么你的所有Python程序无需要修改就可以在下述任何平台上面运行。

   解释性---这一点需要一些解释。

   面向对象---Python即支持面向过程的编程也支持面向对象的编程。在“面向过程”的语言中，程序是由过程或仅仅是可重用代码的函数构建起来的。在“面向对象”的语言中，程序是由数据和功能组合而成的对象构建起来的。与其他主要的语言如C++和Java相比，Python以一种强大又简单的方式实现面向对象编程。
 
   可扩展性---如果你需要你的一段关键字代码运行得更快或者希望某些算法不公开，你可以把你的部分程序用C或C++编写，然后在你的Python程序中使用它们。

   丰富的库----Python标准库确实很庞大。

   规范的代码---Python采用强制缩进的方式使用代码具有极佳的可读性。

2.缺点：
  运行速度，有速度要求的话，用C++改写关键部分吧。
  国内市场较小
  中文资料少
  架构选择太多

## 如果喜欢，那就点个赞吧！❤️
