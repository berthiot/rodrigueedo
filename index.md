---
layout: default
title: Home
description: Welcome to Rodrigue Edo's professional portfolio. Discover my projects, skills, and experience in software development.
---

<section class="hero">
  <div class="hero-content">
    <div class="hero-text">
      <h1 class="hero-title">"Welcome to My Portfolio"</h1>
      <h2 class="hero-subtitle">"I'm Rodrigue Edo"</h2>
      <p class="hero-description">
        "Passionate Software Developer crafting innovative digital solutions with modern technologies and best practices."
      </p>
      <div class="hero-actions">
        <a href="{{ '/about/' | relative_url }}" class="btn btn-primary">Learn About Me</a>
        <a href="{{ '/projects/' | relative_url }}" class="btn btn-secondary">View My Work</a>
      </div>
    </div>
    <div class="hero-image">
      <div class="profile-container">
        <img src="{{ '/assets/img/profile.jpg' | relative_url }}" alt="Rodrigue Edo - Professional Photo" class="profile-photo">
      </div>
    </div>
  </div>
</section>

<section class="skills-overview">
  <div class="wrapper">
    <h2>What I Do</h2>
    <div class="skills-grid">
      <div class="skill-card">
        <h3>Frontend Development</h3>
        <p>Creating responsive and interactive user interfaces with modern frameworks like React, Vue.js, and Angular.</p>
        <div class="tech-tags">
          <span class="tech-tag">JavaScript</span>
          <span class="tech-tag">React</span>
          <span class="tech-tag">Vue.js</span>
          <span class="tech-tag">CSS3</span>
        </div>
      </div>
      
      <div class="skill-card">
        <h3>Backend Development</h3>
        <p>Building robust server-side applications and APIs using Node.js, Python, and various database technologies.</p>
        <div class="tech-tags">
          <span class="tech-tag">Node.js</span>
          <span class="tech-tag">Python</span>
          <span class="tech-tag">REST APIs</span>
          <span class="tech-tag">Databases</span>
        </div>
      </div>
      
      <div class="skill-card">
        <h3>DevOps & Cloud</h3>
        <p>Deploying and managing applications with modern cloud platforms and containerization technologies.</p>
        <div class="tech-tags">
          <span class="tech-tag">Docker</span>
          <span class="tech-tag">AWS</span>
          <span class="tech-tag">CI/CD</span>
          <span class="tech-tag">Git</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="cta">
  <div class="wrapper">
    <h2>Let's Work Together</h2>
    <p>Ready to bring your ideas to life? I'm always excited to take on new challenges and collaborate on innovative projects.</p>
    <a href="{{ '/contact/' | relative_url }}" class="btn btn-primary">Get In Touch</a>
  </div>
</section>