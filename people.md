---
layout: index
color: "#de24c7"
---

# People in the Group

<div id="photo-container"></div>

### Ph.D. Alumni

* <a href="http://www.mathcs.emory.edu/~eugene/" target="_blank">Eugene Agichtein</a> (current employment: Associate Professor, <a href="http://www.mathcs.emory.edu/" target="_blank">Department of Mathematics and Computer Science, Emory University</a>) 
* <a href="http://www.cs.columbia.edu/~pjbarrio" target="_blank">Pablo Barrio</a> (current employment: Software Engineer, <a href="http://www.google.com/" target="_blank">Google</a>)
* <a href="http://www.cs.columbia.edu/~hila" target="_blank">Hila Becker</a> (current employment: Software Engineer, <a href="http://www.google.com/" target="_blank">Google</a>)
* <a href="http://www.cs.columbia.edu/~nicolas/" target="_blank">Nicolas Bruno</a> (current employment: Software Engineer, <a href="http://www.google.com/" target="_blank">Google</a>)
* <a href="http://www.dmst.aueb.gr/damianos/" target="_blank">Damianos Chatziantoniou</a> (current employment: Associate Professor, <a href="http://www.dmst.aueb.gr/index.php/el/" target="_blank"> Department of Management Science and Technology, Athens University of Economics and Business</a>)
* <a href="http://www.cs.columbia.edu/~johnc" target="_blank">John Cieslewicz</a> (current employment: Software Engineer, <a href="http://www.google.com/" target="_blank">Google</a>)
* <a href="http://www.cs.columbia.edu/~wisam" target="_blank">Wisam Dakka</a> (current employment: Software Engineer, <a href="http://www.snap.com/en-US/" target="_blank">Snapchat</a>)
* <a href="http://pages.stern.nyu.edu/~panos/" target="_blank">Panagiotis Ipeirotis</a> (current employment: Professor, <a href="http://www.stern.nyu.edu/" target="_blank">Stern School of Business, New York University</a>)
* <a href="http://www.cs.columbia.edu/~alpa" target="_blank">Alpa Jain</a> (current employment: Software Engineer, <a href="http://www.google.com/" target="_blank">Google</a>)
* <a href="http://www-cs.engr.ccny.cuny.edu/~akira" target="_blank">Akira Kawaguchi</a> (current employment: Professor and Chair, <a href="http://www.ccny.cuny.edu/compsci/" target="_blank"> Department of Computer Science, City College of New York</a>)
* Zhe Li
* <a href="http://www.cs.rutgers.edu/~amelie/" target="_blank">Amelie Marian</a> (current employment: Associate Professor, <a href="http://www.cs.rutgers.edu/" target="_blank">Department of  Computer Science, Rutgers University</a>) 
* <a href="http://www.cs.columbia.edu/~orestis" target="_blank">Orestis Polychroniou</a> (current employment: Software Engineer, <a href="http://aws.amazon.com/" target="_blank">Amazon Web Services</a>)
* <a href="http://www.cs.columbia.edu/~junr/" target="_blank">Jun Rao</a> (current employment: Co-Founder, <a href="http://www.confluent.io/" target="_blank">Confluent</a>)
* <a href="https://fenix.tecnico.ulisboa.pt/homepage/ist155840" target="_blank">Gonçalo Simoes</a> (current employment: Software Engineer, <a href="http://www.google.com/" target="_blank">Google</a>)
* <a href="http://www.cs.columbia.edu/~eva/" target="_blank">Eva Sitaridi</a> (current employment: Software Engineer, <a href="http://aws.amazon.com/redshift/" target="_blank">Amazon RedShift</a>)
* <a href="https://www.cs.drexel.edu/~julia/" target="_blank">Julia Stoyanovich</a> (current employment: Associate Professor, <a href="http://drexel.edu/cci/departments/computer-science/" target="_blank">College of Computing & Informatics, Drexel University</a>)
* <a href="https://sites.google.com/site/kazizaman/" target="_blank">Kazi Zaman</a> (current employment: Vice President of Engineering, <a href="http://www.ea.com/" target="_blank">Electronic Arts</a>)
* <a href="http://www.cs.columbia.edu/~jrzhou/" target="_blank">Jingren Zhou</a> (current employment: Vice President, <a href="http://www.alibabagroup.com/" target="_blank">Alibaba Group</a>)


### Other Alumni

* Shu-Wie Chen
* <a href="http://users.atlantis.ugent.be/cdvelder/" target="_blank">Chris Develder</a>
* Junyan Ding
* Ioannis Giannakakis
* Pankaj Kulkarni
* Hui Lei
* Lei Liu
* William Mee
* Anurag Singla
* <a href="http://www.cs.columbia.edu/~solomon/" target="_blank">Matthew Solomon</a>
* <a href="http://www.cs.columbia.edu/~yeyang/" target="_blank">Yang Ye</a>
* Xiaoning Zhang






{% raw %}
<script id="entry-template" type="text/x-handlebars-template">
  {{#each rows}}
    <h3>{{{type}}}</h3>
    <ul class="row">
    {{#each people}}
    <li class="col-lg-4 col-md-4 col-sm-4 col-xs-4 person" style="">
      <div class="photo" style="background-image:url(./files/images/members/{{{img}}}.jpg); '"></div>
      <div>
        <a href="{{#if url}}{{url}}{{else}}#{{/if}}" target="_blank"> {{{name}}} </a>
      </div>
    </li>
    {{/each}}
    </ul>
  {{/each}}
</script>




<script>
    var data = {
      rows: [
      {
        type: "Faculty",
        people: [
          {
            url: "http://www.cs.columbia.edu/~gravano",
            img: "1",
            name: "Luis Gravano"
          },
          {
            url: "http://www.cs.columbia.edu/~kar",
            img: "2",
            name: "Kenneth Ross"
          },
          {
            url: "http://www.eugenewu.net",
            img: "41",
            name: "Eugene Wu"
          },
          {
            url: "http://www.cs.columbia.edu/~mihalis",
            img: "11",
            name: "Mihalis Yannakakis"
          },
         ]
      },
      {
        type: "Ph.D. Students",
        people: [
          {
            url: "http://teffland.github.io/",
            img: "tom",
            name: "Tom Effland"
          },
          {
            url: "#", //http://teffland.github.io/",
            img: "lampros",
            name: "Lampros Flokas"
          },
          {
            url: "#", //"http://teffland.github.io/",
            img: "giannis",
            name: "Giannis Karamanolakis"
          },
          {
            url: "http://www.cs.columbia.edu/~jopa/",
            img: "4",
            name: "Ioannis Paparrizos"
          },
          {
            url: "http://www.cs.columbia.edu/~fotis",
            img: "3",
            name: "Fotis Psallidas"
          },
          {
            url: "http://zwd.nyc",
            img: "39",
            name: "Wangda Zhang"
          },
          {
            url: "http://haneensa.github.io/",
            img: "haneen",
            name: "Haneen Mohammed"
          },
          {
            url: "http://yiliangs.com/",
            img: "yiliangs",
            name: "Yiliang Shi"
          },
          {
            url: "https://ireneruru.github.io/",
            img: "yiru",
            name: "Yiru Chen"
          },
         ]
      },
      {
        type: "Postdocs",
        people: [
          {
            url: "http://sellam.me",
            img: "thibault",
            name: "Thibault Sellam"
          },
         ]
      }
      ]
    };
    var source   = $("#entry-template").html();
    var template = Handlebars.compile(source);
    $("#photo-container").html(template(data));

</script>

{% endraw %}
