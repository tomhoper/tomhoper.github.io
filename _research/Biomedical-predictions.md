---
title: "Biomedical Predictions"
layout: single-portfolio
excerpt: "<img src='/images/research/kglm.png' alt=''>"
collection: research
order_number: 40
header: 
  og_image: "research/kglm.png"
---

In these projects, I have developed models that leverage scientific literature for generating biomedical hypotheses and predicting clinical outcomes of hospital patients. These projects represent the promise of tapping into latent knowledge in scholarly literature for helping scientists and practioners scale the process of discovery and make better decisions.


Literature-Augmented Clinical Outcome Prediction
Aakanksha Naik, Sravanthi Parasa, Sergey Feldman, Lucy Lu Wang, **Tom Hope**

> Predictive models for medical outcomes hold great promise for enhancing clinical decision-making. These models are trained on rich patient data such as clinical notes, aggregating many patient signals into an outcome prediction. However, AI-based clinical models have typically been developed in isolation from the prominent paradigm of Evidence Based Medicine (EBM), in which medical decisions are based on explicit evidence from existing literature. In this work, we introduce techniques to help bridge this gap between EBM and AI-based clinical models, and show that these methods can improve predictive accuracy. We propose a novel system that automatically retrieves patient-specific literature based on intensive care (ICU) patient information, aggregates relevant papers and fuses them with internal admission notes to form outcome predictions. Our model is able to substantially boost predictive accuracy on three challenging tasks in comparison to strong recent baselines; for in-hospital mortality, we are able to boost top-10% precision by a large margin of over 25%.


[Preprint](https://arxiv.org/abs/2111.08374){: .btn--research}


Scientific Language Models for Biomedical Knowledge Base Completion
Rahul Nadkarni, David Wadden, Iz Beltagy, Noah A. Smith, Hannaneh Hajishirzi, **Tom Hope**
AKBC 2021


> Identifying networks of cooperation and conflict between actors in broader social movements can be a challenging task even when data are easily obtainable. When actors are involved in socially marginal movements such as extremist groups, this task becomes even more difficult due to the high degree of secrecy that surrounds communication and interaction between members. However, extremist groups such as terrorist groups often release extensive amounts of propaganda material, including video, magazines, and social media content. I focus on video propaganda and use computer vision techniques to identify points of interest within video frames and extract quantitative descriptions of them. I then find unsupervised clusters of these image fragment that I hand label e.g. guns, faces, banners, etc. I assign each point of interest in a frame to its appropriate category, and then generate counts of each category's frequency within each video. I then rely on unsupervised clustering methods to detect groups of videos that use similar visual imagery. Extremist group propaganda materials represent an untapped potential source of information about patterns of allegiance within the broader movement as groups that are aligned with one another are likely to produce material sharing many of the same images, terms, and themes. I evaluate this method on a sample of propaganda videos produced by groups within the Salafi Jihadi movement and compare this video-derived measure of group relationships with existing qualitative work mapping these connections to validate my findings. This computer vision approach will allow researchers to identify individual terrorist groups within broader movements when the extensive information on group interactions required for traditional network analysis is unavailable.
[Paper](https://arxiv.org/abs/2106.09700){: .btn--research} [Github](https://github.com/rahuln/lm-bio-kgc)

<!-- [Paper](/files/pdf/research/PolMeth 2019 Poster.pdf){: .btn--research} -->
