---
title: Resources
---

<h1>{{ page.title }}</h1>

<ul class="posts">
  {% for post in site.posts %}
    <li>
      <span class="post-date">{{ post.date | date: "%B %e, %Y" }}</span>
      &raquo;
      <a href="{{ post.url | relative_url }}" title="{{ post.title }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
