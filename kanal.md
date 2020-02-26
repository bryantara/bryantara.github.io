---
layout: page
permalink: /kanal/
---
Halo, selamat datang di bryantara.com! Blog ini memiliki tiga kanal utama, yaitu kumpulan esai, resensi buku, dan pengolahan data. Selamat menikmati ☕

***

<h3>3 Artikel Baru</h3>
<ul class="related_posts">
  {% for post in site.related_posts limit: 3 %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

***

<h3>Kumpulan Esai</h3>
{% for post in site.categories.esai %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

***

<h3>Resensi Buku</h3>
{% for post in site.categories.buku %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

***

<h3>Pengolahan Data</h3>
{% for post in site.categories.data %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
