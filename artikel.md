---
layout: page
permalink: /artikel/
---
![Gunung Batu, Lembang](https://raw.githubusercontent.com/bryantara/bryantara.github.io/master/images/gunung-batu-lembang.jpg)
Selamat datang di bryantara.com! _Monggo_ dinikmati kontennya.

<h3>📜 Kumpulan Esai</h3>
{% for post in site.categories.esai %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

<h3>📚 Resensi Buku</h3>
{% for post in site.categories.buku %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

<h3>📈 Pengolahan Data</h3>
{% for post in site.categories.data %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
