---
layout: page
title: research
permalink: /projects/
description: Formal Methods, Machine Learning for Systems, and High-Performance Computing.
nav: true
nav_order: 1
display_categories: [current]
horizontal: true
---

<!-- pages/projects.md -->
<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}

{% else %}

<!-- Display projects without categories -->

{% assign sorted_projects = site.projects | sort: "importance" %}

  <!-- Generate cards for each project -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>

<a id="earlier" href=".#earlier">
  <h2 class="category">earlier projects</h2>
</a>

- **Dataflow Analysis of Event-Driven Programs.** A static-analysis technique for event-driven programs such as Android
  apps: model them as multi-threaded programs, build Control-Vector Flow Graphs (CVFGs), and apply Sync-CFG–based
  points-to and null-dereference analysis. Implemented in the tool StAnDroid
  ([paper](https://drive.google.com/file/d/1gy6U1mZL9ewavx59bM0wzga6VNDHZuO4/view?usp=sharing)).
  <br><small>Java, Soot, Android Studio</small>
- **Per-Process System-Call Sandbox.** A Linux kernel security module plus a static-analysis pipeline that extracts
  system-call graphs as NFAs, combines function-level graphs into one control automaton, and enforces fine-grained
  per-process system-call policies at runtime.
  <br><small>C, Python, angr, NetworkX</small>
- **Face Recognition from Limited Data.** A manifold-matching approach to face recognition that learns from few samples.
  <br><small>Python, NumPy, OpenCV</small>
- **Overlapping Communities in the DBLP Citation Network.** Detected overlapping and hierarchical research communities
  with the BIGCLAM model, ranked influential papers within communities, and evaluated scalability on the full dataset.
  <br><small>Python, NetworkX, NumPy</small>
- **COVID-19 India Dashboard** (IIT Guwahati, with Duke-NUS Medical School). An R-based
  [interactive web app](https://palash.shinyapps.io/IITG_COVID-19-India/) for state-wise COVID-19 prediction and data
  visualization, recognized by India's Ministry of Education.
  <br><small>R, Shiny</small>
