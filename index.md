---
layout: default
description: Experiments in fluidity.
thumbnail: index.png
desco: "I'm a PhD student studying film & media, but here I'll write about more: anarchism, capitalism, cybernetics, gender, programming, philosophy, and whatever else comes to mind."
---


"There are and will be those who think I have gone overboard. Let them rest assured that this assessment is correct, probably beyond their wildest imagination, and that I will continue to do so." --- Mary Daly.

"Women diffuse themselves according to modalities scarcely compatible with the framework of ruling symbolics. Which doesn't happen without causing some turbulence, we might even say some whirlwinds..." --- Luce Irigaray.

"This sex which was never one is not an empty zero but a cipher. A channel to the blank side, to the dark side, to the other side of the cycle...to doomsday..." --- Ccru.

## Archives
<hr class="separator">
<ul class="post-list">
{% assign count = site.posts | size | minus: 1 %}
{% for post in site.posts %}
<li>[{{ count }}] <a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}.</a><!-- <div class="post-meta">{{ post.date | date: '%-d %B %Y' | downcase }}</div> --></li>

{% assign count = count | minus: 1 %}
{% endfor %}
</ul>
<hr class="separator">