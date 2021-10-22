---
layout: page
title: "#blog"
permalink: /blog/
---
<h3Pengolahan Data</h3>
{% for post in site.categories.data %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

<h3Resensi Buku</h3>
{% for post in site.categories.buku %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

<h3Personal</h3>
{% for post in site.categories.personal %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}  

Intip juga tumblr saya [di sini](https://bryantara.tumblr.com).
