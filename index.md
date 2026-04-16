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
  text-align: center;
}

   :root {
  --main-color: #2c3e50;
  --accent-color: #1abc9c;
  --bg-light: #f7f7f7;
  --card-bg: #ffffff;
}

/* SECTION */
.bio-section {
  background: var(--bg-light);
}

/* TIMELINE WRAPPER */
.timeline {
  position: relative;
  max-width: 900px;
  margin: 40px auto;
  padding: 20px 0;
}

/* LIGNE CENTRALE */
.timeline::after {
  content: '';
  position: absolute;
  width: 3px;
  background-color: var(--accent-color);
  top: 0;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
}

/* ITEM */
.timeline-item {
  padding: 20px 40px;
  position: relative;
  width: 50%;
}

/* LEFT / RIGHT ALTERNANCE */
.timeline-item:nth-child(odd) {
  left: 0;
  text-align: right;
}

.timeline-item:nth-child(even) {
  left: 50%;
  text-align: left;
}

/* POINT */
.timeline-dot {
  width: 14px;
  height: 14px;
  background-color: var(--accent-color);
  border-radius: 50%;
  position: absolute;
  top: 25px;
  z-index: 2;
}

/* POSITION DOT LEFT/RIGHT */
.timeline-item:nth-child(odd) .timeline-dot {
  right: -7px;
}

.timeline-item:nth-child(even) .timeline-dot {
  left: -7px;
}

/* CONTENT BOX */
.timeline-content {
  background: var(--card-bg);
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.08);
  display: inline-block;
  max-width: 350px;
}

/* TITRE */
.timeline-content h3 {
  margin: 0 0 5px;
  color: var(--main-color);
}

/* DATE */
.timeline-content span {
  font-size: 0.85em;
  color: var(--accent-color);
  display: block;
  margin-bottom: 10px;
}

/* MOBILE */
@media screen and (max-width: 768px) {
  .timeline::after {
    left: 10px;
  }

  .timeline-item {
    width: 100%;
    padding-left: 40px;
    padding-right: 20px;
    text-align: left !important;
    left: 0 !important;
  }

  .timeline-dot {
    left: 3px !important;
  }

  .timeline-content {
    max-width: 100%;
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

<section id="bio" class="section bio-section">
  <h2>Short bio</h2>

  <div class="timeline">

    <div class="timeline-item">
      <div class="timeline-dot"></div>
      <div class="timeline-content">
        <h3>Project Manager</h3>
        <span>2023 - Present</span>
        <p>
          Gestion de projets data et IT, coordination d’équipes,
          pilotage Agile et delivery de solutions BI.
        </p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-dot"></div>
      <div class="timeline-content">
        <h3>BI Analyst</h3>
        <span>2021 - 2023</span>
        <p>
          Création de dashboards Power BI, analyse de données,
          automatisation de reporting et support décisionnel.
        </p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-dot"></div>
      <div class="timeline-content">
        <h3>Data Enthusiast</h3>
        <span>Before 2021</span>
        <p>
          Exploration de la data visualisation, apprentissage SQL,
          Python et outils BI.
        </p>
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
  <p>Email : example@email.com<br>
     LinkedIn : https://linkedin.com</p>
</section>
