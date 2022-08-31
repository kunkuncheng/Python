## Python的定义

Python 是一种简单易学并且结合了 解释性、编译性、互动性和面向对象的脚本语言。 Python提供了高级数据结构，它的语法和动态类型以及解释性使它成为广大开发者的首选编程语言。

- Python 是解释型语言： 开发过程中没有了编译这个环节。类似于PHP和Perl语言。
- Python 是交互式语言： 可以在一个 Python 提示符 >>> 后直接执行代码。
- Python 是面向对象语言: Python支持面向对象的风格或代码封装在对象的编程技术。

> Python发展历史：[ https://baike.baidu.com/item/Python/407313?fr=aladdin](https://baike.baidu.com/item/Python/407313?fr=aladdin)

## Python的版本

目前python发布的版本过程主要包括如下：

| 发布版本     | 年份      | GPL 兼容 |
| ------------ | --------- | -------- |
| 0.9.0 至 1.2 | 1991-1995 | 是       |
| 1.3 至 1.5.2 | 1995-1999 | 是       |
| 1.6          | 2000      | 否       |
| 2.0          | 2000      | 否       |
| 1.6.1        | 2001      | 否       |
| 2.1          | 2001      | 否       |
| 2.0.1        | 2001      | 是       |
| 2.1.1        | 2001      | 是       |
| 2.1.2        | 2002      | 是       |
| 2.1.3        | 2002      | 是       |
| 2.2 及更高   | 2001至今  | 是       |
| ...          | ...       | ...      |
| 3.10.4       | 2022      | 是       |

Python2和Python3两个版本各有优缺，Python2由于是比较早的版本，因此资料相对多;而Python3是以后的发展趋势，一般企业久而久之都会转成使用P3。根据自己的实际情况选择，虽然是两个版本，但差异也不大，通常一个学会以后另一个版本花些时间就可以。

> 本次学习使用的版本：3.7.2

## Python的应用

Python的应用主要有以下领域：

- Linux/UNIX运维：提供API（Application Programming Interface应用程序编程接口），能方便进行系统维护和管理。
- GUI程序开发（PyQt、Kivy等）
- Web程序开发（Django、Flask等框架）：支持最新的XML技术。
- 移动App开发（PyQt、Kivy等）：Python的PyOpenGL模块封装了“OpenGL应用程序编程接口”，能进行二维和三维图像处理。PyGame模块可用于编写游戏软件。
- 网络爬虫（为搜索引擎、深度学习等领域提供数据源）
- 网络编程（基于Socket等协议）：提供丰富的模块支持sockets编程，能方便快速地开发分布式应用程序。很多大规模软件开发计划例如Zope，Mnet 及BitTorrent. Google都在广泛地使用它。
- 图形处理：有PIL、Tkinter等图形库支持，能方便进行图形处理。
- 文本处理：python提供的re模块能支持正则表达式，还提供SGML，XML分析模块，许多程序员利用python进行XML程序的开发。
- 数据库编程：可通过遵循Python DB-API（数据库应用程序编程接口）规范的模块与Microsoft SQL Server，Oracle，Sybase，DB2，Mysql、SQLite等数据库通信。python自带有一个Gadfly模块，提供了一个完整的SQL环境。
- 数据科学：NumPy扩展提供大量与许多标准数学库的接口。机器学习（scikit-learn、TensorFlow框架）、数据统计分析和可视化（Matplotlib、seaborn框架）。

## Python的特点

- 简单易读易学：Python是非常简单的语言，并且具有清晰的风格和强制缩进，Python具有简单的语法，极其容易入门。
- 免费、开源：Python是自由/开放源码的软件。可以自行对其源代码进行修改使用。
- 可移植性：Python可以被移植在许多平台上，常用的平台包括Linux、Windows、VxWorks、PlayStation、Windows CE、PocketPC等。
- 解释性： Python解释器把源代码转换成字节码，然后再把它翻译成计算机使用的机器语言并运行，即Python代码在运行之前不需要编译。
- 面向对象：Python支持面向对象的编程。程序通过组合（composition）与继承（inheritance）的方式定义类（class）。
- 可扩展性：如果需要一段关键代码运行得更快或者希望某些算法不公开，那么可以将部分程序用C或C++进行编写，然后在Python程序中调用。
- 可嵌入性：可以把Python嵌入C/C++程序，从而向程序用户提供脚本功能。
- 交互式命令行：python可以单步直译运行，可以在一个 Python 提示符 >>> 后直接执行代码。
- 丰富的标准库：Python标准库包括字符串处理（字典、数组切片、正则表达式re）、文档生成、多线程、串行化、数据库、HTML/XML解析（BeautifulSoup，Expat）、单元测试（PyUnit）、代码版本控制（PySVN）、WAV文件、网络控制（urllib2）、密码系统、GUI（图形用户界面，PyQt）、图形模块（Tkinter、PyTCL、WxPython）等。除了标准库以外，还有许多其他高质量的库，如wxPython、Twisted和Python图像库等等。
- 规范性：采用强制缩进的方式使得代码具有较好可读性，减少了视觉上的错乱。
- 胶水语言：python经常用作将不同语言编写的程序“粘”在一起的胶水语言。Boost.Python使得Python和C++的类库可互相调用（.pyc）；Jpython是用Java实现的Python，可以同时使用两者的类库；Ironpython是Python在.NET平台上的版本。

## Python优点

- 易于学习，非常适合初学者，也特别适合专家使用
- 可伸缩程度高，适于大型项目或小型的一次性程序(称为脚本)
- 可移植，跨平台
- 可嵌入(使 ArcGIS 可脚本化)
- 稳定成熟
- 用户社区规模大

