---
layout: home
---
# Ghaleb0x317374.github.io
## My Blog

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
