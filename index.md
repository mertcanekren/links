---
layout: default
---

{% for post in site.posts %}

## [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}

{{ post.description }}

{{ post.content }}

---

{% endfor %}
