---
layout: default
---
{% for post in site.posts %}
  <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
  {{ post.content }}
{% endfor %}