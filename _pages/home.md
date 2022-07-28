---
title: "Huang Jia - Home"
layout: homelay
excerpt: " "
sitemap: false
permalink: /
---

<!-- Timeline 
------
- [0X-0X-2022]  &ldquo;A few significant things and assignments&rdquo; is accomplished!
- [03-01-2022]  <b> Start creating personal homepage and learning records -->


------
### About me
I am a Master student who majors in the Control Engineering at the Department of Automation,Shanghai Jiao Tong University. My current research interests lie in Systems and Control Theory, Formal Methods, Discrete-Event Systems and Industrial Control Safety and Security.

### Education 
- M.S. in Electronic Information, Shanghai Jiao Tong University, Sept. 2020 - Mar. 2023
- B.S. in Mechatronic Engineering, Xihua University, Sept. 2015 - Jun. 2019

### Research Interests 
Systems and Control Theory, Formal Methods, Discrete-Event Systems, Industrial Control Safety and Security

------
### MY homepage
One of the  projects back from my job-proposal is to develop nanofabricated STM tips. 

The idea behind these “smart tips” is to use the technologies that were developed over decades in nanofabrication and make them available for scanning probe by using a nano-device instead of the traditional STM tungsten tip.

One gains the flexibility of using different functionalities that are known from the fields of nanofabrication and mesoscopic physics. We are collaborating with the group Simon Groeblacher at TU Delft to realize this concept, benefitting from their unparalleled micro/nano fabrication know how.  A prototype of a smart tip is shown to the left. See publications in Microsyst Nanoeng, Nanotechnology, and PRB.

------
### DEMO 
We are a dynamic research group at the [Leiden Institute of Physics](http://www.physics.leidenuniv.nl). Our aim is to explore and understand [quantum materials](http://condensedconcepts.blogspot.nl/2013/05/what-is-quantum-matter.html), including strange metals, high-temperature superconductors, and quantum critical electron matter.

------


{% for member in site.data.pi %}

<div class="row">
  <img src="{{ site.url }}{{ site.baseurl }}/images/profile.jpg" class="img-responsive" width="30%" style="float: left" />
  <h3>{{ member.name }}</h3>
  <i style="font-size:20px">{{ member.info }}</i><br>

  {% if member.website %}<a href="{{ member.website }}" target="_blank"><i class="fa fa-home fa-3x"></i></a> {% endif %}
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
  {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %}
  {% if member.cv %} <a href="{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> {% endif %}
  {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-3x"></i></a> {% endif %}
  {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-3x"></i></a> {% endif %}
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  {% if member.number_educ == 6 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  <li> {{ member.education6 }} </li>
  {% endif %}

  </ul>
</div>

{% endfor %}

## Sketch

Dr. Ethan Pickering investigates chaotic systems of engineering interest that exhibit rare and extreme events. He is currently a postdoctoral associate in Mechanical Engineering at the Massachusetts Institute of Technology, working with Themis Sapsis and collaborating with numerous institutions that cover state of the art computational, experimental, and theoretical abilities.

{% if site.data.awards %}
## Awards

{% for award in site.data.awards %}
* {{ award.name }}
{% endfor %}

{% endif %}

{% if site.data.grants %}
## Grants

{% for grant in site.data.grants %}
* {{ grant.name }}
{% endfor %}

{% endif %}

## Collaborators

* <a href="http://colonius.caltech.edu/" target="_blank">Professor Tim Colonius (Department of Mechanical and Civil Engineering, Caltech)</a>
* <a href="https://www.imperial.ac.uk/people/g.rigas" target="_blank">Professor Georgios Rigas (Department of Aeronautics, Imperial College London)</a>
* <a href="http://flowphysics.ucsd.edu/" target="_blank">Professor Oliver Schmidt (Department of Mechanical and Aerospace Engineering, UC San Diego)</a>
* <a href="http://atowne.com/" target="_blank">Professor Aaron Towne (Department of Mechanical Engineering, University of Michigan)</a>
* <a href="https://scholar.google.fr/citations?user=X7P6FUEAAAAJ&hl=fr" target="_blank"> Dr. Peter Jordan (Institut Pprime, CNRS, Universit ́e de Poitiers )</a>
* <a href="http://denissipp.free.fr/" target="_blank"> Dr. Denis Sipp (Research Director at ONERA)</a>
* <a href="http://www.ita.br/~cavalieri" target="_blank"> Professor Andre Cavalieri (Engenharia Aeronáutica, Instituto Tecnológico de Aeronáutica)</a>
* <a href="https://www.cascadetechnologies.com/" target="_blank"> Dr. Guillaume Brès (Director of Operations and Senior Research Scientist, CASCADE Technologies)</a>
