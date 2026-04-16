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
  --main-color: #2c3e50;   /* couleur principale */
  --accent-color: #1abc9c; /* couleur accent */
  --text-color: #111;
  --card-bg: rgba(255, 255, 255, 0.9);
}

/* SECTION BIO */
.bio-section {
  background: #f7f7f7;
}

/* GRID */
.bio-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  margin-top: 30px;
}

/* CARDS */
.bio-card {
  background: var(--card-bg);
  border-left: 5px solid var(--accent-color);
  border-radius: 10px;
  padding: 20px;
  text-align: left;

  box-shadow: 0 4px 15px rgba(0,0,0,0.08);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.bio-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.12);
}

/* TITRES */
.bio-card h3 {
  margin-bottom: 10px;
  color: var(--main-color);
}

/* TEXTE */
.bio-card p {
  color: #444;
  line-height: 1.5;
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

  <div class="bio-grid">

    <div class="bio-card">
      <h3>Project Manager</h3>
      <p>
        Gestion de projets data et IT, coordination d’équipes et suivi de delivery
        dans des environnements agiles.
      </p>
    </div>

    <div class="bio-card">
      <h3>BI Analyst</h3>
      <p>
        Conception de dashboards Power BI, analyse des données et transformation
        en insights décisionnels.
      </p>
    </div>

    <div class="bio-card">
      <h3>Data Enthusiast</h3>
      <p>
        Passionnée par la data visualisation, l’optimisation des processus et
        l’aide à la décision.
      </p>
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
