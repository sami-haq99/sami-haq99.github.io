---
layout: archive
title: "All Projects"
permalink: /projects_full/
author_profile: true
---

This is a list of all my projects; please visit [here](/projects/) for a list of selected projects.

{% include base_path %}

# Computer Science

{% for post in site.projects reversed %}
  {% if post.type == 'cs' %}
    {% include archive-single-mine.html %}
  {% endif %}
{% endfor %}

# Microcontroller Unit

{% for post in site.projects reversed %}
  {% if post.type == 'ee' %}
    {% include archive-single-mine.html %}
  {% endif %}
{% endfor %}