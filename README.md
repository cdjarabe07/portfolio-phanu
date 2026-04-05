<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    
<!-- Begin Jekyll SEO tag v2.8.0 -->
<title>portfolio-phanu</title>
<meta name="generator" content="Jekyll v3.10.0" />
<meta property="og:title" content="portfolio-phanu" />
<meta property="og:locale" content="en_US" />
<link rel="canonical" href="https://cdjarabe07.github.io/portfolio-phanu/" />
<meta property="og:url" content="https://cdjarabe07.github.io/portfolio-phanu/" />
<meta property="og:site_name" content="portfolio-phanu" />
<meta property="og:type" content="website" />
<meta name="twitter:card" content="summary" />
<meta property="twitter:title" content="portfolio-phanu" />
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"WebSite","headline":"portfolio-phanu","name":"portfolio-phanu","url":"https://cdjarabe07.github.io/portfolio-phanu/"}</script>
<!-- End Jekyll SEO tag -->
    <link rel="stylesheet" href="/portfolio-phanu/assets/css/style.css?v=59b408cf64f48c918726a98f7bfbbc985b9f4ba0">
    <!-- start custom head snippets, customize with your own _includes/head-custom.html file -->
<!-- Setup Google Analytics -->
<!-- You can set your favicon here -->
<!-- link rel="shortcut icon" type="image/x-icon" href="/portfolio-phanu/favicon.ico" -->
<!-- end custom head snippets -->

  </head>
  <body>
    <div class="container-lg px-3 my-5 markdown-body">
      <h1><a href="https://cdjarabe07.github.io/portfolio-phanu/">portfolio-phanu</a></h1>
      <p>&lt;!DOCTYPE html&gt;</p>
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
<a href="CV_Phanuel.pdf" class="btn-cv" download="">Télécharger le CV</a>
</nav>

<header>
<h1>Djarabé Djeramadji Phanuel</h1>
<h3>Ingénieur Génie Électrique &amp; Énergétique</h3>
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
<li>Dimensionnement de lignes et postes HTB, HTA et BT</li>
<li>Études de raccordement au réseau</li>
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
<h3>Analyse &amp; Gestion de projet</h3>
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
<li>PVCase, PVSyst, Diablux, XLPro, NEPLAN, AutoCAD, ARCGis, QGis</li>
<li>MS Project, Word, PowerPoint, Excel avancé, Access</li>
</ul>
<h3>Compétences supplémentaires</h3>
<ul>
<li>Énergie éolienne (principes de fonctionnement et intégration réseau)</li>
<li>Hydroélectricité (bases de conception et production)</li>
<li>Systèmes CVC pour bâtiments (VRV/VRF, principes de dimensionnement)</li>
</ul>
</div>

</div>
</section>

<section id="projects">
  <h2>Projets</h2>

  <div class="projects-grid">
    <!-- 1. KONE -->
    <div class="project">
      <img src="Projet_kone.jpeg" />
      <div class="project-info">
<p><strong>Février 2026 - A nos jours</strong></p>
        <h4>Superviseur de travaux - Projet de construction du poste 225 kV de la mine d'or de Koné</h4>
        <p><strong>Entreprise :</strong> VINCI Energies Côte d’Ivoire</p>
        <p><strong>Localisation :</strong> Koné, Côte d’Ivoire</p>
        <ul>
          <li>Coordination des travaux BT: tirage et raccordement des câbles du poste de la mine</li>
          <li>Supervision de l’assemblage des équipements électromécaniques</li>
          <li>Elaboration des rapports techniques et des fiches de suivi d'avancement des travaux</li>
          <li>Suivi opérationnel des activités pour assurer la conformité technique</li>
        </ul>
      </div>
    </div>
    <!-- 2. CENTRALE FERKESSE -->
    <div class="project">
      <img src="Projet_ferkesse.jpeg" />
      <div class="project-info">
<p><strong>Septembre 2025 - Février 2026</strong></p>
        <h4>Superviseur de travaux - Projet de construction de la centrale solaire photovoltaïque de 52,44 MWc</h4>
        <p><strong>Entreprise :</strong> VINCI Energies Côte d’Ivoire</p>
        <p><strong>Localisation :</strong> Ferkessédougou, Côte d’Ivoire</p>
        <ul>
          <li>Coordination des travaux BT: tirage et raccordement des câbles du poste électrique</li>
          <li>Supervision des travaux électromécanique et planification des activités sur site</li>
          <li>Participation à la configuration du système de contrôle, commande, et protection du poste de la
centrale</li>
          <li>Suivi des contres essaies réalisées par la Compagnie Ivoirienne d'Electricité</li>
          <li>Rédaction de rapports techniques et procès verbaux de suivi de chantier</li>
        </ul>
      </div>
    </div>
    <!-- 3. EXTENSION FERKESSE -->
    <div class="project">
      <img src="Projet_extension.jpeg" />
      <div class="project-info">
<p><strong>Mars 2025 - Septembre 2025</strong></p>
        <h4>Bureau d'étude - Conception technico-économique de l'extension de la centrale solaire photovoltaïque de 52,44 MWc</h4>
        <p><strong>Entreprise :</strong> VINCI Energies Côte d’Ivoire</p>
        <p><strong>Localisation :</strong> Ferkessédougou, Côte d’Ivoire</p>
        <ul>
          <li>Dimensionnement complet de la centrale photovoltaïque selon deux variantes : structure fixe et
système tracker</li>
          <li>Etude et dimensionnement du système de stockage d'énergie par batterie (BESS)</li>
          <li>Réalisation des schémas électriques et des plans d'implantation des équipements de la centrale</li>
          <li>Analyse financière et évaluation de la rentabilité des différentes solutions</li>
        </ul>
        <p>
          <a href="20190113_DJARABE_Djeramadji Phanuel_S10 GEEI_Janvier 2026.pdf" target="_blank" class="btn-cv">Voir le projet</a>
        </p>
      </div>
    </div>
    <!-- 4. ELECTRIFICATION -->
    <div class="project">
      <img src="Projet_2.jpeg" />
      <div class="project-info">
<p><strong>Février 2025 - Mars 2025</strong></p>
        <h4>Eco-Electrical Service - Conducteur de travaux - Projet d'électrification de 32 localités rurales du
Burkina Faso, Lot 01</h4>
        <p><strong>Entreprise :</strong> Eco-Electrical Service</p>
        <p><strong>Localisation :</strong> Burkina Faso</p>
        <ul>
          <li> Suivi et coordination des travaux d'exécution des réseaux électriques HTA/BT sur le terrain</li>
          <li>Réalisation des opérations de réception de piquetage et contrôle de conformité des implantations</li>
        </ul>
      </div>
    </div>
    <!-- 5. ZAGTOULI (SANS IMAGE) -->
    <div class="project">
      <div class="project-info">
<p><strong>Juillet 2023-Septembre 2023</strong></p>
        <h4> Bureau d'étude - Electrification de zone non lotie de Zagtouli</h4>
        <p><strong>Entreprise :</strong> SONABEL</p>
        <p><strong>Localisation :</strong> Burkina Faso</p>
        <ul>
          <li>Etude du réseau de distribution pour la zone non lotie de Zagtouli</li>
          <li>Dimensionnement de la ligne HTA, du réseau BT et réalisation du carnet de piquetage</li>
          <li>Réalisation du devis quantitatif et estimatif</li>
        </ul>
      </div>
    </div>

  </div>
</section>

<section id="experience">
<h2>Expérience Professionnelle</h2>

<div style="display:flex; align-items:center; gap:15px; margin-bottom:15px;">
  <img src="vinci.jpeg" style="width:50px; height:50px; object-fit:contain;">
  <div>
    <strong>Vinci Energies Côte d’Ivoire</strong><br>
    Ingénieur Études et Travaux – Stage Professionnel
  </div>
</div>
<div style="display:flex; align-items:center; gap:15px; margin-bottom:15px;">
  <img src="vinci.jpeg" style="width:50px; height:50px; object-fit:contain;">
  <div>
    <strong>Vinci Energies Côte d’Ivoire</strong><br>
    Ingénieur Études – Stage PFE
  </div>
</div>
<div style="display:flex; align-items:center; gap:15px; margin-bottom:15px;">
  <img src="eco.jpeg" style="width:50px; height:50px; object-fit:contain;">
  <div>
    <strong>Eco-Electrial Service</strong><br>
    Ingénieur Études et Travaux – Stage d'apprentissage
  </div>
</div>
<div style="display:flex; align-items:center; gap:15px; margin-bottom:15px;">
  <img src="sonabel.jpeg" style="width:50px; height:50px; object-fit:contain;">
  <div>
    <strong>SONABEL</strong><br>
    Stage académique
  </div>
</div>
</section>

<section id="education">
<h2>Formation</h2>
<ul>
<li>Master – Génie Électrique, Énergétique et Industriel, Institut 2iE (2023 - 2026)</li>
<li>Bachelor – Génie Électrique, Institut 2iE (2022 - 2023)</li>
<li>Classes Préparatoires – Institut 2iE (2019 - 2021)</li>
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
<strong>Dr Aboubakar GOMNA</strong> | Enseignant chercheur département GEEI (Institut 2iE) |
📞 +226 51 98 24 20 |
✉️ <a href="mailto:aboubakar.gomna@2ie-edu.org">aboubakar.gomna@2ie-edu.org</a>
</li>
<li>
<strong>Roland TIAPANI</strong> | Responsable bureau d'étude OMEXOM Poste, Ligne et Centrale (VECI) | 📞 +225 07 87 751 275 |
✉️ <a href="mailto:roland.tiapani@omexom.com">roland.tiapani@omexom.com</a>
</li>
<li>
<strong>Ing. TRAORE K. Aichatou</strong> | Responsable CCN (VECI) |
📞 +225 07 58 853 668 |
✉️ <a href="mailto:aichatou.traore@omexom.com">aichatou.traore@omexom.com</a>
</li>
</ul>
</section>

<footer>
© 2026 Djarabé Djeramadji Phanuel — Tous droits réservés.
</footer>

</body>
</html>
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/anchor-js/4.1.0/anchor.min.js" integrity="sha256-lZaRhKri35AyJSypXXs4o6OPFTbTmUoltBbDCbdzegg=" crossorigin="anonymous"></script>
    <script>anchors.add();</script>
  </body>
</html>
