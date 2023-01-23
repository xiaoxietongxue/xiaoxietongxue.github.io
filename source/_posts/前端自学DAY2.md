---
title: 前端自学DAY2
date: 2023-01-02 11:14:54
tags:
categories: 前端
cover: img/前端.jpg

---

# CSS

## 通配符选择器

![image-20230102112420280](前端自学DAY2/image-20230102112420280.png)

## 群组和后代选择器

<img src="前端自学DAY2/image-20230102113931557.png" alt="image-20230102113931557" style="zoom:50%;" />

## 伪类选择器（简单实用）

<img src="前端自学DAY2/image-20230102115019642.png" alt="image-20230102115019642" style="zoom:50%;" />

# Javascript(p184)

## 历史与背景

Netscape公司

<img src="前端自学DAY2/image-20230102150055755.png" alt="image-20230102150055755" style="zoom:50%;" />

## JS组成部分

+ HTML决定网页的内容
+ CSS决定网页的样式
+ JS决定网页的行为，主要由三部分构成
  + BOM（browser object model)——操作浏览器发生变化的属性和方法
  + DOM（document  object model)——操作文档流发生变化的属性和方法
  + ECMAScript——JS代码的书写规则

+ 图示JS作用

<img src="前端自学DAY2/image-20230102150651716.png" alt="image-20230102150651716" style="zoom:50%;" />

## JS代码的书写位置

+ 同CSS一样，也分为行内式、内嵌式、外链式
+ ![image-20230102170944512](前端自学DAY2/image-20230102170944512.png)

![image-20230102171446999](前端自学DAY2/image-20230102171446999.png)

## JS变量

### 变量

<img src="前端自学DAY2/image-20230102171652670.png" alt="image-20230102171652670" style="zoom:50%;" />

+ 命名规则同C语言近乎一致（不一样的地方是数字、字母、下划线的基础上加上了美元符）

+ 注释语句 //

<img src="前端自学DAY2/image-20230102172541809.png" alt="image-20230102172541809" style="zoom:50%;" />

### JS数据类型

<img src="前端自学DAY2/image-20230102172637845.png" alt="image-20230102172637845" style="zoom:50%;" />

#### 数值类型

![image-20230102172729670](前端自学DAY2/image-20230102172729670.png)

#### 字符串类型

+ 不区分单引号和双引号

<img src="前端自学DAY2/image-20230102173000384.png" alt="image-20230102173000384" style="zoom:50%;" />

#### 布尔类型

![image-20230102173034310](前端自学DAY2/image-20230102173034310.png)

#### 空类型

![image-20230102173133621](前端自学DAY2/image-20230102173133621.png)

#### 数值类型检测手段

![image-20230102173240202](前端自学DAY2/image-20230102173240202.png)

```javascript
var num=100
result=typeof num
console.write(result)
```

<img src="前端自学DAY2/image-20230102173622264.png" alt="image-20230102173622264" style="zoom:50%;" />

#### JS数据类型转换

##### 字符串到数字的转换

###### Number方法

```javascript
var s1='100'
console.log(typeof s1)

var s2=Number(s1)
console.log(typeof s2)
```

解析规则：

+ 如果字符串可以直接转换成数字，转换后的结果就是number
+ 如果字符串不能直接转换成数字，转换后的结果为NaN（Not a number)

###### parseInt方法

###### parseFloat方法

##### 转字符串
