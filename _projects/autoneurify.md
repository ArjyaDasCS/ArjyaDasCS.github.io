---
layout: page
title: AutoNeurify
description: Neural surrogates for accelerating scientific simulations
img: assets/img/projects/autoneurify.jpg
importance: 1
category: research
related_publications: false
---

Many scientific simulations spend most of their time in a small number of expensive, well-structured kernels.
**AutoNeurify** replaces such regions with **learned neural surrogates**, trading a controlled amount of accuracy
for large speedups while keeping the rest of the application unchanged.

**What I work on**

- Identifying code regions in HPC applications that are good candidates for surrogate replacement.
- Training and integrating surrogates (PyTorch, ONNX) back into C/C++ simulation codes.
- Evaluating speedup and accuracy across **ten HPC benchmarks**, both across input configurations
  and over long simulation horizons.

**Status:** paper in preparation.

**Related interests:** HPC proxy applications such as LULESH and miniWeather, numerical properties of
financial and physical kernels (e.g., binomial option pricing), and prior surrogate systems such as Auto-HPCnet.
