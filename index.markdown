---
layout: default
title: Frontflip Podcast
---

## Мы ищем таланты
Мы составили <a href='/possible_themes.html'>список тем</a>, которые бы нам интересно обсудить в новых выпусках.   
Изучайте, передавайте друзьям, приходите в гости.

## Выпуски

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date: "%d/%m/%Y" }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a> <a href="{{ post.url }}#disqus_thread"></a></a></li>
  {% endfor %}
</ul>
