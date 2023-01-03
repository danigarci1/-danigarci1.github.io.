---
layout: post
title: 'Project One'
---

{% assign image_files = {{ site.github.url }}/assets/img/proj-1/ | where: "jpg", true %}
{% for img in image_files %}
{% include image.html image="projects/proj-1/{{img}}.jpg" %}
{% endfor %}
