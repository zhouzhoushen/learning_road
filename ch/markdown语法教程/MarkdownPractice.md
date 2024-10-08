---
title: "MarkdownPractice"
author: Zhou29
date: September 16, 2023
output: word_document
export_on_save:
  pdf: true
---

[TOC]

# 这个标题有 1 个 id  {#my_id}

safsf

## 这个标题有 2 个 classes {.class1 .class2}

a sf asf

## 接下来是强调的内容

*这会是 斜体 的文字*
*这会是 斜体 的文字_

**这会是 粗体 的文字**
**这会是 粗体 的文字__

==*你也可以 **组合** 这些符号*==

~~这行文字将会被横线删除~~

## <center> 接下来是有序和无序列表

- Item1
- Item2
  - Item 2a
  - Item 2b

1. Item1
2. Item2
3. Item3
   1. Item 3a
   2. Item 3b

## 接下来是图片和超链接

![GitHub Logo](./images/Lena.bmp)
Format: ![Alt Text](./images/Lena.bmp)

<https://github.com> - 自动生成！
[GitHub](https://github.com.s)

## 接下来是引用

正如 Kanye West 所说：

> We're living the future so
> the present is our past

这是一行普通的文字。

> 这又是一行引用。

## 接下来是分割线

如下，三个或者更多的

---

连字符

---

星号

***

下划线

___

## 接下来是行内代码

我觉得你应该在这里使用
`<addr>` 才对。

## 接下来是代码块

下面是一行示例代码块

```c++
int a = 1;
int b = 2;
int c = a + b;
return c;
```

## 接下来是语法高亮

你可以给你的代码添加任何一种语言的语法高亮
例如，给ruby代码添加语法高亮：

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

## 代码块class（MPE扩展的特性）

你可以给你的代码块设置class。

例如，添加 `class1 class2` 到一个 代码块：

```javascript {.class1 .class2}
function add(x, y) {
  return x + y
}
```

## 显示代码行数

如果你想要你的代码块**显示代码行数**，只要添加 *line-numbers class* 就可以了。

例如：

```javascript {.line-numbers}
function add(x, y) {
  return x + y
}
```

## 高亮代码行数

你可以通过添加 ==highlight== 属性的方式来高亮代码行数：

```javascript {highlight=1}
function add(x, y) {
  return x + y
}
```

```javascript {highlight=1-3}
function add(x, y) {
  return x + y
}
```

```javascript {highlight=[1-10,15,20-22]}
function add(x, y) {
  return x + y
}
```

## 接下来是任务列表

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

## 接下来是表格

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

## 试试emoji表情

:smile:
:fa-car:

## 试试上标

10^th^

## 试试下标

H~2~O

## 试试数学表达式

$f(x) = sin(x) + 12$

$$\sum_{n=1}^{100} n$$

## 更多的内容

更多的内容请查看 [Markdown-Preview-Enhanced官方文档](https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-cn/)

注释:

<!-- 你看不见我 -->

<!-- 多行注释
就像这样 -->