---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

We are at a unique point in the history of science, where essentially all of scientific knowledge is in the digital space. This presents huge opportunity for computational approaches that augment and accelerate innovation by harnessing humankind’s collective knowledge. Progress in research relies on leveraging existing knowledge for creating new knowledge. Similarly, practitioners in fields like medicine and engineering are often required to make complex decisions rooted in deep scientific knowledge. But with an explosion of scholarly information produced every day, experts often cannot see the broad landscape of possibility. My goal is to build systems that help do precisely that, leveraging AI to help researchers and science-driven practitioners throughout all stages of their work: from coming up with ideas, generating hypotheses and finding literature, to performing analyses and making decisions. I create novel systems that mine scholarly literature, scientific knowledge bases and medical records -- to automatically find useful knowledge at a scale previously impossible, to identify important problems, directions and solutions, to inform decisions made by researchers and practioners, and to form connections between diverse ideas and areas.

My work spans a ``full-stack'' spectrum --- from constructing new datasets, tasks and machine learning models, to designing user experiments and user-facing systems. In order to be able to work with scientific knowledge, I develop novel methods and models in diverse computer science areas including text mining, search and retrieval, information extraction, human-computer interation, weak supervision, complex network visualization, knowledge graph construction and link prediction. Below is a sample of some representative projects.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
