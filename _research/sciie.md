---
title: "Scientific IE"
layout: single-portfolio
excerpt: "<img src='/images/research/scico_teaser.png' alt=''>"
collection: research
order_number: 4
header: 
  og_image: "/images/research/scico_teaser.png"
---

SciCo: Hierarchical Cross-Document Coreference for Scientific Concepts
Arie Cattan, Sophie Johnson, Daniel Weld, Ido Dagan, Iz Beltagy, Doug Downey, **Tom Hope**
<br>
AKBC 2021 **_Outstanding paper award_**

> Determining coreference of concept mentions across multiple documents is a fundamental task in natural language understanding. Previous work on cross-document coreference resolution (CDCR) typically considers mentions of events in the news, which seldom involve abstract technical concepts that are prevalent in science and technology. These complex concepts take diverse or ambiguous forms and have many hierarchical levels of granularity (e.g., tasks and subtasks), posing challenges for CDCR. We present a new task of Hierarchical CDCR (H-CDCR) with the goal of jointly inferring coreference clusters and hierarchy between them. We create SciCo, an expert-annotated dataset for H-CDCR in scientific papers, 3X larger than the prominent ECB+ resource. We study strong baseline models that we customize for H-CDCR, and highlight challenges for future work.

[Paper](https://arxiv.org/abs/2104.08809){: .btn--research} [Github](https://github.com/ariecattan/SciCo){: .btn--research} [Hugging Face](https://huggingface.co/datasets/allenai/scico){: .btn--research}


Extracting a knowledge base of mechanisms from COVID-19 papers
**Tom Hope** *, Aida Amini*, David Wadden, Madeleine van Zuylen, Sravanthi Parasa, Eric Horvitz, Daniel Weld, Roy Schwartz, Hannaneh Hajishirzi
<br>
NAACL 2021

> The COVID-19 pandemic has spawned a diverse body of scientific literature that is challenging to navigate, stimulating interest in automated tools to help find useful knowledge. We pursue the construction of a knowledge base (KB) of mechanisms -- a fundamental concept across the sciences encompassing activities, functions and causal relations, ranging from cellular processes to economic impacts. We extract this information from the natural language of scientific papers by developing a broad, unified schema that strikes a balance between relevance and breadth. We annotate a dataset of mechanisms with our schema and train a model to extract mechanism relations from papers. Our experiments demonstrate the utility of our KB in supporting interdisciplinary scientific search over COVID-19 literature, outperforming the prominent PubMed search in a study with clinical experts.

[Paper](https://arxiv.org/abs/2010.03824){: .btn--research} [Search engine](https://covidmechanisms.apps.allenai.org/){: .btn--research} [Github](https://github.com/AidaAmini/DyGIE-MECHANIC){: .btn--research}
