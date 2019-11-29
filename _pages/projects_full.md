---
layout: archive
title: "All Projects"
permalink: /projects_full/
author_profile: true
---

This is a list of all my projects; please visit [here](/projects/) for a list of selected projects.

{% include base_path %}

# Computer Science

{% for post in site.projects_cs reversed %}
  {% include archive-single-mine.html %}
{% endfor %}

# Microcontroller Unit

{% for post in site.projects_mcu reversed %}
  {% include archive-single-mine.html %}
{% endfor %}