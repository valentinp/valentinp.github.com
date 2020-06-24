---
layout: page
title: Prose and Poetry
subtitle: The blog of Valentin Peretroukhin
permalink: /blog/
---

<div class="pretty-links">

<div class="lead lead-about"> I like writing. Well, no that's not true. I don't like writing. In fact, I <a href='https://youtu.be/sUMzQ0karAk?t=168'>hate writing</a>. But from time-to-time, something compels me to write. Perhaps you may enjoy the output of those brief moments of inspiration.
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

