---
layout: page
title: ""
permalink: /
---
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
<style>
body {
  font-family: "Inter", Arial, Helvetica, sans-serif;
}

h1, h2, h3, h4, p, a, li {
  font-family: inherit;
}
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

  padding: 30px 20px 30px;
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
  margin-top: 15px;
  font-size: 1.2em;
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
  border-radius: 0px;

  font-weight: 500;
  text-align: center;
}

/* =========================
   SECTION
========================= */
.section {
  padding: 20px 20px;
  text-align: left;
}
/* =========================
   LinkedIn blue style
========================= */
   :root {
  --primary: #0a66c2;
  --text: #1f1f1f;;
  --muted: #666;
  --line: #e6e6e6;
  --bg: #ffffff;
}

/* SECTION */
.bio-premium {
  background: var(--bg);
  padding-top: 20px;
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
  margin-bottom: 20px;
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

.bio-role a:link,
.bio-role a:visited,
.bio-role a:hover,
.bio-role a:active {
  color: black;
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
  border-radius: 0px;
}
#contact i {
  margin-right: 8px;
  color: #444;
}
h1, h2, h3 {
  margin-top: 6px;
  margin-bottom: 6px;
  line-height: 1.2;
}

/* TIGHTER SECTION SPACING */
.section {
  padding: 8px 20px;
}

.section h2 {
  margin-top: 6px;
  margin-bottom: 8px;
}

.section p {
  margin-top: 6px;
  margin-bottom: 8px;
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
  <p>I’m a Project Manager with strong communication skills and a growing focus on Business Intelligence, using data to support decision-making and improve performance across diverse sectors. I approach my work with both curiosity and rigor, combining analytical thinking, project management expertise, and a collaborative approach to deliver clear, measurable results.</p>
</section>

<section id="bio" class="section bio-premium">
  <h2>Short bio</h2>

  <div class="bio-premium-timeline">

    <div class="bio-premium-item">
      <div class="bio-premium-dot"></div>

      <div class="bio-premium-content">
        <div class="bio-role"><a href="https://ds4h.univ-cotedazur.eu/about-us/academy-of-excellence-1" target="_blank" rel="noopener noreferrer">Project Manager of the RISE Academy of Excellence</a></div>
        <div class="bio-date">2023 — Present</div>
        <div class="bio-text">
          Centre Inria d'Université Côte d'Azur, Sophia Antipolis, France
        </div>
      </div>
    </div>

    <div class="bio-premium-item">
      <div class="bio-premium-dot"></div>

      <div class="bio-premium-content">
        <div class="bio-role"><a href="https://openclassrooms.com/fr/apprenticeship" target="_blank" rel="noopener noreferrer">Student Success Manager for the Apprenticeship segment</a></div>
        <div class="bio-date">2021 — 2023</div>
        <div class="bio-text">
          OpenClassrooms, Paris (remote), France
        </div>
      </div>
    </div>

    <div class="bio-premium-item">
      <div class="bio-premium-dot"></div>

      <div class="bio-premium-content">
        <div class="bio-role"><a href="https://www.blevinsfranks.com/" target="_blank" rel="noopener noreferrer">Marketing Communications Manager for France & Monaco</a></div>
        <div class="bio-date">2009 - 2020</div>
        <div class="bio-text">
          Blevins Franks Wealth Management, Valbonne, France
        </div>
      </div>
    </div>
    
   <div class="bio-premium-item">
      <div class="bio-premium-dot"></div>

      <div class="bio-premium-content">
        <div class="bio-role"><a href="https://www.corfehills.net/" target="_blank" rel="noopener noreferrer">Teacher of French (Secondary & Sixth form)</a></div>
        <div class="bio-date">2002 — 2006</div>
        <div class="bio-text">
          Corfe Hills School Academy Trust, Broadstone, UK
        </div>
      </div>
    </div>
  </div>
</section>

<section id="Qualities" class="section">
  <h2>Qualities</h2>
  <p>Analytical • Organised • Collaborative • Results-driven • Curious • Reliable</p>
</section>

<section id="Skills" class="section">
  <h2>Skills</h2>
<p><strong>Project management:</strong> Project coordination • Agile methodologies • Stakeholder management • Requirements gathering • Process documentation </p>

<p><strong>Data analysis and transformation:</strong> Data preparation and transformation (ETL with Power Query) • Exploratory data analysis</p>

<p><strong>Data and Business Intelligence:</strong> Reporting and dashboard development • Data-driven decision support • Power BI • SQL • Excel • Python (Pandas, Matplotlib)</p>

<p><strong>Collaboration tools:</strong> Miro (workshops, mockups, mind maps) • Notion • Loom (training videos) • Slack • GitHub • Markdown</p>

<p><strong>Web and digital platforms:</strong> Web and intranet content management (K-Sup) • Marketing automation (Blueshift) • Google Analytics • Google Ads • Ticketing and workflow management (Zendesk) </p>

<p><strong>Languages:</strong> French (native) • English (fluent)</p>

</section>

<section id="contact" class="section">
  <h2>Contact</h2>

  <p>
    <i class="fas fa-envelope"></i>
    <a href="mailto:nathalie.currid@gmail.com">
      nathalie.currid@gmail.com
    </a>
  </p>

  <p>
    <i class="fab fa-linkedin"></i>
    <a href="https://www.linkedin.com/in/nathalie-currid-ab87a042/" target="_blank">
      LinkedIn
    </a>
  </p>

  <p>
    <i class="fab fa-github"></i>
    <a href="https://github.com/ncurrid" target="_blank">
      GitHub
    </a>
  </p>

</section>
