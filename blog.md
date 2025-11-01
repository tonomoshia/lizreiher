---
layout: default
title: Blog
---

# Blog

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

---
{% endfor %}
