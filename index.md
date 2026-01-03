---
layout: home
title: ""
show_posts: false
---

<style>
/* ======================================================
   DESIGN SYSTEM
   ====================================================== */
:root {
  --bg-main: #0B0D12;
  --bg-surface: #141821;
  --bg-soft: #1A1F2B;

  --text-main: #E6E8EB;
  --text-muted: #A0A4AB;

  --accent: #4C78A8;
  --accent-soft: #8FB3D9;

  --border: #2A2E38;
}

/* ======================================================
   BASE
   ====================================================== */
body {
  margin: 0;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  line-height: 1.65;
  color: var(--text-main);
  background: radial-gradient(
    circle at top right,
    #1E2A3A 0%,
    var(--bg-main) 55%
  );
}

a {
  color: var(--accent);
  text-decoration: none;
}

a:hover {
  color: var(--accent-soft);
}

/* ======================================================
   CONTAINER
   ====================================================== */
.container {
  max-width: 1240px;
  margin: 0 auto;
  padding: 72px 32px;
}

@media (max-width: 768px) {
  .container {
    padding: 56px 24px;
  }
}

@media (max-width: 480px) {
  .container {
    padding: 44px 20px;
  }
}

/* ======================================================
   HERO
   ====================================================== */
.hero {
  display: grid;
  grid-template-columns: auto 1fr;
  gap: 36px;
  align-items: center;
  margin-bottom: 88px;
}

.hero img {
  width: 240px;
  height: 240px;
  border-radius: 50%;
  border: 3px solid var(--border);
  box-shadow: 0 0 40px rgba(76,120,168,0.28);
  object-fit: cover;
}

.hero h1 {
  margin: 0;
  font-size: 3rem;
  white-space: nowrap;
}

.hero h2 {
  margin: 10px 0 20px;
  font-size: 1.35rem;
  font-weight: 400;
  color: var(--accent);
}

.hero p {
  max-width: 700px;
  font-size: 1.05rem;
  color: var(--text-muted);
}

/* Tablet */
@media (max-width: 900px) {
  .hero h1 {
    font-size: 2.4rem;
  }

  .hero img {
    width: 200px;
    height: 200px;
  }
}

/* Mobile */
@media (max-width: 600px) {
  .hero {
    grid-template-columns: 1fr;
    text-align: center;
  }

  .hero img {
    margin: 0 auto 20px;
    width: 160px;
    height: 160px;
  }

  .hero h1 {
    white-space: normal;
    font-size: 2rem;
  }

  .hero p {
    text-align: left;
  }
}

/* ======================================================
   SECTIONS
   ====================================================== */
section {
  background: linear-gradient(180deg, var(--bg-surface), var(--bg-soft));
  border: 1px solid var(--border);
  border-radius: 12px;
  padding: 42px;
  margin-bottom: 48px;
}

section h2 {
  margin-top: 0;
  font-size: 1.8rem;
}

@media (max-width: 600px) {
  section {
    padding: 28px 22px;
  }

  section h2 {
    font-size: 1.55rem;
  }
}

/* ======================================================
   SERVICES
   ====================================================== */
.services {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 24px;
}

.service {
  background: rgba(255,255,255,0.02);
  border: 1px solid var(--border);
  border-radius: 10px;
  padding: 24px;
}

.service span {
  display: block;
  margin-bottom: 8px;
  font-weight: 600;
  color: var(--accent);
}

/* ======================================================
   BUTTON
   ====================================================== */
.button {
  display: inline-block;
  margin-top: 22px;
  padding: 14px 34px;
  font-weight: 600;
  color: #fff;
  background: linear-gradient(135deg, var(--accent), #5A8BC0);
  border-radius: 6px;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.button:hover {
  transform: translateY(-2px);
  box-shadow: 0 12px 30px rgba(76,120,168,0.35);
}

/* ======================================================
   PROJECTS
   ====================================================== */
.project-title {
  font-weight: 600;
  color: var(--accent-soft);
}

/* ======================================================
   VIDEO
   ====================================================== */
video {
  width: 100%;
  max-height: 480px;
  border-radius: 10px;
  border: 1px solid var(--border);
  object-fit: cover;
}

@media (max-width: 600px) {
  video {
    max-height: 300px;
  }
}

/* ======================================================
   FOOTER
   ====================================================== */
footer {
  text-align: center;
  padding: 56px 20px;
  font-size: 0.9rem;
  color: var(--text-muted);
}

/* ======================================================
   HERO – MOBILE IMAGE ABOVE NAME
 ====================================================== */

@media (max-width: 600px) {
  .hero {
    grid-template-columns: 1fr;
    justify-items: center;
    text-align: center;
  }

  .hero img {
    margin-bottom: 16px;
  }

  .hero h1 {
    margin-top: 0;
  }

  .hero h2 {
    margin-top: 6px;
  }

  .hero p {
    margin-top: 14px;
    text-align: left; /* better readability on mobile */
  }
}

</style>

<div class="container">

  <!-- HERO -->
  <div class="hero">
    <img src="assets/images/Muataz.jpg" alt="Muataz Albadri">
    <div>
      <h1>Muataz Albadri</h1>
      <h2>R&D Engineer & Scan-to-BIM Specialist</h2>
      <p>
        I help engineering firms, contractors, and asset owners convert reality
        data into reliable digital twins and automated BIM workflows that reduce
        delivery time, minimize errors, and improve decision-making.
      </p>
    </div>
  </div>

  <!-- SERVICES -->
  <section>
    <h2>Consulting Services</h2>
    <div class="services">
      <div class="service">
        <span>Scan-to-BIM</span>
        Point clouds to Revit / IFC models with structured semantics and QA-ready outputs.
      </div>
      <div class="service">
        <span>AI for Reality Data</span>
        Automated detection of building elements from point clouds.
      </div>
      <div class="service">
        <span>BIM Automation</span>
        Python, Dynamo, and Revit API pipelines for scalable production.
      </div>
      <div class="service">
        <span>Digital Twins</span>
        Operational-ready BIM models connected to analytics platforms.
      </div>
    </div>
  </section>

  <!-- DEMO -->
  <section>
    <h2>Technical Demonstration</h2>
    <video autoplay muted loop playsinline>
      <source src="assets/demo.mp4" type="video/mp4">
    </video>
    <p style="margin-top:14px; color:var(--text-muted);">
      Demonstrating Scan-to-BIM automation, AI segmentation, and BIM scripting workflows.
    </p>
  </section>

  <!-- PROJECTS -->
  <section>
    <h2>Selected Engagements</h2>
    <ul>
      <li>
        <span class="project-title">Automated Indoor Scan-to-BIM</span><br>
        Reduced modeling time by over 60%.
      </li>
      <li>
        <span class="project-title">AI-Based Object Recognition</span><br>
        Integrated segmentation into BIM authoring workflows.
      </li>
      <li>
        <span class="project-title">Enterprise BIM Automation</span><br>
        Delivered reusable pipelines for large-scale projects.
      </li>
    </ul>
  </section>

  <!-- PORTFOLIO -->
  <section>
    <h2>Portfolio & Credentials</h2>
    <a href="assets/portfolio.pdf" target="_blank" class="button">
      Download Consultant Portfolio
    </a>
  </section>

  <!-- CONTACT -->
  <section>
    <h2>Contact</h2>
    <p>Email: your@email.com</p>
    <p>
      LinkedIn:
      <a href="https://www.linkedin.com/in/muataz-albadri-2290381a4/" target="_blank">
        linkedin.com/in/muataz-albadri
      </a>
    </p>
  </section>

</div>

<footer>
  © {{ site.time | date: "%Y" }} Muataz Albadri · Scan-to-BIM & AI Consulting
</footer>
