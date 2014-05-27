---
layout: index
title: Frontflip Podcast
---

### Последние выпуски

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a> <a href="{{ post.url }}#disqus_thread"></a></li>
  {% endfor %}
</ul>
