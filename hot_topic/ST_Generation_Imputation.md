# 🔍 ST_Generation_Imputation Papers · 2026-05-25

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Knowledge Graph Modulated Deep Learning for Limited-Sample Clinical Data Analysis](https://arxiv.org/abs/2605.24162)**  `arXiv:2605.24162`  `cs.LG` `cs.AI`  
  _Yuwei Xue, Sakib Mostafa, James Zou, Joseph Liao, Maximilian Diehn, Ash A. Alizadeh, et al._
  <details open><summary>Abstract</summary>
  Biological systems are governed by structured molecular interactions, where pathways, regulatory circuits, and functional gene relationships shape cellular behavior and disease progression. Much of this knowledge is naturally represented as graphs. However, most biomedical AI models cannot directly use graph-encoded biological knowledge and instead require compressed low-dimensional representations, which can lose important structure and reduce performance, especially in limited-sample clinical studies. Here, we introduce Graph-in-Graph (GiG), a knowledge graph-modulated deep learning framework for data-efficient clinical prediction. GiG represents each patient as a standalone modular graph, in which curated biological knowledge graphs define edges and patient-specific measurements, such as gene expression, define node features. This design allows multiple biological knowledge graphs to be integrated while preserving gene-gene interactions and pathway topology during patient-level representation learning. Across cohorts comprising nearly 9,700 patients and five clinical tasks, including liquid biopsy cancer detection, prostate cancer diagnosis, and 32-class pan-cancer classification, GiG consistently outperforms traditional and state-of-the-art methods, with the largest gains in limited-sample settings. On the challenging prostate cancer diagnosis task, GiG improves macro-F1 by up to 49 percentage points relative to competing methods. Control experiments replacing real pathway graphs with random topologies confirm that these gains arise from biologically grounded knowledge graph structure rather than graph modeling alone. These findings show that knowledge graph-modulated deep learning can improve robustness, interpretability, and sample efficiency in clinical data analysis, and provide a principled framework for integrating biological knowledge graphs into predictive modeling.
  </details>

- **[Learning Latent Dynamical Causal Processes for Single-Cell Perturbation Prediction](https://arxiv.org/abs/2605.25581)**  `arXiv:2605.25581`  `cs.LG`  
  _Wenkang Jiang, Yuhang Liu, Erdun Gao, Ehsan Abbasnejad, Lina Yao, Javen Qinfeng Shi_
  <details open><summary>Abstract</summary>
  Single-cell perturbation prediction aims to infer how cells respond to unseen interventions and to achieve out-of-distribution (OOD) generalization, providing a computational route to understanding how perturbations reshape cellular programs over time. Existing machine learning methods have made important progress, but typically capture only one side of the response. Latent causal approaches seek mechanisms that support generalization and interpretation, yet often treat perturbation effects as static outcomes. Temporal models describe how gene expression changes across time, but usually do not explicitly recover the latent causal generative mechanisms driving these changes. In practice, perturbation effects are both latent and dynamical: interventions act through unobserved cellular programs, whose states evolve over time and give rise to observed expression profiles. Motivated by this view, we propose a latent dynamical causal generative model for single-cell perturbation data that jointly captures latent cellular programs, perturbation-conditioned mechanisms, and temporal evolution. We further provide an identifiability analysis showing that, under suitable conditions, the latent causal variables are recoverable up to standard equivalence classes. Guided by this analysis, we develop CITE-VAE, a learning framework for recovering latent cellular programs and their perturbation-driven dynamics from single-cell sequencing data. Experiments on Causal-3DIdent validate the theoretical results and the effectiveness of the proposed method in controlled settings. Additional experiments on real-world CRISPR-based single-cell perturbation data show improved generalization to unseen perturbations compared with state-of-the-art baselines, highlighting the practical robustness of our approach.
  </details>
