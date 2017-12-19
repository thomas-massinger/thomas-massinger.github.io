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
* Ph.D Physics, Syracuse University, 2016
  * Thesis: Detector Characterization for Advanced LIGO
  * Advisor: Peter Saulson
* B.S. Physics, Utica College, 2011
* B.A. Mathematics, Utica College, 2011

Work experience
======
* Postdoctoral Scholar, Caltech 
  * August 2016 - Present

* Research Assistant, Syracuse University
  * August 2012 - August 2016
  
Programming experience
======
* Python (numpy, scipy, pandas, Keras, Tensorflow)
* C/C++
* Bash
* MATLAB/Simulink

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
