---
layout: page
title: NEWS
permalink: /news/
---

<hr>
{% for post in site.posts %}
  <a href="{{ post.url }}" style="font-size: 25.5px;">{{ post.title }}</a><br>
  {{ post.date | date: "%Y年%-m月%-d日" }}
  <hr>
{% endfor %}
