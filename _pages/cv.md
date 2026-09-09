---
layout: archive
title: "Curriculum vitae"
permalink: /cv/
author_profile: true
intro: "PhD candidate in applied mathematics, working on inverse problems, computational imaging and machine learning for 3D photoacoustic tomography, between IMT Toulouse and A*STAR / IPAL Singapore."
redirect_from:
  - /resume
---

{% include base_path %}

<p class="cv-download">
  <a class="btn-hero" href="{{ base_path }}/files/CV_TrungThaiDo.pdf">
    <i class="fas fa-file-pdf" aria-hidden="true"></i> Download CV as PDF
  </a>
</p>

Education
======
*   **PhD in Applied Mathematics** (2024–2028, in progress)
    *   *Université de Toulouse, France — joint programme with A\*STAR, Singapore*
    *   Inverse problems, computational imaging and deep learning for 3D photoacoustic tomography
*   **Engineering Degree (Master 2) in Applied Mathematics** (2021–2024)
    *   *INSA Toulouse, France — Department of Mathematical & Modeling Engineering (GMM)*
    *   Statistics, optimization and machine learning; coursework in inverse problems, signal/image processing and high-dimensional data analysis
*   **Preparatory Classes for Grandes Écoles (CPGE)** (2019–2021)
    *   *Hue University of Education, Vietnam*
    *   Two-year intensive programme in mathematics and physics
*   **Baccalaureate in Mathematics** (2016–2019)
    *   *Quoc Hoc – Huế High School for the Gifted, Vietnam — graduated with honours*

Current position
======
*   **2024–2028: PhD Candidate in Applied Mathematics**
    *   *IMT, Université de Toulouse, France  &  BII, A\*STAR / IPAL, Singapore*
    *   Supervisors: Caroline Chaux, Paul Escande, Hwee Kuan Lee

Research experience
======
*   **Large-scale reconstruction methods for 3D photoacoustic tomography (PAT)**
    *   *PhD thesis — IMT Toulouse & A\*STAR / IPAL Singapore, 2024–2028*
    *   Designing fast, accurate reconstruction methods — combining inverse problems, optimization and deep learning — to deploy a novel 3D PAT scanner for biomedical imaging.
    *   Developed a combined Total Variation–Cauchy regularization for PAT image reconstruction (GRETSI 2025).
    *   Modelling the electrical impulse response of the 3D PAT system and implementing efficient forward/adjoint operators for large-scale data.
    *   With the A\*STAR team, exploring deep-learning-based reconstruction for large-scale 3D PAT data.

*   **May – June 2025: Visiting research stay — photoacoustic image reconstruction**
    *   *BII, IPAL, A\*STAR, Singapore*

*   **March – August 2024: Computer vision for road-safety analysis**
    *   *Research internship, Cerema Occitanie, France. Supervisors: G. Saint-Pierre, P. Salmane*
    *   Analysed road-user behaviour from aerial / smart-camera data using object detection and trajectory extraction.
    *   Built a computer-vision pipeline for road-safety risk analysis (Python, deep learning); co-authored a paper at IEEE ICPRS-24.

*   **June – September 2023: Inverse problems in photoacoustic tomography**
    *   *Research internship, Institut de Mathématiques de Toulouse (IMT), France. Supervisor: P. Escande*
    *   Implemented optimization algorithms to solve inverse problems in PAT.
    *   Built a blood-vessel image simulator for synthetic training data and trained deep neural networks for reconstruction (PyTorch).

Teaching
======
  <ul class="cv-list">{% assign cv_teaching = site.teaching | sort: 'date' | reverse %}{% for post in cv_teaching %}{% include cv-entry.html %}{% endfor %}</ul>

Publications
======
  <ul class="cv-list">{% assign cv_pubs = site.publications | sort: 'date' | reverse %}{% for post in cv_pubs %}{% include cv-entry.html %}{% endfor %}</ul>

**In preparation**

*   T.-T. Do, et al., "Implementations of photoacoustic tomography models."
*   T.-T. Do, et al., "Electrical impulse response for 3D photoacoustic tomography models."

Talks & presentations
======
  <ul class="cv-list">{% assign cv_talks = site.talks | sort: 'date' | reverse %}{% for post in cv_talks %}{% include cv-entry.html %}{% endfor %}</ul>

Technical skills & languages
======
*   **Programming:** Python, C/C++, CUDA, MATLAB, R
*   **Scientific computing:** PyTorch, NumPy/SciPy, Scikit-Learn, Matplotlib
*   **Tools:** Git, Docker, Linux, LaTeX, Jupyter
*   **Languages:** Vietnamese (native), French (fluent), English (professional)

Other activities
======
*   **2019–2020: Student tutor** — mathematics tutoring for students preparing the baccalaureate, Vietnam
*   **April 2018: Volunteer** — Hue Festival, Vietnam

Outside research, see [Beyond research]({{ base_path }}/beyond/).
