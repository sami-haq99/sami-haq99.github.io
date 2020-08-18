---
layout: archive
title: "Selected Projects"
permalink: /projects/
author_profile: true
---

This is a list of selected projects; please visit [here](/projects_full/) for a full list.

{% include base_path %}

{% for post in site.projects reversed %}
  {% if post.selected %}
    {% include archive-single-mine.html %}
  {% endif %}
{% endfor %}
