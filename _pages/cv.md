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
* Bsc in Mathematics, Universidad de Málaga, 2015
* Master in Mathematics, Universidad de Málaga, 2016
* Ph.D in Mathematics, Universitat Autònoma de Barcelona, 2023

Work experience
======
* October 2023 - Now: Postdoc at Universidad de Málaga.

* July 2018 - April 2023: Predoctoral Researcher at Universitat Autònoma de Barcelona (FPI)
  

Publications
======
  <ul>{% for post in site.publications %}
    {%if post.venue %}
      {% include archive-single-cv.html %}
    {%endif%}
  {% endfor %}</ul>

Preprints
======
  <ul>{% for post in site.publications %}
  {%if post.unpublished %}
      {% include archive-single-cv.html %}
  {%endif%}
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
  
