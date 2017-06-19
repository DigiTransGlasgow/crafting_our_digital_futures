<nav aria-label="...">
  <ul class="pager">
        {% if page.previous.url != nil %}
                <li class="previous"><a href="{{ site.baseurl }}{{ page.previous.url }}"><span aria-hidden="true">&larr;</span> Previous</a></li>
        {% endif %}
        {% if page.next.url != nil %}
                <li class="next"><a href="{{ site.baseurl }}{{ page.next.url }}">Next <span aria-hidden="true">&rarr;</span></a></li>
        {% endif %}
  </ul>
</nav>

---
