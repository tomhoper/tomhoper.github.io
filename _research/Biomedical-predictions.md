---
title: "Biomed Predictions"
layout: single-portfolio
excerpt: "<img src='/images/research/kglm.png' alt=''>"
collection: research
order_number: 2
header: 
  og_image: "research/kglm.png"
---

Literature-Augmented Clinical Outcome Prediction<br>
_Aakanksha Naik, Sravanthi Parasa, Sergey Feldman, Lucy Lu Wang, **Tom Hope**_
NAACL 2022

> Predictive models for medical outcomes hold great promise for enhancing clinical decision-making. These models are trained on rich patient data such as clinical notes, aggregating many patient signals into an outcome prediction. However, AI-based clinical models have typically been developed in isolation from the prominent paradigm of Evidence Based Medicine (EBM), in which medical decisions are based on explicit evidence from existing literature. In this work, we introduce techniques to help bridge this gap between EBM and AI-based clinical models, and show that these methods can improve predictive accuracy. We propose a novel system that automatically retrieves patient-specific literature based on intensive care (ICU) patient information, aggregates relevant papers and fuses them with internal admission notes to form outcome predictions. Our model is able to substantially boost predictive accuracy on three challenging tasks in comparison to strong recent baselines; for in-hospital mortality, we are able to boost top-10% precision by a large margin of over 25%.

[Preprint](https://arxiv.org/abs/2111.08374){: .btn--research}

Scientific Language Models for Biomedical Knowledge Base Completion<br>
_Rahul Nadkarni, David Wadden, Iz Beltagy, Noah A. Smith, Hannaneh Hajishirzi, **Tom Hope**_<br>
AKBC 2021

> Biomedical knowledge graphs (KGs) hold rich information on entities such as diseases, drugs, and genes. Predicting missing links in these graphs can boost many important applications, such as drug design and repurposing. Recent work has shown that general-domain language models (LMs) can serve as "soft" KGs, and that they can be fine-tuned for the task of KG completion. In this work, we study scientific LMs for KG completion, exploring whether we can tap into their latent knowledge to enhance biomedical link prediction. We evaluate several domain-specific LMs, fine-tuning them on datasets centered on drugs and diseases that we represent as KGs and enrich with textual entity descriptions. We integrate the LM-based models with KG embedding models, using a router method that learns to assign each input example to either type of model and provides a substantial boost in performance. Finally, we demonstrate the advantage of LM models in the inductive setting with novel scientific entities. Our datasets and code are made publicly available.

[Paper](https://arxiv.org/abs/2106.09700){: .btn--research} [Github](https://github.com/rahuln/lm-bio-kgc){: .btn--research}
