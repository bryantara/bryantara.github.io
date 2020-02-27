---
layout: page
permalink: /kanal/
---
Halo, selamat datang di bryantara.com! Blog ini memiliki tiga kanal utama, yaitu esai, buku, dan data. Selamat menikmati ☕

![Gunung Batu, Lembang](https://raw.githubusercontent.com/bryantara/bryantara.github.io/master/images/gunung-batu-lembang.jpg)

<h3>Kumpulan Esai</h3>
{% for post in site.categories.esai %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

<h3>Resensi Buku</h3>
{% for post in site.categories.buku %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

<h3>Pengolahan Data</h3>
{% for post in site.categories.data %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
