---
layout: index
---

# Courses Offered by the Database Research Group

<div>
{% for p in site.data.courses.present %}
    <h3>
        <a href="{{p.url}}" target="_blank"> {{p.name}} </a>
    </h3>
   <p>{{p.details}}</p>
{% endfor %}
</div>

# Past Courses 

<div>
{% for p in site.data.courses.past %}
    <h3>
        <a href="{{p.url}}" target="_blank"> {{p.name}} </a>
    </h3>
   <p>{{p.details}}</p>
{% endfor %}
</div>

