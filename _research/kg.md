---
title: "Knowledge Graphs"
layout: single-portfolio
excerpt: "<img src='/images/research/kg.png' alt=''>"
collection: research
order_number: 2
header: 
  og_image: "research/kg.png"
---


Scientific Language Models for Biomedical Knowledge Base Completion
<br>
_Rahul Nadkarni, David Wadden, Iz Beltagy, Noah A. Smith, Hannaneh Hajishirzi, **Tom Hope**
_AKBC 2021

> Biomedical knowledge graphs (KGs) hold rich information on entities such as diseases, drugs, and genes. Predicting missing links in these graphs can boost many important applications, such as drug design and repurposing. Recent work has shown that general-domain language models (LMs) can serve as "soft" KGs, and that they can be fine-tuned for the task of KG completion. In this work, we study scientific LMs for KG completion, exploring whether we can tap into their latent knowledge to enhance biomedical link prediction. We evaluate several domain-specific LMs, fine-tuning them on datasets centered on drugs and diseases that we represent as KGs and enrich with textual entity descriptions. We integrate the LM-based models with KG embedding models, using a router method that learns to assign each input example to either type of model and provides a substantial boost in performance. Finally, we demonstrate the advantage of LM models in the inductive setting with novel scientific entities. Our datasets and code are made publicly available.

[Paper](https://arxiv.org/abs/2106.09700){: .btn--research} [Github](https://github.com/rahuln/lm-bio-kgc){: .btn--research}


Extracting a knowledge base of mechanisms from COVID-19 papers
<br>
_**Tom Hope** *, Aida Amini*, David Wadden, Madeleine van Zuylen, Sravanthi Parasa, Eric Horvitz, Daniel Weld, Roy Schwartz, Hannaneh Hajishirzi
_<br>
NAACL 2021

> The COVID-19 pandemic has spawned a diverse body of scientific literature that is challenging to navigate, stimulating interest in automated tools to help find useful knowledge. We pursue the construction of a knowledge base (KB) of mechanisms -- a fundamental concept across the sciences encompassing activities, functions and causal relations, ranging from cellular processes to economic impacts. We extract this information from the natural language of scientific papers by developing a broad, unified schema that strikes a balance between relevance and breadth. We annotate a dataset of mechanisms with our schema and train a model to extract mechanism relations from papers. Our experiments demonstrate the utility of our KB in supporting interdisciplinary scientific search over COVID-19 literature, outperforming the prominent PubMed search in a study with clinical experts.

[Paper](https://arxiv.org/abs/2010.03824){: .btn--research} [Search engine](https://covidmechanisms.apps.allenai.org/){: .btn--research} [Github](https://github.com/AidaAmini/DyGIE-MECHANIC){: .btn--research}


SciCo: Hierarchical Cross-Document Coreference for Scientific Concepts
<br>
_Arie Cattan, Sophie Johnson, Daniel Weld, Ido Dagan, Iz Beltagy, Doug Downey, **Tom Hope**
_
<br>
AKBC 2021 **_Outstanding paper award_**

> Determining coreference of concept mentions across multiple documents is a fundamental task in natural language understanding. Previous work on cross-document coreference resolution (CDCR) typically considers mentions of events in the news, which seldom involve abstract technical concepts that are prevalent in science and technology. These complex concepts take diverse or ambiguous forms and have many hierarchical levels of granularity (e.g., tasks and subtasks), posing challenges for CDCR. We present a new task of Hierarchical CDCR (H-CDCR) with the goal of jointly inferring coreference clusters and hierarchy between them. We create SciCo, an expert-annotated dataset for H-CDCR in scientific papers, 3X larger than the prominent ECB+ resource. We study strong baseline models that we customize for H-CDCR, and highlight challenges for future work.

[Paper](https://arxiv.org/abs/2104.08809){: .btn--research} [Github](https://github.com/ariecattan/SciCo){: .btn--research} [Hugging Face](https://huggingface.co/datasets/allenai/scico){: .btn--research}

Learning a faceted customer segmentation for discovering new business opportunities at Intel
<br>
_Itay Lieder, Meirav Segal, Eran Avidan, Asaf Cohen, **Tom Hope**
_
<br>
2019 IEEE International Conference on Big Data 

>For sales and marketing organizations within large enterprises, identifying and understanding new markets, customers and partners is a key challenge. Intel's Sales and Marketing Group (SMG) faces similar challenges while growing in new markets and domains and evolving its existing business. In today's complex technological and commercial landscape, there is need for intelligent automation supporting a fine-grained understanding of businesses in order to help SMG sift through millions of companies across many geographies and languages and identify relevant directions. We present a system developed in our company that mines millions of public business web pages, and extracts a faceted customer representation. We focus on two key customer aspects that are essential for finding relevant opportunities: industry segments (ranging from broad verticals such as healthcare, to more specific fields such as …

[Paper](https://ieeexplore.ieee.org/abstract/document/9006589){: .btn--research} [News report](https://venturebeat-com.cdn.ampproject.org/c/s/venturebeat.com/2020/02/27/intel-uses-ai-to-find-new-customers-in-specific-industries/amp/){: .btn--research}

