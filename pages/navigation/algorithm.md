---
layout: page
show_meta: false
title: "ALGORITHMS"
subheadline: "Core of Coding"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/geek/algorithms/"
---
<ul>
    {% for post in site.categories.algorithms %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
