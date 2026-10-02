---
layout: page
title: Whole-Program FP Error Tracking
description: Scaling floating-point error tracking with shadow execution
img: assets/img/projects/fp-shadow-execution.jpg
importance: 2
category: current
related_publications: false
---

Floating-point rounding error accumulates silently in scientific codes. **Shadow execution** tracks it by running every
floating-point operation a second time in higher precision and comparing the two results.

This project scales shadow execution to **whole programs**: optimized builds, applications split across multiple modules,
and **MPI** workloads. It instruments programs with LLVM so that error can be followed across module and process
boundaries.

**Status:** in preparation for submission to CGO '27.

**Tech:** C, C++, Python, LLVM
