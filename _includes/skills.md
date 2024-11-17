### Skills

{% for skill in site.skills %}
- **{{ skill.label }}** - {% for item in skill.items %} {{ item.label }}{% unless forloop.last %}, {% endunless %}{% endfor %}
{% endfor %}