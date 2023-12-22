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
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
