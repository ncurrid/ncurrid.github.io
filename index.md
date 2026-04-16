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
