---
layout: page
title: Prose and Poetry
subtitle: The blog of Valentin Peretroukhin
permalink: /blog/
---

<div class="pretty-links">

<div class="lead lead-about">Writing is tough. Ideas seem profound until one writes them down. Often the ostensibly deep, complex thought is turned into a nebulous soup of trivialities and trite clichés. But, nevertheless, the writer presses on, constantly searching for that rush of excitement that comes from reading one's own words and thinking, 'that's...that's pretty good.' Here are my attempts.
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

