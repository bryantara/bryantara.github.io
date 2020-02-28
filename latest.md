---
layout: page
permalink: /latest/
---
![mesin ketik Photo by Florian Klauer on Unsplash](https://raw.githubusercontent.com/bryantara/bryantara.github.io/b1765855563fb2e9effcedbea5a6d37d067c99d2/images/ketik.png)
<p style="text-align:center">
Yang baru di bryantara.com:</p>
<div class="entry">
  {% for post in site.posts limit:2 %}
      <ul class="b"><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></ul>
  {% endfor %}
</div>
<p style="text-align:center">📰 <a href="https://bryantara.com/artikel">arsip...</a></p>
