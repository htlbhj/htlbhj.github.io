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
======
* Ph.D in Statistics, The Chinese University of Hong Kong, 2015
* B.S. in Statistics, Peking University, 2011

Work experience
======
* Fall 2021: Associate Professor
  * Xiamen University

* Fall 2015: Assistant Professor
  * Xiamen University

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
