---
layout: post
title: Jekyll 的一些函数和技巧
---
#{{ page.title }}
{{ page.date | date:"%B %d, %Y" }} By PIZn @杭州
##一些函数
    //循环输出 3 篇文章
    for post in site.posts limit:3
    endfor
    //循环输出最近 3 篇
    for post in site.posts offset:3 limit:3
    endfor
    //日期
    page.date | date:"%B %b, %Y"
