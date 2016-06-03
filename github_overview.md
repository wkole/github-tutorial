<!--
author: 东方鹗
date: 2016-06-02
title: github概述
tags: git, github, 你应该会玩github
category: git
status: publish
summary: **“寻找合伙人，进行社会化的编程和培训”**，这是作者的理想。但是光有美好的愿望是不行的，仰望星空的前提是脚踏实地，如何才能进行社会化编程培训呢？这就需要从基本的工具开始学习了，而Github恰好能够满足我们的愿望，掌握它，驾驭它，从使用Github开始。
-->


> **“寻找合伙人，进行社会化的编程和培训”**，这是作者的理想。但是光有美好的愿望是不行的，仰望星空的前提是脚踏实地，如何才能进行社会化编程培训呢？这就需要从基本的工具开始学习了，而Github恰好能够满足我们的愿望，掌握它，驾驭它，从使用Github开始。

## 什么是 Git

Git 属于分散型版本管理系统，是为版本管理而设计的软件，其仓库管理功能是 Github 的核心。因此，先了解一下 Git 的相关知识是有必要的。

### 什么是版本管理

版本管理就是管理更新的历史记录。它为我们提供了一些在软件开发工程中必不可少的功能，例如记录一款软件添加或者更改源代码的过程，回滚到特定阶段，恢复误删除的文件等。
在 Git 出现以前， 人们普遍采用 Subversion 等集中型版本管理系统，而现在 Git 已经成为了主流。由于 Github 的普及，相比世界上使用 Git 的人会越来越多。

## 什么是 Github

Github 是为开发者提供 Git 仓库的托管服务。这是一个让开发者与朋友、同事、同学及陌生人共享代码的完美场所
Github 除提供 Git 仓库的托管服务外，还为开发者或团队提供了一系列功能，帮助其提高效率、高品质地进行代码编写。
Github 的创始人之一 Chris Wanstrath 曾有个愿望，那就是能有一个 Git 仓库的托管服务让自己与朋友能够轻松分享代码，而这便成为了 Github 诞生的契机。不过，他也曾表示： Git 仓库的托管服务是 Github  项目的目标之一，这只是漫长路程的一个点而已。

## Github 提供的主要功能

### Git 仓库

一般情况下，我们可以免费建立任意个 Git 仓库。但是如果需要建立只对特定人物或只对自己公开的私有仓库，那么就需要收费了。当然这是一种“免费理论”的商业模式，我们需要充分理解。其实你不理解也可以，用免费的产品已经可以满足我们的需求了。

### Organization （组织）

通常情况下，个人使用时只要使用个人账户就足够了，但是如果是公司，建议使用 Organization 账户。它的优点在于可以统一管理账户和权限，还能统一支付一些费用。
**如果只使用公开仓库，是可以免费创建 Organization 账户**。因此，如果是以交流群或 IT 小团体的形式进行软件开发时不妨试一试。

### Issue （讨论区）

Issue功能，是将一个人物或问题分配给一个Issue进行追踪和管理的功能。可以像 BUG 管理系统或 TiDD （ Ticket-driven Development ）的 Ticket 一样使用。在 Github 上，每当进行我们即将讲解的 Pull Request ， 都会同时创建一个 Issue。
每一个功能更改或修正都对应一个 Issue，讨论或者修改都以这个 Issue 为中心进行。只要查看 Issue，就能知道和这个更改相关的一切信息，并以此进行管理。
在 Git 的提交信息中写上 Issue 的 ID （例如“#8”）， Github 就会自动生成从 Issue 到对应的链接。另外，只要按照特定的格式描述提交信息，还可以关闭 Issue 。

### Wiki

通过 Wiki 功能，任何人都能随时对一篇文章进行更改并保存，因此可以多人共同完成一篇文章。该功能常用在开发文档或手册的编写中。
Wiki 页也是作为 Git 仓库进行管理的，改版的历史记录会被切实保存下来，使用者可以放心改写。由于其支持克隆至本地进行编辑，所以程序员使用时可以不必开启浏览器。

### Pull Request

开发者向 Github 的仓库推送更改或功能添加后，可以通过 Pull Request 功能向别人的仓库提出申请，请求对方合并。
Pull Request 送出后，目标仓库的管理者等人将能够查看 Pull Request 的内容及其中包含的代码更改。
同时， Github 还提供了对 Pull Request 和源代码前后差别进行讨论的功能。通过此功能，可以以行为为单位对源代码添加评论，让程序员之间高效地交流。
