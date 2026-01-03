---
layout: home
title: ""
show_posts: false
---

<!-- Header: Photo + Name + Title + Description -->
<div style="
      display:flex;
      align-items:flex-start;
      margin-bottom:30px;
      flex-wrap:wrap;
      gap:20px;
  ">
  
  <!-- Avatar image -->
  <img src="{{ '/assets/images/Muataz.jpg' | relative_url }}" 
     alt="Muataz Albadri"
     style="width:140px; height:140px; border-radius:50%; object-fit:cover; border: 3px solid #2C3E50;"
>


  <!-- Text container -->
  <div style="flex:1; min-width:200px;">
    <h1 style="margin:0; font-size:2.5rem; color:#222222;">Muataz Albadri</h1>
    <h3 style="margin:5px 0 10px; font-weight:normal; color:#2C3E50; font-size:1.25rem;">
      R&D Engineer & Scan-to-BIM Specialist
    </h3>
    <p style="color:#555555; margin-top:0; font-size:1rem; line-height:1.5;">
      I help engineering firms, contractors, and asset owners convert reality data into reliable digital twins and automated BIM workflows that reduce delivery time, minimize errors, and improve decision-making.
    </p>
  </div>
</div>


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

<section>
  <h2>Technical Demonstration</h2>
  <video autoplay muted loop playsinline>
    <source src="assets/demo.mp4" type="video/mp4">
  </video>
  <p>
    Demonstrating Scan-to-BIM automation, AI segmentation, and BIM scripting workflows.
  </p>
</section>

<section>
  <h2>Selected Engagements</h2>
  <ul>
    <li><strong>Automated Indoor Scan-to-BIM</strong> — reduced modeling time by over 60%</li>
    <li><strong>AI-Based Object Recognition</strong> — integrated segmentation into BIM workflows</li>
    <li><strong>Enterprise BIM Automation</strong> — reusable pipelines for large-scale projects</li>
  </ul>
</section>

<section>
  <h2>Portfolio & Credentials</h2>
  <a href="assets/portfolio.pdf" target="_blank" class="button">
    Download Consultant Portfolio
  </a>
</section>

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
