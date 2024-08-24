---
layout: page
title: "Materi Ekonomi"
permalink: /ekonomi/
---
<h3>Ekonomi Kelas 10</h3>
{% for post in site.categories.ekonomi-10 %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
