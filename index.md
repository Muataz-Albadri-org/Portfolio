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
       HERO
  ========================== -->
  <section style="margin-bottom:60px;">

    <div style="
      display:flex;
      flex-direction:column;
      align-items:center;
      text-align:center;
      gap:20px;
    ">

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

      <div>
        <h1 style="margin:0;">Muataz Albadri</h1>
        <h3 style="
          margin:6px 0 0;
          font-weight:400;
          color:#666;
        ">
          R&amp;D Engineer &amp; Scan-to-BIM Specialist
        </h3>
      </div>

      <p style="
        max-width:760px;
        margin-top:24px;
        text-align:justify;
        text-justify:inter-word;
        hyphens:auto;
      ">
        I help engineering firms, contractors, and asset owners transform reality capture
        data into reliable digital twins and automated BIM workflows. My work focuses on
        reducing delivery time, minimizing modeling errors, and enabling data-driven
        decision-making across the asset lifecycle.
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
        <span>Scan-to-BIM</span>
        <p style="
          margin:8px 0 0;
          text-align:justify;
          hyphens:auto;
        ">
          Conversion of point clouds into Revit and IFC models with structured semantics,
          modeling standards compliance, and quality-assurance–ready deliverables.
        </p>
      </div>

      <div class="service">
        <span>AI for Reality Data</span>
        <p style="
          margin:8px 0 0;
          text-align:justify;
          hyphens:auto;
        ">
          Automated detection and classification of building elements from laser scanning
          and photogrammetric data using AI-assisted workflows.
        </p>
      </div>

      <div class="service">
        <span>BIM Automation</span>
        <p style="
          margin:8px 0 0;
          text-align:justify;
          hyphens:auto;
        ">
          Development of scalable production pipelines using Python, Dynamo, and the Revit
          API to standardize and accelerate BIM delivery.
        </p>
      </div>

      <div class="service">
        <span>Digital Twins</span>
        <p style="
          margin:8px 0 0;
          text-align:justify;
          hyphens:auto;
        ">
          Creation of operational-ready BIM models integrated with analytics and asset
          management platforms to support informed operational decisions.
        </p>
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
        margin:20px 0;
        border-radius:8px;
        display:block;
      "
    >
      <source src="assets/demo.mp4" type="video/mp4">
    </video>

    <p style="
      max-width:900px;
      text-align:justify;
      hyphens:auto;
    ">
      Demonstration of Scan-to-BIM automation workflows, AI-based semantic segmentation,
      and BIM scripting pipelines applied to real-world project data.
    </p>
  </section>

  <!-- =========================
       EXPERIENCE
  ========================== -->
  <section style="margin-bottom:60px;">
    <h2>Selected Engagements</h2>

    <ul style="
      max-width:900px;
      text-align:justify;
      hyphens:auto;
    ">
      <li>
        <strong>Automated Indoor Scan-to-BIM</strong> — Achieved a reduction in modeling
        time exceeding 60% through automation and standardized workflows.
      </li>
      <li>
        <strong>AI-Based Object Recognition</strong> — Integrated semantic segmentation
        outputs directly into downstream BIM authoring processes.
      </li>
      <li>
        <strong>Enterprise BIM Automation</strong> — Delivered reusable, production-ready
        pipelines supporting large-scale and multi-site projects.
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
