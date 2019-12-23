---
layout:     post
title:      Markdown Beginner
subtitle:   
date:       2018-09-25
author:     Sayai
catalog: true
tags:
    - Markdown
---
<!-- MarkdownTOC -->

- [前言](#%e5%89%8d%e8%a8%80)
  - [Tools](#tools)
- [Markdown: Syntax](#markdown-syntax)
  - [目录](#%e7%9b%ae%e5%bd%95)
  - [标题](#%e6%a0%87%e9%a2%98)
  - [列表](#%e5%88%97%e8%a1%a8)
    - [无序](#%e6%97%a0%e5%ba%8f)
    - [有序](#%e6%9c%89%e5%ba%8f)
    - [嵌套列表](#%e5%b5%8c%e5%a5%97%e5%88%97%e8%a1%a8)
  - [引用](#%e5%bc%95%e7%94%a8)
  - [图片](#%e5%9b%be%e7%89%87)
  - [链接](#%e9%93%be%e6%8e%a5)
  - [索引链接](#%e7%b4%a2%e5%bc%95%e9%93%be%e6%8e%a5)
  - [本身就是链接](#%e6%9c%ac%e8%ba%ab%e5%b0%b1%e6%98%af%e9%93%be%e6%8e%a5)
  - [分割线](#%e5%88%86%e5%89%b2%e7%ba%bf)
  - [表格](#%e8%a1%a8%e6%a0%bc)
  - [代码块](#%e4%bb%a3%e7%a0%81%e5%9d%97)
  - [转义](#%e8%bd%ac%e4%b9%89)
  - [Others](#others)
    - [粗体](#%e7%b2%97%e4%bd%93)
    - [斜体](#%e6%96%9c%e4%bd%93)
    - [字体, 字号, 和颜色](#%e5%ad%97%e4%bd%93-%e5%ad%97%e5%8f%b7-%e5%92%8c%e9%a2%9c%e8%89%b2)
- [Reference](#reference)

<!-- /MarkdownTOC -->

# 前言
我则是希望有一些储备，有一些积累。

阶段性总结有利于精确自己的目标, 以及为后续的想法开辟空间.

因此开始有必要整理记录.

但是因为没必要像写paper那样规范使用latex, 因此就选择了Markdown.


## Tools
Windows - [MarkdownPad](http://www.markdownpad.com/)

Github Pages - (If you have one)

# Markdown: Syntax
## 目录
    [TOC]

由于github不支持显示TOC, 因此需要先用**markdown-toc**[4]进行预处理
也可以使用sublime里的**markdown-toc**[5]插件.

## 标题
    # content
    ## content
    ### content
    ......

一共可以设置六级标题

## 列表
### 无序
    * 1
    * 2
    * 3
* 1
* 2
* 3

### 有序
    1. 1
    2. 2
    3. 3
1. 1
2. 2
3. 3

### 嵌套列表
    - AAA
      + A
        - a
          1. contentA
          2. contentB

- AAA
  + A
    - a
      1. contentA
      2. contentB

## 引用
    > contentA
      >> contentB

> contentA
  >> contentB

之后的文本内容需要插入空行

## 图片
    ！[icon](link to the picture)

## 链接
    [content](link to the content)

## 索引链接
    [content][1]
    [1]:Url
[content][1]
[1]:Url

## 本身就是链接
    <url>
<https://xinyao1994.github.io/>

## 分割线
    ***
	---

## 表格
    | Tables        | Are           | Cool  |
    | ------------- |:-------------:| -----:|
    | col 3 is      | right-aligned | $1600 |
    | col 2 is      | centered      |   $12 |
    | zebra stripes | are neat      |    $1 |

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

## 代码块
    ``` [python]
    @requires_authorization
    def add(a, b): # add a and b
        return a+b
    class TA:
    ```

``` [python]
@requires_authorization
def add(a, b): # add a and b
	return a+b
class TA:
```

or 每行文字前加4个空格或者1个Tab

## 转义


## Others
### 粗体
    **content**
**content**

    __content__
__content__

### 斜体
    *content*
*content*

    _content_
_content_

### 字体, 字号, 和颜色
    <font face="黑体">我是黑体字</font>
    <font face="微软雅黑">我是微软雅黑</font>
    <font face="Verdana">I like Verdana format</font>

<font face="黑体">我是黑体字</font>

<font face="微软雅黑">我是微软雅黑</font>

<font face="Verdana">I like Verdana format</font> 

# Reference
[1]:[Markdown: Syntax](https://daringfireball.net/projects/markdown/syntax)

[2]:[认识与入门 Markdown](https://sspai.com/post/25137)

[3]:[Markdown 语法大全](https://blog.csdn.net/qcx321/article/details/53780672)

[4]:[markdown toc](https://github.com/houbb/markdown-toc)

[5]:[sublime with markdown-toc](https://www.cnblogs.com/Sinte-Beuve/p/5148108.html)
