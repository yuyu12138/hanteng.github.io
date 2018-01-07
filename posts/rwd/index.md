---
layout: archive
title: "网页设计小笔记_(:з」∠)_"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: ""
tags: []
image: 
  feature: 
  teaser:
---

这是我无意中发现的一个方便修改文章的github小功能_(:з」∠)_

{% include toc.html %}

![gt](https://image.ipaiban.com/upload-ueditor-image-20180106-1515175326761074279.png)

-  最近这几天为了修改模板都commit了几百次了，提交完了之后发现跑出来有错误又要重新点进去改。但是github有一个挺人性化的交互按钮，就能省去很多麻烦。这个摁钮的位置很容易被忽略↓↓↓

![gt](https://image.ipaiban.com/upload-ueditor-image-20180106-1515176471610054919.png)

- 你编辑好文章，在提交之前就可以摁一下这个按钮，`预览一下你的代码`出来的效果。
- 新建的文件，第一次编辑完了之后只要你的内容不出现红色的提示标记的话那你就可以安心提交了。
- 第一次commint之后，你想再次删改或者增加内容，每次编辑后都可以摁一次预览，如果`你的代码有错误`，它就会出现这样的标记来提示你：

![gt2](https://image.ipaiban.com/upload-ueditor-image-20180106-1515177224047065931.png)

`红色部分`就代表你的代码有误需要修改，绿色部分就不需要。

- 还有一种情况，就是你如果删掉了一些内容，它就出现这样的标记：

![gt3](https://image.ipaiban.com/upload-ueditor-image-20180106-1515177816997091137.png)

`黄色标记`的这部分内容里，有`红色删除线`的内容就是你在编辑过程中已经删除的内容。

- 这样就能在每一次commit之前有反馈地修改了。
- 不过好像只有md格式文档编辑的时候才有这个交互按钮。


<div class="tiles">
{% for post in site.categories.rwd %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 rwd 的列出来-->
