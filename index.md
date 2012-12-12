---
layout: page
title: Casey Watts
tagline: Systems Optimizer
---

Casey Watts likes to `optimize systems`.

He likes `technology`, `healthcare`, `coding`, `dancing`, `singing`, and `lolling`.

----
{% for post in site.posts %}
<a href="{{ BASE_PATH }}{{ post.url }}">
<div class="posttitle">
{{ post.title }}<span class="datesnip">{{ post.date | date_to_string }}</span>
</div>
<div class="postsubtitle">
  {{ post.subtitle }}
</div>
</a>
----
{% endfor %}
