---
layout: archive
title: "Research Highlights"
permalink: /research/
author_profile: true
header:
  og_image: "images/research/light.png"
---
<!-- [[For my list of publications, see here.]](https://scholar.google.com/citations?hl=en&user=RZbspgIAAAAJ&view_op=list_works&sortby=pubdate) -->
We are at a unique point in the history of science, where essentially all of scientific knowledge is in the digital space. This presents a huge opportunity for computational approaches that augment and accelerate discovery by harnessing humankind’s collective knowledge. 

Progress in science relies on leveraging _existing_ knowledge for creating _new_ knowledge; similarly, practitioners in fields like medicine make complex decisions that require deep knowledge. But, with an explosion of information, experts often cannot see the broad landscape of possibility. My goal is to build new AI models and systems that **mine scientific literature and knowledge bases** to help researchers and practitioners by generating ideas and hypotheses, finding solutions to problems, performing analyses and making decisions. I discuss this vision and core work to date in a recent [perspective paper on the cover of CACM](https://mags.acm.org/communications/august_2023/MobilePagedReplica.action?=undefined&pm=2&folio=61#pg63).

<iframe src="https://player.vimeo.com/video/840526776?h=672d34af59" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe><script src="https://player.vimeo.com/api/player.js"></script>

My work spans a "full-stack" spectrum: from constructing new datasets, tasks and machine learning models, to designing user experiments and user-facing systems. I explore new paradigms in diverse areas of computer science such as text mining, search and retrieval, multimodal models and LLMs, information extraction, human-computer interaction, weak supervision, knowledge graph construction and link prediction. Below are some representative examples. 


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
