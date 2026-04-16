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
  z-index: 0; /* 👈 important */
}

/* overlay corrigé */
.hero::before {
  content: "";
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.25); /* un peu plus visible */
  z-index: 1; /* 👈 doit être derrière le contenu */
}

/* contenu AU-DESSUS de l’overlay */
.hero > * {
  position: relative;
  z-index: 2;
}
.hero {
  position: relative;
  isolation: isolate;
}
