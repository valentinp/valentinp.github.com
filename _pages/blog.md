---
layout: page
title: Blog
subtitle: My thoughts and musings.
desc: Thoughts of a lost graduate student.
permalink: /blog/
---

<div class="pretty-links">

<div class="lead lead-about">Writing is tough. Ideas seem profound until you try to write them down. Often the deep, complex thought is turned into a nebulous soup of trivialities and trite clichés. But, nevertheless, the writer presses on, constantly searching for that rush of excitement that comes from reading one's own prose and thinking, 'damn, that is pretty good.' Here are my attempts.
</div>
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

</div>

