<ul>
{% for project in site.projects %}
<li><span><a href="{{ project.url }}">{{ project.title }}</a> - <small>{{ project.short_description }}</small></span></li>
{% endfor %}
</ul>
