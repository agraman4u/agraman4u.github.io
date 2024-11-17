### Timeline
{% for company in site.work_history %}
[{{ company.companyName }} - *{{ company.startDate }} - {{ company.endDate }}*]({{ company.url }}) 
{% endfor %}