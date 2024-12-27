---
layout: page
title: "Indonesia Updates"
permalink: /indonesia/
---
{% for post in site.categories.indonesia %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
