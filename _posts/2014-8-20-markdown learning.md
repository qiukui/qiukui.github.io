---
layout: post
title: Markdown learning!
category: "markdown"
tag: "markdown"
---


1. 这篇文章主要记录一些 markdown 语法摘要，随时补充，随时修改完善。  
2. 学习贵在坚持，不积跬步，无以至千里。

##markdown学习笔记##

###基本语法###

1. **粗体**是用 \*\* ... \*\*    
2. *斜体*是用 \* ... \*  
3. 使用**一个或多个空行**生成段落  
4. 标题 H1-H6 格式使用相应个数的 **#** 作为前缀  
5. 使用\>作为段落前缀来标识引用文字段落。 For example:  
>  引用内容    
>  这个记号直接借鉴的邮件标准    
>  > 缩进的引用内容      
  
6. 使用 *, +, - 来表示无序列表；使用数字加 . 表示有序列表  
	* 无序项1
	+ 无序项2 
	+ 无序项3
7. 使用4个以上的空格或一个以上的 tab 来标记代码段落  
8. 使用 [百度](http://www.baidu.com "title") 来标记普通链接  
9. 使用 ![img](http://image6.tuku.cn/pic/wallpaper/fengjing/yangguangshatanhaian/020.jpg) 来标记图片  

###给力的特性

1. 普通换行并不会产生新的段落或<br\>,但是产生空格   
> 可以手动的将文字折行，插入<br\>, 比如  
> <br>我<br>其实<br>是一首诗  

2. 支持引用式的链接格式，  
> 比如，下面的一段文字.  
> 首先，什么是markdown？ 我们可以直接看一下 [baidu][1]      
> 另外，markdown 可以被直接编译为html, 比如使用在线的 [pandoc][2]       
> 同时，可以显示一段url文本，比如<http://www.baidu.com>用<http://www.baidu.com\>就可以了    
> [1]: http://www.baidu.com    
> [2]: http://www.3600.com    
