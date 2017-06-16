---
layout: index_layout
---

{% for item in site.list %}
<ul><li><a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a></li></ul>
{% endfor %}
