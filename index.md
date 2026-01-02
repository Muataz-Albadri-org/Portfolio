---
layout: home
title: ""
show_posts: false
---
<style>
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

body {
  background: radial-gradient(circle at top right, #1E2A3A 0%, var(--bg-main) 55%);
  color: var(--text-main);
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  line-height: 1.65;
  margin: 0;
}

  .container {
  max-width: 1240px;  
  margin: 0 auto;
  padding: 70px 32px;
}



/* HERO */
.hero {
  display: grid;
  grid-template-columns: 140px 1fr;
  gap: 30px;
  align-items: center;
  margin-bottom: 80px;
}

.hero img { 
  width: 240px; 
  height: 240px; 
  border-radius: 50%; 
  border: 3px solid var(--border); 
  box-shadow: 0 0 30px rgba(76,120,168,0.25); 
}
.hero p {
  text-align: justify;
  text-justify: inter-word;
}

.hero h1 {
  font-size: 3rem;
  margin: 0;
}

.hero h2 {
  font-size: 1.35rem;
  font-weight: 400;
  color: var(--accent);
  margin: 8px 0 18px;
}

.hero p {
  max-width: 680px;
  color: var(--text-muted);
  font-size: 1.05rem;
}

/* BUTTONS */
.button {
  display: inline-block;
  margin-top: 20px;
  background: linear-gradient(135deg, var(--accent), #5A8BC0);
  color: #fff;
  padding: 14px 32px;
  border-radius: 6px;
  font-weight: 600;
  text-decoration: none;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.button:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 30px rgba(76,120,168,0.35);
}

/* SECTIONS */
section {
  background: linear-gradient(180deg, var(--bg-surface), var(--bg-soft));
  border: 1px solid var(--border);
  border-radius: 10px;
  padding: 40px;
  margin-bottom: 40px;
}

section h2 {
  margin-top: 0;
  font-size: 1.8rem;
}

/* SERVICES */
.services {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 20px;
}

.service {
  background: rgba(255,255,255,0.02);
  border: 1px solid var(--border);
  border-radius: 8px;
  padding: 20px;
}

.service span {
  color: var(--accent);
  font-weight: 600;
}

/* PROJECTS */
.project-title {
  color: var(--accent-soft);
  font-weight: 600;
}

/* VIDEO */
video {
  width: 100%;
  border-radius: 8px;
  border: 1px solid var(--border);
}

/* FOOTER */
footer {
  margin-top: 80px;
  text-align: center;
  color: var(--text-muted);
  font-size: 0.9rem;
}

.hero h1 {
  white-space: nowrap;
}

@media (max-width: 480px) {
  .hero h1 {
    white-space: normal;
  }
}

  /* ===== NAVIGATION LINKS – FORCE CONSISTENT COLOR ===== */

/* Catch all possible theme selectors */
header a,
header a:visited,
.site-header a,
.site-header a:visited,
.site-title,
.site-nav a,
.page-link {
  color: #E6E8EB !important;
}

/* Hover */
header a:hover,
.site-header a:hover,
.site-nav a:hover,
.page-link:hover {
  color: #4C78A8 !important;
}

/* Active page */
.page-link.active,
header a[aria-current="page"] {
  color: #4C78A8 !important;
  border-bottom: 2px solid #4C78A8;
  padding-bottom: 4px;
}


</style>

<div class="container">

  <!-- HERO -->
  <div class="hero">
    <img src="assets/images/Muataz.jpg" alt="Muataz Albadri">
    <div>
      <h1>Muataz Albadri</h1>
      <h2> R&D Engineer & Scan-to-BIM Specialist </h2>
      <p>
        I help engineering firms, contractors, and asset owners convert
        reality data into reliable digital twins and automated BIM workflows
        that reduce delivery time, minimize errors, and improve decision-making.
      </p>
    </div>
  </div>
  

  <!-- SERVICES -->
  <section>
    <h2>Consulting Services</h2>
    <div class="services">
      <div class="service">
        <span>Scan-to-BIM</span>
        <p>Point clouds to Revit / IFC models with structured semantics and QA-ready outputs.</p>
      </div>
      <div class="service">
        <span>AI for Reality Data</span>
        <p>Automated detection of walls, openings, MEP elements, and assets from point clouds.</p>
      </div>
      <div class="service">
        <span>BIM Automation</span>
        <p>Python, Dynamo, and Revit API pipelines for scalable and repeatable BIM production.</p>
      </div>
      <div class="service">
        <span>Digital Twins</span>
        <p>Operational-ready BIM models connected to analytics and visualization platforms.</p>
      </div>
    </div>
  </section>

  <!-- DEMO -->
  <section>
    <h2>Technical Demonstration</h2>
    <video autoplay muted loop playsinline>
      <source src="assets/demo.mp4" type="video/mp4">
    </video>
    <p style="color:var(--text-muted); margin-top:15px;">
      Demonstrating Scan-to-BIM automation, AI segmentation, and BIM scripting workflows.
    </p>
  </section>

  <!-- PROJECTS -->
  <section>
    <h2>Selected Engagements</h2>
    <ul>
      <li>
        <span class="project-title">Automated Indoor Scan-to-BIM</span><br>
        Reduced manual modeling time by over 60% across multi-storey buildings.
      </li>
      <li>
        <span class="project-title">AI-Based Object Recognition</span><br>
        Integrated point cloud segmentation directly into BIM authoring workflows.
      </li>
      <li>
        <span class="project-title">Enterprise BIM Automation</span><br>
        Developed reusable pipelines for large-scale project delivery.
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
  <section id="contact">
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

