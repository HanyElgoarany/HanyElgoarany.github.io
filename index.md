---
layout: home
title: Home
---

## About Me

I’m a technical professional currently focused on imaging, deployment, and automation.
This site documents real-world projects, testing, and outcomes.

## Projects

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url }})
  - {{ project.description }}
{% endfor %}
