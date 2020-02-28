---
layout: page
permalink: /latest/
---

<div class="depan">
  {% for post in site.posts limit:2 %}
      <li>{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</div>
📂 lihat <a href="https://bryantara.com/artikel">arsip...</a> yo
