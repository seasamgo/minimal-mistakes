---
title: 
permalink: /content/
layout: archive
author_profile: true
---

<ul>
  {% for post in site.posts %}
    <li>
      <b><a href="{{ post.url }}">{{ post.title }}</a></b>
      <p>{{ post.read_time }}</p>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
