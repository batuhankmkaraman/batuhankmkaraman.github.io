---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
feature_row:
  - image_path: pub-lomar.png
    alt: "LoMaR model diagram"
    title: "LoMaR: Longitudinal Mammogram Risk Prediction"
    excerpt: "*MICCAI 2024*<br/>A breast cancer risk prediction model that ingests an arbitrary number of longitudinal mammograms. Incorporating longer histories of prior annual mammograms significantly boosts the accuracy of predicting future breast cancer risk."
    url: "https://github.com/batuhankmkaraman/LoMaR"
    btn_label: "Code"
feature_row2:
  - image_path: pub-dispo.png
    alt: "DISPO's four policy update regimes"
    title: "DISPO: Decoupled Importance Sampling-weighted Policy Optimization"
    excerpt: "*AISTATS 2026*<br/>A REINFORCE-style RL algorithm for LLM mathematical reasoning that clips importance-sampling weights with separate, independently tunable bounds across four policy-update regimes, matching PPO-style stability while training as efficiently as REINFORCE."
    url: "https://github.com/batuhankmkaraman/dispo"
    btn_label: "Code"
feature_row3:
  - image_path: pub-lsmad.png
    alt: "LSM-AD architecture diagram"
    title: "A Deep Survival Model for Predicting Alzheimer's Diagnosis Based on Multi-Modal Longitudinal Data"
    excerpt: "*Big Data Mining and Analytics, 2026*<br/>A Transformer-based survival model (LSM-AD) that integrates cognitive assessments and MRI biomarkers across a patient's visit history to predict future Alzheimer's diagnosis, improving AUROC by up to 15% over prior state-of-the-art."
    url: "https://ieeexplore.ieee.org/document/11373479/"
    btn_label: "Paper"
feature_row4:
  - image_path: pub-porover.png
    alt: "Examples of safety and overrefusal in LLM responses"
    title: "POROver: Improving Safety and Reducing Overrefusal with Overgeneration and Preference Optimization"
    excerpt: "*ICML 2025*<br/>Shows that overgenerating instruction-finetuning data with stronger teacher models improves the safety/usefulness trade-off, and introduces POROver, a DPO-based alignment strategy that reduces LLM overrefusal while preserving safety."
    url: "https://github.com/batuhankmkaraman/POROver"
    btn_label: "Code"
---

## About me

I am an Applied Scientist at **AWS Health AI**, where I work on **responsible AI** for multiple healthcare agents.

I recently completed my PhD at **Cornell University**, where I was advised by [Mert Sabuncu](https://sabuncu.engineering.cornell.edu/people/). My doctoral research focused on developing time-series and computer vision methods for predicting clinical outcomes from longitudinal multimodal biomedical data.

During a Summer 2025 internship at **Amazon AGI**, I developed a novel REINFORCE-based RLVR algorithm for **reasoning LLMs** that achieves state-of-the-art performance across multiple benchmarks.

During a Summer 2024 internship at **Microsoft AI**, I worked on **responsible AI** research, developing supervised fine-tuning and alignment methods to improve LLM safety and usefulness.

For more details and a full list of my publications, please refer to [my resume](https://batuhankmkaraman.github.io/files/resume_batuhan.pdf).

Below you can find my highlighted publications.

## Highlighted Publications

{% include feature_row id="feature_row" type="left" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="right" %}
