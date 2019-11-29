---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

This is a list of selected projects; please visit [here](/projects_full/) for a full list.

{% include base_path %}

# Computer Science

{% for post in site.projects_cs reversed %}
  {% if post.selected %}
    {% include archive-single-mine.html %}
  {% endif %}
{% endfor %}

# Microcontroller Unit

{% for post in site.projects_mcu reversed %}
  {% if post.selected %}
    {% include archive-single-mine.html %}
  {% endif %}
{% endfor %}