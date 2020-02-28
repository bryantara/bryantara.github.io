---
layout: page
permalink: /latest/
---
![Gunung Batu, Lembang](https://raw.githubusercontent.com/bryantara/bryantara.github.io/master/images/gunung-batu-lembang.jpg)
Yang baru di bryantara.com:
  {% for post in site.posts limit:2 %}
      <ul class="b"><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></ul>
  {% endfor %}
arsip <a href="https://bryantara.com/artikel">selengkapnya..</a>
