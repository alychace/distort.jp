---
layout: default
description: Writings on cyberculture, horror, technology, capitalism, gender, and whatever else comes to mind.
thumbnail: index.png
---

Welcome to NecroSystems.

This is a blog, written by me of course. I'm a PhD student studying film & media, but here I'll write about more: anarchism, capitalism, cybernetics, gender, programming, philosophy, and whatever else comes to mind.

Feel free to follow me on [Twitter](http://twitter.com/{{site.twitter}}).

## Archives
<hr class="separator">
<ul class="post-list">
{% assign count = site.posts | size | minus: 1 %}
{% for post in site.posts %}
<li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">[{{ count }}] {{ post.title }}.</a><!-- <div class="post-meta">{{ post.date | date: '%-d %B %Y' | downcase }}</div> --></li>

{% assign count = count | minus: 1 %}
{% endfor %}
</ul>
<hr class="separator">