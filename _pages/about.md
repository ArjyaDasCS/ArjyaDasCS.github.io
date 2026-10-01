---
layout: about
title: about
permalink: /
subtitle: PhD Student, Computer Science · <a href='https://www.ucdavis.edu/'>University of California, Davis</a>

profile:
  align: right
  image: prof_pic.jpg # replace assets/img/prof_pic.jpg with your photo
  image_circular: true
  more_info: >
    <p>Department of Computer Science</p>
    <p>UC Davis, Davis, CA</p>
    <p>arjdas [at] ucdavis [dot] edu</p>

selected_papers: false # set to true once papers.bib has entries marked selected={true}
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
---

I'm a third-year PhD student in Computer Science at **UC Davis**. My research sits at the intersection of
**programming languages** and **high-performance computing**: I build tools and techniques that make scientific
software faster and more numerically trustworthy.

I've been affiliated with **Lawrence Livermore National Laboratory (LLNL)** for several years, most recently as a
Graduate Computing Intern (summer 2026) working on HPC simulation.

**Current work**

- **Neural surrogates for scientific simulation.** [AutoNeurify]({{ '/projects/autoneurify/' | relative_url }}) replaces
  expensive regions of HPC applications with learned surrogates to speed them up.
- **Floating-point reliability.** I study how [rounding error flips control flow]({{ '/projects/fp-branch-instability/' | relative_url }})
  in scientific codes, and how well current error-detection tools catch it.

**Interests:** numerical reliability · HPC proxy applications (LULESH, miniWeather) · program analysis ·
logic and functional languages (Prolog, Common Lisp) · Go concurrency · parsing theory.
