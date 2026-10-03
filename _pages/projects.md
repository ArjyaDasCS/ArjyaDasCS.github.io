---
layout: page
title: research
permalink: /projects/
description: Formal Methods, Machine Learning for Systems, and High-Performance Computing.
nav: true
nav_order: 1
---

<div class="rp">
  <article class="rp-item">
    <a class="rp-img" href="{{ '/projects/neural-surrogates/' | relative_url }}"><img src="{{ '/assets/img/projects/neural-surrogates.jpg' | relative_url }}" alt="Simulation grid mapped to a neural network"></a>
    <div>
      <h3><a href="{{ '/projects/neural-surrogates/' | relative_url }}">Code-aware Neural Surrogates for HPC Applications</a></h3>
      <p>Combines machine learning with program analysis and compiler optimizations to accelerate performance-critical kernels in large-scale HPC codes.</p>
    </div>
  </article>
  <article class="rp-item">
    <a class="rp-img" href="{{ '/projects/fp-shadow-execution/' | relative_url }}"><img src="{{ '/assets/img/projects/fp-shadow-execution.jpg' | relative_url }}" alt="Floating-point traces drifting from their higher-precision shadows"></a>
    <div>
      <h3><a href="{{ '/projects/fp-shadow-execution/' | relative_url }}">Scaling Floating-Point Error Tracking with Whole-Program Shadow Execution</a></h3>
      <p>Tracks floating-point error across optimized HPC applications using LLVM instrumentation and higher-precision shadow execution, including multi-module and MPI workloads.</p>
    </div>
  </article>
  <article class="rp-item">
    <a class="rp-img" href="{{ '/projects/dfa-verification/' | relative_url }}"><img src="{{ '/assets/img/projects/dfa-verification.jpg' | relative_url }}" alt="A curve crossing a physical bound, with the counterexample marked"></a>
    <div>
      <h3><a href="{{ '/projects/dfa-verification/' | relative_url }}">Verifying Exact Conditions for Implementations of Density Functional Approximations</a></h3>
      <p>An automated formal verification pipeline that proves simulation code satisfies its required physical constraints, or produces concrete counterexamples where it does not.</p>
    </div>
  </article>
</div>

<style>
  .rp { display: grid; gap: 1.75rem; margin-top: 0.5rem; }
  .rp .rp-item { display: grid; grid-template-columns: 11rem minmax(0, 1fr); gap: 1.25rem; align-items: center; }
  .rp .rp-img img { display: block; width: 100%; aspect-ratio: 3 / 2; object-fit: cover; border-radius: 0.4rem; border: 1px solid var(--global-divider-color); }
  .rp h3 { font-size: 1.15rem; font-weight: 500; line-height: 1.35; margin: 0 0 0.4rem; }
  .rp h3 a { color: var(--global-theme-color); }
  .rp p { margin: 0; color: var(--global-text-color); }
  @media (max-width: 575px) { .rp .rp-item { grid-template-columns: 6rem minmax(0, 1fr); gap: 0.9rem; align-items: start; } }
</style>
