---
title: Home
---

The content for this page is in the `index.md` file. When GitHub Pages turns a repository into a website it looks for one of the following files (in descending order) to use as the home page:

- index.html
- index.md
- readme.md


### Using Markdown syntax

Webpages can be written in _HTML_ or _Markdown_. This example uses Markdown, which is often easier to write and read in its plain text form. See these resources to learn more about Markdown:

- [Markdown overview](https://wwww.markdownguide.org/)
- [Basic Markdown syntax](https://www.markdownguide.org/basic-syntax/)


### Site navigation

Each Markdown and html file in your repository becomes a web page, but pages only appear in the navigation menu if specified in the configuration file. See [Configuring your site](configure-site.md) for more information about the website theme and page titles. 

<ul class="posts">
  {% for post in site.posts %}
    <li>
      <span class="post-date">{{ post.date | date: "%B %e, %Y" }}</span>
      &raquo;
      <a href="{{ post.url | relative_url }}" title="{{ post.title }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
