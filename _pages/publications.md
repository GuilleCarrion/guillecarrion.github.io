---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



{% for post in site.posts reversed %}
Preprints
====
  {% include archive-single.html %}
{% endfor %}
