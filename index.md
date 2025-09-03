---
layout: home
title: "My ITSM Journey"
---

# Welcome to My Digital Home

This is my IT Service Management (ITSM) journey! Here you'll find all my assignments, labs, reflections, and projects throughout the semester. Each milestone represents a 'room' in my house, showcasing my growth in IT Service Management.

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}
{% endfor %}
