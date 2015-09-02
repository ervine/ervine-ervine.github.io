---
layout: page
show_meta: false
title: "SHARE"
subheadline: "Something interesting to share with you"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/share/"
---
<ul>
    {% for post in site.categories.share %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
