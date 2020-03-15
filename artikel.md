---
layout: page
permalink: /artikel/
---
<h3>📈 Pengolahan Data</h3>
{% for post in site.categories.data %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

<h3>📚 Resensi Buku</h3>
{% for post in site.categories.buku %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

<h3>👨‍💻 Personal</h3>
{% for post in site.categories.personal %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
