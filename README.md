基本概念
=
 
`iOS SDK`: iOS Software Development Kit(SDK、软件开发包)包含了出现iOS设备主屏幕上的native apps所需要的开发、安装、运行和测试的工具和接口。通过使用iOS系统框架和Objective-C语言直接运行在iOS上来构建native app。

`iOS Frameworks`: Apple将它的系统接口分发在不同的框架（frameworks）中，细分功能接口。想要使用哪一个框架，才把它添加到Xcode工程中。

建议：

作为一个菜鸟，建议我自己

* 端正你自己在iOS平台的态度
* 学习iOS软件技术，什么时候、为什么你会想要使用这个技术
* 把握学习平台的发展机会
* 学习如何把iOS移植到其他平台
* 找到你感兴趣的关键技术文档 

应用程序开发：  

Native app 本地应用，原生代码开发，开发与维护成本高，用户体验优秀，跨平台困难。 

Hybrid app 混合开发应用，介于Native app 和 Web app之间的混合开发模式，继承了Native的用户体验，和Web app的跨平台、开发和维护成本低的特点。 

Web app 网页应用，使用Web语言进行开发，开发和维护成本低，可跨平台，但用户体验差。

在iOS开发中，分了很多层级，高级框架并不会直接去底层硬件直接交互，底层框架才会去与硬件交互。高级框架只是对底层框架的一种封装，使得硬件功能实现更加容易代码化，比如：线程、套接字等复杂逻辑。高级框架减少了代码量并做了许多封装，所以，尽可能的使用高级框架。如果高级框架不能实现底层框架功能的时候，就需要使用底层框架和技术。  上面是针对iOS开发做出的框架分级，苹果所封装的高级接口称为框架frameworks。The iOS Developer Library 是一个重要的资源库，在开发过程中，可以查阅API、编程指南、技术笔记、示例代码、和一些其他的工具推荐介绍等。可以通过网页来访问这个图书室，也可以通过Xcode进去。
