---
layout: page
permalink: /latest/
---
![pesawat kertas](https://raw.githubusercontent.com/bryantara/bryantara.github.io/master/images/pswt.png)
Yang baru di bryantara.com:
<div class="entry">
  {% for post in site.posts limit:2 %}
      <ul class="b"><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></ul>
  {% endfor %}
</div>
arsip <a href="https://bryantara.com/artikel">selengkapnya...</a>
