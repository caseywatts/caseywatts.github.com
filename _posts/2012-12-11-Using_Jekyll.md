---
layout: post
title: Using Jekyll
tags:
---

## Really liking Jekyll

Jekyll works great for so many things! In particular:

- I enjoy hosting my blog and deploying using git
- I realllly like writing using markdown :)
- I'm totally comfortable modifying CSS in my text editor, and I can do
  that!

But I miss:

- Tumblr-style sharing. Tumblr doesn't really have a community of code-posts
  anyway though.

----

## Still Want Github-Flavored CodeBlocks
I really want to write github-style code blocks, so I tried using this plugin

<pre>https://github.com/nono/Jekyll-plugins</pre>

And it worked great locally! But I couldn't get it to run on github
pages :/

<pre>
  def lol
    puts "lol"
  end
</pre>

Except that it doesn't work on github pages, had to roll back :P

----

## Debugging
Sometimes if you have bad syntax, jekyll won't compile anything. No
changes.

Running this always tells me what's wrong:

<pre>
  jekyll --no-server --no-auto
</pre>
