---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can find my CV [here](http://izabelcavassim.github.io/files/MICA_CV_2022_February.pdf).

Education
======
* B.S. in Agriculture Engineering, University of Sao Paulo, 2014
* M.S. in Bioinformatics, Aarhus University, 2018
* Ph.D in Bioinformatics, Aarhus University, 2020

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
  
Service and leadership
======
* Currently contributing to the development of a standard library of population
genetic models.
* Providing computational research support to projects initiated by
experimentalists at UCLA while also training researchers in Bioinformatics
and population genetics through the [QCBioCollaboratory](https://qcb.ucla.edu/collaboratory/people/).
