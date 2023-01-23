---
title: Dec06
toc: true
categories:
  - 每日工作总结
date: 2022-12-06 14:54:22
tags:
password: C91920010812
message: 靓仔美女们输个密码呗
cover: img/清华大学.png
description: 每天的学习点滴～
---
# 技术文件——20221203工作日志			拟制：解辰锋

# 本文中的所有信息均为清华大学内部消息，不得向外传播

---

# 1.学习记录

## CAN学习

### 什么是CAN2.0？

+ CAN2.0是总线接口标准；CAN2.0定义了CAN控制器的数据链路层（包括对象层与传输层）和CAN收发器的物理层；前几天总结的关于CAN物理层和数据层的内容均为CAN2.0的一部分

### CANFD比CAN提升了哪些方面？

+ CAN-FD协议支持了更高的速率，可以更快刷写ECU
+ CAN-FD可以将CAN线束以及其他物理层原件重新利用起来，节省了升级成本
+ 上层应用层的架构也不需要改变，在原有基础上扩展即可

### CANFD的波特率

+ SAE标准

  + SAE J2284-4 推荐汽车CAN-FD网络应用采用500k/2M波特率
  + SAE J2284-5推荐汽车 CAN-FD网络采用500k/5M的波特率

  <img src="Dec06/image-20221206191635003.png" alt="image-20221206191635003" style="zoom:33%;" />

### CANFD的帧

<img src="Dec06/image-20221206192450772.png" alt="image-20221206192450772" style="zoom:33%;" />

#### `<img src="Dec06/image-20221206192531140.png" alt="image-20221206192531140" style="zoom: 33%;" />`

<img src="Dec06/image-20221206192727904.png" alt="image-20221206192727904" style="zoom:33%;" />

<img src="Dec06/image-20221206193105239.png" alt="image-20221206193105239" style="zoom:33%;" />

### CANFD的应用

<img src="Dec06/image-20221206193615813.png" alt="image-20221206193615813" style="zoom:33%;" />

### CAN与CANFD的网络兼容问题

<img src="Dec06/image-20221206193923843.png" alt="image-20221206193923843" style="zoom:33%;" />

<img src="Dec06/image-20221206194416000.png" alt="image-20221206194416000" style="zoom:33%;" />

<img src="Dec06/image-20221206194433545.png" alt="image-20221206194433545" style="zoom:33%;" />

## hexo博客搭建

+ 最近每天都有工作汇报，想起了之前常用的博客工具，于是今天花了很长时间重新维护博客系统，在之前的博客系统之上做了一定程度的升级

### 工作内容

+ 重新创建了一个项目工程
+ 挑选了一个专门用于知识管理的模版wikitten，并且做了一些基本的测试，感觉体验不错
+ 维修了一系列bug
  + 图片不加载bug
+ 添加了一系列附加功能
  + 文章加密
  + 创建模版
  + 远程部署（未完全解决——最近因不可抗力github崩了，无法作远程部署，转而采用国内的gitee，可是gitee的博客托管服务pages需要实名认证，审核需要一定时间）
+ 对问题作了记录，总结

<img src="Dec06/image-20221206190151819.png" alt="image-20221206190151819" style="zoom:50%;" />

### 博客效果展示

<img src="Dec06/image-20221206190247693.png" alt="image-20221206190247693" style="zoom: 25%;" />

## 参考资料

### 视频资源

[CAN FD基础_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1gD4y1U7bJ?p=3&vd_source=2d5ec0a230549ed2b672ea4be8a2cc58)

### 博客资源

# 2.问题

# 3.下一步计划

明天准备开始确定毕业设计选题方向，对研究方向作进一步的细化

---

# 本文中的所有信息均为清华大学内部消息，不得向外传播
