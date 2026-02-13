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

    /* --- NAVIGATION --- */
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
    }

    .btn-cv:hover {
      background: #ffe69d;
      transform: scale(1.05);
    }

    /* --- HEADER / ACCUEIL --- */
    header {
      background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.8)), url('background.JPEG') center/cover no-repeat;
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

    /* --- SECTIONS --- */
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

    /* --- PROJETS --- */
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

  <!-- Navigation -->
  <nav>
    <div class="logo">Phanuel</div>
    <ul>
      <li><a href="#accueil">Accueil</a></li>
      <li><a href="#about">À propos</a></li>
      <li><a href="#skills">Compétences</a></li>
      <li><a href="#projects">Projets</a></li>
      <li><a href="#experience">Expériences</a></li>
      <li><a href="#education">Formation</a></li>
      <li><a href="#contacts">Contact</a></li>
      <li><a href="#references">Références</a></li>
    </ul>
    <a href="CV_Phanuel.pdf" class="btn-cv" download>Télécharger le CV</a>
  </nav>

  <!-- Accueil -->
  <header id="accueil">
    <h1>Djarabé Djeramadji Phanuel</h1>
    <h3>Ingénieur en formation – Génie Électrique et Énergétique</h3>
    <p>Passionné par la conception et l’optimisation de systèmes électriques et photovoltaïques pour soutenir la transition énergétique en Afrique.</p>
  </header>

  <!-- À propos -->
  <section id="about">
    <h2>À propos</h2>
    <p>Je suis Djarabé Djeramadji Phanuel, titulaire d'un Master en Génie Électrique, Énergétique et Industriel (option Réseaux Électriques) à l’Institut 2iE. 
    Mon intérêt porte sur le développement d’infrastructures énergétiques fiables et durables, avec un focus particulier sur les centrales solaires photovoltaïques et leur intégration au réseau.</p>
  </section>

  <!-- Compétences -->
  <section id="skills">
    <h2>Compétences</h2>
    <div class="grid-2">
      <div>
        <h3>Techniques</h3>
        <ul>
          <li>Conception et dimensionnement de systèmes solaires PV</li>
          <li>Études de pertes, intégration réseau, DAO, SCADA</li>
          <li>Planification et suivi de projet (MS Project)</li>
        </ul>
      </div>
      <div>
        <h3>Logiciels & Outils</h3>
        <ul>
          <li>AutoCAD, PowerFactory, NEPLAN, PVsyst, WinRelais</li>
          <li>MS Project, Excel, PowerPoint, Access</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Projets -->
  <section id="projects">
    <h2>Projets</h2>
    <div class="projects-grid">

      <div class="project">
        <img src="projet1.jpg" alt="Extension de la Centrale Solaire de Ferkessédougou">
        <div class="project-info">
          <h4>Centrale Solaire de Ferkessédougou</h4>
          <p>Étude comparative, optimisation, simulation PVsyst et intégration BESS.</p>
        </div>
      </div>

      <div class="project">
        <img src="projet2.jpg" alt="Projet Solaire de Kong">
        <div class="project-info">
          <h4>Projet Solaire de Kong</h4>
          <p>Analyse du DAO, préparation d’appel d’offres, étude des verrous HTA.</p>
        </div>
      </div>

      <div class="project">
        <img src="projet3.jpg" alt="Système PV connecté au réseau">
        <div class="project-info">
          <h4>Système PV Connecté au Réseau</h4>
          <p>Dimensionnement et simulation pour autoconsommation sur PVsyst.</p>
        </div>
      </div>

<div class="project">
  <a href="memoire/Memoire_Phanuel_Reseaux_Electriques.pdf" target="_blank">
    <img src="images/memoire-cover.jpg" alt="Mémoire de Master – Réseaux Électriques">
  </a>
  <div class="project-info">
    <h4>Mémoire de Master – Réseaux Électriques</h4>
    <p>
      Étude approfondie sur l’intégration des systèmes photovoltaïques au réseau électrique,
      analyse des contraintes techniques et propositions d’optimisation.
    </p>
    <p><strong>Mots-clés :</strong> Réseaux électriques, PV, intégration réseau</p>
  </div>
</div>

    </div>
  </section>

  <!-- Expériences -->
  <section id="experience">
    <h2>Expériences professionnelles</h2>
    <ul>
      <li>Stagiaire Ingénieur – VINCI Energies CI (2025)</li>
      <li>Stagiaire – SONABEL, Burkina Faso (2023)</li>
      <li>Projets académiques – Institut 2iE (2023)</li>
    </ul>
  </section>

  <!-- Formation -->
  <section id="education">
    <h2>Formation</h2>
    <ul>
      <li>Master – Génie Électrique, Énergétique et Industriel, Institut 2iE (2023 – 2026)</li>
      <li>Bachelor – Génie Électrique, Institut 2iE (2022 – 2023)</li>
      <li>Classes Préparatoires – Institut 2iE (2019 – 2021)</li>
    </ul>
  </section>

  <!-- Contacts -->
  <section id="contacts">
    <h2>Contact</h2>
    <p>📧 <a href="mailto:djarabedjeramadjiphanuel@gmail.com">djarabedjeramadjiphanuel@gmail.com</a> | <a href="mailto:phanuel.djarabe@2ie-edu.org">phanuel.djarabe@2ie-edu.org</a></p>
    <p>📱 +226 54 66 43 56 / +226 61 00 39 09</p>
    <p>🏠 Ouagadougou, Burkina Faso</p>
    <p>🔗 <a href="https://www.linkedin.com/in/phanuel-djarabébs02-ptec04-D07" target="_blank">LinkedIn</a></p>
  </section>

  <!-- Références -->
  <section id="references">
    <h2>Références</h2>
    <ul>
      <li><strong>Pr. Y. Moussa SORO</strong> – Chef de département GEEI, Institut 2iE | 📞 +226 68 76 88 22 | ✉️ <a href="mailto:moussa.soro@2ie-edu.org">moussa.soro@2ie-edu.org</a></li>
      <li><strong>Dr Aboubakar GOMNA</strong> – Enseignant chercheur, Institut 2iE | 📞 +226 51 98 24 20 | ✉️ <a href="mailto:aboubakar.gomna@2ie-edu.org">aboubakar.gomna@2ie-edu.org</a></li>
      <li><strong>Roland TIAPANI</strong> – Responsable Bureau d’étude Omexon Poste, VINCI Energies CI | ✉️ <a href="mailto:roland.tiapani@omexom.com">roland.tiapani@omexom.com</a></li>
      <li><strong>Dr. Yohan RICHARDSON</strong> – Chef du département STI, Institut 2iE | 📞 +226 68 76 88 71 | ✉️ <a href="mailto:yohan.richardson@2ie-edu.org">yohan.richardson@2ie-edu.org</a></li>
    </ul>
  </section>

  <footer>
    © 2025 Djarabé Djeramadji Phanuel — Tous droits réservés.
  </footer>

</body>
</html>
