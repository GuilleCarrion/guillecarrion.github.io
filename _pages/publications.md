---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% for post in site.publications reversed %}
  {%if post.venue %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

Preprints
===
{% for post in site.publications reversed %}
  a
  {%if post.unpublished %}
  a
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
