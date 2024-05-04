---
title: "Dual-Granularity Medication Recommendation Based on Causal Inference"
collection: arxiv
excerpt: 'This article proposes a dual-granularity framework for medication recommendation that utilizes causal
inference to combine molecular-level and entity-level relationships, and designs a causality-based bias correction
approach.'
date: 2024-03-01
venue: 'arxiv'
paperurl: 'https://arxiv.org/abs/2403.00880'
citation: 'Liang S, Li X, Li C, et al. Dual-Granularity Medication Recommendation Based on Causal Inference[J]. arXiv
preprint arXiv:2403.00880, 2024.'
---

Project completion date: 2024-3  
Final publication date: unknown

Medication recommendation aims to integrate patients' long-term health records, recommending accuracy and safe
medication combinations for specific health status.
Although existing research makes significant strides from the perspectives of relationships between medical entities
level or their molecular structures level, it does not consider combining these two different granularities to express
the complex relationships between medications and diseases. To address this challenge, we propose a novel medication
recommendation framework, CIDGMed. It utilizes causal inference methods to merge information from both entity and
molecular levels, facilitating a complementary interplay of dual-granularity information.
Specifically, we first use causal inference to learn and quantify the relationships between medications and diseases.
Then, we align medication and disease embeddings in the molecular space to address heterogeneity issues. Finally, we
integrate the patient's longitudinal records to generate personalized representations and recommend medication
combinations based on the current health status and causal effects between entities.
Through extensive experimentation, CIDGMed outperforms the current state-of-the-art models on multiple metrics, with an
increase in accuracy by 4.40%, a decrease in side effects by 6.14%, and a 47.15% improvement in time efficiency.
Additionally, we demonstrate the interpretability of CIDGMed through a case study.