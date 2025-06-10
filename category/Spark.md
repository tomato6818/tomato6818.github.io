---
layout: category
title: "Spark"
permalink: /categories/Development/Spark/
---

<h2>Spark 글 목록</h2>
<ul>
  {% for post in site.posts %}
    {% if post.categories contains "Spark" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

