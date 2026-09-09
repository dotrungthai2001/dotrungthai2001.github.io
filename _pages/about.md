---
layout: home
permalink: /
title: "Trung-Thai Do"
excerpt: "PhD student working on large-scale reconstruction methods for 3D photoacoustic imaging, between IMT Toulouse and A*STAR Singapore."
author_profile: false
redirect_from:
  - /about/
  - /about.html

hero:
  eyebrow: "PhD candidate in applied mathematics · 2024–2028"
  name: "Trung-Thai Do"
  lede: "I build fast, large-scale reconstruction methods for **3D photoacoustic tomography** — at the interface of inverse problems, computational imaging, and machine learning."
  affiliations:
    - name: "Institut de Mathématiques de Toulouse"
      url: "https://www.math.univ-toulouse.fr/"
      place: "France"
    - name: "Bioinformatics Institute, A*STAR — IPAL (CNRS IRL 2955)"
      url: "https://ipal.cnrs.fr/"
      place: "Singapore"
  actions:
    - title: "Publications"
      url: /publications/
      primary: true
    - title: "CV"
      url: /cv/

research:
  heading: "Research"
  intro: "My thesis, *Large-scale reconstruction methods for high-quality 3D photoacoustic imaging*, supports the deployment of a new 3D photoacoustic tomography (PAT) scanner for biomedical studies. The difficulty is scale: a full 3D forward operator cannot be stored, so every reconstruction step has to be computed on the fly. Supervised by [Paul Escande](https://pescande.perso.math.cnrs.fr/) (CNRS, IMT), [Caroline Chaux](https://www.i2m.univ-amu.fr/perso/caroline.chaux-moulin/) (CNRS, IPAL) and [Hwee Kuan Lee](https://www.a-star.edu.sg/cfar/about-cfar/our-team/dr-hwee-kuan-lee) (A*STAR, IPAL)."
  # Drop a figure in /images/ and give its filename here to feature it, e.g. pat-reconstruction.png
  figure:
  figure_caption:
  themes:
    - title: "Inverse problems"
      icon: "fas fa-wave-square"
      text: "Variational reconstruction with sparsity-promoting and heavy-tailed priors. We combine total variation with a Cauchy prior to recover structure from limited, sparsely sampled PAT data."
    - title: "Large-scale computation"
      icon: "fas fa-microchip"
      text: "The 3D forward operator is far too large to store. We use on-the-fly matrix–vector products so that advanced algorithms run on real scanner data within a realistic memory budget."
    - title: "Operator approximation"
      icon: "fas fa-project-diagram"
      text: "Modelling the electrical impulse response of the scanner, and approximating forward and adjoint operators accurately enough to reconstruct without paying the full physical cost."
    - title: "Learning for imaging"
      icon: "fas fa-brain"
      text: "With the A*STAR team, exploring deep-learning-based reconstruction for large-scale 3D PAT — and where learned components can safely replace or accelerate model-based steps."

news:
  - date: "Jun 2026"
    text: "Poster on large-scale reconstruction for 3D photoacoustic imaging at **SinFra 2026**, Singapore."
  - date: "Sep 2025"
    text: "Poster on TV–Cauchy reconstruction at the *Journées modèles proxy et co-conception* (GDR Ondes / RT MAIAGES / GDR IASIS), Institut Henri Poincaré, Paris."
  - date: "Aug 2025"
    text: "Talk on combined Total Variation–Cauchy regularization for PAT at **GRETSI 2025**, Strasbourg."

beyond:
  heading: "Beyond research"
  url: /beyond/
  text: "Reconstruction is not the only thing I spend time on. Films, football and racket sports keep the week honest, across Toulouse, Singapore and Huế."
  cta: "More about that"
  tags:
    - icon: "fas fa-film"
      label: "Film"
    - icon: "fas fa-futbol"
      label: "Football"
    - icon: "fas fa-table-tennis-paddle-ball"
      label: "Racket sports"
---
