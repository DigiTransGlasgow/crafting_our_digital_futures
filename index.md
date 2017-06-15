---
layout: default
---

{% for item in site.collections.docs %}
<ul><li><a href="{{ item.url.name }}">{{ item.title }}</a></li></ul>
{% endfor %}
