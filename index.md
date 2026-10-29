---
layout: default
title: Ana C. Murrieta
description: Doctoral researcher
---

<style>
  .profile-hero {
    display: flex;
    align-items: center;
    gap: 2rem;
    margin: 2rem 0 3rem;
    flex-wrap: wrap;
  }

  .profile-photo {
    width: 220px;
    height: 220px;
    object-fit: cover;
    border-radius: 50%;
    border: 4px solid #eaecef;
    box-shadow: 0 8px 24px rgba(0,0,0,0.12);
    background: #f7f7f7;
  }

  .profile-text h1 {
    margin-bottom: 0.5rem;
  }

  .profile-text h2 {
    margin-top: 0;
    margin-bottom: 1rem;
    font-size: 1.2rem;
    color: #586069;
    font-weight: normal;
  }

  .social-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
    margin-top: 1rem;
  }

  .social-links a {
    display: inline-block;
    padding: 0.45rem 0.9rem;
    border-radius: 999px;
    background: #f0f6ff;
    border: 1px solid #d0d7de;
    color: #0366d6;
    text-decoration: none;
    font-size: 0.9rem;
    font-weight: 600;
  }

  .social-links a:hover {
    background: #eaf3ff;
  }

  .section-card {
    margin: 2.5rem 0;
    padding: 1.5rem 1.25rem;
    border: 1px solid #e1e4e8;
    border-radius: 12px;
    background: #fff;
    box-shadow: 0 2px 10px rgba(27,31,35,0.04);
  }

  .section-card h3 {
    margin-top: 0;
    margin-bottom: 1rem;
    color: #24292e;
  }

  .two-columns {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 1rem;
  }

  .mini-card {
    padding: 1rem;
    border: 1px solid #e1e4e8;
    border-radius: 10px;
    background: #fafbfc;
  }

  .mini-card h4 {
    margin-top: 0;
    margin-bottom: 0.5rem;
  }

  .publication-list,
  .conference-list,
  .awards-list,
  .volunteering-list {
    list-style: none;
    padding-left: 0;
    margin: 0;
  }

  .publication-list li,
  .conference-list li,
  .awards-list li,
  .volunteering-list li {
    margin-bottom: 0.85rem;
    padding-bottom: 0.85rem;
    border-bottom: 1px solid #eef1f4;
  }

  .publication-list li:last-child,
  .conference-list li:last-child,
  .awards-list li:last-child,
  .volunteering-list li:last-child {
    margin-bottom: 0;
    padding-bottom: 0;
    border-bottom: none;
  }

  .muted {
    color: #586069;
  }

  @media (max-width: 600px) {
    .profile-photo {
      width: 180px;
      height: 180px;
    }
  }
</style>

<div class="profile-hero">
  <img class="profile-photo" src="{{ '/assets/20260428_004056000_iOS 1.jpg' | relative_url }}" alt="Ana C. Murrieta photo">
  <div class="profile-text">
    <h1>Ana C. Murrieta</h1>
    <h2>PhD Student in Nanotechnology | Tecnológico de Monterrey</h2>
    <p>
      I am a PhD student interested in computational drug discovery, with a focus on
      obesity and metabolic syndrome. My work combines chemoinformatics,
      machine learning, molecular docking and molecular dynamics to explore integral computational
      approaches to find the next generation of therapies.
    </p>
    <div class="social-links">
      <a href="https://github.com/anamurrieta" target="_blank" rel="noopener">GitHub</a>
      <a href="https://www.researchgate.net/profile/Ana-Murrieta" target="_blank" rel="noopener">ResearchGate</a>
      <a href="https://orcid.org/0000-0002-7619-8880" target="_blank" rel="noopener">ORCID</a>
      <a href="https://scholar.google.com/citations?user=D2Vv2hAAAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar</a>
      <a href="https://www.linkedin.com/in/ana-murrieta" target="_blank" rel="noopener">LinkedIn</a>
    </div>
  </div>
</div>

<div class="section-card">
  <h3>Research Line</h3>
  <div class="two-columns">
    <div class="mini-card">
      <h4>Main focus</h4>
      <p>
        Create integral and robust computational pipelines to aid in drug discovery for diseases, with a particular focus on obesity and metabolic syndrome.
      </p>
    </div>
    <div class="mini-card">
      <h4>Methods</h4>
      <p>
        <p><strong>Chemoinformatics:</strong></p> Molecular descriptors, dimensionality reduction techniques, visualization methods, and scaffold analysis.
        <p><strong>Machine learning:</strong></p> Support vector classifier, random forest, extreme gradient boosting and deep neural networks algorithms for binary classification.
        <p><strong>Molecular docking:</strong></p> AutoDock Vina, LeDock, PyMOL, Chimera.
        <p><strong>Molecular dynamics:</strong></p> CHARMM-GUI, AMBER, CPPTRAJ, MMPBSA.py.
        <p><strong>Figures:</strong></p> Python, Adobe, PyMOL.
      </p>
    </div>
    <div class="mini-card">
      <h4>Motivation</h4>
      <p>
        I am highly motivated to contribute in discovering the next generation of therapies that will solve many health problems
        and improve the quality of life of people, through rigorous, data-driven, and multidisciplinary research.
      </p>
    </div>
    <div class="mini-card">
      <h4>Current interests</h4>
      <p>
        Drug discovery, chemoinformatics, AI for health, molecular modeling, nanomaterials
      </p>
    </div>

<div class="section-card">
  <h3>GitHub Developments / Projects</h3>
  <div class="two-columns">
    <div class="mini-card">
      <h4>Computational Drug Discovery</h4>
      <p><strong>AI and chemoinformatics workflows</strong></p>
      <p class="muted">Development of computational approaches for molecular screening, feature analysis, and model interpretation in drug discovery.</p>
      <p><a href="https://github.com/anamurrieta" target="_blank" rel="noopener">Repository</a></p>
    </div>
    <div class="mini-card">
      <h4>Nanotechnology Research</h4>
      <p><strong>Materials and structure-property analysis</strong></p>
      <p class="muted">Research focused on nanomaterials, structural characterization, and the study of material behavior using data-driven methods.</p>
      <p><a href="https://github.com/anamurrieta" target="_blank" rel="noopener">Repository</a></p>
    </div>
    <div class="mini-card">
      <h4>Machine Learning for Health</h4>
      <p><strong>Predictive and interpretable models</strong></p>
      <p class="muted">Application of classification and optimization methods for biomedical and molecular data analysis.</p>
      <p><a href="https://github.com/anamurrieta" target="_blank" rel="noopener">Repository</a></p>
    </div>
    <div class="mini-card">
      <h4>Scientific Computing</h4>
      <p><strong>Reproducible pipelines in Python</strong></p>
      <p class="muted">Automation of workflows, visualization, and analysis in computational chemistry and structural biology projects.</p>
      <p><a href="https://github.com/anamurrieta" target="_blank" rel="noopener">Repository</a></p>
    </div>
  </div>
</div>

<div class="section-card">
  <h3>Selected Publications</h3>
  <ul class="publication-list">
    <li>
      <strong>LigandHub: Web-Based Ligand Preparation and Docking Output Recovery Platform</strong><br>
      <span class="muted">ChemRxiv, 2026</span><br>
      <span>LigandHub is a web-based platform that integrates ligand validation, preparation, batch processing, and docking-output recovery within a unified workflow.</span>
    </li>
    <li>
      <strong>Identification and structural characterization of CB1 receptor antagonists: A comprehensive virtual screening and molecular dynamics study of arachidin-2</strong><br>
      <span class="muted">Biophysical Chemistry, 2025</span><br>
      <span>Computational methods in the discovery and development of novel CB1 modulators.</span>
    </li>
    <li>
      <strong>Mitochondrial Ca overload is a pivotal risk factor for lethal ventricular arrhythmias due to the oxidation of mitochondrial respirasome and energetic failure</strong><br>
      <span class="muted">British Journal of Pharmacology, 2025</span><br>
      <span>Structural characterization of calcium channels with Ru360 and verapamil.</span>
    </li>
  </ul>
</div>

<div class="section-card">
  <h3>Selected Conference Presentations</h3>
  <ul class="conference-list">
    <li>
      <strong>MELITE: Multimodel evaluation of classifiers for chemoinformatics</strong><br>
      <span class="muted">Poster: Congress of the Mexican Chemistry Society. 2026, Oaxaca, México.</span>
    </li>
    <li>
      <strong>Computational identification of 2-arylbenzofuran derivatives as CB1 ligands from the chemical space of natural products</strong><br>
      <span class="muted">Oral talk: Congress of the Mexican Chemistry Society. 2026, Oaxaca, Mexico.</span>
    </li>
    <li>
      <strong>Gender bias in artificial intelligence models in drug development</strong><br>
      <span class="muted">Poster: Internstional Conference of Women Researchers in Iberoamerica. 2025, Tampico, Mexico.</span>
    </li>
  </ul>
</div>

<div class="section-card">
  <h3>Awards and Distinctions</h3>
  <ul class="awards-list">
    <li>
      <strong>Guanajuato State Youth Award: Academy and Science category - Finalist</strong><br>
      <span class="muted">Guanajuato State Youth Institute, 2025</span>
    </li>
    <li>
      <strong>Ludo Frevel Crystallography Scholarship</strong><br>
      <span class="muted">International Centre for Diffraction Data, 2023</span>
    </li>
    <li>
      <strong>Robert L. Snyder Student Award</strong><br>
      <span class="muted">Internatilnal Centre for Diffraction Data, 2022</span>
    </li>
  </ul>
</div>

<div class="section-card">
  <h3>Selected Volunteering</h3>
  <ul class="volunteering-list">
    <li>
      <strong>She in Nano - Mentor</strong><br>
      <span class="muted">Nanotechnology Student Society, Tecnologico de Monterrey. 2026</span><br>
      <span>I mentor a undergrad nanotechnology student in her carrer and academic development and research involvement.</span>
    </li>
    <li>
      <strong>Summer research internship - Instructor</strong><br>
      <span class="muted">DELFIN summer school</span><br>
      <span>I participated in a 7-week summer program with 3 undergraduate students and trained them in computational techniques for drug discovery. 2026</span>
    </li>
    <li>
      <strong>FIRST Robotics Competition - Judge and volunteer</strong><br>
      <span class="muted">FIRST Mexico and FIRST international</span><br>
      <span>Several times a year I volunteer in robotics competitions for middle and high school students. 2018-2026</span>
    </li>
  </ul>
</div>
