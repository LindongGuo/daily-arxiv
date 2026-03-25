# 🔍 Med_Foundation_Models Papers · 2026-03-24

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Cross-Slice Knowledge Transfer via Masked Multi-Modal Heterogeneous Graph Contrastive Learning for Spatial Gene Expression Inference](https://arxiv.org/abs/2603.22821)**  `arXiv:2603.22821`  `cs.CV`  
  _Zhiceng Shi, Changmiao Wang, Jun Wan, Wenwen Min_
  <details open><summary>Abstract</summary>
  While spatial transcriptomics (ST) has advanced our understanding of gene expression in tissue context, its high experimental cost limits its large-scale application. Predicting ST from pathology images is a promising, cost-effective alternative, but existing methods struggle to capture complex cross-slide spatial relationships. To address the challenge, we propose SpaHGC, a multi-modal heterogeneous graph-based model that captures both intra-slice and inter-slice spot-spot relationships from histology images. It integrates local spatial context within the target slide and cross-slide similarities computed from image embeddings extracted by a pathology foundation model. These embeddings enable inter-slice knowledge transfer, and SpaHGC further incorporates Masked Graph Contrastive Learning to enhance feature representation and transfer spatial gene expression knowledge from reference to target slides, enabling it to model complex spatial dependencies and significantly improve prediction accuracy. We conducted comprehensive benchmarking on seven matched histology-ST datasets from different platforms, tissues, and cancer subtypes. The results demonstrate that SpaHGC significantly outperforms the existing nine state-of-the-art methods across all evaluation metrics. Additionally, the predictions are significantly enriched in multiple cancer-related pathways, thereby highlighting its strong biological relevance and application potential.
  </details>

- **[Pretext Matters: An Empirical Study of SSL Methods in Medical Imaging](https://arxiv.org/abs/2603.22649)**  `arXiv:2603.22649`  `cs.CV`  
  _Vedrana Ivezić, Mara Pleasure, Ashwath Radhachandran, Saarang Panchavati, Shreeram Athreya, Vivek Sant, et al._
  <details open><summary>Abstract</summary>
  Though self-supervised learning (SSL) has demonstrated incredible ability to learn robust representations from unlabeled data, the choice of optimal SSL strategy can lead to vastly different performance outcomes in specialized domains. Joint embedding architectures (JEAs) and joint embedding predictive architectures (JEPAs) have shown robustness to noise and strong semantic feature learning compared to pixel reconstruction-based SSL methods, leading to widespread adoption in medical imaging. However, no prior work has systematically investigated which SSL objective is better aligned with the spatial organization of clinically relevant signal. In this work, we empirically investigate how the choice of SSL method impacts the learned representations in medical imaging. We select two representative imaging modalities characterized by unique noise profiles: ultrasound and histopathology. When informative signal is spatially localized, as in histopathology, JEAs are more effective due to their view-invariance objective. In contrast, when diagnostically relevant information is globally structured, such as the macroscopic anatomy present in liver ultrasounds, JEPAs are optimal. These differences are especially evident in the clinical relevance of the learned features, as independently validated by board-certified radiologists and pathologists. Together, our results provide a framework for matching SSL objectives to the structural and noise properties of medical imaging modalities.
  </details>
