---
layout: page
title: Nathalie Currid
permalink: /
---

<style>
/* =========================
   HEADER TITLE (no blue styling override)
========================= */
.page__title,
.site-title,
.site-brand__title {
  color: #111 !important;
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

  text-align: center;
  color: white;

  padding: 40px 20px;

  position: relative;
}

/* overlay léger pour lisibilité */
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
   BUTTONS
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

  <div class="hero-top">
    <h1>Nathalie Currid</h1>
    <p>Adaptable • Creative • Project Manager</p>
  </div>

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
    I combine creativity, communication, and strong project management skills.
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
