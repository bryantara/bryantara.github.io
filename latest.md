---
layout: page
permalink: /latest/
---
![mesin ketik Photo by Florian Klauer on Unsplash](https://raw.githubusercontent.com/bryantara/bryantara.github.io/b1765855563fb2e9effcedbea5a6d37d067c99d2/images/ketik.png)
<p style="text-align:right">
Yang baru di bryantara.com:</p>
<div class="entry">
<p style="text-align:right">
  {% for post in site.posts limit:2 %}
      <ul class="b"><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></ul>
  {% endfor %}
</p>
</div>
<p style="text-align:right">arsip <a href="https://bryantara.com/artikel">selengkapnya...</a> :o</p>
