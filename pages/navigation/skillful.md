---
layout: page
show_meta: false
title: "SKILLFUL"
subheadline: "Learn how to improve your life."
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/geek/skillful/"
---
<ul>
    {% for post in site.categories.skillful %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
