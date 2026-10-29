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
  .volunteering-list,
  .education-list {
    list-style: none;
    padding-left: 0;
    margin: 0;
  }

  .publication-list li,
  .conference-list li,
  .awards-list li,
  .volunteering-list li,
  .education-list li {
    margin-bottom: 0.85rem;
    padding-bottom: 0.85rem;
    border-bottom: 1px solid #eef1f4;
  }

  .publication-list li:last-child,
  .conference-list li:last-child,
  .awards-list li:last-child,
  .volunteering-list li:last-child,
  .education-list li:last-child {
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
      I am a doctoral researcher in nanotechnology with a strong interest in computational drug discovery,
      chemoinformatics, and molecular modeling. My work integrates artificial intelligence, molecular docking,
      and molecular dynamics to advance the design and discovery of therapeutic candidates for metabolic disease.
    </p>
    <div class="social-links">
      <a href="https://github.com/anamurrieta" target="_blank" rel="noopener">GitHub</a>
      <a href="https://www.researchgate.net/profile/Ana-Murrieta" target="_blank" rel="noopener">ResearchGate</a>
      <a href="https://orcid.org/0000-0002-7619-8880" target="_blank" rel="noopener">ORCID</a>
      <a href="https://scholar.google.com/citations?user=D2Vv2hAAAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar</a>
      <a href="https://www.linkedin.com/in/ana-murrieta" target="_blank" rel="noopener">LinkedIn</a>
      <a href="mailto:ana.murrieta@tec.mx">Professional email</a>
      <a href="mailto:murrieta.ana@hotmail.com">Personal email</a>
    </div>
  </div>
</div>

<div class="section-card">
  <h3>Interests and skills</h3>
  <div class="two-columns">
    <div class="mini-card">
      <h4>Main focus</h4>
      <p>
        Computational drug discovery, molecular design, and the integration of data-driven methodologies
        for health applications, with a special focus on obesity and metabolic syndrome.
      </p>
    </div>
    <div class="mini-card">
      <h4>Methods</h4>
      <p><strong>Chemoinformatics:</strong> molecular descriptors, dimensionality reduction, visualization, and scaffold analysis.</p>
      <p><strong>Machine learning:</strong> support vector classifiers, random forests, XGBoost, and neural networks.</p>
      <p><strong>Molecular docking:</strong> AutoDock Vina and related ligand-protein methods.</p>
      <p><strong>Molecular dynamics:</strong> simulation workflows for biomolecular analysis and validation.</p>
    </div>
    <div class="mini-card">
      <h4>Motivation</h4>
      <p>
        I am driven by the opportunity to contribute to the next generation of therapeutic development through
        rigorous, multidisciplinary, and data-informed computational research.
      </p>
    </div>
    <div class="mini-card">
      <h4>Current interests</h4>
      <p>
        Drug discovery, chemoinformatics, AI for health, molecular modeling, nanomaterials, and reproducible scientific computing.
      </p>
    </div>
  </div>
</div>

<div class="section-card">
  <h3>Education</h3>
  <ul class="education-list">
    <li>
      <strong>B.Sc. in [Degree]</strong><br>
      <span class="muted">[University], [Year]</span>
    </li>
    <li>
      <strong>M.Sc. in [Degree]</strong><br>
      <span class="muted">[University], [Year]</span>
    </li>
    <li>
      <strong>Ph.D. in Nanotechnology</strong><br>
      <span class="muted">Tecnológico de Monterrey, [Year or expected year]</span>
    </li>
  </ul>
</div>

<div class="section-card">
  <h3>Publications</h3>
  <ul class="publication-list">
    <li>
      <strong>LigandHub: Web-Based Ligand Preparation and Docking Output Recovery Platform</strong><br>
      <span class="muted">ChemRxiv, 2026</span><br>
      <a href="https://doi.org/10.0000/placeholder-ligandhub" target="_blank" rel="noopener">DOI: placeholder</a>
    </li>
    <li>
      <strong>Identification and structural characterization of CB1 receptor antagonists: A comprehensive virtual screening and molecular dynamics study of arachidin-2</strong><br>
      <span class="muted">Biophysical Chemistry, 2025</span><br>
      <a href="https://doi.org/10.0000/placeholder-cb1" target="_blank" rel="noopener">DOI: placeholder</a>
    </li>
    <li>
      <strong>Mitochondrial Ca overload is a pivotal risk factor for lethal ventricular arrhythmias due to the oxidation of mitochondrial respirasome and energetic failure</strong><br>
      <span class="muted">British Journal of Pharmacology, 2025</span><br>
      <a href="https://doi.org/10.0000/placeholder-arrhythmia" target="_blank" rel="noopener">DOI: placeholder</a>
    </li>
  </ul>
</div>

<div class="section-card">
  <h3>Conferences</h3>
  <ul class="conference-list">
    <li>
      <strong>MELITE: Multimodel evaluation of classifiers for chemoinformatics</strong><br>
      <span class="muted">Poster presentation. Congress of the Mexican Chemistry Society, Oaxaca, México, 2026.</span>
    </li>
    <li>
      <strong>Computational identification of 2-arylbenzofuran derivatives as CB1 ligands from the chemical space of natural products</strong><br>
      <span class="muted">Oral presentation. Congress of the Mexican Chemistry Society, Oaxaca, México, 2026.</span>
    </li>
    <li>
      <strong>Gender bias in artificial intelligence models in drug development</strong><br>
      <span class="muted">Poster presentation. International Conference of Women Researchers in Iberoamerica, Tampico, México, 2025.</span>
    </li>
  </ul>
</div>

<div class="section-card">
  <h3>Developments</h3>
  <div class="two-columns">
    <div class="mini-card">
      <h4>Chemvault</h4>
      <p class="muted">Repository for chemical data management and structure-related workflows.</p>
      <p><a href="https://github.com/NanoBiostructuresRG-lab/chemvault" target="_blank" rel="noopener">View repository</a></p>
    </div>
    <div class="mini-card">
      <h4>MELITE</h4>
      <p class="muted">Multimodel evaluation framework for chemoinformatics and predictive model benchmarking.</p>
      <p><a href="https://github.com/NanoBiostructuresRG/melite" target="_blank" rel="noopener">View repository</a></p>
    </div>
    <div class="mini-card">
      <h4>Autodock Viña docking tutorial</h4>
      <p class="muted">Educational tutorial and practical workflow for molecular docking using AutoDock Vina.</p>
      <p><a href="https://github.com/NanoBiostructuresRG/AutodockTutorial-fork" target="_blank" rel="noopener">View repository</a></p>
    </div>
    <div class="mini-card">
      <h4>Scientific Computing</h4>
      <p class="muted">Reproducible analysis pipelines for computational chemistry, molecular modeling, and scientific visualization.</p>
      <p><a href="https://github.com/anamurrieta" target="_blank" rel="noopener">GitHub profile</a></p>
    </div>
  </div>
</div>

<div class="section-card">
  <h3>Volunteering</h3>
  <ul class="volunteering-list">
    <li>
      <strong>She in Nano - Mentor</strong><br>
      <span class="muted">Nanotechnology Student Society, Tecnológico de Monterrey, 2026</span><br>
      <span>I mentor undergraduate students in academic development and research involvement.</span>
    </li>
    <li>
      <strong>Summer research internship - Instructor</strong><br>
      <span class="muted">DELFIN summer school, 2026</span><br>
      <span>I trained students in computational techniques for drug discovery and molecular analysis.</span>
    </li>
    <li>
      <strong>FIRST Robotics Competition - Judge and volunteer</strong><br>
      <span class="muted">FIRST Mexico and FIRST international, 2018-2026</span><br>
      <span>I supported STEM outreach and volunteer activities for middle and high school students.</span>
    </li>
  </ul>
</div>
