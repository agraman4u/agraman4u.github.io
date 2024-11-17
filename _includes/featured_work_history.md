### Work History
{% for company in site.work_history %}
[{{ company.companyName }} - *{{ company.startDate }} - {{ company.endDate }}*]({{ company.url }}) 
{% for role in company.roles %}
* {{ role.designation }} ({{ role.role }}) - *{{ role.startDate }} - {{ role.endDate }}*
{% endfor %}
{% endfor %}
