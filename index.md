---
layout: page
title: Casey Watts
tagline: Systems Optimizer
---
{% include JB/setup %}

Casey Watts likes to `optimize systems`.

He likes `technology`, `healthcare`, `coding`, `dancing`, `singing`, and `lolling`.

He writes about

<ul class="tag_box inline">
  {% assign tags_list = site.tags %}  
  {% include JB/tags_list %}
</ul>

----
{% for post in site.posts %}
<a href="{{ BASE_PATH }}{{ post.url }}">
<div class="posttitle">
{{ post.title }}<span class="datesnip">{{ post.date | date_to_string }}</span>
</div>
<div class="postsubtitle">
  {{ post.tagline }}
</div>
</a>
----
{% endfor %}
