---
layout: default
description: Accelerated writings on cybernetics, technology, capitalism, gender, and whatever else comes to mind.
---

Welcome.

This is a blog of sorts. The title is a a reference to the late Mark Fisher's book, *[Ghosts Of My Life](https://thequietus.com/articles/13004-mark-fisher-ghosts-of-my-life-extract)*. [Elsewhere]({{site.homepage}}), I'm a grad student studying film, but here I'll write about more: anarchism, capitalism, cybernetics, gender, programming, philosophy, and whatever else comes to mind.

Feel free to follow me on [Twitter](http://twitter.com/{{site.twitter}}).

## Archives
<ul class="post-list">
{% assign count = site.posts | size | minus: 1 %}
{% for post in site.posts %}
<li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">[{{ count }}] {{ post.title }}.</a><!-- <div class="post-meta">{{ post.date | date: '%-d %B %Y' | downcase }}</div> --></li>

{% assign count = count | minus: 1 %}
{% endfor %}
</ul>