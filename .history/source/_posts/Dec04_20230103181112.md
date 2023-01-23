---
title: Dec04
date: 2022-12-04 23:24:33
toc: true
tags: 
categories: 
 - 每日工作总结
password: C91920010812
message: 靓仔美女们输个密码呗
cover: img/清华大学.png
description: 每天的学习点滴～
---
# 技术文件——20221204工作日志			拟制：解辰锋

# 本文中的所有信息均为清华大学内部消息，不得向外传播

# 1.学习记录

## CAN

### CAN物理层

#### 收发器（*CAN Tranceivr*）——逻辑电平和物理电平之间的转换

CAN逻辑信号和物理信号之间的转换采用差分电平的方式

#### CAN编码方式

<img src="Dec04/image-20221206001211669.png" alt="image-20221206001211669" style="zoom:50%;" />

#### CAN采样点

<img src="Dec04/image-20221204150512241.png" alt="image-20221204150512241" style="zoom:50%;" />

<img src="Dec04/image-20221204150623792.png" alt="image-20221204150623792" style="zoom:50%;" />

#### CAN终端电阻与线缆

<img src="Dec04/image-20221204150852678.png" alt="image-20221204150852678" style="zoom:50%;" />

<img src="Dec04/image-20221204151040069.png" alt="image-20221204151040069" style="zoom:50%;" />

<img src="Dec04/image-20221204151110186.png" alt="image-20221204151110186" style="zoom:50%;" />

## 论文

### 阅读文献

CAN网络层次化动态调度策略设计与实现(文献DOI 10.20009/j.cnki.21-1106/TP.2021-0327)

### 学习内容

#### 什么是有限状态机？有限状态机与stateflow有什么关系？为什么可以用有限状态机建模CAN网络？

+ 有限状态机是一种用来进行对象行为建模的工具，其作用主要是描述对象在它的生命周期内所经历的状态序列，以及如何响应来自外界的各种事件。在计算机科学中，有限状态机被广泛用于建模应用行为、硬件电路系统设计、软件工程，编译器、网络协议、和计算与语言的研究。比如下图非常有名的TCP协议状态机。

<img src="Dec04/image-20221204120438678.png" alt="image-20221204120438678" style="zoom:50%;" />

+ 可以类比数字电路时序电路部分学过的状态转移图

## 参考资料

### 视频资源

> [CAN总线基础之物理层篇_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1gD4y1U7bJ?p=1&vd_source=2d5ec0a230549ed2b672ea4be8a2cc58)

### 博客资源

> [深入浅出理解有限状态机 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/46347732)

# 2.问题

本来准备学一下stateflow的，但是在具体读了一下文献之后感觉重点不是理解stateflow的使用，而是理解CAN的state、transition与condition,我对于CAN的物理层、数据链路层理解还不够透彻，这部分还需要我再仔细消化一下。

# 3.下一步计划

深究CAN物理层与数据链路层的实现细节

# 本文中的所有信息均为清华大学内部消息，不得向外传播
