# 🔍 ST_Generation_Imputation Papers · 2026-09-07

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[MedFlow: Class-Aware Multi-Scale Generation for Medical Time-Series Synthesis](https://arxiv.org/abs/2609.04804)**  `arXiv:2609.04804`  `cs.AI`  
  _Yanhao Huang, Shibo Feng, Wanjin Feng, Peilin Zhao, Chunyan Miao_
  <details open><summary>Abstract</summary>
  Synthetic medical time-series generation can alleviate data scarcity and support the development of reliable clinical prediction models. However, existing methods mainly focus on matching the overall distribution and temporal dynamics of real data, which does not necessarily ensure strong downstream utility on imbalanced medical datasets. Clinically informative patterns often occur at heterogeneous temporal scales, while rare minority-class characteristics can be obscured by dominant population patterns. To address these challenges, we propose MedFlow, a class-aware multi-scale flow matching framework for medical time-series synthesis. MedFlow employs a vector-quantized multi-scale tokenizer to represent medical sequences at complementary temporal resolutions, capturing both coarse clinical trends and fine-grained dynamics. We further introduce Token Marginal Guidance, which incorporates class-conditional token statistics directly into the flow matching process to steer generation toward class-specific regions of the learned tokens. This mechanism strengthens minority-class patterns, while preserving the global and tail distributions of real data. Experiments on four public datasets covering electronic health records, EEG, and ECG signals demonstrate that MedFlow consistently outperforms recent state-of-the-art diffusion-based baselines across downstream prediction tasks. On average, it improves AUPRC by 5.8%, reduces Context-FID by 88.6%, and achieves 3.8$\times$ higher sampling throughput.
  </details>
