---
layout: home
title: ""
show_posts: false
---

<style>
body {
    background-color: #F5F6FA; /* light gray background */
    color: #222222;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

.container {
    max-width: 1000px;
    margin: 0 auto;
    padding: 20px;
}

/* Card-style sections */
section {
    background-color: #FFFFFF;
    padding: 30px;
    margin: 20px 0;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
}

/* Header */
.header {
    display: flex;
    align-items: center;
    margin-bottom: 30px;
}

.header img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    margin-right: 20px;
    object-fit: cover;
}

.header h1 {
    margin: 0;
    color: #222222;
    font-size: 2rem;
}

.header h3 {
    margin: 5px 0 0;
    font-weight: normal;
    color: #2C3E50; /* professional dark blue */
}

.header p {
    margin: 5px 0 0;
    color: #555555;
    font-size: 0.95rem;
}

/* Service list */
.services span {
    color: #2C3E50;
    font-weight: bold;
}

/* Buttons */
.button {
    background-color: #2C3E50; /* professional dark blue */
    color: #FFFFFF;
    padding: 12px 25px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    transition: background-color 0.3s;
}

.button:hover {
    background-color: #34495E; /* hover effect */
}

/* Project highlights */
.project-title {
    color: #FF6B6B; /* subtle accent for highlights */
    font-weight: bold;
}

/* Demo video */
video {
    width: 100%;
    max-width: 900px;
    border-radius: 8px;
    margin-bottom: 20px;
}
</style>

<div class="container">

  <!-- Header -->
  <div class="header">
    <img src="assets/images/Muataz.jpg" alt="Muataz Albadri">
    <div>
      <h1>Muataz Albadri</h1>
      <h3>Scan-to-BIM & AI Automation Specialist</h3>
      <p>Transforming reality data into actionable digital models</p>
    </div>
  </div>

  <!-- Welcome Section -->
  <section>
    <h2>Welcome</h2>
    <p style="color:#555555;">
      I help <strong>engineering, construction, and asset management companies</strong> turn reality data into <strong>accurate BIM models</strong> and <strong>automated digital workflows</strong>. My expertise delivers <strong>fast, reliable, and intelligent solutions</strong> for the built environment.
    </p>
  </section>

  <!-- What I Do -->
  <section>
    <h2>What I Do</h2>
    <ul class="services">
      <li>🔹 <span>Scan-to-BIM</span>: Point clouds → Revit / IFC</li>
      <li>🔹 <span>AI & Automation</span>: Object segmentation, condition assessment</li>
      <li>🔹 <span>BIM Automation</span>: Python, Dynamo, Revit pipelines</li>
      <li>🔹 <span>Digital Twin & Visualization</span>: Interactive BIM models & dashboards</li>
    </ul>
  </section>

  <!-- Demo Reel -->
  <section>
    <h2>Demo Reel</h2>
    <video autoplay muted loop playsinline poster="assets/demo-poster.jpg">
      <source src="assets/demo.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="color:#555555;">*Showcasing Scan-to-BIM, AI segmentation, and BIM automation workflows.*</p>
  </section>

  <!-- Selected Projects -->
  <section>
    <h2>Selected Projects</h2>
    <ul>
      <li>
        <span class="project-title">Automated Scan-to-BIM for Indoor Environments</span><br>
        → Converted point clouds to intelligent Revit models, reducing modeling time by 60%.
      </li>
      <li>
        <span class="project-title">AI-based Object Detection from Point Clouds</span><br>
        → Detected walls, windows, doors, and furniture; integrated results into BIM workflow.
      </li>
      <li>
        <span class="project-title">BIM Automation Pipelines</span><br>
        → Scripts for automated modeling and clash detection; streamlined delivery for multi-building projects.
      </li>
    </ul>
  </section>

  <!-- Portfolio Download -->
  <section>
    <h2>Download Portfolio</h2>
    <p>
      <a href="assets/portfolio.pdf" target="_blank" class="button">Download PDF Portfolio</a>
    </p>
  </section>

  <!-- Contact Section -->
  <section>
    <h2>Contact</h2>
    <ul>
      <li>Email: your@email.com</li>
      <li>LinkedIn: <a href="https://www.linkedin.com/in/muataz-albadri/" target="_blank">linkedin.com/in/muataz-albadri-2290381a4</a></li>
      <li>GitHub: <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></li>
    </ul>
  </section>

</div>
