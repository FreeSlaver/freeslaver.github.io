---
layout: page

show_meta: false
title: "佛"
subheadline: ""
header:
   image_fullwidth: "header/buddha.jpg"
permalink: "/buddha/"
---
<ul>
    {% for post in site.categories.buddha %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>