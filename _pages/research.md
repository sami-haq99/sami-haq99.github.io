---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

This is a list of selected research; please visit [here](/research_full/) for a full list.

{% include base_path %}

# Natural Language Processing

{% for post in site.research_nlp reversed %}
  {% if post.selected %}
    {% include archive-single-mine.html %}
  {% endif %}
{% endfor %}

# Computer Vision

{% for post in site.research_cv reversed %}
  {% if post.selected %}
    {% include archive-single-mine.html %}
  {% endif %}
{% endfor %}
