# 🔍 Multimodal_ST_Pathology Papers · 2026-05-25

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Benchmarking Pathology Foundation Models for Spatial Domain Understanding](https://arxiv.org/abs/2605.25764)**  `arXiv:2605.25764`  `cs.CV` `cs.AI`  
  _Bokai Zhao, Yiyang Zhang, Yuanchi Zhu, Hanqing Chao, Long Bai, Tai Ma, et al._
  <details open><summary>Abstract</summary>
  Pathology foundation models (PFMs) have emerged as a core approach for learning transferable representations from whole slide images (WSIs), and they are typically benchmarked through downstream clinical endpoints. While such task level evaluations are indispensable, they offer limited insight into what the representations themselves encode, particularly whether PFM embeddings can distinguish meaningful tissue regions and capture their spatial relationships. We present SpaPath-Bench, a representation level benchmark designed to diagnose spatial representation capability in PFMs. SpaPath-Bench formulates spatial domain identification (SDI) on paired whole slide image and spatial transcriptomics (ST) data as a diagnostic task. It curates 42 public paired WSI and ST slides, enables large scale evaluation across 19 encoders and seven SDI methods, and measures partition quality using three complementary criteria: unsupervised spatial coherence, transcriptomics referenced agreement, and expert referenced agreement. Across 83K runs, SpaPath-Bench reveals that different pretraining paradigms capture distinct aspects of tissue spatial architecture, and it provides practical guidance for building the next generation of spatially aware computational pathology models. Code and data pipelines are publicly available atthis https URL.
  </details>
