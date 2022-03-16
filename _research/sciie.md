---
title: "Scientific IE"
layout: single-portfolio
excerpt: "<img src='/images/research/scico_teaser.png' alt=''>"
collection: research
order_number: 4
header: 
  og_image: "/images/research/scico_teaser.png"
---

SciCo: Hierarchical Cross-Document Coreference for Scientific Concepts<br>
_Arie Cattan, Sophie Johnson, Daniel Weld, Ido Dagan, Iz Beltagy, Doug Downey, **Tom Hope**_<br>
AKBC 2021 **_Outstanding paper award_**

> Determining coreference of concept mentions across multiple documents is a fundamental task in natural language understanding. Previous work on cross-document coreference resolution (CDCR) typically considers mentions of events in the news, which seldom involve abstract technical concepts that are prevalent in science and technology. These complex concepts take diverse or ambiguous forms and have many hierarchical levels of granularity (e.g., tasks and subtasks), posing challenges for CDCR. We present a new task of Hierarchical CDCR (H-CDCR) with the goal of jointly inferring coreference clusters and hierarchy between them. We create SciCo, an expert-annotated dataset for H-CDCR in scientific papers, 3X larger than the prominent ECB+ resource. We study strong baseline models that we customize for H-CDCR, and highlight challenges for future work.

[Paper](https://arxiv.org/abs/2104.08809){: .btn--research} [Github](https://github.com/ariecattan/SciCo){: .btn--research} [Hugging Face](https://huggingface.co/datasets/allenai/scico){: .btn--research}


Extracting a Knowledge Base of Mechanisms from COVID-19 Papers<br>
_**Tom Hope** *, Aida Amini*, David Wadden, Madeleine van Zuylen, Sravanthi Parasa, Eric Horvitz, Daniel Weld, Roy Schwartz, Hannaneh Hajishirzi_<br>
NAACL 2021

> The COVID-19 pandemic has spawned a diverse body of scientific literature that is challenging to navigate, stimulating interest in automated tools to help find useful knowledge. We pursue the construction of a knowledge base (KB) of mechanisms -- a fundamental concept across the sciences encompassing activities, functions and causal relations, ranging from cellular processes to economic impacts. We extract this information from the natural language of scientific papers by developing a broad, unified schema that strikes a balance between relevance and breadth. We annotate a dataset of mechanisms with our schema and train a model to extract mechanism relations from papers. Our experiments demonstrate the utility of our KB in supporting interdisciplinary scientific search over COVID-19 literature, outperforming the prominent PubMed search in a study with clinical experts.

[Paper](https://arxiv.org/abs/2010.03824){: .btn--research} [Search engine](https://covidmechanisms.apps.allenai.org/){: .btn--research} [Github](https://github.com/AidaAmini/DyGIE-MECHANIC){: .btn--research}

A Search Engine for Discovery of Scientific Challenges and Directions<br>
_Dan Lahav, Jon Saad Falcon, Bailey Kuehl, Sophie Johnson, Sravanthi Parasa, Noam Shomron, Duen Horng Chau, Diyi Yang, Eric Horvitz, Daniel S Weld, **Tom Hope**_<br>
AAAI 2022

> Keeping track of scientific challenges, advances and emerging directions is a fundamental part of research. However, researchers face a flood of papers that hinders discovery of important knowledge. In biomedicine, this directly impacts human lives. To address this problem, we present a novel task of extraction and search of scientific challenges and directions, to facilitate rapid knowledge discovery. We construct and release an expert-annotated corpus of texts sampled from full-length papers, labeled with novel semantic categories that generalize across many types of challenges and directions. We focus on a large corpus of interdisciplinary work relating to the COVID-19 pandemic, ranging from biomedicine to areas such as AI and economics. We apply a model trained on our data to identify challenges and directions across the corpus and build a dedicated search engine. In experiments with 19 researchers and clinicians using our system, we outperform a popular scientific search engine in assisting knowledge discovery. Finally, we show that models trained on our resource generalize to the wider biomedical domain and to AI papers, highlighting its broad utility. We make our data, model and search engine publicly available.

[Paper](https://arxiv.org/abs/2108.13751){: .btn--research} [Search engine](https://challenges.apps.allenai.org/){: .btn--research} [Github](https://github.com/Dan-La/scientific-challenges-and-directions){: .btn--research} [Hugging Face](https://huggingface.co/DanL/scientific-challenges-and-directions){: .btn--research}

