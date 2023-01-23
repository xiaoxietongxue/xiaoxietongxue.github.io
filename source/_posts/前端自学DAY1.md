---
title: 前端自学DAY1
date: 2023-01-01 12:12:38
tags: 
categories: 前端
cover: img/前端.jpg
---

# 前端核心知识组成

+ HTML：定义了网站的结构
+ CSS：定义了网站的表现
+ JS（javascript）：定义了网站的行为

# 浏览器解析的标准——W3C

# 趁手兵器——Vscode

## 快速操作

+ ！+回车自动创建html模版

## 配套插件

+ auto rename tag
+ live server
+ Html tag wrap(标签包裹)

# HTML

## 常规标记与空标记

+ 常规标记——“有头有尾”

```html
<标记> </标记>
```

+ 空标记，也称为单标记

```html
</标记>
```



## 文档声明与字符编码

<img src="前端自学DAY1/image-20230101124701487.png" alt="image-20230101124701487" style="zoom:50%;" />

<img src="前端自学DAY1/image-20230101125014593.png" alt="image-20230101125014593" style="zoom:50%;" />

## HTML常用标签

<img src="前端自学DAY1/image-20230101130253486.png" alt="image-20230101130253486" style="zoom: 33%;" />



<img src="前端自学DAY1/image-20230101130414608.png" alt="image-2023010113041460" style="zoom: 33%;" />

<img src="前端自学DAY1/image-20230101130854670.png" alt="image-20230101130854670" style="zoom: 50%;" />

<img src="前端自学DAY1/image-20230101131254292.png" alt="image-20230101131254292" style="zoom:50%;" />

<img src="前端自学DAY1/image-20230101191830890.png" alt="image-20230101191830890" style="zoom:50%;" />

+ hr的几个常用属性

<img src="前端自学DAY1/image-20230101192615121.png" alt="image-20230101192615121" style="zoom:50%;" />

## 特殊符号

![image-20230101192942292](前端自学DAY1/image-20230101192942292.png)

+ 不推荐使用nbsp缩进，推荐使用emsp
+ 可以用lorem生成一个文字序列

## div标签和span标签（无语义标签）

+ div没有具体含义，用来划分页面区域，独占一行（无外力作用下——忽略CSS作用）
+ <img src="前端自学DAY1/image-20230101195009644.png" alt="image-20230101195009644" style="zoom:50%;" />

## 列表

![image-20230101195158328](前端自学DAY1/image-20230101195158328.png)

+ ul和ol里面相邻层只可以放li，li里面可以嵌套别的标签

### 有序列表

+ 可以加入type属性

```html
<ol type="a">
  <li></li>
  <li></li>
  <li></li>
</ol>
```

type还可以设定为“A”，“i”，“I”等

+ 可以加入start属性，其值只能是一个数字

### 无序列表

+ 可以加入type属性
  + disc
  + square
  + none

### 自定义列表（常用于图文混排）

## 图片标签img

![image-20230101203506187](前端自学DAY1/image-20230101203506187.png)

这种表示方式要尽可能避免，尽量使用相对路径（为了投送到服务器上还可以正常使用）

<img src="前端自学DAY1/image-20230101203605954.png" alt="image-20230101203605954" style="zoom:50%;" />

<img src="前端自学DAY1/image-20230101203634322.png" alt="image-20230101203634322" style="zoom:50%;" />

![image-20230101204219674](前端自学DAY1/image-20230101204219674.png)

+ 在调整height和width的一个量时图片的另一个值也会变化（等比例）

## 超链接标签

![image-20230101205811915](前端自学DAY1/image-20230101205811915.png)

<a href=./Dec03.md>dasda</a>

## 表格table

<img src="前端自学DAY1/image-20230101210355730.png" alt="image-20230101210355730" style="zoom:50%;" />

<img src="前端自学DAY1/image-20230101210723402.png" alt="image-20230101210723402" style="zoom:50%;" />

![image-20230101211400888](前端自学DAY1/image-20230101211400888.png)

### 行tr属性

<img src="前端自学DAY1/image-20230101214849301.png" alt="image-20230101214849301" style="zoom:50%;" />

### 列td属性

<img src="前端自学DAY1/image-20230101215250461.png" alt="image-20230101215250461" style="zoom:50%;" />

## 表单标签

<img src="前端自学DAY1/image-20230101230528398.png" alt="image-20230101230528398" style="zoom:50%;" />

+ 目的：收集用户信息

<img src="前端自学DAY1/image-20230101230606697.png" alt="image-20230101230606697" style="zoom:50%;" />

<img src="前端自学DAY1/image-20230101230855191.png" alt="image-20230101230855191" style="zoom:50%;" />

<img src="前端自学DAY1/image-20230101231534323.png" alt="image-20230101231534323" style="zoom:50%;" />

<img src="前端自学DAY1/image-20230101231659000.png" alt="image-20230101231659000" style="zoom:50%;" />

## CSS

<img src="前端自学DAY1/image-20230101232745258.png" alt="image-20230101232745258" style="zoom:50%;" />

<img src="前端自学DAY1/image-20230101232836125.png" alt="image-20230101232836125" style="zoom:50%;" />

### 内部样式

+ CSS声明嵌套在style标签中，大家统一规定style标签放在head标签下

### 外部样式

<img src="前端自学DAY1/image-20230101234312013.png" alt="image-20230101234312013" style="zoom:50%;" />



<img src="前端自学DAY1/image-20230101234633139.png" alt="image-20230101234633139" style="zoom:50%;" />

创建方法

+ 方法一：弃用style标签，直接用link标签导入

+ 方法二：保留style标签，在里面通过@import语句导入



###  行内样式

<img src="前端自学DAY1/image-20230102103648969.png" alt="image-20230102103648969" style="zoom:50%;" />

### CSS样式表的优先级

+ 基于规定的写作方式——style标签写在head的末尾（在link标签之后），所以可以认为内部样式表优先级高于外部样式表优先级
+ 行内优先级高于内部样式表优先级

### 标签选择器

<img src="前端自学DAY1/image-20230102104551170.png" alt="image-20230102104551170" style="zoom:50%;" />

### 类选择器

<img src="前端自学DAY1/image-20230102104816072.png" alt="image-20230102104816072" style="zoom:50%;" />

<img src="前端自学DAY1/image-20230102104946120.png" alt="image-20230102104946120" style="zoom:50%;" />

### id选择器

<img src="前端自学DAY1/image-20230102105712068.png" alt="image-20230102105712068" style="zoom:50%;" />

<img src="前端自学DAY1/image-20230102111020648.png" alt="image-20230102111020648" style="zoom:50%;" />
