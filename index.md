---
layout: page
title: ""
permalink: /
---

<style>

/* =========================
   HEADER FIX (évite doublon titre)
========================= */
.page__title {
  display: none !important;
}

.site-brand__title {
  color: #111 !important;
}

/* =========================
   HERO
========================= */
.hero {
  background-image: url('/assets/images/background.jpg');
  background-size: cover;
  background-position: center;
  height: 80vh;

  display: flex;
  flex-direction: column;
  justify-content: space-between;

  text-align: center;
  color: white;

  padding: 40px 20px;
  position: relative;
}

/* overlay léger */
.hero::before {
  content: "";
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.25);
}

.hero > * {
  position: relative;
}

/* =========================
   TOP
========================= */
.hero-top img {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  margin-bottom: 10px;
}

.hero-top h1 {
  font-size: 2.8em;
  margin: 10px 0;
}

/* =========================
   BUTTONS
========================= */
.hero-bottom a {
  display: inline-block;
  margin: 10px;
  padding: 12px 25px;
  background-color: rgba(0,0,0,0.6);
  color: white;
  text-decoration: none;
  border-radius: 6px;
}

/* =========================
   SECTIONS
========================= */
.section {
  padding: 40px 20px;
  text-align: center;
}
</style>

<!-- HERO -->
<div class="hero">

  <div class="hero-top">

    <!-- NOM (UNE SEULE FOIS ICI) -->
    <h1>Nathalie Currid</h1>

    <p>Business Intelligence Analyst • Project Manager</p>

  </div>

  <div class="hero-bottom">

    <a href="https://github.com/ncurrid/WELCOME-PAGE">BI projects</a>

    <a href="https://app.powerbi.com/view?r=eyJrIjoiZjRiOTc3NDItN2Y3OS00Mjc3LWE3MjUtNTM3N2E4NzRjODZlIiwidCI6IjI0ZmZjMGRmLTZiM2YtNGVkZS1iYWNkLWRkNDlmZDFiNGEzMCJ9"
       target="_blank">
      View CV
    </a>

  </div>

</div>

<!-- ABOUT -->
<div class="section">
  <h2>About me</h2>
  <p>
    I work across a variety of sectors with adaptability, creativity, and strong project management skills.
  </p>
</div>
