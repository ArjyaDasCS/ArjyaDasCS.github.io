---
layout: page
title: Code-aware Neural Surrogates
description: Accelerating performance-critical kernels in HPC applications
img: assets/img/projects/neural-surrogates.jpg
importance: 1
category: current
related_publications: false
---

Large scientific simulations spend most of their time in a small number of performance-critical kernels. This project
integrates **machine learning with program analysis and compiler optimizations** to replace such kernels with learned
**neural surrogates**, speeding up large-scale HPC codes while keeping the rest of the application unchanged.

The approach targets C, C++, and Fortran applications and is evaluated across ten HPC benchmarks.

**Status:** in preparation for submission to IPDPS '27. Supported by the U.S. Department of Energy.

**Tech:** C, C++, Fortran, Python, OpenMP, CUDA, ONNX, LLVM/Clang, LFortran, PyTorch, NumPy, TensorRT
