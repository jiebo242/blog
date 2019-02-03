---
title: Markdown基本使用
date: 2018-07-24 11:54:34
updated: 2018-07-24 12:00:00
categories: 博客
tags: [markdown, github]
---
Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。目前用于博客编写和github上面md文件的编写。<!-- more -->
# 基本语法
~~~  
标题：
	#代表一级标题，######代表六级标题
字体：
	**加粗**，*斜体*，***斜体加粗***，~~删除线~~
引用：
	>引用文字
分割线：
	---或***
插入图片：
	网络图片：![图片说明](图片url地址 '图片title')
	本地图片：![图片说明](./01.png '图片title')
超链接：
	[超链接名](超链接地址 "超链接title")，title可以不要
列表：
	无序列表：用 - + * 任何一种都可以，跟内容之间都要有一个空格
	有序列表：数字加点，序号跟内容之间要有空格
	列表嵌套：上一级列表和下一级列表之间敲三个空格即可
表格：
	| a | b | c |
	|:-:|:-|-:|
	|   居中  |     左对齐    |   右对齐   |
代码：
	单行代码： `代码内容`，不管代码内容有没有换行，展示的效果都会变成有一行
	多行代码： ```<c/java/go/javascript/bash>
           	 代码内容
           	  ```，可以通过指定语言类型进行代码块的上色
流程图：
	居然还能画流程图，不过咱们还是通过图片来插入吧
~~~
# 编写工具
在windows上面，使用的markdownPad，通过[MarkdownPad官网](http://markdownpad.com/)下载安装  
- [markdownPad 2无法正常html预览](https://blog.csdn.net/wyc12306/article/details/51504906)  
- [markdownpad激活及快捷键](https://www.cnblogs.com/shierfen/p/5997558.html)

# 参考资料
- [Markdown——入门指南](https://www.jianshu.com/p/1e402922ee32/)