 ---
 layout: archive
 title: "可视化图表类型"
 date: 2018-1-5 00:07:50 +0800
 modified:
 excerpt: "可持续发展，含＂生态文明＂倡议"
 tags: []
 image: 
   feature: tableau.png
   teaser: tableau.png
 ---
 
+在此展示可持续发展目标内容介绍及思考
 
 <div class="tiles">
 {% for post in site.categories.SDG %}
   {% include post-grid.html %}
 {% endfor %}
 </div><!-- /.tiles 把所有categories 有 SDG 的列出来-->