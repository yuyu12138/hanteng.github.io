---
layout: archive
title: "Tableau笔记"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: "emmmm是关于tableau的小笔记"
tags: []
image: 
  feature: shenle.gif
  teaser:
---


<div class="tiles">
{% for post in site.categories.infovisnotes %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovisnotes 的列出来-->
