---
layout: page
title: ""
permalink: /
---

<style>
/* =========================
   SUPPRESSION TITRE THEME
========================= */
.site-title,
.site-brand,
.site-nav__title,
.site-header__title,
.header__title {
  display: none !important;
}

/* =========================
   HERO SECTION
========================= */
.hero {
  background-image: url('/assets/images/background.jpg');
  background-size: cover;
  background-position: center;
  height: 80vh;

  display: flex;
  flex-direction: column;
  justify-content: space-between;

  color: white;
  text-align: center;
  padding: 40px 20px;

  position: relative;
}

/* overlay léger (IMPORTANT pour lisibilité sans assombrir trop) */
.hero::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: rgba(0,0,0,0.25);
}

.hero > * {
  position: relative;
}

/* =========================
   TOP TEXT
========================= */
.hero-top {
  margin-top: 20px;
}

.hero-top h1 {
  font-size: 3em;
  margin-bottom: 10px;
  font-weight: 600;
}

.hero-top p {
  font-size: 1.2em;
  opacity: 0.95;
}

/* =========================
   BOTTOM BUTTONS
========================= */
.hero-bottom {
  margin-bottom: 20px;
}

.hero-bottom a {
  display: inline-block;
  margin: 10px;
  padding: 12px 25px;

  background-color: rgba(0,0,0,0.6);
  color: white;

  text-decoration: none;
  border-radius: 6px;

  font-weight: 500;
}

.hero-bottom a:hover {
  background-color: rgba(0,0,0,0.75);
}

/* =========================
   SECTIONS
========================= */
.section {
  padding: 40px 20px;
  text-align: center;
}

.section h2 {
  margin-bottom: 10px;
}
</style>

<!-- HERO -->
<div class="hero">

  <!-- TOP TEXT -->
  <div class="hero-top">
    <h1>Nathalie Currid</h1>
    <p>Adaptable • Creative • Project Manager</p>
  </div>

  <!-- BOTTOM BUTTONS -->
  <div class="hero-bottom">
    <a href="/about/">About Me</a>

    <a href="https://app.powerbi.com/view?r=eyJrIjoiZjRiOTc3NDItN2Y3OS00Mjc3LWE3MjUtNTM3N2E4NzRjODZlIiwidCI6IjI0ZmZjMGRmLTZiM2YtNGVkZS1iYWNkLWRkNDlmZDFiNGEzMCJ9"
       target="_blank">
      View CV
    </a>
  </div>

</div>

<!-- ABOUT -->
<div class="section">
  <h2>About Me</h2>
  <p>
    I work across a variety of sectors with enthusiasm and adaptability.  
    I combine creativity, communication skills, and strong project management experience.
  </p>
</div>

<!-- SKILLS -->
<div class="section">
  <h2>Skills</h2>
  <p>
    Project Management • Communication • Leadership • Problem Solving • Adaptability
  </p>
</div>

<!-- CONTACT -->
<div class="section">
  <h2>Contact</h2>
  <p>
    📧 nathalie.currid@gmail.com <br>
    🔗 <a href="https://www.linkedin.com/in/nathalie-currid-ab87a042/">LinkedIn</a> <br>
    💻 <a href="https://github.com/ncurrid">GitHub</a>
  </p>
</div>
