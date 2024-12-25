---
layout: page
title: "/ECON"
permalink: /econ/
---
<h3>Coming soon...</h3>
{% for post in site.categories.econ %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
