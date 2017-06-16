---
layout: index_layout
---

{% for item in site.contributions.navigation.yml %}
<ul><li><a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a></li></ul>
{% endfor %}
