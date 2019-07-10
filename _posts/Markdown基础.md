---
layout: post
title:  "MarkDown基础"
date:   2019-07-10 18:48:21 +0800
tags: makedown
color: rgb(255,90,90)
cover: '../assets/profile.jpeg'
subtitle: 'makedown学习'
---

# MarkDown基础

> 为了构建自己的个人小站，需要使用到makedown，现在正在学习之中，特此边记边学...
>
> 来源：[最完整的Markdown基础教程](https://www.jianshu.com/p/335db5716248)，[Markdown语法解析](https://www.jianshu.com/p/7aec157c395f)

### 基础语法

#### 标题

makedown支持6种级别的标题，以 # 号数量来进行划分

```
# h1
## h2
### h3
#### h4
##### h5
###### h6
```

对应的效果如下：

# h1

## h2

### h3

#### h4

##### h5

###### h6

除此之外，Markdown还支持另外一种形式的标题展示形式，其类似于 [Setext](https://link.jianshu.com/?t=http%3A%2F%2Fdocutils.sourceforge.net%2Fmirror%2Fsetext.html) 标记语言的表现形式,但是由于它自身有缺陷，所以推荐使用上面的方式来书写，这里就不再对其分析。

#### 段落及区块引用

Markdown提供了一个特殊符号 > 用于段首进行强调，被强调的文字部分将会高亮显示。

```
> 这段文字将被高亮显示...
```

以上标记显示效果如下：

> 这段文字将被高亮显示...

#### 插入链接

在 Markdown 中，插入链接不需要其他按钮，你只需要使用 `[显示文本](链接地址)` 这样的语法即可， ()中的”“中可以为链接指定title属性，title属性可加可不加。title属性的效果是鼠标悬停在链接上会出现指定的 title文字。`[链接文字](链接地址 "链接标题")`这样的形式。**链接地址与链接标题前有一个空格**。例如：

```
[我的个人小站](https://lovelovefish.github.io/ "我的博客")
```

实际的文本的显示：

[我的个人小站](https://lovelovefish.github.io/ "我的博客")

#### 插入图片

![](E:\lovelovefish.github.io\assets\lineart.png)