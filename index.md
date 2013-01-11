---
layout: page
title: Casey Watts
tagline: Systems Optimizer
---
{% include JB/setup %}

Casey Watts likes to `optimize systems`.

Casey is Showing Dad

He likes `technology`, `healthcare`, `coding`, `dancing`, `singing`, and `lolling`.

He currently codes using these tools:

- Computer
  - Mac OS X 10.8 Mountain Lion
  - MacVIM + Janus + [many dotfile tweaks](https://github.com/caseywatts/dotfiles)
  - git + github (for everything, including this jekyll-based blog
- Phone
  - Samsung Galaxy S3 + Android 4.1 Jelly Bean
  - Google voice for everything (woo Android!)
  - GMail + Boomerang + GChat
- Languages
  - Ruby on Rails (love rails 3 and pry so much!)
  - Javascript (bookmarklets, using RoR gems)
  - Plenty of HTML/CSS
- Favorite Markups
  - Markdown (for blogging & emailing)
  - Wikitext (for a few 'private, internal wikis')

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
