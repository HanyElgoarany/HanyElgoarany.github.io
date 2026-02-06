---
title: Home
---

<main id="main-content">

  <!-- Home Section -->
  <section id="home-section" class="fade-section">
    <p><strong>Welcome!</strong> Hi, I’m {{ site.title }}! This is my technical portfolio showcasing my projects and work.</p>
  </section>

  <!-- Projects Section -->
  <section id="projects-section" class="fade-section hidden">
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

