---
layout: page
title: ""
permalink: /
---

<style>

/* =========================
   HEADER FIX
========================= */
.page__title {
  display: none !important;
}

.site-brand__title {
  color: #111 !important;
}
.hero-bottom {
  padding-top: 50px;
}
.hero {
  background-image: url('/assets/images/background.jpg');
  background-size: cover;
  background-position: center;
  height: 60vh;

  display: flex;
  flex-direction: column;
  justify-content: space-between;

  text-align: center;
  color: white;

  padding: 60px 20px 30px;
  position: relative;
}

/* overlay */
.hero::before {
  content: "";
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.10);
}

.hero > * {
  position: relative;
}

/* TOP */
.hero-top {
  margin-top: 20px;
}

/* BOTTOM */
.hero-bottom {
  display: flex;
  justify-content: center;
  gap: 15px;
  margin-bottom: 20px;
  flex-wrap: wrap;
}

/* BOUTONS EGAL SIZE */
.hero-bottom a {
  display: flex;
  align-items: center;
  justify-content: center;

  width: 180px;
  height: 45px;

  background-color: rgba(0,0,0,0.6);
  color: white;
  text-decoration: none;
  border-radius: 6px;

  font-weight: 500;
  text-align: center;
}

/* =========================
   SECTION
========================= */
.section {
  padding: 60px 20px;
  text-align: left;
}
/* =========================
   LinkedIn blue style
========================= */
   :root {
  --primary: #0a66c2;
  --text: #1f1f1f;
  --muted: #666;
  --line: #e6e6e6;
  --bg: #ffffff;
}

/* SECTION */
.bio-premium {
  background: var(--bg);
  padding-top: 40px;
}

/* TIMELINE WRAPPER */
.bio-premium-timeline {
  max-width: 850px;
  margin: 40px auto;
  position: relative;
  padding-left: 30px;
}

/* LINE */
.bio-premium-timeline::before {
  content: "";
  position: absolute;
  left: 8px;
  top: 0;
  bottom: 0;
  width: 1px;
  background: var(--line);
}

/* ITEM */
.bio-premium-item {
  position: relative;
  margin-bottom: 40px;
}

/* DOT */
.bio-premium-dot {
  width: 10px;
  height: 10px;
  background: var(--primary);
  border-radius: 50%;
  position: absolute;
  left: -5px;
  top: 6px;
}

/* CONTENT */
.bio-premium-content {
  padding-left: 20px;
}

/* ROLE (TITLE) */
.bio-role {
  font-size: 1.05em;
  font-weight: 600;
  color: var(--text);
  margin-bottom: 3px;
}

/* DATE */
.bio-date {
  font-size: 0.85em;
  color: var(--primary);
  margin-bottom: 10px;
  font-weight: 500;
}

/* TEXT */
.bio-text {
  font-size: 0.95em;
  color: var(--muted);
  line-height: 1.6;
  max-width: 700px;
}

/* HOVER (subtil premium feel) */
.bio-premium-item:hover .bio-role {
  color: var(--primary);
  transition: 0.2s ease;
}
  .bio-premium {
  background-color: #f5f5f5;
  border-radius: 12px;
}
</style>

<div class="hero">

  <div class="hero-top">
    <h1>Nathalie Currid</h1>
    <p>Project Manager • Business Intelligence Analyst</p>
  </div>

  <div class="hero-bottom">

    <a href="https://github.com/ncurrid/WELCOME-PAGE" target="_blank">
      BI Projects
    </a>

    <a href="https://app.powerbi.com/view?r=eyJrIjoiZjRiOTc3NDItN2Y3OS00Mjc3LWE3MjUtNTM3N2E4NzRjODZlIiwidCI6IjI0ZmZjMGRmLTZiM2YtNGVkZS1iYWNkLWRkNDlmZDFiNGEzMCJ9"
       target="_blank">
      View CV
    </a>

  </div>

</div>

<section id="about" class="section">
  <h2>About me</h2>
  <p>I’m a Project Manager with a growing focus on Business Intelligence, using data to support decision-making and improve performance. I work across diverse sectors with an open mind and rigour, combining analytical thinking and project management to deliver clear, measurable results. My focus is on turning data into actionable insights through KPIs, reporting, and performance tracking. I communicate effectively and manage projects independently and in cross-functional teams, ensuring alignment between stakeholders and operations.</p>
</section>

<section id="bio" class="section bio-premium">
  <h2>Short bio</h2>

  <div class="bio-premium-timeline">

    <div class="bio-premium-item">
      <div class="bio-premium-dot"></div>

      <div class="bio-premium-content">
        <div class="bio-role">Project Manager of the RISE Academy of Excellence</div>
        <div class="bio-date">2023 — Present</div>
        <div class="bio-text">
          Centre Inria d'Université Côte d'Azur, Sophia Antipolis, France
        </div>
      </div>
    </div>

    <div class="bio-premium-item">
      <div class="bio-premium-dot"></div>

      <div class="bio-premium-content">
        <div class="bio-role">Student Success Manager - Apprenticeship segment</div>
        <div class="bio-date">2021 — 2023</div>
        <div class="bio-text">
          OpenClassrooms, Paris (remote), France
        </div>
      </div>
    </div>

    <div class="bio-premium-item">
      <div class="bio-premium-dot"></div>

      <div class="bio-premium-content">
        <div class="bio-role">Marketing Communications Manager (France & Monaco)</div>
        <div class="bio-date">2009 - 2020</div>
        <div class="bio-text">
          Blevins Franks Wealth Management, Valbonne, France
        </div>
      </div>
    </div>
    
   <div class="bio-premium-item">
      <div class="bio-premium-dot"></div>

      <div class="bio-premium-content">
        <div class="bio-role">French Teacher (Secondary and 6th form)</div>
        <div class="bio-date">2002 — 2006</div>
        <div class="bio-text">
          Corfe Hills School Academy Trust, Broadstone, UK
        </div>
      </div>
    </div>
  </div>
</section>

<section id="projects" class="section">
  <h2>Projects</h2>
  <p>Quelques projets Power BI, dashboards et analyses disponibles sur GitHub et Power BI Service.</p>
</section>

<section id="contact" class="section">
  <h2>Contact</h2>
  <p>Email : nathalie.currid@gmail.com<br>
     LinkedIn : [https://linkedin.com](https://www.linkedin.com/in/nathalie-currid-ab87a042)</p>
</section>
