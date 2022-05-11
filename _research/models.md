---
title: "Weak Supervision"
layout: single-portfolio
excerpt: "<img src='/images/research/aspire.png' alt=''>"
collection: research
order_number: 3
header: 
  og_image: "/images/research/aspire.png"
---

Multi-Vector Models with Textual Guidance for Fine-Grained Scientific Document Similarity<br>
_Sheshera Mysore, Arman Cohan, **Tom Hope**_<br>
NAACL 2022

> We present Aspire, a new scientific document similarity model based on matching fine-grained aspects. Our model is trained using co-citation contexts that describe related paper aspects as a novel form of textual supervision. We use multi-vector document representations, recently explored in settings with short query texts but under-explored in the challenging document-document setting. We present a fast method that involves matching only single sentence pairs, and a method that makes sparse multiple matches with optimal transport. Our model improves performance on document similarity tasks across four datasets. Moreover, our fast single-match method achieves competitive results, opening up the possibility of applying fine-grained document similarity models to large-scale scientific corpora.

[Preprint](https://arxiv.org/abs/2111.08366){: .btn--research} [Github](https://github.com/allenai/aspire){: .btn--research} 


Ballpark Crowdsourcing: The Wisdom of Rough Group Comparisons<br>
_**Tom Hope**, Dafna Shahaf_<br>
WSDM 2018

> Crowdsourcing has become a popular method for collecting labeled training data. However, in many practical scenarios traditional labeling can be difficult for crowdworkers (for example, if the data is high-dimensional or unintuitive, or the labels are continuous). In this work, we develop a novel model for crowdsourcing that can complement standard practices by exploiting people's intuitions about groups and relations between them. We employ a recent machine learning setting, called Ballpark Learning, that can estimate individual labels given only coarse, aggregated signal over groups of data points. To address the important case of continuous labels, we extend the Ballpark setting (which focused on classification) to regression problems. We formulate the problem as a convex optimization problem and propose fast, simple methods with an innate robustness to outliers.
We evaluate our methods on real-world datasets, demonstrating how useful constraints about groups can be harnessed from a crowd of non-experts. Our methods can rival supervised models trained on many true labels, and can obtain considerably better results from the crowd than a standard label-collection process (for a lower price). By collecting rough guesses on groups of instances and using machine learning to infer the individual labels, our lightweight framework is able to address core crowdsourcing challenges and train machine learning models in a cost-effective way.

[Paper](https://arxiv.org/abs/1712.04828){: .btn--research} [Github](https://github.com/tomhoper/ballpark/blob/master/ballpark_feasibility_reg.py){: .btn--research}


A Weak Supervision Approach to Detecting Visual Anomalies for Automated Testing of Graphics Units<br>
_Adi Szeskin, Lev Faivishevsky, Ashwin K Muppalla, Amitai Armon, **Tom Hope**_<br>
KDD 2021 & NeurIPS ML4SYS 2019

> We present a deep learning system for testing graphics units by detecting novel visual corruptions in videos. Unlike previous work in which manual tagging was required to collect labeled training data, our weak supervision method is fully automatic and needs no human labelling. This is achieved by reproducing driver bugs that increase the probability of generating corruptions, and by making use of ideas and methods from the Multiple Instance Learning (MIL) setting. In our experiments, we significantly outperform unsupervised methods such as GAN-based models and discover novel corruptions undetected by baselines, while adhering to strict requirements on accuracy and efficiency of our real-time system.

[NeurIPS report](https://arxiv.org/abs/1912.04138){: .btn--research} [KDD paper](https://dl.acm.org/doi/abs/10.1145/3447548.3467116){: .btn--research}


