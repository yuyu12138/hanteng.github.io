---
layout: archive
title: "可视化作品"
date: 2017-12-31T11:40:45-04:00
modified:
excerpt: "一个学期来做到的可视化作品"
tags: []
image: 
  feature: tutou2.jpg
  teaser:
---



<div class="tiles">
{% for post in site.categories.portfolio %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 portfolio 的列出來-->
