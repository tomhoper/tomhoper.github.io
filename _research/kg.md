---
title: "Knowledge Graphs"
layout: single-portfolio
excerpt: "<img src='/images/research/kg.png' alt=''>"
collection: research
order_number: 2
header: 
  og_image: "research/kg.png"
---

CARE: Extracting Experimental Findings From Clinical Literature<br>
_Aakanksha Naik, Bailey Kuehl, Erin Bransom, Doug Downey, **Tom Hope**_<br>
NAACL 2024

> Extracting fine-grained experimental findings from literature can provide dramatic utility for scientific applications. Prior work has developed annotation schemas and datasets for limited aspects of this problem, failing to capture the real-world complexity and nuance required. Focusing on biomedicine, this work presents CARE -- a new IE dataset for the task of extracting clinical findings. We develop a new annotation schema capturing fine-grained findings as n-ary relations between entities and attributes, which unifies phenomena challenging for current IE systems such as discontinuous entity spans, nested relations, variable arity n-ary relations and numeric results in a single schema. We collect extensive annotations for 700 abstracts from two sources: clinical trials and case reports. We also demonstrate the generalizability of our schema to the computer science and materials science domains. We benchmark state-of-the-art IE systems on CARE, showing that even models such as GPT4 struggle. We release our resources to advance research on extracting and aggregating literature findings.

[Paper](https://arxiv.org/abs/2311.09736){: .btn--research} [Github](https://github.com/allenai/CARE){: .btn--research}



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


Extracting a Knowledge Base of Mechanisms from COVID-19 Papers<br>
_**Tom Hope** *, Aida Amini*, David Wadden, Madeleine van Zuylen, Sravanthi Parasa, Eric Horvitz, Daniel Weld, Roy Schwartz, Hannaneh Hajishirzi_<br>
NAACL 2021

> The COVID-19 pandemic has spawned a diverse body of scientific literature that is challenging to navigate, stimulating interest in automated tools to help find useful knowledge. We pursue the construction of a knowledge base (KB) of mechanisms -- a fundamental concept across the sciences encompassing activities, functions and causal relations, ranging from cellular processes to economic impacts. We extract this information from the natural language of scientific papers by developing a broad, unified schema that strikes a balance between relevance and breadth. We annotate a dataset of mechanisms with our schema and train a model to extract mechanism relations from papers. Our experiments demonstrate the utility of our KB in supporting interdisciplinary scientific search over COVID-19 literature, outperforming the prominent PubMed search in a study with clinical experts.

[Paper](https://arxiv.org/abs/2010.03824){: .btn--research} [Search engine](https://covidmechanisms.apps.allenai.org/){: .btn--research} [Github](https://github.com/AidaAmini/DyGIE-MECHANIC){: .btn--research}


SciCo: Hierarchical Cross-Document Coreference for Scientific Concepts<br>
_Arie Cattan, Sophie Johnson, Daniel Weld, Ido Dagan, Iz Beltagy, Doug Downey, **Tom Hope**_<br>
AKBC 2021 **_Outstanding paper award_**

> Determining coreference of concept mentions across multiple documents is a fundamental task in natural language understanding. Previous work on cross-document coreference resolution (CDCR) typically considers mentions of events in the news, which seldom involve abstract technical concepts that are prevalent in science and technology. These complex concepts take diverse or ambiguous forms and have many hierarchical levels of granularity (e.g., tasks and subtasks), posing challenges for CDCR. We present a new task of Hierarchical CDCR (H-CDCR) with the goal of jointly inferring coreference clusters and hierarchy between them. We create SciCo, an expert-annotated dataset for H-CDCR in scientific papers, 3X larger than the prominent ECB+ resource. We study strong baseline models that we customize for H-CDCR, and highlight challenges for future work.

[Paper](https://arxiv.org/abs/2104.08809){: .btn--research} [Github](https://github.com/ariecattan/SciCo){: .btn--research} [Hugging Face](https://huggingface.co/datasets/allenai/scico){: .btn--research}

Learning a Faceted Customer Segmentation for Discovering New Business Opportunities at Intel<br>
_Itay Lieder, Meirav Segal, Eran Avidan, Asaf Cohen, **Tom Hope**_<br>
2019 IEEE International Conference on Big Data 

>For sales and marketing organizations within large enterprises, identifying and understanding new markets, customers and partners is a key challenge. Intel's Sales and Marketing Group (SMG) faces similar challenges while growing in new markets and domains and evolving its existing business. In today's complex technological and commercial landscape, there is need for intelligent automation supporting a fine-grained understanding of businesses in order to help SMG sift through millions of companies across many geographies and languages and identify relevant directions. We present a system developed in our company that mines millions of public business web pages, and extracts a faceted customer representation. We focus on two key customer aspects that are essential for finding relevant opportunities: industry segments (ranging from broad verticals such as healthcare, to more specific fields such as …

[Paper](https://ieeexplore.ieee.org/abstract/document/9006589){: .btn--research} [News report](https://venturebeat-com.cdn.ampproject.org/c/s/venturebeat.com/2020/02/27/intel-uses-ai-to-find-new-customers-in-specific-industries/amp/){: .btn--research}

