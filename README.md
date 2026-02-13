<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio – Djarabé Djeramadji Phanuel</title>

  <style>
    :root {
      --bg-dark: #0d0d0d;
      --bg-light: #181818;
      --text: #f5f5f5;
      --accent: #ffd369;
      --muted: #999;
    }

    * {
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: "Poppins", Arial, sans-serif;
      background-color: var(--bg-dark);
      color: var(--text);
      line-height: 1.6;
    }

    a {
      color: var(--accent);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: rgba(10, 10, 10, 0.95);
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 12px 8%;
      z-index: 1000;
      backdrop-filter: blur(10px);
    }

    nav .logo {
      color: var(--accent);
      font-weight: 600;
      font-size: 1.1rem;
      letter-spacing: 1px;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
      margin: 0;
      padding: 0;
    }

    nav ul li a {
      color: var(--text);
      font-weight: 500;
    }

    nav ul li a:hover {
      color: var(--accent);
    }

    .btn-cv {
      background: var(--accent);
      color: #000;
      padding: 8px 16px;
      border-radius: 6px;
      font-weight: 600;
      text-decoration: none;
      transition: 0.3s;
      display: inline-block;
      margin-top: 15px;
    }

    .btn-cv:hover {
      background: #ffe69d;
      transform: scale(1.05);
    }

    header {
      background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.8)), url('background.jpg') center/cover no-repeat;
      padding: 180px 10% 120px;
      text-align: center;
    }

    header h1 {
      color: var(--accent);
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    header h3 {
      color: #ddd;
      font-weight: 400;
    }

    header p {
      max-width: 700px;
      margin: 20px auto;
      color: #ccc;
      font-style: italic;
    }

    section {
      padding: 80px 10%;
    }

    section:nth-child(even) {
      background-color: var(--bg-light);
    }

    h2 {
      color: var(--accent);
      margin-bottom: 30px;
    }

    .grid-2 {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 30px;
    }

    @media (max-width: 900px) {
      .grid-2 {
        grid-template-columns: 1fr;
      }

      nav ul {
        display: none;
      }
    }

    ul {
      list-style: none;
      padding: 0;
    }

    ul li::before {
      content: "• ";
      color: var(--accent);
    }

    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
    }

    .project {
      background-color: #111;
      border-radius: 10px;
      overflow: hidden;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .project:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(255, 211, 105, 0.1);
    }

    .project img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .project-info {
      padding: 15px;
    }

    .project-info h4 {
      color: var(--accent);
      margin: 0 0 8px;
    }

    .project-info p {
      color: #ccc;
      margin: 0;
      font-size: 0.95rem;
    }

    footer {
      text-align: center;
      padding: 30px 10px;
      background-color: #0b0b0b;
      color: #aaa;
    }

  </style>
</head>

<body>

<nav>
  <div class="logo">Phanuel</div>
  <ul>
    <li><a href="#accueil">Accueil</a></li>
    <li><a href="#about">À propos</a></li>
    <li><a href="#objective">Objectif</a></li>
    <li><a href="#skills">Compétences</a></li>
    <li><a href="#projects">Projets</a></li>
    <li><a href="#experience">Expériences</a></li>
    <li><a href="#education">Formation</a></li>
    <li><a href="#contacts">Contact</a></li>
  </ul>
  <a href="CV_Phanuel.pdf" class="btn-cv" download>Télécharger le CV</a>
</nav>

<header id="accueil">
  <h1>Djarabé Djeramadji Phanuel</h1>
  <h3>Ingénieur en formation – Génie Électrique et Énergétique</h3>
  <p>Passionné par la conception et l’optimisation de systèmes électriques et photovoltaïques pour soutenir la transition énergétique en Afrique.</p>
  <a href="#contacts" class="btn-cv">Me contacter</a>
</header>

<section id="about">
  <h2>À propos</h2>
  <p>Ingénieur en Génie Électrique spécialisé en réseaux et systèmes photovoltaïques, avec une expertise en dimensionnement, intégration réseau et analyse technico-économique. Mon ambition est de contribuer au développement d’infrastructures énergétiques fiables et durables en Afrique.</p>
</section>

<section id="objective">
  <h2>Objectif Professionnel</h2>
  <p>Contribuer au développement de centrales photovoltaïques et d’infrastructures énergétiques à forte valeur technique, en combinant optimisation réseau, performance énergétique et gestion de projet.</p>
</section>

<section id="skills">
  <h2>Compétences</h2>
  <div class="grid-2">
    <div>
      <h3>Techniques</h3>
      <ul>
        <li>⚡ Conception et dimensionnement de centrales solaires PV</li>
        <li>🔌 Études d’intégration réseau HTA/HTB</li>
        <li>📊 Analyse de pertes, SCADA, DAO</li>
        <li>📅 Planification et suivi de projet (MS Project)</li>
      </ul>
    </div>
    <div>
      <h3>Logiciels</h3>
      <ul>
        <li>☀️ PVsyst</li>
        <li>⚡ PowerFactory & NEPLAN</li>
        <li>📐 AutoCAD</li>
        <li>📊 MS Project, Excel avancé</li>
      </ul>
    </div>
  </div>
</section>

<section id="projects">
  <h2>Projets</h2>
  <div class="projects-grid">

    <div class="project">
      <img src="projet1.jpg" alt="Centrale Solaire de Ferkessédougou">
      <div class="project-info">
        <h4>Centrale Solaire de Ferkessédougou</h4>
        <p>Étude comparative et optimisation d’extension d’une centrale PV avec intégration BESS, simulations avancées sous PVsyst et analyse des performances réseau.</p>
      </div>
    </div>

    <div class="project">
      <img src="projet2.jpg" alt="Projet Solaire de Kong">
      <div class="project-info">
        <h4>Projet Solaire de Kong</h4>
        <p>Analyse technique du DAO, préparation d’appel d’offres et étude des contraintes HTA pour raccordement réseau.</p>
      </div>
    </div>

    <div class="project">
      <img src="projet3.jpg" alt="Système PV connecté au réseau">
      <div class="project-info">
        <h4>Système PV Connecté au Réseau</h4>
        <p>Dimensionnement d’un système photovoltaïque pour autoconsommation industrielle, optimisation des pertes et simulation complète sous PVsyst.</p>
      </div>
    </div>

  </div>
</section>

<section id="experience">
  <h2>Expériences professionnelles</h2>
  <ul>
    <li>Stagiaire Ingénieur – VINCI Energies CI (2025)</li>
    <li>Stagiaire – SONABEL, Burkina Faso (2023)</li>
    <li>Projets académiques – Institut 2iE (2023)</li>
  </ul>
</section>

<section id="education">
  <h2>Formation</h2>
  <ul>
    <li>Master 2 – Génie Électrique, Énergétique et Industriel – Institut 2iE</li>
    <li>Bachelor – Génie Électrique – Institut 2iE</li>
    <li>Classes Préparatoires Scientifiques – Institut 2iE</li>
  </ul>
</section>

<section id="contacts">
  <h2>Contact</h2>
  <p>📧 djarabedjeramadjiphanuel@gmail.com</p>
  <p>📱 +226 54 66 43 56</p>
  <p>📍 Ouagadougou, Burkina Faso</p>
  <p>🔗 <a href="https://www.linkedin.com/in/phanuel-djarabébs02-ptec04-D07" target="_blank">LinkedIn</a></p>
</section>

<section id="references">
  <h2>Références</h2>
  <p>Références disponibles sur demande.</p>
</section>

<footer>
  © 2025 Djarabé Djeramadji Phanuel — Tous droits réservés.
</footer>

</body>
</html>
