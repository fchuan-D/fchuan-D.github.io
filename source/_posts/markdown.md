---
title: Markdown
date: 2021-12-31 22:54:56
categories:
- 语言
- Markdown
tags:
- html插图
---
*使用html来引用插入的图片，固定图片大小：width=256,height=256设置的是显示图像的尺寸，src后面接的就是<u>图像对象</u>*

    <img src="图片路径" width=256 height=256 />
*还可以使用<u>百分比</u>的方式来给width,height传参*
<!--more-->
    <img src="/images/mine.jpg" width="50%" height="50%" />
*如果想给图像加个标注，可以这么做*

    <center>
    <img src="/images/mine.jpg" width="25%" height="25%" />
    Figure 1. xx
    </center>
    <center>
    <img src="/images/mine.jpg" width="10%" height="10%" />
    </center>
*如果想让图和标注间距离增大，可以这么做*

    <center>
    <img src="/images/mine.jpg" width="25%" height="25%" />
    $ $
    Figure 1. xx
    </center>
  **Markdown 菜鸟教程**
  https://www.runoob.com/markdown/md-tutorial.html
  **常用**
  https://blog.csdn.net/u011732358/article/details/83098211