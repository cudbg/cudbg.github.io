---
layout: index
---

<div class="hcontain">
 <div class="gallery">
  <figure class="gallery__item gallery__item--11">
    <img src="./files/images/members/1.jpg" class="gallery__img">
  </figure>
  <figure class="gallery__item gallery__item--12">
    <img src="./files/images/members/2.jpg" class="gallery__img">
  </figure>
  <figure class="gallery__item gallery__item--13">
    <img src="./files/images/members/41.jpg" class="gallery__img">
  </figure>
  <figure class="gallery__item gallery__item--14">
    <img src="./files/images/members/lampros.jpg" class="gallery__img">
  </figure>
  <figure class="gallery__item gallery__item--15">
    <img src="./files/images/members/giannis.jpg" class="gallery__img">
  </figure>


  <figure class="gallery__item gallery__item--21">
    <img src="./files/images/members/haneen.jpg" class="gallery__img">
  </figure>
  <figure class="gallery__item gallery__item--22">
    <img src="./files/images/members/yiru.jpg" class="gallery__img">
  </figure>
  <figure class="gallery__item gallery__item--23">
    <img src="./files/images/members/zach.jpg" class="gallery__img">
  </figure>
  <figure class="gallery__item gallery__item--24">
    <img src="./files/images/members/keyang.jpg" class="gallery__img">
  </figure>
  <figure class="gallery__item gallery__item--25">
    <img src="./files/images/members/kim.jpg" class="gallery__img">
  </figure>
 </div>
</div>

# Columbia University Database Research Group

Welcome to the Columbia University Database Research Group! We are interested in high-performance database architectures, web-scale information extraction, social media, data analysis, visualization tools, and database theory.

We are affiliated with the [Department of Computer Science](http://www.cs.columbia.edu) and the [Data Science Institute](http://datascience.columbia.edu).


<!--
## Seminar

The database group holds regular meetings Mondays 3-4:30PM in <a href="http://eugenewu.net/images/map.png" target="_blank">417 Mudd</a>.  We typically discuss a relevant paper or host outside speakers.  If you are interested in attending or speaking <a href="mailto:teffland@cs.columbia.edu" target="_blank">please get in contact with us</a>.

Below is a list of outside speakers.
-->


## News

<ul class="row">
{% for n in site.data.news %}
<li><b>{{ n.date }}</b> : {{ n.news }}</li>
{% endfor %}
</ul> 
