---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% for post in site.publications reversed %}
  {%if post.published==true%}
  {% include archive-single.html %}
{% endfor %}

Preprints
===
{% for post in site.publications reversed %}
  {%if post.published!=true%}
  {% include archive-single.html %}
{% endfor %}
