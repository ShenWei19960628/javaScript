
# 第 1 章 JavaScript 概述

### 1.什么是 JavaScript
### 2.JavaScript 特点
### [3.JavaScript 历史
### 4.JavaScript 核心


JavaScript 诞生于 1995 年。它当时的目的是为了验证表单输入的验证。因为在 JavaScript 问世之前，表单的验证都是通过服务器端验证的。而当时都是电话拨号上网的年代，服务器验证数据是一件非常痛苦的事情。

经过许多年的发展，JavaScript 从一个简单的输入验证成为一门强大的编程语言。所以，学会使用它是非常简单的，而真正掌握它则需要很漫长的时间。那么本套视频就带领大家进入 JavaScript 课堂，去学习和理解它。

### 一．什么是 JavaScript


JavaScript 是一种具有面向对象能力的、解释型的程序设计语言。更具体一点，它是基于对象和事件驱动并具有相对安全性的客户端脚本语言。因为他不需要在一个语言环境下运行，而只需要支持它的浏览器即可。它的主要目的是，验证发往服务器端的数据、增加 Web 互动、加强用户体验度等。

### 二．JavaScript 特点

##### 松散性

JavaScript 语言核心与 C、C++、Java 相似，比如条件判断、循环、运算符等。但，它却是一种松散类型的语言，也就是说，它的变量不必具有一个明确的类型。

##### 对象属性

JavaScript 中的对象把属性名映射为任意的属性值。它的这种方式很像哈希表或关联数组，而不像 C 中的结构体或者 C++、Java 中的对象。

##### 继承机制

JavaScript 中的面向对象继承机制是基于原型的，这和另外一种不太为人所知的 Self 语言很像，而和 C++以及 Java 中的继承大不相同。

### 三．JavaScript 历史

##### 引子

大概在 1992 年，有一家公司 Nombas 开发一种叫做 C--(C-minus-minus,简称 Cmm)的嵌入式脚本语言。后应觉得名字比较晦气，最终改名为 ScripEase。而这种可以嵌入网页中的脚本的理念将成为因特网的一块重要基石。

##### 诞生

1995 年，当时工作在 Netscape(网景)公司的布兰登(Brendan Eich)为解决类似于“向服务器提交数据之前验证”的问题。在 Netscape Navigator 2.0 与 Sun 公司联手开发一个称之为 LiveScript 的脚本语言。为了营销便利，之后更名为 JavaScript(目的是在 Java 这课大树下好乘凉)。

##### 邪恶的后来者

因为 JavaScript 1.0 如此成功，所以微软也决定进军浏览器，发布了 IE 3.0 并搭载了一个 JavaScript 的克隆版，叫做 JScript（这样命名是为了避免与 Netscape 潜在的许可纠纷），并且也提供了自己的 VBScript。

##### 标准的重要

在微软进入后，有 3 种不同的 JavaScript 版本同时存在：Netscape Navigator 3.0 中的JavaScript、IE 中的 JScript 以及 CEnvi 中的 ScriptEase。与 C 和其他编程语言不同的是，

JavaScript 并没有一个标准来统一其语法或特性，而这 3 种不同的版本恰恰突出了这个问题。随着业界担心的增加，这个语言标准化显然已经势在必行。

##### ECMA

1997 年，JavaScript 1.1 作为一个草案提交给欧洲计算机制造商协会（ECMA）。第 39 技术委员会（TC39）被委派来“标准化一个通用、跨平台、中立于厂商的脚本语言的语法和语义”（http://www.ecma-international.org/memento/TC39.htm）。由来自 Netscape、Sun、微软、Borland 和其他一些对脚本编程感兴趣的公司的程序员组成的 TC39 锤炼出了

##### ECMA-262，该标准定义了叫做 ECMAScript 的全新脚本语言。

##### 灵敏的微软、迟钝的网景

虽然网景开发了 JavaScript 并首先提交给 ECMA 标准化，但因计划改写整个浏览器引擎的缘故，网景晚了整整一年才推出“完全遵循 ECMA 规范”的 JavaScript1.3。而微软早在一年前就推出了“完全遵循 ECMA 规范”的 IE4.0。这导致一个直接恶果：JScript 成为 JavaScript 语言的事实标准。

##### 标准的发展

在接下来的几年里，国际标准化组织及国际电工委员会（ISO/IEC）也采纳 ECMAScript 作为标准（ISO/IEC-16262）。从此，Web 浏览器就开始努力（虽然有着不同程度的成功和失败）将 ECMAScript 作为 JavaScript 实现的基础。

##### 山寨打败原创

JScript 成为 JavaScript 语言的事实标准，加上 Windows 绑定着 IE 浏览器，几乎占据全部市场份额，因此，1999 年之后，所有的网页都是基于 JScript 来开发的。而 JavaScript1.x


##### 变成可怜的兼容者。

##### 网景的没落与火狐的崛起

网景在微软强大的攻势下，1998 年全面溃败。但，星星之火可以燎原。同年成立 Mozilla 项目中 Firefox(火狐浏览器)在支持 JavaScript 方面无可比拟，在后来的时间里一步步蚕食 IE 的市场，成为全球第二大浏览器。

##### 谷歌的野心

Google Chrome，又称 Google 浏览器，是一个由 Google（谷歌）公司开发的开放原始码网页浏览器。他以简洁的页面，极速的浏览，一举成为全球第三大浏览器。随着移动互联网的普及，嵌有 Android 系统的平板电脑和智能手机，在浏览器这块将大有作为。

##### 苹果的战略

Safari 浏览器是苹果公司各种产品的默认浏览器，在苹果的一体机(iMac)、笔记本(Mac)、MP4(ipod)、iphone(智能手机)、ipad(平板电脑)，并且在 windows 和 Linux 平台都有相应版本。目前市场份额全球第四，但随着苹果的产品不断的深入人心，具有称霸之势。

##### 幸存者

Opera 的全球市场份额第五，2%左右。它的背后没有财力雄厚的大公司，但它从“浏览器大战”存活下来的，有着非常大的潜力。


### 四．JavaScript 核心

虽然 JavaScript 和 ECMAScript 通常被人们用来表达相同的含义，但 JavaScript 的含义却比ECMA-262 中规定的要多得多。一个完整的JavaScript 应该由下列三个不同的部分组成。

##### 1.核心(ECMAScript)

##### 2.文档对象模型(DOM)

##### 3.浏览器对象模型(BOM)

##### ECMAScript 介绍

由 ECMAScript-262 定义的 ECMAScript 与 Web 浏览器没有依赖关系。ECMAScript 定

义的只是这门语言的基础，而在此基础之上可以构建更完善的脚本语言。我们常见的 Web 浏览器只是 ECMAScript 实现可能的宿主环境之一。

既然他不依赖于 Web 浏览器，那么他还在哪些环境中寄宿呢？比如：ActionScript、 ScriptEase 等。而他的组成部分有：语法、类型、语句、关键字、保留字、操作符、对象等。

##### ECMAScript 版本

ECMAScript 目前有四个版本，1、2、3、4、5 版本，这里不再进行详细探讨。有兴趣的同学，可以搜索查阅。

Web 浏览器对 ECMAScript 的支持

到了 2008 年，五大主流浏览器(IE、Firefox、Safari、Chrome、Opera)全部做到了与

ECMA-262 兼容。其中，只有 Firefox 力求做到与该标准的第 4 版兼容。以下是支持表。


##### 浏 览 器	ECMAScript 兼容性
	
Netscape Navigator 2	----
	
Netscape Navigator 3	----
	
Netscape Navigator 4 -- 4.05	----
	
Netscape Navigator 4.06 -- 4.79	第 1 版
	
Netscape 6+ (Mozilla 0.6.0+)	第 3 版
	
Internet Explorer 3	----
	
Internet Explorer 4	----
	
Internet Explorer 5	第 1 版
	
Internet Explorer 5.5 -- 7	第 3 版
	
Internet Explorer 8	第 3.1 版(不完全兼容)
	
Internet Explorer 9	第 5 版
	
Opera 6 - 7.1	第 2 版
	
Opera 7.2+	第 3 版
	
Opera 11+	第 5 版
	
Safari 3+	第 3 版
	
Firefox 1--2	第 3 版
	
Firefox 3/4/5/6/7/8/9	第 3/5 版
	

##### 文档对象模型(DOM)

文档对象模型(DOM，Document Object Model)是针对 XML 但经过扩展用于 HTML 的应用程序编程接口(API，Application Programming Interface)。
DOM 有三个级别，每个级别都会新增
