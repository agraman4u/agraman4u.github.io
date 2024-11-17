### Projects

<ul>
{% for project in site.projects %}
{% if project.is_featured %}
<li><span><a href="{{ project.url }}">{{ project.title }}</a> - <small>{{ project.short_description }}</small></span></li>
{% endif %}
{% endfor %}
</ul>
