---
layout: default
title: Blog
---

# Latest Posts

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url | absolute_url }})
{{ post.excerpt }}
{% endfor %}
