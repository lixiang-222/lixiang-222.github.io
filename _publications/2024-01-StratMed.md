---
title: "StratMed: Relevance stratification between biomedical entities for sparsity on medication recommendation"
collection: Elsevier
author: Li X, Liang S, Hou Y, et al.
excerpt: 'This article aims to address the sparsity of entities in medication recommendations.'
date: 2024-01-25
venue: 'Knowledge-Based Systems'
paperurl: 'https://linkinghub.elsevier.com/retrieve/pii/S0950705123009887'
citation: '@article{li2024stratmed,
  title={StratMed: Relevance stratification between biomedical entities for sparsity on medication recommendation},
  author={Li, Xiang and Liang, Shunpan and Hou, Yulei and Ma, Tengfei},
  journal={Knowledge-Based Systems},
  volume={284},
  pages={111239},
  year={2024},
  publisher={Elsevier}
}
'
---

Project completion date: 2023-09  
Final publication date: 2024-01

With the growing imbalance between limited medical resources and escalating demands, AI-based clinical tasks have become
paramount. As a sub-domain, medication recommendation aims to amalgamate longitudinal patient history with medical
knowledge, assisting physicians in prescribing safer and more accurate medication combinations.
Existing works ignore the inherent long-tailed distribution of medical data, have uneven learning strengths for hot and
sparse data, and fail to balance safety and accuracy.
To address the above limitations, we propose StratMed, which introduces a stratification strategy that overcomes the
long-tailed problem and achieves fuller learning of sparse data. It also utilizes a dual-property network to address the
issue of mutual constraints on the safety and accuracy of medication combinations, synergistically enhancing these two
properties.
Specifically, we construct a pre-training method using deep learning networks to obtain medication and disease
representations.
After that, we design a pyramid-like stratification method based on relevance to strengthen the expressiveness of sparse
data.
Based on this relevance, we design two graph structures to express medication safety and precision at the same level to
obtain patient representations.
Finally, the patient's historical clinical information is fitted to generate medication combinations for the current
health condition.
We employed the MIMIC-III dataset to evaluate our model against state-of-the-art methods in three aspects
comprehensively. Compared to the sub-optimal baseline model, our model reduces safety risk by 15.08%, improves accuracy
by 0.36%, and reduces training time consumption by 81.66%.