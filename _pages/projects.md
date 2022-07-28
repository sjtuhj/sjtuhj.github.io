---
title: "Huang Jia - Projects"
layout: gridlay
excerpt: "Huang Jia - Projects."
sitemap: false
permalink: /projects/
---

# Projects DEMO page

**At the end of this page, you can find the [full list of publications and patents](#full-list-of-publications). All papers are also available on [arXiv](https://arxiv.org/search/?searchtype=author&query=Allan%2C+M+P).**


{% for projli in site.data.projlist %}
{% if projli.highlight == 1 %}

<div class="col-sm-12 clearfix">
 <div class="well">
  <pubtit>{{ projli.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/projpic/{{ projli.image }}" class="img-responsive" width="12%"  style="float: left" />
  <p>{{ projli.description }}</p>
  <p><em>{{ projli.authors }}</em></p>
  <p><strong><a href="{{ projli.link.url }}">{{ projli.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ projli.news1 }}</strong></p>
  <p> {{ projli.news2 }}</p>
 </div>
</div>

{% endif %}
{% endfor %}

<p> &nbsp; </p>


## Patents
<em>Milan P Allan, S Gröblacher, RA Norte, M Leeuwenhoek</em><br />Novel atomic force microscopy probes with phononic crystals<br /> PCT/NL20-20/050797 (2020)

<em>Milan P Allan</em><br /> Methods of manufacturing superconductor and phononic elements <br /> <a href="https://patents.google.com/patent/US10439125B2/en?inventor=Milan+ALLAN&oq=inventor:(Milan+ALLAN)">US10439125B2 (2016)</a>

## Full List of publications

{% for projli in site.data.publist %}

  {{ projli.title }} <br />
  <em>{{ projli.authors }} </em><br /><a href="{{ projli.link.url }}">{{ projli.link.display }}</a>

{% endfor %}
