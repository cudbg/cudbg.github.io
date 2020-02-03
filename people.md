---
layout: index
color: "#de24c7"
---

# People in the Group

<div id="photo-container">
  
{% for p in site.data.people.present %}
<h3>{{ p.rule }}</h3>
<ul class="row">
 {% for i in p.ppl %}
    <li class="col-lg-4 col-md-4 col-sm-4 col-xs-4 person" style="">
      <div class="photo" style="background-image:url(./files/images/members/{{i.img}}.jpg); '"></div>
      <div>
        <a href="{{i.url}}" target="_blank"> {{i.name}} </a>
      </div>
    </li>
 {% endfor %}
 </ul>
{% endfor %}

</div>

### Ph.D. Alumni

<ul>
{% for p in site.data.people.alumni %}
<li><a href="{{ p.url }}" target="_blank">{{ p.name }}</a>
{% if p.status %}, current employment: {{ p.status }} {% endif %}</li>
{% endfor %}
</ul>
