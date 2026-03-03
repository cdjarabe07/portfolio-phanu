:root {
  --bg-dark: #0d0d0d;
  --bg-light: #181818;
  --text: #f5f5f5;
  --accent: #ffd369;
  --muted: #999;
}

/* RESET */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: "Poppins", Arial, sans-serif;
  background-color: var(--bg-dark);
  color: var(--text);
  line-height: 1.6;
}

/* GLOBAL CONTAINER */
.container {
  max-width: 1400px;
  margin: 0 auto;
  padding: 0 20px;
}

/* LINKS */
a {
  color: var(--accent);
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

/* NAVIGATION */
nav {
  position: fixed;
  top: 0;
  width: 100%;
  background-color: rgba(10, 10, 10, 0.95);
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 12px 5%;
  z-index: 1000;
  backdrop-filter: blur(10px);
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
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
  transition: 0.3s;
}

.btn-cv:hover {
  background: #ffe69d;
  transform: scale(1.05);
}

/* HEADER */
header {
  padding: 180px 5% 120px;
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
  max-width: 800px;
  margin: 20px auto;
  color: #ccc;
  font-style: italic;
}

/* SECTIONS */
section {
  padding: 80px 5%;
  margin-bottom: 60px;
}

section:nth-child(even) {
  background-color: var(--bg-light);
}

h2 {
  color: var(--accent);
  margin-bottom: 30px;
}

h3 {
  margin-bottom: 15px;
}

/* GRID 2 */
.grid-2 {
  display: grid;
  grid-template-columns: 1fr;
  gap: 40px;
}

@media (min-width: 900px) {
  .grid-2 {
    grid-template-columns: 1fr 1fr;
  }
}

/* LIST STYLE */
ul {
  list-style: none;
  margin-top: 10px;
}

ul li {
  margin-bottom: 6px;
}

ul li::before {
  content: "• ";
  color: var(--accent);
}

/* PROJECTS GRID */
.projects-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 30px;
}

/* TABLET */
@media (min-width: 700px) {
  .projects-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

/* DESKTOP */
@media (min-width: 1100px) {
  .projects-grid {
    grid-template-columns: repeat(3, 1fr);
  }
}

/* 4e projet pleine largeur tablette + desktop */
@media (min-width: 700px) {
  .project:nth-child(4) {
    grid-column: 1 / -1;
  }
}

/* PROJECT CARD */
.project {
  background-color: #111;
  border-radius: 12px;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  transition: 0.3s ease;
}

.project:hover {
  transform: translateY(-6px);
  box-shadow: 0 10px 25px rgba(255, 211, 105, 0.15);
}

/* IMAGE CONTAINER */
.project-image {
  width: 100%;
  height: 220px;
  background-color: #000;
  display: flex;
  align-items: center;
  justify-content: center;
}

.project-image img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}

/* PROJECT INFO */
.project-info {
  padding: 20px;
}

.project-info h4 {
  color: var(--accent);
  margin-bottom: 10px;
  word-break: break-word;
}

.project-info p {
  margin-bottom: 10px;
  color: #ccc;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 30px;
  background-color: #0b0b0b;
  color: #aaa;
}
