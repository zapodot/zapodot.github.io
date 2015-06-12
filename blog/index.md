---
layout: page
title: Words from the <em>Tech Troll</em>
tagline: A personal blob, mostly about technical stuff
---

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
    {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
{% include JB/setup %}
