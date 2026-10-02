---
layout: page
title: Branch-Flip Detection in FPChecker
description: Finding branches that rounding error can flip (LLNL, 2026)
img: assets/img/projects/fpchecker-branch-flips.jpg
importance: 4
category: current
related_publications: false
---

A floating-point comparison like `x < t` can evaluate differently once numerical error has accumulated in `x`, sending
the program down a different path. These **branch flips** can silently change the results of a simulation.

During my 2026 Graduate Computing Internship at **Lawrence Livermore National Laboratory**, I implemented a new
branch-flip detection feature in [FPChecker](https://github.com/LLNL/FPChecker), LLNL's floating-point analysis tool. The
feature extends FPChecker's LLVM instrumentation and runtime to identify floating-point branch conditions that may become
unstable due to accumulated numerical error.

**Tech:** C, C++, LLVM
