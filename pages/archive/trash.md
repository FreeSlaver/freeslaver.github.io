---
layout: page
show_meta: false
title: "trash"
subheadline: "trash，价值不够的文章"
header:
   image_fullwidth: "header/trash.jpg"
permalink: "/trash/"
---
<ul>
    {% for post in site.categories.trash %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>