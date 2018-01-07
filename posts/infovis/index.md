---
layout: archive
title: "可视化笔记"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: ""
tags: []
image: 
  feature: 
  teaser:
---

想要获取高德地图的地图数据？超级简单！

{% include toc.html %}

- 首先进入 → <a href="http://lbs.amap.com/?:display_count=yes" target="_blank">高德地图平台→高德地图API</a>

- 然后你会看到右上角有个`控制台`的字样

![kong](https://image.ipaiban.com/upload-ueditor-image-20180106-1515187004903005840.png)然后注册或者登录账号

- 登录好了之后，点击`控制台`

![zhi](https://image.ipaiban.com/upload-ueditor-image-20180106-1515186913294017233.png)

- 点击左侧栏的第一个图标`应用管理`

![ying](https://image.ipaiban.com/upload-ueditor-image-20180106-1515187316054099876.png)

- 然后`创建新应用`，应用名称随便填，应用类别随便选，创建以后点击添加新key

- 接着，`key名称`根据命名规范随便命名，`服务平台`则选择`web服务`,提交之后就创建成功啦！

<div class="tiles">
{% for post in site.categories.infovisnotes %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovisnotes 的列出来-->
