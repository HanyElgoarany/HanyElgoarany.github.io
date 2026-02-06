---
layout: home
title: Home
---

<main id="main-content">

  <!-- Home Section -->
  <section id="home-section">
    <h2>Welcome</h2>
    <p>Hi, I’m {{ site.title }}! This is my technical portfolio showcasing my projects and work.</p>
  </section>

  <!-- Projects Section -->
  <section id="projects-section" style="display:none;">
    <h2>Projects</h2>
    <ul>
      {% for project in site.projects %}
      <li>
        <a href="{{ project.url }}">{{ project.title }}</a> - {{ project.description }}
      </li>
      {% endfor %}
    </ul>
  </section>

</main>
