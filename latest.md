---
layout: page
permalink: /latest/
---

<div class="posts">
  {% for post in site.posts limit:2 %}
    <article class="post">

      <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>

      <div class="entry">
         {{ post.content }}
      </div>
    </article>
  {% endfor %}
</div>
