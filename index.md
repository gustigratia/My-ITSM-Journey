---
layout: home
title: "My ITSM Journey"
---

# Welcome to My Digital Home

This is my IT Service Management (ITSM) journey! Here you'll find all my assignments, labs, reflections, and projects throughout the semester. Each milestone represents a 'room' in my house, showcasing my growth in IT Service Management.

{% for post in site.posts %}
  <h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt }}</p>
{% endfor %}
