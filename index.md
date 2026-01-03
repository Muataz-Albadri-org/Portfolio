---
layout: home
title: ""
show_posts: false
---
<div style="
  max-width:1100px;
  margin:0 auto;
  padding:40px 20px;
">

  <!-- =========================
       HERO SECTION
  ========================== -->
  <section style="margin-bottom:60px;">

    <div style="
      display:flex;
      flex-direction:column;
      align-items:center;
      text-align:center;
      gap:20px;
    ">

      <!-- Avatar -->
      <img
        src="{{ '/assets/images/Muataz.jpg' | relative_url }}"
        alt="Muataz Albadri"
        style="
          width:150px;
          height:150px;
          border-radius:50%;
          object-fit:cover;
          border:3px solid #2C3E50;
        "
      >

      <!-- Name & Title -->
      <div>
        <h1 style="margin:0;">
          Muataz Albadri
        </h1>
        <h3 style="
          margin:6px 0 0;
          font-weight:400;
          color:#666;
        ">
          R&amp;D Engineer &amp; Scan-to-BIM Specialist
        </h3>
      </div>

      <!-- Summary -->
      <p style="
        max-width:720px;
        margin-top:20px;
      ">
        I help engineering firms, contractors, and asset owners convert reality data into
        reliable digital twins and automated BIM workflows that reduce delivery time,
        minimize errors, and improve decision-making.
      </p>

    </div>
  </section>

  <!-- =========================
       SERVICES
  ========================== -->
  <section style="margin-bottom:60px;">
    <h2>Consulting Services</h2>

    <div class="services">
      <div class="service">
        <span>Scan-to-BIM</span><br>
        Point clouds to Revit / IFC models with structured semantics and QA-ready outputs.
      </div>

      <div class="service">
        <span>AI for Reality Data</span><br>
        Automated detection and classification of building elements from point clouds.
      </div>

      <div class="service">
        <span>BIM Automation</span><br>
        Python, Dynamo, and Revit API pipelines for scalable production environments.
      </div>

      <div class="service">
        <span>Digital Twins</span><br>
        Operational-ready BIM models connected to analytics and asset management platforms.
      </div>
    </div>
  </section>

  <!-- =========================
       TECHNICAL DEMO
  ========================== -->
  <section style="margin-bottom:60px;">
    <h2>Technical Demonstration</h2>

    <video
      autoplay
      muted
      loop
      playsinline
      style="
        width:100%;
        max-width:900px;
        border-radius:8px;
        margin:20px 0;
      "
    >
      <source src="assets/demo.mp4" type="video/mp4">
    </video>

    <p>
      Demonstration of Scan-to-BIM automation, AI-based segmentation,
      and BIM scripting workflows applied to real project data.
    </p>
  </section>

  <!-- =========================
       EXPERIENCE
  ========================== -->
  <section style="margin-bottom:60px;">
    <h2>Selected Engagements</h2>

    <ul>
      <li>
        <strong>Automated Indoor Scan-to-BIM</strong>
        — Reduced modeling time by more than 60%.
      </li>
      <li>
        <strong>AI-Based Object Recognition</strong>
        — Integrated semantic segmentation into BIM workflows.
      </li>
      <li>
        <strong>Enterprise BIM Automation</strong>
        — Delivered reusable pipelines for large-scale projects.
      </li>
    </ul>
  </section>

  <!-- =========================
       PORTFOLIO
  ========================== -->
  <section style="margin-bottom:60px;">
    <h2>Portfolio &amp; Credentials</h2>

    <a
      href="assets/portfolio.pdf"
      target="_blank"
      class="button"
    >
      Download Consultant Portfolio
    </a>
  </section>

  <!-- =========================
       CONTACT
  ========================== -->
  <section>
    <h2>Contact</h2>

    <p>Email: your@email.com</p>

    <p>
      LinkedIn:
      <a
        href="https://www.linkedin.com/in/muataz-albadri-2290381a4/"
        target="_blank"
      >
        linkedin.com/in/muataz-albadri
      </a>
    </p>
  </section>

</div>

<footer style="
  text-align:center;
  padding:20px 0;
  color:#777;
">
  © {{ site.time | date: "%Y" }} Muataz Albadri · Scan-to-BIM &amp; AI Consulting
</footer>
