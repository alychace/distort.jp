---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

{% assign post = site.posts.first %}

<h1>{{ post.title | downcase }}</h1>

{% include post-metadata.html %}

{{ post.content }}