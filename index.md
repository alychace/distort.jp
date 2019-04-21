---
layout: default
---

<ul class="post-list">
{% assign count = site.posts | size | minus:1 %}
{% for post in site.posts %}
<li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">[{{ count }}] {{ post.title | downcase }}</a><p class="post-meta">{{ site.author }} | {{ post.date | date: '%-d %B %Y' | downcase }}</p></li>

{% assign count = count | minus: 1 %}
{% endfor %}
</ul>