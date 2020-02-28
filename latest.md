---
layout: page
permalink: /latest/
---

<div class="entry">
  {% for post in site.posts limit:2 %}
      <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</div>
<p>👉 selengkapnya di [arsip](https://bryantara.com/artikel).<p>
