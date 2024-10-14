---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
---

<div class="post-list">
  {% for post in site.posts %}
    <article class="post">
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <div class="post-content">{{ post.excerpt }}</div>
    </article>
  {% endfor %}
</div>


