---
layout: page
title: Essays
order: 3
---

<div class="posts">
  {% for post in site.posts %}
    <div class="post">
    <h3 class="post-title-list"> <a href="{{ post.url }}">{{ post.title }}</a></h3>
    <span class="post-date">{{ post.date | date_to_string }}</span>
    {{ post.content }}
    </div>
  {% endfor %}
</div>
