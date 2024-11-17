{% for company in site.work_history %}
[{{ company.companyName }}]({{ company.url }}) - *{{ company.startDate }} - {{ company.endDate }}*
{% for role in company.roles %}
{{ role.designation }} ({{ role.role }}) - *{{ role.startDate }} - {{ role.endDate }}*
<ul>
{% for item in role.primaryDeliverables %}
<li> {{item}}</li>
{% endfor %}
{% for item in role.secondaryDeliverables %}
<li> {{item}}</li>
{% endfor %}
</ul>
{% endfor %}
{% unless forloop.last %}<hr/>{% endunless %}
{% endfor %}
