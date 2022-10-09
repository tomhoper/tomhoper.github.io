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
_Aakanksha Naik, Sravanthi Parasa, Sergey Feldman, Lucy Lu Wang, **Tom Hope**_<br>
NAACL 2022

> Predictive models for medical outcomes hold great promise for enhancing clinical decision-making. These models are trained on rich patient data such as clinical notes, aggregating many patient signals into an outcome prediction. However, AI-based clinical models have typically been developed in isolation from the prominent paradigm of Evidence Based Medicine (EBM), in which medical decisions are based on explicit evidence from existing literature. In this work, we introduce techniques to help bridge this gap between EBM and AI-based clinical models, and show that these methods can improve predictive accuracy. We propose a novel system that automatically retrieves patient-specific literature based on intensive care (ICU) patient information, aggregates relevant papers and fuses them with internal admission notes to form outcome predictions. Our model is able to substantially boost predictive accuracy on three challenging tasks in comparison to strong recent baselines; for in-hospital mortality, we are able to boost top-10% precision by a large margin of over 25%.

[Paper](https://arxiv.org/abs/2111.08374){: .btn--research}


CascadER: Cross-Modal Cascading for Knowledge Graph Link Prediction<br>
_Tara Safavi, Doug Downey, **Tom Hope**_<br>
AKBC 2022

> Knowledge graph (KG) link prediction is a fundamental task in artificial intelligence, with applications in natural language processing, information retrieval, and biomedicine. Recently, promising results have been achieved by leveraging cross-modal information in KGs, using ensembles that combine knowledge graph embeddings (KGEs) and contextual language models (LMs). However, existing ensembles are either (1) not consistently effective in terms of ranking accuracy gains or (2) impractically inefficient on larger datasets due to the combinatorial explosion problem of pairwise ranking with deep language models. In this paper, we propose a novel tiered ranking architecture CascadER to maintain the ranking accuracy of full ensembling while improving efficiency considerably. CascadER uses LMs to rerank the outputs of more efficient base KGEs, relying on an adaptive subset selection scheme aimed at invoking the LMs minimally while maximizing accuracy gain over the KGE. Extensive experiments demonstrate that CascadER improves MRR by up to 9 points over KGE baselines, setting new state-of-the-art performance on four benchmarks while improving efficiency by one or more orders of magnitude over competitive cross-modal baselines. Our empirical analyses reveal that diversity of models across modalities and preservation of individual models' confidence signals help explain the effectiveness of CascadER, and suggest promising directions for cross-modal cascaded architectures. Code and pretrained models are made available.


[Paper](https://arxiv.org/abs/2205.08012){: .btn--research} [Github](https://github.com/tsafavi/cascader){: .btn--research}


Scientific Language Models for Biomedical Knowledge Base Completion<br>
_Rahul Nadkarni, David Wadden, Iz Beltagy, Noah A. Smith, Hannaneh Hajishirzi, **Tom Hope**_<br>
AKBC 2021

> Biomedical knowledge graphs (KGs) hold rich information on entities such as diseases, drugs, and genes. Predicting missing links in these graphs can boost many important applications, such as drug design and repurposing. Recent work has shown that general-domain language models (LMs) can serve as "soft" KGs, and that they can be fine-tuned for the task of KG completion. In this work, we study scientific LMs for KG completion, exploring whether we can tap into their latent knowledge to enhance biomedical link prediction. We evaluate several domain-specific LMs, fine-tuning them on datasets centered on drugs and diseases that we represent as KGs and enrich with textual entity descriptions. We integrate the LM-based models with KG embedding models, using a router method that learns to assign each input example to either type of model and provides a substantial boost in performance. Finally, we demonstrate the advantage of LM models in the inductive setting with novel scientific entities. Our datasets and code are made publicly available.

[Paper](https://arxiv.org/abs/2106.09700){: .btn--research} [Github](https://github.com/rahuln/lm-bio-kgc){: .btn--research}
