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

<section class="projects-overview">
  <div class="wrapper">
    <h2>My Projects & Achievements</h2>
    <div class="projects-grid">
      <div class="skill-card">
        <h3>Healthcare Appointment Scheduler & Patient Portal</h3>
        <p>Built a cross-platform system for medical institutes with multi-provider calendars, patient self-booking, secure portal, automated reminders, insurance checks, telemedicine, and analytics. Designed for compliance, scalability, and seamless experience.</p>
        <div class="tech-tags">
          <span class="tech-tag">React</span>
          <span class="tech-tag">React Native</span>
          <span class="tech-tag">FastAPI</span>
          <span class="tech-tag">PostgreSQL</span>
          <span class="tech-tag">Redis</span>
          <span class="tech-tag">Twilio</span>
          <span class="tech-tag">Docker</span>
          <span class="tech-tag">Authentication</span>
          <span class="tech-tag">Calendar API</span>
          <span class="tech-tag">HIPAA</span>
        </div>
      </div>
      <div class="skill-card">
        <h3>Real-Time Task Queue System</h3>
        <p>Architected and delivered a distributed task queue platform using FastAPI, Python, RabbitMQ, and Redis. Implemented robust RESTful APIs for task submission, asynchronous workers for scalable processing, and real-time status updates with Redis pub/sub. Ensured reliability with Dockerized deployment and automated monitoring.</p>
        <div class="tech-tags">
          <span class="tech-tag">FastAPI</span>
          <span class="tech-tag">Python</span>
          <span class="tech-tag">RabbitMQ</span>
          <span class="tech-tag">Redis</span>
          <span class="tech-tag">Docker</span>
          <span class="tech-tag">REST API</span>
        </div>
      </div>
      <div class="skill-card">
        <h3>Data Analytics Pipeline</h3>
        <p>Designed and implemented a scalable analytics pipeline using PyFlink for real-time and batch data processing. Integrated PostgreSQL for structured data ingestion and MongoDB for flexible reporting. Automated ETL workflows, data validation, and dashboarding with Grafana. Deployed on Docker and orchestrated with Kubernetes for high availability.</p>
        <div class="tech-tags">
          <span class="tech-tag">PyFlink</span>
          <span class="tech-tag">PostgreSQL</span>
          <span class="tech-tag">MongoDB</span>
          <span class="tech-tag">ETL</span>
          <span class="tech-tag">Grafana</span>
          <span class="tech-tag">Kubernetes</span>
          <span class="tech-tag">Docker</span>
        </div>
      </div>
      <div class="skill-card">
        <h3>Learning Management System API</h3>
        <p>Led the extension of a Django-based LMS with FastAPI microservices for modular course management and user progress tracking. Integrated Redis for real-time notifications and PostgreSQL for transactional data. Implemented JWT authentication, role-based access, and CI/CD pipelines for automated testing and deployment.</p>
        <div class="tech-tags">
          <span class="tech-tag">FastAPI</span>
          <span class="tech-tag">Django</span>
          <span class="tech-tag">PostgreSQL</span>
          <span class="tech-tag">Redis</span>
          <span class="tech-tag">JWT Auth</span>
          <span class="tech-tag">CI/CD</span>
        </div>
      </div>
      <div class="skill-card">
        <h3>Banking System Microservices</h3>
        <p>Architected and delivered secure banking microservices for account management, transaction processing, and notifications using FastAPI, Django, RabbitMQ, and PostgreSQL. Implemented OAuth2 authentication, audit logging, and automated unit/integration testing. Deployed with Docker and monitored with Prometheus for reliability and compliance.</p>
        <div class="tech-tags">
          <span class="tech-tag">FastAPI</span>
          <span class="tech-tag">Django</span>
          <span class="tech-tag">RabbitMQ</span>
          <span class="tech-tag">PostgreSQL</span>
          <span class="tech-tag">OAuth2</span>
          <span class="tech-tag">Prometheus</span>
          <span class="tech-tag">Docker</span>
        </div>
      </div>
    </div>
  </div>

<section class="cta">
  <div class="wrapper">
    <h2>Let's Work Together</h2>
    <p>Ready to bring your ideas to life? I'm always excited to take on new challenges and collaborate on innovative projects.</p>
    <a href="{{ '/contact/' | relative_url }}" class="btn btn-primary">Get In Touch</a>
  </div>
</section>