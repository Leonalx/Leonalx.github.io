---
layout: post
title: 《CSS网站布局实录》读书笔记
date: 2014-7-13

---

一直没系统的学过CSS，最近做项目越来越觉得CSS写不顺手，所以找来了这本书看看。 现在看这本已经有些过时了，权当是过一遍基本的知识点，碰到不太熟的东西就上网搜搜文章外加自己实践。这里简单的记录下以前不太熟的知识点。

##高度自适应
书里给的居然不是min-height的做法，而是给html/body元素一个height:100%,然后再讲元素本身的height设为100%就可以了【[具体代码](http://jsbin.com/piyovixa/1/edit)】。

##上下margin叠加问题
上下两个div如果都有margin，那个将会出现margin的叠加。如果将某个元素设float熟悉，讲不再叠加【[具体代码](http://jsbin.com/yiteyonu/3/edit)】。




