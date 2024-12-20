---
title: "AI Inspiration"
layout: single-portfolio
excerpt: "<img src='/images/research/light.png' alt=''>"
collection: research
order_number: 1
header: 
  og_image: "/images/research/light.png"
---

SciMON: Scientific Inspiration Machines Optimized for Novelty<br>
_Qingyun Wang, Doug Downey, Heng Ji, **Tom Hope**_<br>
ACL, 2024

> We explore and enhance the ability of neural language models to generate novel scientific directions grounded in literature. Work on literature-based hypothesis generation has traditionally focused on binary link prediction--severely limiting the expressivity of hypotheses. This line of work also does not focus on optimizing novelty. We take a dramatic departure with a novel setting in which models use as input background contexts (e.g., problems, experimental settings, goals), and output natural language ideas grounded in literature. We present SciMON, a modeling framework that uses retrieval of "inspirations" from past scientific papers, and explicitly optimizes for novelty by iteratively comparing to prior papers and updating idea suggestions until sufficient novelty is achieved. Comprehensive evaluations reveal that GPT-4 tends to generate ideas with overall low technical depth and novelty, while our methods partially mitigate this issue. Our work represents a first step toward evaluating and developing language models that generate new ideas derived from the scientific literature

[Paper](https://arxiv.org/abs/2305.14259){: .btn--research}


Scideator: Human-LLM Scientific Idea Generation Grounded in Research-Paper Facet Recombination<br>
_Marissa Radensky, Simra Shahid, Raymond Fok, Pao Siangliulue, Daniel S. Weld*, **Tom Hope***_<br>
preprint, 2024

> The scientific ideation process often involves blending salient aspects of existing papers to create new ideas. To see if large language models (LLMs) can assist this process, we contribute Scideator, a novel mixed-initiative tool for scientific ideation. Starting from a user-provided set of papers, Scideator extracts key facets (purposes, mechanisms, and evaluations) from these and relevant papers, allowing users to explore the idea space by interactively recombining facets to synthesize inventive ideas. Scideator also helps users to gauge idea novelty by searching the literature for potential overlaps and showing automated novelty assessments and explanations. To support these tasks, Scideator introduces four LLM-powered retrieval-augmented generation (RAG) modules: Analogous Paper Facet Finder, Faceted Idea Generator, Idea Novelty Checker, and Idea Novelty Iterator. In a within-subjects user study, 19 computer-science researchers identified significantly more interesting ideas using Scideator compared to a strong baseline combining a scientific search engine with LLM interaction.

[Paper](https://arxiv.org/abs/2409.14634){: .btn--research}



Bursting Scientific Filter Bubbles: Boosting Innovation via Novel Author Discovery<br>
_Jason Portenoy, Marissa Radensky, Jevin West, Eric Horvitz, Daniel Weld, **Tom Hope**_<br>
CHI 2022 Conference on Human Factors in Computing Systems

> Isolated silos of scientific research and the growing challenge of information overload limit awareness across the literature and hinder innovation. Algorithmic curation and recommendation, which often prioritize relevance, can further reinforce these informational "filter bubbles." In response, we describe Bridger, a system for facilitating discovery of scholars and their work. We construct a faceted representation of authors with information gleaned from their papers and inferred author personas, and use it to develop an approach that locates commonalities and contrasts between scientists to balance relevance and novelty. In studies with computer science researchers, this approach helps users discover authors considered useful for generating novel research directions. We also demonstrate an approach for displaying information about authors, boosting the ability to understand the work of new, unfamiliar scholars. Our analysis reveals that Bridger connects authors who have different citation profiles and publish in different venues, raising the prospect of bridging diverse scientific communities.

[Paper](https://arxiv.org/abs/2108.05669){: .btn--research}


Accelerating Innovation Through Analogy Mining
<br>
_**Tom Hope**, Joel Chan, Aniket Kittur, Dafna Shahaf_<br>
KDD 2017 (**_Best Research Paper Award_**)

> The availability of large idea repositories (e.g., the U.S. patent database) could significantly accelerate innovation and discovery by providing people with inspiration from solutions to analogous problems. However, finding useful analogies in these large, messy, real-world repositories remains a persistent challenge for either human or automated methods. Previous approaches include costly hand-created databases that have high relational structure (e.g., predicate calculus representations) but are very sparse. Simpler machine-learning/information-retrieval similarity metrics can scale to large, natural-language datasets, but struggle to account for structural similarity, which is central to analogy. In this paper we explore the viability and value of learning simpler structural representations, specifically, "problem schemas", which specify the purpose of a product and the mechanisms by which it achieves that purpose. Our approach combines crowdsourcing and recurrent neural networks to extract purpose and mechanism vector representations from product descriptions. We demonstrate that these learned vectors allow us to find analogies with higher precision and recall than traditional information-retrieval methods. In an ideation experiment, analogies retrieved by our models significantly increased people's likelihood of generating creative ideas compared to analogies retrieved by traditional methods. Our results suggest a promising approach to enabling computational analogy at scale is to learn and leverage weaker structural representations.

[Paper](https://arxiv.org/abs/1706.05585){: .btn--research}

Scaling Creative Inspiration with Fine-Grained Functional Aspects of Ideas
<br>
_**Tom Hope**, Ronen Tamari, Hyeonsu Kang, Daniel Hershcovich, Joel Chan, Aniket Kittur, Dafna Shahaf_<br>
CHI 2022 Conference on Human Factors in Computing Systems

> Large repositories of products, patents and scientific papers offer an opportunity for building systems that scour millions of ideas and help users discover inspirations. However, idea descriptions are typically in the form of unstructured text, lacking key structure that is required for supporting creative innovation interactions. Prior work has explored idea representations that were either limited in expressivity, required significant manual effort from users, or dependent on curated knowledge bases with poor coverage. We explore a novel representation that automatically breaks up products into fine-grained functional aspects capturing the purposes and mechanisms of ideas, and use it to support important creative innovation interactions: functional search for ideas, and exploration of the design space around a focal problem by viewing related problem perspectives pooled from across many products. In user studies, our approach boosts the quality of creative search and inspirations, substantially outperforming strong baselines by 50-60%.

[Paper](https://arxiv.org/abs/2102.09761){: .btn--research}


ACCoRD: A Multi-Document Approach to Generating Diverse Descriptions of Scientific Concepts<br>
_Sonia K. Murthy, Kyle Lo, Daniel King, Chandra Bhagavatula, Bailey Kuehl, Sophie Johnson, Jonathan Borchardt, Daniel S. Weld, **Tom Hope**, Doug Downey_
<br>
EMNLP 2022

> Systems that can automatically define unfamiliar terms hold the promise of improving the accessibility of scientific texts, especially for readers who may lack prerequisite background knowledge. However, current systems assume a single "best" description per concept, which fails to account for the many potentially useful ways a concept can be described. We present ACCoRD, an end-to-end system tackling the novel task of generating sets of descriptions of scientific concepts. Our system takes advantage of the myriad ways a concept is mentioned across the scientific literature to produce distinct, diverse descriptions of target scientific concepts in terms of different reference concepts. To support research on the task, we release an expert-annotated resource, the ACCoRD corpus, which includes 1,275 labeled contexts and 1,787 hand-authored concept descriptions. We conduct a user study demonstrating that (1) users prefer descriptions produced by our end-to-end system, and (2) users prefer multiple descriptions to a single "best" description.

[Paper](https://arxiv.org/abs/2205.06982){: .btn--research} [Github](https://github.com/allenai/ACCoRD){: .btn--research}

