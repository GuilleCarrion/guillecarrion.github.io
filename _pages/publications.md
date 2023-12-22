---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% for post in site.publications reversed %}
  {%if post.published==true%}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

Preprints
===
{% for post in site.publications reversed %}
  a
  {%if post.published==true%}
  a
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
