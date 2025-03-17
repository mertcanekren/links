---
layout: default
---

{% for post in site.posts %}

## {{ post.title }} - {{ post.date | date: "%d-%m-%Y" }}

{{ post.description }}

{{ post.content }}

---

{% endfor %}
