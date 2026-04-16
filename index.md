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

/* =========================
   HERO
========================= */
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

  padding: 60px 20px;
  position: relative;
}

/* overlay léger */
.hero::before {
  content: "";
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.10);
}

.hero > * {
  position: relative;
}

/* =========================
   TOP
========================= */
.hero-top {
  margin-top: 20px;
}

.hero-top h1 {
  font-size: 2.8em;
  margin: 10px 0;
}

.hero-top p {
  font-size: 1.2em;
}

/* =========================
   ABOUT (DANS HERO)
========================= */
.hero-about {
  max-width: 600px;
  margin: 20px auto;
  font-size: 0.8em;
}
}

/* =========================
   BUTTONS
========================= */
.hero-bottom {
  margin-bottom: 10px;
}

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
   SECTION (SI BESOIN PLUS BAS)
========================= */
.section {
  padding: 60px 20px;
  text-align: center;
}
</style>

<!-- HERO -->
<div class="hero">

  <!-- TOP -->
  <div class="hero-top">
    <h1>Nathalie Currid</h1>
    <p>Business Intelligence Analyst • Project Manager</p>

    <!-- ABOUT DIRECTEMENT SOUS LE TITRE -->
    <div class="hero-about">
      <p>
        Project Manager with a strong background in delivering results.
        Recently expanded into Business Intelligence, focusing on turning data into actionable insights to improve performance.
      </p>
    </div>
  </div>

  <!-- BOTTOM BUTTONS -->
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
