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


A Dataset for N-ary Relation Extraction of Drug Combinations<br>
_Aryeh Tiktinsky, Vijay Viswanathan, Danna Niezni, Dana Meron Azagury, Yosi Shamay, Hillel Taub-Tabib, **Tom Hope**, Yoav Goldberg_
<br>
NAACL 2022

> Combination therapies have become the standard of care for diseases such as cancer, tuberculosis, malaria and HIV. However, the combinatorial set of available multi-drug treatments creates a challenge in identifying effective combination therapies available in a situation. To assist medical professionals in identifying beneficial drug-combinations, we construct an expert-annotated dataset for extracting information about the efficacy of drug combinations from the scientific literature. Beyond its practical utility, the dataset also presents a unique NLP challenge, as the first relation extraction dataset consisting of variable-length relations. Furthermore, the relations in this dataset predominantly require language understanding beyond the sentence level, adding to the challenge of this task. We provide a promising baseline model and identify clear areas for further improvement. We release our dataset, code, and baseline models publicly to encourage the NLP community to participate in this task.

[Paper](https://arxiv.org/abs/2205.02289){: .btn--research} [Search engine](https://spike4cancer.apps.allenai.org/){: .btn--research} [Github](https://github.com/allenai/drug-combo-extraction){: .btn--research} [Hugging Face](https://huggingface.co/allenai/drug-combo-classifier-pubmedbert-dapt){: .btn--research}


ACCoRD: A Multi-Document Approach to Generating Diverse Descriptions of Scientific Concepts<br>
_Sonia K. Murthy, Kyle Lo, Daniel King, Chandra Bhagavatula, Bailey Kuehl, Sophie Johnson, Jonathan Borchardt, Daniel S. Weld, **Tom Hope**, Doug Downey_
<br>
EMNLP 2022

> Systems that can automatically define unfamiliar terms hold the promise of improving the accessibility of scientific texts, especially for readers who may lack prerequisite background knowledge. However, current systems assume a single "best" description per concept, which fails to account for the many potentially useful ways a concept can be described. We present ACCoRD, an end-to-end system tackling the novel task of generating sets of descriptions of scientific concepts. Our system takes advantage of the myriad ways a concept is mentioned across the scientific literature to produce distinct, diverse descriptions of target scientific concepts in terms of different reference concepts. To support research on the task, we release an expert-annotated resource, the ACCoRD corpus, which includes 1,275 labeled contexts and 1,787 hand-authored concept descriptions. We conduct a user study demonstrating that (1) users prefer descriptions produced by our end-to-end system, and (2) users prefer multiple descriptions to a single "best" description.

[Paper](https://arxiv.org/abs/2205.06982){: .btn--research} [Github](https://github.com/allenai/ACCoRD){: .btn--research}




