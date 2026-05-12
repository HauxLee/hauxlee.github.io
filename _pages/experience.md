---
layout: single
title: "Experience"
permalink: /experience/
author_profile: true
---

<style>
.experience-section {
  margin-top: 1rem;
}

.section-title {
  font-size: 1.45rem;
  font-weight: 700;
  margin-top: 1.2rem;
  margin-bottom: 1.5rem;
  padding-bottom: 0.45rem;
  border-bottom: 1px solid var(--border-color);
}

.timeline {
  position: relative;
  margin-left: 1.4rem;
  padding-left: 2.2rem;
  border-left: 2px solid var(--timeline-line);
}

.timeline-item {
  position: relative;
  margin-bottom: 2.4rem;
}

.timeline-item::before {
  content: "";
  position: absolute;
  left: -2.68rem;
  top: 0.55rem;
  width: 14px;
  height: 14px;
  background: var(--background-color);
  border: 3px solid var(--timeline-dot);
  border-radius: 50%;
}

.edu-card {
  display: flex;
  gap: 1.2rem;
  align-items: flex-start;
}

.edu-logo {
  width: 74px;
  height: 74px;
  object-fit: contain;
  flex-shrink: 0;
  margin-top: 0.15rem;
}

.edu-content {
  flex: 1;
}

.item-title {
  font-size: 1.08rem;
  font-weight: 700;
  margin-bottom: 0.2rem;
  line-height: 1.4;
}

.item-title a {
  color: inherit;
  text-decoration: none;
  transition: opacity 0.2s ease;
}

.item-title a:hover {
  opacity: 0.75;
  text-decoration: underline;
}

.item-title a:focus,
.item-title a:active {
  outline: none;
  box-shadow: none;
}

.item-subtitle {
  font-size: 0.96rem;
  color: var(--subtitle-color);
  margin-bottom: 0.18rem;
  line-height: 1.5;
}

.item-meta {
  font-size: 0.9rem;
  color: var(--meta-color);
}

/* Light Mode */
:root {
  --border-color: #e5e7eb;
  --timeline-line: #d1d5db;
  --timeline-dot: #6b7280;
  --subtitle-color: #374151;
  --meta-color: #6b7280;
  --background-color: #ffffff;
}

/* Dark Mode */
[data-theme="dark"] {
  --border-color: #374151;
  --timeline-line: #4b5563;
  --timeline-dot: #9ca3af;
  --subtitle-color: #d1d5db;
  --meta-color: #9ca3af;
  --background-color: #111827;
}

@media (max-width: 600px) {

  .timeline {
    margin-left: 0.5rem;
    padding-left: 1.5rem;
  }

  .timeline-item::before {
    left: -1.98rem;
  }

  .edu-card {
    gap: 0.9rem;
  }

  .edu-logo {
    width: 58px;
    height: 58px;
  }

  .section-title {
    font-size: 1.3rem;
  }
}
</style>

<div class="experience-section">

<div class="section-title">Education</div>

<div class="timeline">

  <div class="timeline-item">
    <div class="edu-card">

      <img class="edu-logo" src="/images/experiences/usc-logo.png" alt="USC logo">

      <div class="edu-content">

        <div class="item-title">
          <a href="https://www.usc.edu/" target="_blank">
            University of Southern California
          </a>
        </div>

        <div class="item-subtitle">
          Master of Science in Computer Science
        </div>

        <div class="item-meta">
          Los Angeles, CA · Aug. 2023 – May 2025
        </div>

      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="edu-card">

      <img class="edu-logo" src="/images/experiences/uci-logo.png" alt="UCI logo">

      <div class="edu-content">

        <div class="item-title">
          <a href="https://uci.edu/" target="_blank">
            University of California, Irvine
          </a>
        </div>

        <div class="item-subtitle">
          Electrical Engineering and Computer Science<br>
          Joint Program with HIT
        </div>

        <div class="item-meta">
          Irvine, CA · Sept. 2022 – Jun. 2023
        </div>

      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="edu-card">

      <img class="edu-logo" src="/images/experiences/hit-logo.png" alt="HIT logo">

      <div class="edu-content">

        <div class="item-title">
          <a href="https://www.hit.edu.cn/" target="_blank">
            Harbin Institute of Technology
          </a>
        </div>

        <div class="item-subtitle">
          Bachelor of Engineering in Computer Science and Technology
        </div>

        <div class="item-meta">
          Harbin, China · Aug. 2019 – Jun. 2023
        </div>

      </div>
    </div>
  </div>

</div>

</div>

<div class="section-title">Research</div>

<div class="timeline">

  <div class="timeline-item">
    <div class="edu-card">

      <img class="edu-logo" src="/images/experiences/usclab-logo.png" alt="USC logo">

      <div class="edu-content">

        <div class="item-title">
          <a href="https://limenlp.github.io/index.html" target="_blank">
            Language, Intelligence, and Model Ethics (LIME) Lab
          </a>
        </div>

        <div class="item-subtitle">
          Research Assistant · Advisor:
          <a href="https://jyzhao.net/" target="_blank">Prof. Jieyu Zhao</a>
        </div>

        <div class="item-meta">
          University of Southern California · Jul. 2024 – May 2025
        </div>

      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="edu-card">

      <img class="edu-logo" src="/images/experiences/uci-logo.png" alt="UCI logo">

      <div class="edu-content">

        <div class="item-title">
          <a href="https://engineering.uci.edu/users/glenn-healey" target="_blank">
            Computer Vision Lab
          </a>
        </div>

        <div class="item-subtitle">
          Research Assistant · Advisor:
          <a href="https://engineering.uci.edu/users/glenn-healey" target="_blank">Prof. Glenn Healey</a>
        </div>

        <div class="item-meta">
          University of California, Irvine · Oct. 2022 – Jun. 2023
        </div>

      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="edu-card">

      <img class="edu-logo" src="/images/experiences/hitlab-logo.png" alt="HIT logo">

      <div class="edu-content">

        <div class="item-title">
        <a href="https://db.hit.edu.cn/main.htm" target="_blank">
            Massive Data Computing Lab
        </a>
        </div>

        <div class="item-subtitle">
        Research Assistant · Advisors:
        <a href="https://homepage.hit.edu.cn/wang" target="_blank">
            Prof. Hongzhi Wang
        </a>
        &
        <a href="https://scholar.google.com/citations?user=GJUuXGMAAAAJ" target="_blank">
            Dr. Xiaoou Ding
        </a>
        </div>

        <div class="item-meta">
          Harbin Institute of Technology · Mar. 2021 – Jun. 2023
        </div>

      </div>
    </div>
  </div>

</div>


<div class="section-title">Service</div>

<div class="timeline">

  <div class="timeline-item">
    <div class="edu-card">

      <img class="edu-logo"
           src="/images/experiences/colm-logo.png"
           alt="COLM logo">

      <div class="edu-content">

        <div class="item-title">
          <a href="https://colmweb.org/" target="_blank">
            Conference on Language Modeling (COLM)
          </a>
        </div>

        <div class="item-subtitle">
          Official Reviewer
        </div>

        <div class="item-meta">
          COLM 2026
        </div>

      </div>
    </div>
  </div>

</div>