---
layout: default
---

<ul class="post-list">
{% assign count = site.posts | size | minus: 1 %}
{% for post in site.posts %}
<li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">[{{ count }}] {{ post.title }}.</a><!-- <div class="post-meta">{{ post.date | date: '%-d %B %Y' | downcase }}</div> --></li>

{% assign count = count | minus: 1 %}
{% endfor %}
</ul>