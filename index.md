---
layout: default
title: Home
---

<section class="hero">
  <p class="eyebrow">welcome to the deep</p>

  <h1>Security notes from mormaid.</h1>

  <p class="hero-text">
    I write about technical fundamentals, transitioning into engineering, and things I’m building.
  </p>

  <p class="hero-links">
    <a href="{{ '/blog/' | relative_url }}">Read my blog</a>
    <a href="{{ '/projects/' | relative_url }}">See projects</a>
  </p>
</section>

<section class="latest-posts">
  <h2>Latest notes</h2>

  <ul class="post-list">
    {% for post in site.posts limit:5 %}
      <li>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        <span>{{ post.date | date: "%d %b %Y" }}</span>

        {% if post.description %}
          <p>{{ post.description }}</p>
        {% endif %}
      </li>
    {% endfor %}
  </ul>
</section>