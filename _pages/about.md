---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## About me

I am an Applied Scientist at **AWS Health AI**, where I work on **responsible AI** for multiple healthcare agents.

I recently completed my PhD at **Cornell University**, where I was advised by [Mert Sabuncu](https://sabuncu.engineering.cornell.edu/people/). My doctoral research focused on developing time-series and computer vision methods for predicting clinical outcomes from **longitudinal multimodal biomedical data**.

During a Summer 2025 internship at **Amazon AGI**, I developed a novel REINFORCE-based RLVR algorithm for **reasoning LLMs** that achieves state-of-the-art performance across multiple benchmarks.

During a Summer 2024 internship at **Microsoft AI**, I worked on **responsible AI** research, developing supervised fine-tuning and alignment methods to improve LLM safety and usefulness.

For more details and a full list of my publications, please refer to [my resume](https://batuhankmkaraman.github.io/files/resume_batuhan.pdf)[.](https://batuhankmkaraman.github.io/files/graphdatascience.pdf)

Below you can find my highlighted publications.

## Highlighted Publications

<div class="pub-grid">
  <div class="pub-card">
    <div class="pub-card-image"><img src="/images/pub-lomar.png" alt="LoMaR model diagram"></div>
    <div class="pub-card-body">
      <h3 class="archive__item-title">LoMaR: Longitudinal Mammogram Risk Prediction</h3>
      <div class="archive__item-excerpt"><p><em>MICCAI 2024</em><br/>A breast cancer risk prediction model that ingests an arbitrary number of longitudinal mammograms. Incorporating longer histories of prior annual mammograms significantly boosts the accuracy of predicting future breast cancer risk.</p></div>
      <p><a href="https://arxiv.org/abs/2404.19083" class="btn">Paper</a></p>
    </div>
  </div>
  <div class="pub-card">
    <div class="pub-card-image"><img src="/images/pub-dispo.png" alt="Learning curves of RLVR algorithms"></div>
    <div class="pub-card-body">
      <h3 class="archive__item-title">DISPO: Decoupled Importance Sampling-weighted Policy Optimization</h3>
      <div class="archive__item-excerpt"><p><em>AISTATS 2026</em><br/>A REINFORCE-style RL algorithm for LLM mathematical reasoning that clips importance-sampling weights with separate, independently tunable bounds across four policy-update regimes, matching PPO-style stability while training as efficiently as REINFORCE.</p></div>
      <p><a href="https://arxiv.org/abs/2602.00983" class="btn">Paper</a></p>
    </div>
  </div>
  <div class="pub-card">
    <div class="pub-card-image"><img src="/images/pub-lsmad.png" alt="LSM-AD architecture diagram"></div>
    <div class="pub-card-body">
      <h3 class="archive__item-title">A Deep Survival Model for Predicting Alzheimer's Diagnosis Based on Multi-Modal Longitudinal Data</h3>
      <div class="archive__item-excerpt"><p><em>IEEE Big Data Mining and Analytics, 2026</em><br/>A Transformer-based survival model (LSM-AD) that integrates cognitive assessments and MRI biomarkers across a patient's visit history to predict future Alzheimer's diagnosis, improving AUROC by up to 15% over prior state-of-the-art.</p></div>
      <p><a href="https://ieeexplore.ieee.org/document/11373479/" class="btn">Paper</a></p>
    </div>
  </div>
  <div class="pub-card">
    <div class="pub-card-image"><img src="/images/pub-porover.png" alt="Not-unsafe and overrefusal rates before and after POROver"></div>
    <div class="pub-card-body">
      <h3 class="archive__item-title">POROver: Improving Safety and Reducing Overrefusal with Overgeneration and Preference Optimization</h3>
      <div class="archive__item-excerpt"><p><em>ICML 2025</em><br/>Shows that overgenerating instruction-finetuning data with stronger teacher models improves the safety/usefulness trade-off, and introduces POROver, a DPO-based alignment strategy that reduces LLM overrefusal while preserving safety.</p></div>
      <p><a href="https://arxiv.org/abs/2410.12999" class="btn">Paper</a></p>
    </div>
  </div>
</div>

<style>
.pub-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2em;
  margin-bottom: 2em;
}
.pub-card {
  display: flex;
  flex-direction: column;
}
.pub-card-image {
  aspect-ratio: 3 / 2;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  background: #fff;
  border: 1px solid #eee;
  border-radius: 4px;
}
.pub-card-image img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}
.pub-card-body .archive__item-title {
  margin-top: 0.75em;
  margin-bottom: 0.25em;
}
@media (max-width: 600px) {
  .pub-grid {
    grid-template-columns: 1fr;
  }
}
</style>
