---
layout: page
show_meta: false
title: "小说"

subheadline: ""
header:
   image_fullwidth: "header/essay.jpg"
permalink: "/story/"
---
<ul>
    {% for post in site.categories.story %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>