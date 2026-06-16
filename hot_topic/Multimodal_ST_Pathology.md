# 🔍 Multimodal_ST_Pathology Papers · 2026-06-15

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Pathway-Structured Privileged Distillation for Deployable Computational Pathology](https://arxiv.org/abs/2606.02877)**  `arXiv:2606.02877`  `cs.CV`  
  _Yongxin Guo, Hao Lu, Onur Koyun, Muhammet Demir, Metin Gurcan_
  <details open><summary>Abstract</summary>
  Integrating transcriptomics and histopathology can improve cancer risk modelling, yet practical use is constrained by the limited availability of RNA profiling in routine settings. Here we introduce Mixture of Pathway Experts (MoPE), a knowledge-distillation framework that reframes multimodal learning as privileged distillation for histology-only inference. MoPE is motivated by the partial observability between RNA profiles and whole-slide images: histology can capture morphology-linked consequences of certain molecular programmes, but cannot be expected to reconstruct the full transcriptomic state. MoPE encodes RNA-derived pathways and transfers the molecular supervision to pathway-indexed pathology experts through memory-usage alignment. Across diverse public benchmarks and two independent breast cancer cohorts, MoPE consistently improved WSI-only inference performance relative to baseline methods. Pathway-usage analyses and human-audited visual inspection provide bounded inspection of model behaviour and candidate morphology-linked readouts. These results support pathway-structured privileged distillation as a promising route to using molecular information during training while preserving RNA-free inference.
  </details>
