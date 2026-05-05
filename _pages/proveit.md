---
layout: page
permalink: /proveit/
title: PROVE-IT
nav: true
nav_order: 3
---

<style>
  /* ─── Grant Card ──────────────────────────────────────────────────── */
  .grant-card {
    border: 1.5px solid #c8d8ee;
    border-radius: 10px;
    padding: 1.8rem 2rem;
    margin-bottom: 2rem;
    background: #f7faff;
    display: flex;
    flex-wrap: wrap;
    gap: 1.5rem;
    align-items: flex-start;
    justify-content: space-between;
  }

  .grant-card-left {
    display: flex;
    flex-direction: column;
    gap: 0.4rem;
    min-width: 200px;
  }

  .grant-logo-row {
    display: flex;
    align-items: center;
    gap: 1rem;
    margin-bottom: 0.3rem;
  }

  .grant-logo-row img {
    height: 70px;
    width: auto;
  }

  .grant-project-name {
    font-size: 1.5rem;
    font-weight: 800;
    color: #1a3a6b;
    letter-spacing: 0.02em;
    margin: 0;
    line-height: 1.1;
  }

  .grant-pi {
    font-size: 0.95rem;
    color: #1a3a6b;
    background: #ddeaf8;
    display: inline-block;
    border-radius: 4px;
    padding: 2px 8px;
    margin-top: 0.2rem;
    font-weight: 500;
  }

  .grant-institution {
    font-size: 0.9rem;
    color: #2c4a7c;
    font-weight: 400;
    margin-top: 0.1rem;
  }

  .grant-card-right {
    display: flex;
    flex-direction: column;
    gap: 0.55rem;
    min-width: 240px;
  }

  .grant-info-row {
    display: flex;
    align-items: center;
    gap: 0.6rem;
    font-size: 0.88rem;
    color: #1a3a6b;
  }

  .grant-info-row i {
    color: #1a55a0;
    width: 18px;
    text-align: center;
    font-size: 1rem;
  }

  .grant-info-label {
    font-weight: 700;
    min-width: 120px;
  }

  .grant-info-value {
    font-weight: 400;
    color: #2c4a7c;
  }

  .grant-card-bottom {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    gap: 1.5rem;
    align-items: flex-end;
    justify-content: space-between;
    margin-top: 0.5rem;
  }

  .grant-discipline-block {
    flex: 1;
  }

  .grant-section-label {
    font-size: 0.72rem;
    font-weight: 700;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: #1a3a6b;
    margin-bottom: 0.35rem;
  }

  .grant-discipline-text {
    font-size: 0.85rem;
    color: #2c4a7c;
  }

  .grant-keywords {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem;
    margin-top: 0.3rem;
  }

  .grant-keyword {
    background: #e8f0fa;
    color: #1a3a6b;
    border: 1px solid #b8cde8;
    border-radius: 20px;
    padding: 3px 11px;
    font-size: 0.78rem;
    font-weight: 500;
  }

  .fwf-logo-block {
    display: flex;
    align-items: flex-end;
    justify-content: flex-end;
  }

  .fwf-logo-text {
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }

  .fwf-initials {
    font-size: 2rem;
    font-weight: 900;
    color: #1a3a6b;
    letter-spacing: -0.04em;
    line-height: 1;
  }

  .fwf-name {
    display: flex;
    flex-direction: column;
    font-size: 0.8rem;
    font-weight: 700;
    color: #1a3a6b;
    line-height: 1.25;
  }

  /* ─── Description Card ───────────────────────────────────────────── */
  .project-description-card {
    border-left: 4px solid #1a55a0;
    background: #f7faff;
    border-radius: 0 8px 8px 0;
    padding: 1.2rem 1.6rem;
    margin-bottom: 2rem;
    font-size: 0.97rem;
    color: var(--global-text-color);
    line-height: 1.7;
  }

  /* ─── Research Pillars ───────────────────────────────────────────── */
  .pillars-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1.2rem;
    margin-bottom: 2rem;
  }

  .pillar-card {
    border: 1.5px solid #c8d8ee;
    border-radius: 8px;
    padding: 1.1rem 1.3rem;
    background: #fff;
  }

  .pillar-card h4 {
    font-size: 0.9rem;
    font-weight: 700;
    color: #1a3a6b;
    margin: 0 0 0.4rem 0;
    display: flex;
    align-items: center;
    gap: 0.4rem;
  }

  .pillar-card p {
    font-size: 0.83rem;
    color: #3a5a8c;
    margin: 0;
    line-height: 1.5;
  }

  /* Responsive */
  @media (max-width: 600px) {
    .grant-card { flex-direction: column; }
    .grant-card-right { min-width: unset; }
  }
</style>

<!-- ═══ Grant Card ════════════════════════════════════════════════════════ -->
<div class="grant-card">

  <!-- Left: logo + identity -->
  <div class="grant-card-left">
    <div class="grant-logo-row">
      <img src="/assets/img/logo_PROVEIT.png" alt="PROVE-IT logo" />
    </div>
    <p class="grant-project-name">PROVE-IT</p>
    <span class="grant-pi">Luca Marzari</span>
    <span class="grant-institution">Technische Universität Wien</span>
  </div>

  <!-- Right: funding details -->
  <div class="grant-card-right">
    <div class="grant-info-row">
      <i class="fas fa-award"></i>
      <span class="grant-info-label">Funding program:</span>
      <span class="grant-info-value">ESPRIT</span>
    </div>
    <div class="grant-info-row">
      <i class="fas fa-hashtag"></i>
      <span class="grant-info-label">Grant DOI:</span>
      <span class="grant-info-value">
        <a href="https://doi.org/10.55776/ESP1944725" target="_blank" rel="noopener">10.55776/ESP1944725</a>
      </span>
    </div>
    <div class="grant-info-row">
      <i class="fas fa-euro-sign"></i>
      <span class="grant-info-label">Funding amount:</span>
      <span class="grant-info-value">349,732 €</span>
    </div>
    <div class="grant-info-row">
      <i class="fas fa-calendar-alt"></i>
      <span class="grant-info-label">Duration:</span>
      <span class="grant-info-value">2026 – 2029 (3 years)</span>
    </div>
  </div>

  <!-- Bottom: discipline + keywords + FWF logo -->
  <div class="grant-card-bottom">
    <div class="grant-discipline-block">
      <div class="grant-section-label">Discipline</div>
      <div class="grant-discipline-text">Computer Sciences (80%)&nbsp;&nbsp;·&nbsp;&nbsp;Mathematics (20%)</div>

      <div style="margin-top:0.9rem;">
        <div class="grant-section-label">Keywords</div>
        <div class="grant-keywords">
          <span class="grant-keyword">Artificial Intelligence</span>
          <span class="grant-keyword">Neural Network Verification</span>
          <span class="grant-keyword">Counterfactual Explanations</span>
          <span class="grant-keyword">Deep Reinforcement Learning</span>
          <span class="grant-keyword">Trustworthy AI</span>
          <span class="grant-keyword">Energy Systems</span>
        </div>
      </div>
    </div>

    <div class="fwf-logo-block">
      <div class="fwf-logo-text">
        <span class="fwf-initials">FWF</span>
        <span class="fwf-name">Austrian<br/>Science Fund</span>
      </div>
    </div>
  </div>

</div>

---

### About the Project

<div class="project-description-card">
🔍 <strong>PROVE-IT</strong> aims to advance the safety and transparency of AI systems by developing novel probabilistic verification methods and robust counterfactual explanations for sequential decision-making, with a particular focus on reinforcement learning in safety-critical domains such as energy systems. The goal is to provide scalable tools that not only certify system behavior with statistical guarantees but also explain decisions in a way that is meaningful and trustworthy for human operators.
</div>

### Research Pillars

<div class="pillars-grid">

  <div class="pillar-card">
    <h4>🔐 Probabilistic Verification</h4>
    <p>Developing scalable verification algorithms that provide formal statistical guarantees on the behavior of learned policies in safety-critical settings.</p>
  </div>

  <div class="pillar-card">
    <h4>💡 Counterfactual Explanations</h4>
    <p>Generating robust, provably stable counterfactual explanations for sequential decisions, enabling meaningful human-interpretable feedback.</p>
  </div>

   <div class="pillar-card">
    <h4>🤖 Safe Reinforcement Learning</h4>
    <p>Bridging formal verification with iterative decision-making to produce certified, transparent, and trustworthy autonomous agents.</p>
  </div>

  <div class="pillar-card">
    <h4>⚡ Energy Systems</h4>
    <p>Applying verification and explainability tools to real-world reinforcement learning scenarios in smart grid and energy management domains.</p>
  </div>


</div>

---

### People

| Role | Name | Affiliation |
|------|------|-------------|
| Principal Investigator | [Luca Marzari](https://lmarza.github.io) | TU Wien |
| Mentor | [Ezio Bartocci](https://www.eziobartocci.com) | TU Wien |
| Collaborator | [Enrico Marchesini](https://emarche.github.io) | MIT |
| Collaborator | [Changliu Liu](https://icontrol.ri.cmu.edu/people/changliu.html) | Carnegie Mellon University |
| Collaborator | [Francesco Leofante](https://fraleo.github.io) | Imperial College London |

---

### Funding

This project is funded by the **Austrian Science Fund (FWF)** under the ESPRIT fellowship programme (Grant DOI: [10.55776/ESP1944725](https://doi.org/10.55776/ESP1944725)).

<div style="margin-top: 1rem;">
  <a href="https://www.fwf.ac.at/en/research-radar/10.55776/ESP1944725" class="btn btn-primary btn-sm z-depth-0" role="button" target="_blank" rel="noopener">
    <i class="fas fa-external-link-alt"></i>&nbsp; View on FWF
  </a>
  &nbsp;
  <a href="/publications/" class="btn btn-secondary btn-sm z-depth-0" role="button">
    <i class="fas fa-book"></i>&nbsp; Related Publications
  </a>
</div>
