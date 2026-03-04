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
      background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.8)), url('bbackground.jpg') center/cover no-repeat;
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
  grid-template-columns: 1fr; /* mobile */
  gap: 30px;
}
/* Tablette + PC */
@media (min-width: 700px) {
  .projects-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}
.project {
  display: flex;
  flex-direction: column;
  height: 100%;
}
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
  height: 200px;
  object-fit: contain;
  background-color: #000;
}
.project-image {
  width: 100%;
  height: 200px;
  background-color: #000;
  display: flex;
  align-items: center;
  justify-content: center;
}
.project-image img {
  max-width: 100%;
  max-height: 100%;
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

<nav>
<strong style="color:var(--accent)">Phanuel</strong>
<ul>
<li><a href="#about">À propos</a></li>
<li><a href="#skills">Compétences</a></li>
<li><a href="#projects">Projets</a></li>
<li><a href="#experience">Expériences</a></li>
<li><a href="#education">Formation</a></li>
<li><a href="#contact">Contact</a></li>
<li><a href="#references">Références</a></li>
</ul>
<a href="CV_Phanuel.pdf" class="btn-cv" download>Télécharger le CV</a>
</nav>

<header>
<h1>Djarabé Djeramadji Phanuel</h1>
<h3>Ingénieur Génie Électrique & Énergétique</h3>
<p>Passionné par la conception et l’optimisation de systèmes électriques et photovoltaïques pour soutenir la transition énergétique en Afrique.</p>
</header>

<section id="about">
<h2>À propos</h2>
<p>
Ingénieur en Génie Électrique et Énergétique, je mets mes compétences au service de la transformation énergétique en Afrique. Spécialisé dans le dimensionnement des réseaux électriques et les systèmes solaires photovoltaïques, je conçois des solutions techniques fiables, optimisées et adaptées aux réalités locales.
</p>
<p>
Au-delà de la technique, ma vision est claire : accélérer l’accès à une énergie durable, soutenir l’industrialisation et contribuer activement à la modernisation des infrastructures électriques. Chaque projet est pour moi une opportunité d’allier performance technique, viabilité économique et impact social.
</p>
</section>

<section id="skills">
<h2>Compétences</h2>

<div class="grid-2">

<div>
<h3>Réseaux électriques</h3>
<ul>
<li>Dimensionnement de lignes HTB, HTA et BT</li>
<li>Études de raccordement au réseau</li>
<li>Dimensionnement de postes HTB/HTA/BT</li>
<li>Lecture et élaboration de schémas électriques</li>
<li>Suivi de travaux</li>
<li>Réalisation de plans de raccordement</li>
</ul>
</div>

<div>
<h3>Énergies renouvelables</h3>
<ul>
<li>Dimensionnement de centrales photovoltaïques</li>
<li>Études technico-économiques de projets solaires</li>
<li>Intégration de systèmes de stockage d’énergie (BESS)</li>
<li>Analyse de production et optimisation énergétique</li>
</ul>
</div>

<div>
<h3>Analyse & Gestion de projet</h3>
<ul>
<li>Étude de faisabilité</li>
<li>Estimation quantitative et financière</li>
<li>Planification technique</li>
<li>Coordination terrain</li>
</ul>
</div>

<div>
<h3>Outils</h3>
<ul>
<li>AutoCAD, PowerFactory, NEPLAN, PVCase, WinRelais</li>
<li>MS Project, Excel, PowerPoint, Access</li>
</ul>
<p><strong>Compétences supplémentaires :</strong><br>
Énergie éolienne (principes de fonctionnement et intégration réseau) · Hydroélectricité (bases de conception et production) · Systèmes CVC pour bâtiments (VRV/VRF, principes de dimensionnement)
</p>
</div>

</div>
</section>

<section id="projects">
  <h2>Projets</h2>

  <div class="projects-grid">
    <!-- Projet 1 -->
    <div class="project">
      <img src="projet1.jpg" />
      <div class="project-info">
        <h4>Étude de ligne HTA – Zagtoulie (Burkina Faso)</h4>
        <p><strong>Type :</strong> Étude technique de réseau HTA</p>
        <ul>
          <li>Étude de tracé et choix du type de ligne (aérienne)</li>
          <li>Dimensionnement électrique (chute de tension, section des conducteurs, bilan de puissance)</li>
          <li>Dimensionnement mécanique des supports et conducteurs</li>
          <li>Élaboration du devis quantitatif et estimatif</li>
        </ul>
        <p><strong>Impact :</strong> Amélioration de l’accès à l’électricité en zone périurbaine.</p>
      </div>
    </div>
    <!-- Projet 2 -->
    <div class="project">
      <img src="projet2.jpg" />
      <div class="project-info">
        <h4>Électrification de 32 localités rurales – Burkina Faso</h4>
        <p><strong>Type :</strong> Projet d’électrification rurale</p>
        <ul>
          <li>Réalisation des études techniques de raccordement HTA/BT</li>
          <li>Participation à la planification et au dimensionnement des infrastructures</li>
          <li>Suivi des travaux de piquetage et d’implantation des ouvrages</li>
        </ul>
        <p><strong>Impact :</strong> Extension du réseau électrique national vers des zones rurales isolées, favorisant le développement socio-économique local.</p>
      </div>
    </div>
    <!-- Projet 3 -->
    <div class="project">
      <img src="projet3.jpg" />
      <div class="project-info">
        <h4>Construction de la Centrale Solaire et du Poste d’Évacuation de Ferkessédougou – Côte d’Ivoire</h4>
        <p><strong>Type :</strong> Centrale solaire photovoltaïque et poste électrique d’évacuation d’énergie</p>
        <ul>
          <li>Suivi des travaux liés aux infrastructures électriques</li>
          <li>Réalisation des plans de raccordement</li>
          <li>Suivi des travaux de pose et de raccordement des équipements du poste</li>
          <li>Participation à la configuration des systèmes de protection et de contrôle-commande</li>
          <li>Suivi des essais et contre-essais de mise en service des ouvrages</li>
        </ul>
        <p><strong>Impact :</strong> Contribution à l’intégration sécurisée de la production solaire au réseau national et au renforcement du mix énergétique.</p>
      </div>
    </div>
    <!-- Projet 4 : Mémoire -->
    <div class="project">
      <div class="project-image">
        <img src="memoire-cover.jpg" />
      </div>
      <div class="project-info">
        <h4>Mémoire de Fin d’Études – Conception technico-économique de l’extension de la centrale solaire photovoltaïque de 52,44 MWc de Ferkessédougou avec intégration d’un BESS</h4>
        <p><strong>Type :</strong> Étude stratégique d’optimisation énergétique.</p>
        <p><strong>Objectifs :</strong></p>
        <ul>
          <li>Étudier l’extension de capacité de la centrale</li>
          <li>Intégrer un système de stockage d’énergie (BESS)</li>
          <li>Optimiser la rentabilité du projet et la stabilité de l’injection réseau</li>
        </ul>
        <p><strong>Axes d’étude :</strong></p>
        <ul>
          <li>Dimensionnement de l’extension photovoltaïque</li>
          <li>Dimensionnement du système de stockage</li>
          <li>Analyse technico-économique comparative</li>
          <li>Étude de rentabilité et évaluation de l’impact sur le réseau</li>
        </ul>
        <p><strong>Impact :</strong> Amélioration de la flexibilité du système électrique et contribution à la transition énergétique.</p>
        <p><strong>Document disponible sur demande.</strong></p>
      </div>
    </div>

  </div>
</section>

<section id="experience">
<h2>Expérience Professionnelle</h2>

<p><strong>SONABEL</strong><br>Stage académique</p>
<p><strong>Eco-Electrical Service</strong><br>Ingénieur Études et Travaux – Stage d’apprentissage</p>
<p><strong>Vinci Energies Côte d’Ivoire</strong><br>Ingénieur Études – Stage PFE</p>
<p><strong>Vinci Energies Côte d’Ivoire</strong><br>Ingénieur Études et Travaux – Stage Professionnel</p>
</section>

<section id="education">
<h2>Formation</h2>
<ul>
<li>Master – Génie Électrique, Énergétique et Industriel, Institut 2iE (2023–2026)</li>
<li>Bachelor – Génie Électrique, Institut 2iE (2022–2023)</li>
<li>Classes Préparatoires – Institut 2iE (2019–2021)</li>
</ul>
</section>

<section id="contact">
<h2>Contact</h2>
<p>📧 <a href="mailto:djarabedjeramadjiphanuel@gmail.com">djarabedjeramadjiphanuel@gmail.com</a></p>
<p>📱 +226 54 66 43 56 / +225 07 18 93 6055 </p>
<p>🔗 <a href="https://www.linkedin.com/in/phanuel-djarabébs02-ptec04-D07" target="_blank">LinkedIn</a></p>
<p>📍 Abidjan, Côte d'Ivoire</p>
</section>

<section id="references">
<h2>Références</h2>
<ul>
<li>
<strong>Pr. Y. Moussa SORO</strong> – Chef de département GEEI, Institut 2iE |
📞 +226 68 76 88 22 |
✉️ <a href="mailto:moussa.soro@2ie-edu.org">moussa.soro@2ie-edu.org</a>
</li>
<li>
<strong>Dr Aboubakar GOMNA</strong> – Enseignant chercheur, Institut 2iE |
📞 +226 51 98 24 20 |
✉️ <a href="mailto:aboubakar.gomna@2ie-edu.org">aboubakar.gomna@2ie-edu.org</a>
</li>
<li>
<strong>Roland TIAPANI</strong> – Responsable Bureau d’étude Omexon Poste, VINCI Energies CI |
✉️ <a href="mailto:roland.tiapani@omexom.com">roland.tiapani@omexom.com</a>
</li>
<li>
<strong>Dr Yohan RICHARDSON</strong> – Chef du département STI, Institut 2iE |
📞 +226 68 76 88 71 |
✉️ <a href="mailto:yohan.richardson@2ie-edu.org">yohan.richardson@2ie-edu.org</a>
</li>
</ul>
</section>

<footer>
© 2026 Djarabé Djeramadji Phanuel — Tous droits réservés.
</footer>

</body>
</html>
