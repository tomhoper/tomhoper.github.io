---
title: "COVID-19 Search"
layout: single-portfolio
excerpt: "<img src='/images/research/scisight.png' alt=''>"
collection: research
order_number: 10
header: 
  og_image: "/images/research/scisight.png"
---

A Search Engine for Discovery of Scientific Challenges and Directions<br>
_Dan Lahav, Jon Saad Falcon, Bailey Kuehl, Sophie Johnson, Sravanthi Parasa, Noam Shomron, Duen Horng Chau, Diyi Yang, Eric Horvitz, Daniel S Weld, **Tom Hope**_
<br>
AAAI 2022

> Keeping track of scientific challenges, advances and emerging directions is a fundamental part of research. However, researchers face a flood of papers that hinders discovery of important knowledge. In biomedicine, this directly impacts human lives. To address this problem, we present a novel task of extraction and search of scientific challenges and directions, to facilitate rapid knowledge discovery. We construct and release an expert-annotated corpus of texts sampled from full-length papers, labeled with novel semantic categories that generalize across many types of challenges and directions. We focus on a large corpus of interdisciplinary work relating to the COVID-19 pandemic, ranging from biomedicine to areas such as AI and economics. We apply a model trained on our data to identify challenges and directions across the corpus and build a dedicated search engine. In experiments with 19 researchers and clinicians using our system, we outperform a popular scientific search engine in assisting knowledge discovery. Finally, we show that models trained on our resource generalize to the wider biomedical domain and to AI papers, highlighting its broad utility. We make our data, model and search engine publicly available.

[Paper](https://arxiv.org/abs/2108.13751){: .btn--research} [Search engine](https://challenges.apps.allenai.org/){: .btn--research} [Github](https://github.com/Dan-La/scientific-challenges-and-directions){: .btn--research} [Hugging Face](https://huggingface.co/DanL/scientific-challenges-and-directions){: .btn--research}

SciSight: Combining faceted navigation and research group detection for COVID-19 exploratory scientific search <br>
_**Tom Hope**, Jason Portenoy, Kishore Vasan, Jonathan Borchardt, Eric Horvitz, Daniel S Weld, Marti A Hearst, Jevin West_<br>
EMNLP 2020

> The COVID-19 pandemic has sparked unprecedented mobilization of scientists, generating a deluge of papers that makes it hard for researchers to keep track and explore new directions. Search engines are designed for targeted queries, not for discovery of connections across a corpus. In this paper, we present SciSight, a system for exploratory search of COVID-19 research integrating two key capabilities: first, exploring associations between biomedical facets automatically extracted from papers (e.g., genes, drugs, diseases, patient outcomes); second, combining textual and network information to search and visualize groups of researchers and their ties.

[Paper](https://arxiv.org/abs/2005.12668){: .btn--research} [Search engine](https://scisight.apps.allenai.org/){: .btn--research}


Extracting a knowledge base of mechanisms from COVID-19 papers<br>
_**Tom Hope** *, Aida Amini*, David Wadden, Madeleine van Zuylen, Sravanthi Parasa, Eric Horvitz, Daniel Weld, Roy Schwartz, Hannaneh Hajishirzi_<br>
NAACL 2021

> The COVID-19 pandemic has spawned a diverse body of scientific literature that is challenging to navigate, stimulating interest in automated tools to help find useful knowledge. We pursue the construction of a knowledge base (KB) of mechanisms -- a fundamental concept across the sciences encompassing activities, functions and causal relations, ranging from cellular processes to economic impacts. We extract this information from the natural language of scientific papers by developing a broad, unified schema that strikes a balance between relevance and breadth. We annotate a dataset of mechanisms with our schema and train a model to extract mechanism relations from papers. Our experiments demonstrate the utility of our KB in supporting interdisciplinary scientific search over COVID-19 literature, outperforming the prominent PubMed search in a study with clinical experts.

[Paper](https://arxiv.org/abs/2010.03824){: .btn--research} [Search engine](https://covidmechanisms.apps.allenai.org/){: .btn--research} [Github](https://github.com/AidaAmini/DyGIE-MECHANIC){: .btn--research}
