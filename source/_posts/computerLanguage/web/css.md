---
layout: "post"
title: "前端基础之CSS"
date: "2019-10-13 21:29"
categories: web,CSS
tags: [Computer Language, web,CSS]
---

# CSS一些基本概念

## 术语解释

```css
h1{
    color:red;
    background-color: lightblue;
    text-align: center;
}
```

CSS规则 = 选择器 + 声明块

### 选择器

选择器： 选中元素

1. ID选择器： 选中的是对应id值的元素
2. 元素选择器
3. 类选择器

### 声明块

出现在`{}`中，声明块包含很多声明（属性），每一个声明（属性）表达了某一方面的样式

## CSS代码书写位置

1. 内部样式表

书写在`<style>`元素中，一般放在`<head>`里面

2. 内联样式表（元素样式表）

直接书写在元素的style属性中

3. 外部样式表[推荐]

将样式书写到独立的css文件中

1) 外部样式表可以解决多页面样式重复的问题
2) 有利于浏览器缓存，从而提高页面响应速度
3) 有利于代码分离(HTML和CSS)，更容易阅读和维护

# 常见样式声明

1. color

元素内部的文字颜色

**预设值**： 定义好的单词

**三原色(色值)**： 光学三原色（红、绿、蓝），每个颜色可以使用0-255之间的数字来表达色值。

```
rgb表示法：
rgb(0,255,0)
hex(16进制)表示法：
#红绿蓝
```

常用的颜色色号：

淘宝红： #ff4400,#f40
黑色： #000000，#000
白色： #ffffff, #fff
红： #f00
绿： #0f0
蓝： #00f
紫： #f0f
青： #0ff
黄： #ff0
灰色： #ccc

2. background-color

元素背景颜色

3. font-size

元素内部文字的尺寸大小

1) 像素尺寸 px
2) 相对单位 em 相对父元素的字体大小 

每个元素必须有字体大小，如果没有声明，则直接使用父元素的字体大小；若果没有父元素(即html元素)，则使用基准字号，即浏览器中设置的字体大小

>user agent:  UA, 用户代理（浏览器）

4. font-weight

文字粗细程度，可以取值数字，可以取值为预设值

**预设值**

normal-->400 (不加粗)
bold-->700 (加粗)


---

参考视频

 https://www.bilibili.com/video/av57100756?from=search&seid=2646463889570770154 (2019年 HTML+CSS 零基础权威入学宝典【渡一教育】p16~p58)