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
  <p>Je suis spécialisée en data, BI et gestion de projets, avec une forte expérience dans la transformation des données en insights décisionnels.</p>
</section>

<section id="bio" class="section">
  <h2>Short bio</h2>
  <p>Project Manager & BI Analyst basée en Europe, passionnée par la data, la visualisation et l’optimisation des processus métiers.</p>
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
