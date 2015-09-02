---
layout: page
show_meta: false
title: "MOOD"
subheadline: "I'm in good mood; I'm in bad mood."
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/mood/"
---
<ul>
    {% for post in site.categories.mood %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
