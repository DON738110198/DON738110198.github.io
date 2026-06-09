---
permalink: /
title: ""
excerpt: ""
layout: default
author_profile: true
lang: en
seo_title: "Hao Wang - Homepage"
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# About Me

I am a master's student at **South China University of Technology**. Before that, I received my undergraduate education at **South China Normal University**.

My research interests include **Human-Object Interaction**, **text-to-3D human interaction generation**, and **agent test-time scaling**. This homepage collects my research interests, selected projects, publications, experience, and contact links in one public place.

The site is intentionally written in English so it can be shared more easily with an international audience.

<div class="profile-summary" markdown="1">

**Current focus.** Human-object interaction, controllable 3D human interaction generation from text, and scaling agent performance at test time.

**Academic path.** B.S. period at South China Normal University, 2021-2025; master's period at South China University of Technology, 2025-2028.

</div>

<div class="tag-list">
  <span>Human-Object Interaction</span>
  <span>Text-to-3D Interaction</span>
  <span>Agent Test-Time Scaling</span>
</div>

<span class='anchor' id='news'></span>

# News

- **2026.06**: One paper, **MaMi-HOI**, was accepted to **ICML 2026**.
- **2026.06**: Added education background and research interests to the homepage.
- **Next update**: Add more project materials, demos, and research artifacts.

<span class='anchor' id='research'></span>

# Research Interests

<div class="research-cards">
  <article class="research-card">
    <img src="/images/research-hoi.png" alt="Human-object interaction visual">
    <div class="research-card-body">
      <p class="research-kicker">Embodied interaction</p>
      <h3>Human-Object Interaction</h3>
      <p>Modeling interactions between humans and objects, with attention to spatial relations, action semantics, and physically plausible behavior.</p>
    </div>
  </article>
  <article class="research-card">
    <img src="/images/research-text3d.png" alt="Text-to-3D human interaction visual">
    <div class="research-card-body">
      <p class="research-kicker">Generative 3D motion</p>
      <h3>Text-to-3D Human Interaction</h3>
      <p>Generating 3D human-object interaction motions or scenes from natural language descriptions.</p>
    </div>
  </article>
  <article class="research-card">
    <img src="/images/research-agent-tts.png" alt="Agent test-time scaling visual">
    <div class="research-card-body">
      <p class="research-kicker">Inference-time reasoning</p>
      <h3>Agent Test-Time Scaling</h3>
      <p>Improving agent reasoning and decision quality by allocating more computation, sampling, verification, or tool-use effort at test time.</p>
    </div>
  </article>
</div>

<span class='anchor' id='projects'></span>

# Selected Projects

<div class="featured-work" markdown="1">

<div class="featured-work-image">
  <img src="/images/mami-hoi-teaser.png" alt="MaMi-HOI teaser">
</div>

<div class="featured-work-text" markdown="1">

### MaMi-HOI: Harmonizing Global Kinematics and Local Geometry for Human-Object Interaction Generation

**ICML 2026.** MaMi-HOI is a text- and geometry-conditioned framework for high-fidelity 3D human-object interaction generation. It targets the tension between natural global motion and precise local object contact through a geometry-aware and kinematics-aware design.

[[Paper]](/pdf/MaMi-HOI-ICML-2026.pdf) [[arXiv]](https://arxiv.org/abs/2605.05756) [[Code]](https://github.com/DON738110198/MaMi-HOI)

</div>

</div>

<div class='project-entry' markdown="1">

### Personal Homepage

This site is maintained as a compact academic profile and research portfolio.

[[Website]](https://don738110198.github.io) [[GitHub]](https://github.com/DON738110198/DON738110198.github.io)

</div>

<span class='anchor' id='publications'></span>

# Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='/images/mami-hoi-teaser.png' alt="MaMi-HOI teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Hao Wang`, Shiqi Wang, Qi Liu. **MaMi-HOI: Harmonizing Global Kinematics and Local Geometry for Human-Object Interaction Generation.** *Proceedings of the 43rd International Conference on Machine Learning (ICML 2026).*  
[[Paper]](/pdf/MaMi-HOI-ICML-2026.pdf) [[arXiv]](https://arxiv.org/abs/2605.05756) [[Code]](https://github.com/DON738110198/MaMi-HOI)

MaMi-HOI studies 3D human-object interaction generation and introduces a retrieve-and-harmonize framework that preserves natural whole-body motion while improving precise object contact.

</div>
</div>

<span class='anchor' id='honors'></span>

# Honors and Awards

- **ICML 2026 paper acceptance** for MaMi-HOI.

<span class='anchor' id='education'></span>

# Education

- **South China University of Technology**, 2025-2028.

  Master's study.

- **South China Normal University**, 2021-2025.

  Undergraduate study.

<span class='anchor' id='talks'></span>

# Invited Talks

- To be added after talk titles, venues, and dates are confirmed.

<span class='anchor' id='experience'></span>

# Experience

- To be added after internship, work, or project experience is confirmed.
