---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

We are at a unique point in the history of science, where essentially all of scientific knowledge is in the digital space. This presents huge opportunity for computational approaches that augment and accelerate innovation by harnessing humankind’s collective knowledge. I develop artificial intelligence (AI) methods to harness vast repositories of scientific knowledge (e.g., literature, knowledge bases, electronic medical records) for helping humans to discover new knowledge.

Progress in research relies on leveraging existing knowledge for creating new knowledge. Similarly, practitioners in fields like medicine and engineering are often required to make complex decisions rooted in deep scientific knowledge. But with an explosion of scholarly information produced every day, experts often cannot see the broad landscape of possibility. My goal is to build systems that help humans throughout all stages of scientific work: discovering useful literature, exploring new directions and solutions to problems, generating hypotheses, and maing well-informed decisions.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
