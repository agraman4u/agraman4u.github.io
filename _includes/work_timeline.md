### Timeline
{% for company in site.work_history %}
<a href="{{ company.companyUrl }}" target="_blank">{{ company.companyName }}</a> - *{{ company.startDate }} - {{ company.endDate }}*
{% endfor %}