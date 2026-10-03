---
layout: page
permalink: /teaching/
title: teaching
description: Teaching assistantships at UC Davis and IISc.
nav: true
nav_order: 3
---

<div class="tg">
  <h2 class="tg-h">Teaching Assistant</h2>
  <div class="tg-courses">
    <article class="tg-card">
      <span class="tg-code">ECS 140A</span>
      <h3>Programming Languages</h3>
      <p class="tg-meta">UC Davis<br>Undergraduate</p>
      <div class="tg-terms"><span>Winter 2024</span><span>Winter 2025</span><span>Spring 2026</span></div>
    </article>
    <article class="tg-card">
      <span class="tg-code">ECS 36A</span>
      <h3>Programming and Problem Solving</h3>
      <p class="tg-meta">UC Davis<br>Undergraduate</p>
      <div class="tg-terms"><span>Winter 2026</span></div>
    </article>
    <article class="tg-card">
      <span class="tg-code">E0 227</span>
      <h3>Program Analysis and Verification</h3>
      <p class="tg-meta">Indian Institute of Science, Bengaluru<br>Graduate</p>
      <div class="tg-terms"><span>Fall 2022</span></div>
    </article>
  </div>

  <h2 class="tg-h">Mentoring</h2>
  <ul class="tg-list">
    <li><strong>Keena Vaslioff</strong> (B.S. student, 2024–2025), now a graduate student at UC Davis</li>
    <li><strong>Aditya Seth</strong> (B.S. student, 2024–2025), now a Software Engineer at Chevron</li>
  </ul>
</div>

<style>
  .tg { --tg-accent: var(--global-theme-color); --tg-tint: color-mix(in srgb, var(--global-theme-color) 12%, transparent); }
  .tg .tg-h {
    font-size: 0.8rem; font-weight: 600; letter-spacing: 0.12em; text-transform: uppercase;
    color: var(--global-text-color-light); margin: 2rem 0 1rem; padding-bottom: 0.5rem;
    border-bottom: 1px solid var(--global-divider-color);
  }
  .tg .tg-h:first-child { margin-top: 0.5rem; }
  .tg .tg-courses { display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 1rem; }
  .tg .tg-card {
    background: var(--global-card-bg-color); border: 1px solid var(--global-divider-color);
    border-top: 3px solid var(--tg-accent); border-radius: 0.5rem; padding: 1.1rem 1.2rem;
    display: flex; flex-direction: column; min-width: 0;
  }
  .tg .tg-code {
    align-self: flex-start; font-size: 0.85rem;
    font-weight: 600; color: var(--tg-accent); background: var(--tg-tint); border-radius: 0.3rem; padding: 0.15rem 0.5rem;
  }
  .tg h3 { font-size: 1.1rem; font-weight: 500; line-height: 1.3; margin: 0.7rem 0 0.35rem; color: var(--global-text-color); }
  .tg .tg-meta { font-size: 0.9rem; color: var(--global-text-color-light); margin: 0 0 1rem; line-height: 1.45; }
  .tg .tg-terms { margin-top: auto; display: flex; flex-wrap: wrap; gap: 0.4rem; }
  .tg .tg-terms span {
    font-size: 0.8rem; color: var(--global-text-color); border: 1px solid var(--global-divider-color);
    border-radius: 999px; padding: 0.1rem 0.6rem; white-space: nowrap;
  }
  .tg .tg-list { padding-left: 1.2rem; margin: 0; }
  .tg .tg-list li { margin-bottom: 0.4rem; }
  @media (max-width: 767px) { .tg .tg-courses { grid-template-columns: minmax(0, 1fr); } }
</style>
