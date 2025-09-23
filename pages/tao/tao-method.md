---
layout: page

show_meta: false
title: "修炼法门"
subheadline: ""
header:
   image_fullwidth: "header/tao.png"
permalink: "/tao-method/"
---
<ul>
    {% for post in site.categories.tao-method %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>