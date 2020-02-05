---
layout: index
---


# Current Projects

{% for p in site.data.projects.present %}
 <h3> {{ p.name }} </h3>
<p>{% if p.description %} {{ p.description }} {% endif %}</p>
 <ul class="row">
 {% for i in p.projects %}

 <li> <a href="{{ i.url }}" target="_blank"> {{ i.name }}</a></li>
 {% endfor %}
 </ul>
{% endfor %}

# Past Projects

<ul class="row">
{% for p in site.data.projects.past %}
 <li> <a href="{{ p.url }}" target="_blank"> {{ p.name }}</a></li>
{% endfor %}
</ul>
