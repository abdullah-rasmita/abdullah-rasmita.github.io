---
layout: page
title: Posts
permalink: /posts/
---

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url | relative_url }})**  
  <small>{{ post.date | date: "%b %-d, %Y" }}</small>
{% endfor %}
