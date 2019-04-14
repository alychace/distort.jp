---
layout: default
title: archives
---

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <h2><a class="post-title" href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title | downcase}}</a></h2>
      <p class="post-meta">{% include post-metadata.html %}</p>
      <p>{{ post.description }}</p>
    </li>
  {% endfor %}
</ul>