---
layout: page
permalink: /thesis/
title: PhD Thesis
nav: false

citation_title: "Advanced Neural Networks Verification for Safe and Explainable Intelligent Systems"
citation_authors:
  - "Marzari, Luca"
citation_date: "2026"
citation_institution: "University of Verona"
citation_pdf_url: "https://lmarza.github.io/assets/pdf/PhD_Thesis.pdf"
---

<div class="thesis-header">

  <h2>Advanced Neural Networks Verification for Safe and Explainable Intelligent Systems</h2>

  <p class="thesis-meta">
    <strong>Author:</strong> Luca Marzari<br/>
    <strong>Institution:</strong> University of Verona — Computer Science Department<br/>
    <strong>Year:</strong> 2026<br/>
    <strong>Type:</strong> PhD Dissertation
  </p>

  <div class="thesis-links" style="margin: 1.5em 0;">
    <a href="/assets/pdf/PhD_Thesis.pdf" class="btn btn-primary btn-sm z-depth-0" role="button" target="_blank">
      <i class="fas fa-file-pdf"></i> Download PDF
    </a>
    &nbsp;
    <a href="https://iris.univr.it/handle/11562/1183932" class="btn btn-secondary btn-sm z-depth-0" role="button" target="_blank">
      <i class="fas fa-external-link-alt"></i> IRIS Repository
    </a>
  </div>

</div>

---

### Abstract

Deep neural networks (DNNs) have revolutionized artificial intelligence (AI), enabling breakthroughs across domains ranging from medical robotics to sustainable energy management. Yet, their fragility to adversarial perturbations and their opacity as "black boxes" pose significant risks when deployed in safety-critical contexts. In this thesis, we address these challenges by advancing the field of neural network verification, with a particular focus on enhancing the safety and explainability of intelligent systems.

A first set of contributions develops novel verification techniques that address the limitations of existing approaches. Through abstract interpretation and probabilistic reasoning, this work introduces scalable methods that not only provide sound guarantees but also extend verification to richer, semantically grounded safety properties. In particular, the introduction of the **#DNN-Verification** and **AllDNN-Verification** problems establishes new theoretical foundations that enable quantifying and localizing unsafe regions within the input space, thereby linking verification with interpretability.

Building upon these theoretical advances, this work demonstrates how verification can be effectively integrated into deep reinforcement learning (DRL) scenarios. From post-training verification for model selection to verification-informed training, we show how safety assurances can guide policy optimization in safety-critical applications such as robotic navigation and medical procedures. Crucially, these methods further allow the automatic collection of task-level safety properties, reducing reliance on brittle, hand-designed specifications.

Finally, this thesis extends the role of verification toward explainability by providing the first rigorous complexity analysis of generating robust Counterfactual Explanations (CEs). Leveraging probabilistic verification methods, we propose new algorithms that produce counterfactuals with provable probabilistic robustness guarantees, ensuring explanations that remain valid after fine-tuning the model.

Together, these contributions establish verification as a unifying tool at the intersection of safety and explainability of intelligent systems. By bridging theory with practical deployment in the real world, this thesis advances the vision of trustworthy, transparent, and reliable AI systems.

---

### BibTeX

```bibtex
@phdthesis{marzari2026thesis,
  title     = {Advanced Neural Networks Verification for Safe and Explainable Intelligent Systems},
  author    = {Marzari, Luca},
  school    = {University of Verona},
  address   = {Verona, Italy},
  year      = {2026},
  url       = {https://lmarza.github.io/thesis/},
  pdf       = {https://lmarza.github.io/assets/pdf/PhD_Thesis.pdf}
}
```
