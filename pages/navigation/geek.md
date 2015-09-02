---
layout: page
show_meta: false
title: "GEEK"
subheadline: "I'm geek, a hamesome geek ."
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/geek/"
---
<ul>
    {% for post in site.categories.geek %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
