---
layout: post
category : programming
tags : [github]
---


# Code Swarm

It's so pretty!
You can see how rails progress really spiked when they switched to github: `http://vimeo.com/2979844`


I cloned this, set it up etc:

{% highlight html %}
https://github.com/rictic/code_swarm
{% endhighlight %}

I had to revert this commit to make it work (put a note on their wiki page to say so; I don't know enough python to fix it myself)
{% highlight html %}
https://github.com/rictic/code_swarm/commit/f15334b162bd0f3f939f3879fbec1935bd094c8c
{% endhighlight %}


Then I ran code_swarm once

Then I edited the .config file (after running it once) so that it would record frames

`# Save each frame to an image?
TakeSnapshots=true`

Then I followed these instructions to create the video (using ffmpeg, because that's what I had already):
http://code.google.com/p/codeswarm/wiki/GeneratingAVideo

`ffmpeg -f image2 -r 24 -i %05d.png -sameq ./out.mov -pass 2`

It looks like there's a command `code_swarm_video` that would generate a
video more easily, but it requires `mencoder` which I never got working.
