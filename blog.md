---
layout: page
title: Blog
permalink: /blog/
---

Captain's log of tech fundamentals, security notes, engineering learning, and project/build posts.

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%d %b %Y" }}</span>

      {% if post.description %}
        <p>{{ post.description }}</p>
      {% endif %}
    </li>
  {% endfor %}
</ul>