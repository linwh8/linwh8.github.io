---
layout: post
title: Architecture
date: 2018-06-01 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: workflow.jpg # Add image post (optional)
tags: [Model] # add tag
---

> 
>
> **“The secret of change is to focus all of your energy not on fighting the old, but on building the new.”**
>
> – Socrates, Greek Philosopher
>
> 



### 软件架构与框架之间的区别与联系

- 软件架构与框架的定义

  - 软件架构就是把系统分解为一些部件，描述这些部件的职责及它们之间的协作行为。
  - 框架是特定语言和技术的架构应用解决方案。

- 软件架构与框架的区别

  - 软件架构其实就是一个系统的草图。
  - 软件框架就是领域分析结果的软件化，是领域内最终应用的模板。
  - 换句话说就是，软件架构不是软件，而框架是软件
  - 补充：
    - 框架是具体语言和技术相关的
    - 框架是一种或多种架构的组合的实现
    - 框架是集成了你的代码和多种第三方解决方案的工具，让你聚焦 业务逻辑代码 而 不是技术实现

- 软件架构与框架的联系

  - 软件架构用于指导软件框架的设计。

  - 软件架构决定了软件系统如何划分，在一定程度上描述了被划分的各个部分之间的静态、动态关系。

  -  软件架构的决策体现在软件系统的框架中。

    ​

### 以你的项目为案例，绘制三层架构模型图，细致到分区；结合你的程序结构，从程序员角度说明三层架构给开发者带来的便利

![lesson9_system_seq]({{site.baseurl}}/assets/img/lesson13_structure.png)

- 三层架构使得开发人员可以只关注整个结构中的其中某一层，比如对数据库较为熟悉的组员可以将精力放在持久化层；
- 三层架构使得项目结构更清楚，分工更明确，有利于后期的维护和升级。

### 研究VUE与Flux状态管理异同

- 相同点：VUE与Flux状态管理都是基于FLUX架构，该架构有效解决大型业务中复杂数据流的管理问题


- 不同点：VUE与Flux对数据流的顺序不同。
  - 对于Flux，数据流的顺序为：View发起Action->Action传递到Dispatcher->Dispatcher将通知Store->Store的状态改变通知View进行改变
  - 对于Vue，数据流的顺序为：View调用store.commit提交对应的请求到Store中对应的mutation函数->store改变(vue检测到数据变化自动渲染)

