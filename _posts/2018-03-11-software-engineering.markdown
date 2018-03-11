---
layout: post
title: System Analysis：Software Enginering 
date: 2018-03-11 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: workflow.jpg # Add image post (optional)
tags: [Software, Engineering] # add tag
---

### 1. Definition of Software Engineering

>From Wiki,
>
>**Software Engineering** is the application of engineering to the development of software in a systematic method.

软件工程是(1) 将系统化的、规范化的、可度量的方法应用于软件的开发、运行和维护，即将工程化方法应用于软件；(2) 在(1)中所述方法的研究。

### 2. Software crisis && COCOMO

> From Wiki,
>
> **Software crisis** is a term used in the early days of computing science for the difficulty of writing useful and efficient computer programs in the required time. The software crisis was due to the rapid increases in computer power and the complexity of the problems that could not be tackled. With the increase in the complexity of the software, many software problems arose because existing methods were insufficient.
>
> The **Constructive Cost Model** (**COCOMO**) is a procedural software cost estimation model developed by Barry W. Boehm. The model parameters are derived from fitting a regression formula using data from historical projects (61 projects for COCOMO 81 and 163 projects for COCOMO II).

- 《人月神话》对软件危机的描述，可归纳为以下内容：
  - 早期软件开发的特点
    - 软件规模相对较小
    - 程序设计是一门技艺
    - 缺少软件开发工具的支持
    - 缺乏软件开发管理的理论与方法
    - 缺乏有效的软件开发后的维护
  - 软件危机的表现形式
    - 软件开发成本日益增长
    - 软件开发进度难以控制
    - 用户对 “已完成” 系统不满意的现象经常发生
    - 软件产品的质量不可靠
    - 软件的可维护程度低
    - 软件开发生产率跟不上硬件的发展和人们需求的增长
- 《人月神话》对COCOMO的描述，可归纳为以下内容：
  - COCOMO 从本质上说是一种参数化的项目估算方法，参数建模是把项目的某些特征作为参数，通过建立一个数字模型预测项目成本

  - COCOMO模型发现团队质量目前是项目成功最大的决定因素，实际上是下一个次重要因素的4倍。

### 3. 软件生命周期

> From Wiki,
>
> In software engineering, a **software development process** is the process of dividing software development work into distinct phases to improve design, product management, and project management. It is also known as a **software development life cycle**. The methodology may include the pre-definition of specific deliverables and artifacts that are created and completed by a project team to develop or maintain an application.

- 软件生命周期的概念
  - 计算机软件有一个孕育、诞生、成长、成熟、衰亡的生存过程，即软件的生命周期 (也称软件开发生命周期SDLC 或软件开发过程)。软件生命周期被划分为若干阶段，每个阶段有明确的任务，从而使规模、结构和管理复杂的软件开发过程得到适当的控制和管理。
  - 软件生命周期包括可行性分析与开发计划、需求分析、设计 (概要设计和详细设计)、编码实现、测试、运行与维护等活动，将这些活动以适当的方式分配到不同的阶段去完成。
  - 软件生命周期的6个阶段
    - 可行性分析与计划阶段
    - 需求分析阶段
    - 设计阶段
    - 实现阶段
    - 测试阶段
    - 运行与维护阶段

### 4. 课程(系统分析)关注的KA 或 知识领域 

- Software requirements 软件需求


- Software design 软件设计


- Software construction 软件构造


- Software engineering models and methods 软件工程工具和方法

### 5. CMMI 五个级别

- Level 1 - Initial：无序，自发的生产模式。
- Level 2 - Manage：有基本的项目管理过程，制定必要规律的生产模式。
- Level 3 - Defined：软件管理及工程过程化、标准化的生产模式
- Level 4 - Quantitatively Managed：分析度量数据，控制生产流程，管理预测性能的生产模式
- Level 5 - Optimizing：量化反馈、持续更新、改善流程的生产模式

### 6. SWEBok 或 CMMI

SWEBok， 即软件工程知识体系指南，它描述了软件工程事件所需要的知识，为开发本科软件工程教育计划打下了基础。IEEE认为，这是软件工程向职业状态演化的关键。

它总共包括10个知识域：软件需求、软件设计、软件构造 、软件测试、软件维护、软件配置管理、软件工程管理、软件工程过程、软件工程工具和方法、软件质量。

它涉及到的学科有计算机工程、计算机科学、管理、数学、项目管理、质量管理、软件人类工程系、系统工程。

它有两个目标：(1) 促进世界范围内对软件工程的一致观点；(2)为软件工程确立边界

总而言之，软件工程知识体系指南体现了一个职业在核心知识体系上达成一致，是所有学科的关键里程碑！



### 7. PSP各项指标及技能要求

 ![psp2.1](C:\Users\67517\Desktop\linwh8.github.io\assets\img\psp2.1.png)

- 当一个软件工程师接到一个任务之后，首先要估计这个任务需要多少时间，需要用到哪些知识。
- 数据统计，主要就是每个条目时间的统计，有一点很重要，便是统计有效时间，而不是工作周期。比如我用了1天完成了需求的分析，但我的有效时间应当是24h减去与需求分析无关的时间。如果我要统计，我会按照流程，记录好每个流程项目的开始时间与结束时间，以统计该表格的数据。

