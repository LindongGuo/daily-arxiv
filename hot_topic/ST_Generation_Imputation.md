# 🔍 ST_Generation_Imputation Papers · 2026-08-16

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Program-space Diffusion for Morphology-to-Transcriptomics Prediction](https://arxiv.org/abs/2608.14330)**  `arXiv:2608.14330`  `cs.AI`  
  _Ruyter Swann, Dorent Reuben, Racoceanu Daniel_
  <details open><summary>Abstract</summary>
  Spatial transcriptomics (ST) enables genome-wide gene expression profiling while preserving tissue architecture, but its cost and limited scalability remain major bottlenecks. This has motivated models that predict spatial expression directly from routine histology. Despite promising results, most existing approaches operate at the gene level without leveraging established transcriptomic modeling practices and rely on heterogeneous gene selection strategies, which complicates fair comparison across methods.We propose to reformulate morphology-to-transcriptomics prediction as conditional generation in transcriptional program space, thereby exploiting coordinated transcriptional variation instead of predicting genes independently. Using consensus non-negative matrix factorization (cNMF), we extract a low-dimensional set of transcriptional programs capturing coordinated expression variation in the training data, and train a conditional diffusion model to generate program activations from histology. This formulation exploits coordinated transcriptional variation and substantially lowers the dimensionality of the conditional generative task.
  </details>
