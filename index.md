---
layout: page
title: Casey Watts
tagline: Systems Optimizer
---

Casey Watts likes to optimize systems. He likes technology, healthcare,
coding, dancing, singing, and lolling.
 
## List of Posts

<ul class="posts">
  {% for post in site.posts %}
    <li class="postlist"><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>{{ post.content }}</li>
    {% endfor %}
</ul>
