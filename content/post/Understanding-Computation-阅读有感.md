---
title: Understanding Computation 阅读有感
date: 2018-01-09T14:00:11+08:00
lastmod: 2018-01-09T14:00:11+08:00
author: g1eny0ung
cover: /img/Understanding-Computation-阅读有感.jpg
categories: ["读书"]
tags: ["技术", "感悟", "ruby"]
---

Understanding Computation: From Simple Machines to Impossible Programs

<!--more-->

这本书的中文书名是这个：[《计算的本质:深入剖析程序和计算机》](https://www.amazon.cn/dp/B00PG0MM3C/ref=sr_1_1?ie=UTF8&qid=1515477934&sr=8-1&keywords=%E8%AE%A1%E7%AE%97%E7%9A%84%E6%9C%AC%E8%B4%A8)

大部分代码我上传到了[https://github.com/g1eny0ung/Understanding-Computation](https://github.com/g1eny0ung/Understanding-Computation)

但是我觉得还是依据原书名翻译比较好，现书名有着或多或少的误导，一是前后呼应不好，**计算的本质**对不上**深入剖析程序和计算机**，说的太笼统了。
二是最后的计算机很容易被误导，这本书总体是循序渐进地从简单语言，状态机慢慢步入到图灵机，在最后阐释了通用性，不可能问题等等。把**“机”**字去掉，
我觉得就可以接受了。

`满分5星，5星推荐`书的整体还是比较通俗易懂的，不深不浅，对计算理论可以算是入个门吧，读完之后还是很有帮助的。作者的行文总体十分流畅，但是也是有得地方感觉没有能够
更加深入的探讨，只是浅浅的带过，可能是涉及的理论相当复杂，不是很符合本书的意图吧。

对于本书的总结，在本书后记中也是说的很好了，就算没有读过此书，也能通过文字产生或多或少的感想。我是第二遍读这本书了，第一遍在闲杂时间随便翻了翻，第二遍精读了一下，
收获颇丰。

下面是书的后记，我稍微删减了一下：

> 
* 任何人都可以设计和实现一种编程语言。语法和语义的基本思想是简单的。
* 每一个计算机程序都是一个数学对象。按句法来说，一个程序只是一个大数；语义上来说，它可能代表一个数学函数，或者一个能被形式化规约规则操纵的分层结构。这意味 着数学上的许多技术和成果，如 Kleene 规约理论或者 Gödel 不完备定理，都能等价地应用到程序上。
* 计算，最初被描述为只是“一台计算机做的事”，已经被证明是某种自然力量。很容易把计算想象为一个复杂的人类发明，它只能由对许多复杂部分进行特殊设计的系统来执行，但在系统中还可以看到支持它没那么复杂。因此，计算不是一个枯燥的只是发生在微处理器中的人工过程，而是一个在许多不同地点以不同方式发生的普遍现象。
* 计算不是全有或全无的。不同的机器拥有不同的计算能力，这给了我们用途上的连续性: DFA 和 NFA 有有限的能力，DPDA 更强大，NPDA 还更强大，而图灵机是我们知道的最强大的机器。
* 抽象的编码和级别对于利用计算能力必不可少。计算机是维护抽象宝塔的机器，从非常 低层次的半导体物理学开始，上升到层次高得多的多点触控图形用户界面。为了让计算有用，我们需要能把现实世界中复杂的思想编码成机器能处理的更简单的形式，然后再把结果解码回有意义的高层表示。
* 计算能做的事情是有限制的。我们不知道如何构建比图灵机能力更强的机器，但确实存在图灵机无法解决的问题，而这些问题包括发现我们所写程序的信息。可以利用模糊的 或者不完整的答案处理这些限制，以便质疑我们程序的行为。

其实学习这种理论并不会立即看到效果，就像书中说的那样：

> **这些思想可能不会立即改变你工作的方式，但我希望它们已经满足了你的某种好奇心，并且能帮助你享受在宇宙中实现计算时所度过的时光。**
