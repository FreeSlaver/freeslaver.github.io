---
layout: page

show_meta: false
title: "标签"
subheadline: "标签遍历所有文章"
header:
   image_fullwidth: "header/tag.jpg"
permalink: "/tag/"
---
<ul>
    {% for post in site.categories.career %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>