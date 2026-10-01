---
layout: page
title: Floating-Point Branch Instability
description: When rounding error changes which way a program branches
img: assets/img/projects/fp-branch.jpg
importance: 2
category: research
related_publications: false
---

A floating-point comparison like `x < t` can evaluate differently under a tiny rounding perturbation, sending
the program down a different path. These **branch flips** can silently change the results of scientific codes, and
they are hard to detect because nothing crashes.

**What I work on**

- **Comparing error-detection tools.** An empirical study of EFTSanitizer and FPChecker on the NAS Parallel
  Benchmarks, including cases where one tool reports a branch flip that the other misses.
- **Microbenchmarks.** fp32 branch-flip microbenchmark suites, run on LLNL clusters, that isolate the patterns
  that lead to control-flow divergence.
- **Literature.** Building on prior work on detecting floating-point instability, from Bao &amp; Zhang (OOPSLA 2013)
  and Chiang et al. (LCPC 2015) to PFPSanitizer (FSE 2021) and EFTSanitizer (OOPSLA 2022).

**Status:** ongoing.
