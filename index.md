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
      <strong>Microstructure of polycrystalline gold nanoparticles and thin-films from a comparative X-ray line profile analysis</strong><br>
      <span class="muted">Materials Chemistry and Physics, 2021</span><br>
      <span>Study on structural microstructure and X-ray line profile analysis of polycrystalline gold nanomaterials.</span>
    </li>
    <li>
      <strong>Frustrated folding of guanine quadruplexes in telomeric DNA</strong><br>
      <span class="muted">Nucleic Acids Research, 2021</span><br>
      <span>Investigation of structural folding mechanisms in telomeric DNA and their implications for stability and conformation.</span>
    </li>
    <li>
      <strong>Characterization of hydrothermally synthesized ZnFe2O4 spinel ferrite</strong><br>
      <span class="muted">Journal of Physics and Chemistry of Solids, 2023</span><br>
      <span>Structural and materials characterization of hydrothermally synthesized spinel ferrite compounds.</span>
    </li>
  </ul>
</div>

<div class="section-card">
  <h3>Conference Presentations</h3>
  <ul class="conference-list">
    <li>
      <strong>Computational approaches for nanomaterials and molecular modeling</strong><br>
      <span class="muted">Scientific meetings and research forums, recent years</span>
    </li>
    <li>
      <strong>Machine learning and chemoinformatics in drug discovery</strong><br>
      <span class="muted">Conference presentations and workshops</span>
    </li>
    <li>
      <strong>Structural analysis of advanced materials</strong><br>
      <span class="muted">Research seminars and technical presentations</span>
    </li>
  </ul>
</div>

<div class="section-card">
  <h3>Awards and Distinctions</h3>
  <ul class="awards-list">
    <li>
      <strong>Research participation and academic recognition</strong><br>
      <span class="muted">Tecnológico de Monterrey, ongoing</span>
    </li>
    <li>
      <strong>Academic excellence in nanotechnology research</strong><br>
      <span class="muted">Graduate research training, ongoing</span>
    </li>
    <li>
      <strong>Scientific communication and collaboration</strong><br>
      <span class="muted">Research community and training activities</span>
    </li>
  </ul>
</div>

<div class="section-card">
  <h3>Volunteering</h3>
  <ul class="volunteering-list">
    <li>
      <strong>Mentoring and scientific outreach</strong><br>
      <span class="muted">Academic community</span><br>
      <span>Supporting students and promoting scientific engagement in STEM and research-related activities.</span>
    </li>
    <li>
      <strong>Research collaboration and peer support</strong><br>
      <span class="muted">Collaborative teams</span><br>
      <span>Contributing to interdisciplinary work and helping strengthen collaborative scientific environments.</span>
    </li>
    <li>
      <strong>Education and knowledge sharing</strong><br>
      <span class="muted">Workshops and seminars</span><br>
      <span>Improving access to research methods and scientific learning for students and peers.</span>
    </li>
  </ul>
</div>
