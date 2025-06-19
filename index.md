---
layout: default
title: "Ayham Zahabi"
---

<div class="intro">
  <h1>Hi, I'm Ayham Zahabi</h1>
  <p>I’m a Computer Engineer passionate about embedded systems, robotics, and electronics.</p>
</div>

## About Me

write stuff here about yourself, accomplishments, experiences, etc.

<h2>Projects</h2>
<div class="card-grid">
  {% for post in site.posts %}
    <a href="{{ post.url | relative_url }}" class="card">
      <img src="{{ post.thumbnail | relative_url }}" alt="Thumbnail">
      <div class="card-content">
        <h3>{{ post.title }}</h3>
      </div>
    </a>
  {% endfor %}
</div>

<footer>Contact me: email here, linkedin here</footer>
