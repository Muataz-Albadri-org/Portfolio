---
layout: home
title: ""
show_posts: false
---
<style>
/* Global */
body {
    background-color: #0F1115; /* deep dark background */
    color: #E6E8EB;            /* light gray text */
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

/* Layout */
.container {
    max-width: 1000px;
    margin: 0 auto;
    padding: 20px;
}

/* Card-style sections */
section {
    background-color: #1A1D24; /* dark card */
    padding: 30px;
    margin: 20px 0;
    border-radius: 8px;
    box-shadow: 0 6px 18px rgba(0,0,0,0.6);
    border: 1px solid #2A2E38;
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
    border: 2px solid #2A2E38;
}

.header h1 {
    margin: 0;
    color: #FFFFFF;
    font-size: 2rem;
}

.header h3 {
    margin: 5px 0 0;
    font-weight: normal;
    color: #4C78A8; /* professional accent */
}

.header p {
    margin: 5px 0 0;
    color: #A0A4AB;
    font-size: 0.95rem;
}

/* Service list */
.services span {
    color: #4C78A8;
    font-weight: bold;
}

/* Buttons */
.button {
    background-color: #4C78A8;
    color: #FFFFFF;
    padding: 12px 25px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    transition: background-color 0.3s, transform 0.2s;
}

.button:hover {
    background-color: #5A8BC0;
    transform: translateY(-1px);
}

/* Project highlights */
.project-title {
    color: #8FB3D9; /* muted highlight */
    font-weight: bold;
}

/* Demo video */
video {
    width: 100%;
    max-width: 900px;
    border-radius: 8px;
    margin-bottom: 20px;
    border: 1px solid #2A2E38;
}
</style>


<div class="container">

  <!-- Header -->
  <div class="header">
    <img src="assets/images/Muataz.jpg" alt="Muataz Albadri">
    <div>
      <h1>Muataz Albadri</h1>
      <h3>Scan-to-BIM & AI Automation Specialist</h3>
      
    </div>
  </div>

  <!-- Welcome Section -->
  <section>
    <h2>Welcome</h2>
    <p style="color:#555555;">          
        We help <strong>engineering, construction, and asset management stakeholders</strong> transform unstructured reality data into <strong>information-rich digital models</strong> and <strong>automated digital workflows</strong>.
    </p>
  </section>

  <!-- What I Do -->
  <section>
    <h2>What We Do</h2>
    <ul class="services">
      <li> <span>Scan-to-BIM</span>: Point clouds → Revit / IFC</li>
      <li> <span>AI & Automation</span>: Object segmentation, condition assessment</li>
      <li> <span>BIM Automation</span>: Python, Dynamo, Revit pipelines</li>
      <li> <span>Digital Twin & Visualization</span>: Interactive BIM models & dashboards</li>
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
      <li>LinkedIn: 
  <a href="https://www.linkedin.com/in/muataz-albadri-2290381a4/" target="_blank">
    linkedin.com/in/muataz-albadri</a></li>
    </ul>
  </section>

</div>
<footer>
  <ul>
    <li>
      <a href="{{ site.baseurl }}/feed.xml" target="_blank">
        <i class="fas fa-rss"></i> Subscribe
      </a>
    </li>
    {% for link in site.author.links %}
      <li>
        <a href="{{ link.url }}" target="_blank">
          <i class="{{ link.icon }}"></i> {{ link.label }}
        </a>
      </li>
    {% endfor %}
  </ul>
</footer>
