---
layout: home
title: Home
---

<main id="main-content">

  <!-- Home Section -->
  <section id="home-section">
    <h2>Welcome</h2>
    <p>Hi, I’m {{ site.title }}! I'm a Technical Professional currently interested in imaging, deployments, and automation. This is my technical portfolio showcasing my projects and write-ups.</p>
  </section>

  <!-- Projects Section -->
  <section id="projects-section" style="display:none;">
    <h2>Projects</h2>
    <ul>
      {% assign sorted_projects = site.projects | sort: "date" | reverse %}
      {% for project in sorted_projects %}
        <li>
          <a href="{{ project.url }}">{{ project.title }}</a> - {{ project.description }}
        </li>
      {% endfor %}
    </ul>
  </section>

</main>
