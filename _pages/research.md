---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

# Natural Language Processing

{% for post in site.research_nlp reversed %}
  {% include archive-single-mine.html %}
{% endfor %}

# Computer Vision

At USTC, my research is mainly about computer vision.

In Sep. 2019, I joined [National Engineering Laboratory for Speech and Language Information Processing](http://nelslip.ustc.edu.cn/) (NEL-SLIP) (supervised by Prof. [Jun Du](http://staff.ustc.edu.cn/~jundu/The%20team.html)) and explored several different topics including text detection, object detection and text recognition.

In Apr. 2020, I joined MOE-Microsoft Key Laboratory of Multimedia Computing and Communication (supervised by Prof. [Weiping Li](http://dsxt.ustc.edu.cn/zj_ywjs.asp?zzid=1565) and studied No-Reference Video Quality Assessment.

{% for post in site.research_cv reversed %}
  {% include archive-single-mine.html %}
{% endfor %}