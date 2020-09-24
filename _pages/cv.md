---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
---
* Ph.D, Australian National University, 2017
* M.Sc, King Abdullah University of Science and Technology, 2010
* B.Appl.Sc., National University of Singapore, 2008

Work experience
---
* 2020 - : Vice Chancellor's Research Fellow
  * University of Wollongong
* 2017-2020: Faculty Fellow
  * Singapore University of Technology and Design
  
Publications
---
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
---
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
---
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
