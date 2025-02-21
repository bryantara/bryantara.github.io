---
layout: page
title: "Tutorials"
permalink: /tutorials/
---
{% for post in site.categories.tutorial %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
