---
layout: page
subheadline: "Header"
title: "Style your Header!"
teaser: ""
header:
   image_fullwidth: ""
permalink: "/headers/"
---
<ul>
    {% for post in site.tags.header %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>