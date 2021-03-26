---
title: "Ein Leben ohne Sucht?"
layout: home
---  

{% assign sections = site.sections | sort: 'order' %}
{% for section in sections %}
  <div style="background:{{ section.background-color }};color:{{ section.foreground-color }};">
  {% include section.html %}
  </div>
{% endfor %}
