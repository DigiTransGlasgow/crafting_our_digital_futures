<div class="dropdown">

<div class="container">
<button class="btn btn-primary dropdown-toggle" type="button" data-toggle="dropdown">List
        <span class="caret"></span>
</button>
        <ul class="dropdown-menu">
            <li><a href="#">HTML</a></li>
            <li><a href="#">CSS</a></li>
            <li><a href="#">JavaScript</a></li>
        </ul>
</div>
</div>
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
