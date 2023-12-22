---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

w/ Jérôme Scherer. Relative plus construction [Download](https://www.sciencedirect.com/science/article/pii/S0723086923000348'))

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


Preprints
====

{% for post in site.posts reversed %}
  {% include archive-single-posts.html %}
{% endfor %}
