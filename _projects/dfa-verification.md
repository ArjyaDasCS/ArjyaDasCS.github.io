---
layout: page
title: Verifying Density Functional Approximations
description: Proving that simulation code satisfies its exact physical conditions
img: assets/img/projects/dfa-verification.jpg
importance: 3
category: current
related_publications: false
---

Density functional approximations (DFAs) used in quantum chemistry and materials simulation must satisfy known **exact
conditions**, such as the Lieb–Oxford bound on the exchange enhancement factor. Their implementations in simulation code
do not always respect these conditions.

This project builds an **automated formal-verification pipeline** that either proves an implementation satisfies its
required physical constraints or produces a **concrete counterexample** where it does not, using the δ-complete SMT
solver dReal.

**Status:** in preparation for submission to CAV '27. Supported by the U.S. Department of Energy and NSF.

**Tech:** C, C++, Python, dReal, SMT-LIB2
