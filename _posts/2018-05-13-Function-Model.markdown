---
layout: post
title: Function-Modeling
date: 2018-05-13 00:00:00 +0300
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



#### 1）使用 UML State Model

- 建模对象： 参考 Asg_RH 文档， 对 Reservation/Order 对象建模。

- 建模要求： 参考练习不能提供足够信息帮助你对订单对象建模，请参考现在 定旅馆 的旅游网站，尽可能分析围绕订单发生的各种情况，直到订单通过销售事件（柜台销售）结束订单。

- ![lesson8_state]({{site.baseurl}}/assets/img/lesson8_state_model.png)

  ​


#### 2）研究淘宝退货流程活动图，对退货业务对象状态建模

- ![lesson8_state]({{site.baseurl}}/assets/img/lesson8_state_model_taobao.png)




### (1) 系统顺序图

![lesson9_system_seq]({{site.baseurl}}/assets/img/lesson9_system_seq.png)

### (2) 建模

- 用例图

  ![lesson9_meituan_usecase]({{site.baseurl}}/assets/img/lesson9_meituan_usecase.png)


- 活动图

  ![lesson9_meituan_activity]({{site.baseurl}}/assets/img/lesson9_meituan_activity.png)

- 领域模型

  ![lesson9_meituan_domain_model]({{site.baseurl}}/assets/img/lesson9_meituan_domain_model.png)

- 状态图

  ![lesson9_meituan_state_model]({{site.baseurl}}/assets/img/lesson9_meituan_state_model.png)

- 系统顺序图

  ![lesson9_meituan_system_seq]({{site.baseurl}}/assets/img/lesson9_meituan_system_seq.png)

