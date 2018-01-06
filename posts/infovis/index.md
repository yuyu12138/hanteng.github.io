<div class="tiles">
{% for post in site.categories.infovisnotes %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovisnotes 的列出来-->{% for post in site.categories.infovis %} {% include post-grid.html %} {% endfor %}