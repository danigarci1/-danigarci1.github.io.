---
layout: post
title: 'Project One'
---

{% for img in {{ site.github.url }}/assets/img/proj-1/ %}
    {% include image.html image="projects/proj-1/{{img}}.jpg" %}
{% endfor %}
