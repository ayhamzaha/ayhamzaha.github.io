---
layout: default
title: Ayham Zahabi
---

<div class="landing-container">
  <header class="intro">
    <h2>Ayham Zahabi</h2>
    <p>computer engineer passionate about embedded systems and robotics</p>
  </header>

  <section class="about">
    <h3>About me</h3>
    <p>
      bgjbf... (your paragraph text goes here).<br>
      More about your background, interests, and goals.
    </p>
  </section>

  <section class="projects">
    <h3>Projects</h3>
    <div class="project-grid">
      {% for project in site.data.projects %}
      <div class="project-card">
        <img src="{{ project.image | relative_url }}" alt="project image">
        <div class="project-title">{{ project.title }}</div>
      </div>
      {% endfor %}
    </div>
  </section>

  <footer class="contact">
    <p>contact me @ <a href="mailto:youremail@example.com">email</a>, 
    <a href="https://www.linkedin.com/in/your-profile">linkedin</a></p>
  </footer>
</div>
