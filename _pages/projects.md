---
layout: archive
title: "Engineering Projects"
permalink: /projects/
author_profile: true
---

This portfolio highlights selected mechanical engineering, manufacturing, robotics, simulation, and research projects. The collection will continue to be expanded with additional professional and research work.

{% include base_path %}

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
