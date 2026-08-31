# 🔍 Med_Foundation_Models Papers · 2026-08-30

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[EXPOSE: Explainable and Domain-Robust Embeddings from Pathology Vision Foundation Models using Sparse Autoencoders](https://arxiv.org/abs/2608.28191)**  `arXiv:2608.28191`  `cs.CV` `cs.LG`  
  _Anja Witte, Maximilian Lennartz, Jan Baumbach, Guido Sauter, Stefan Bonn, Patrick Fuhlert, et al._
  <details open><summary>Abstract</summary>
  Vision Foundation Models (VFMs) are widely used in computational pathology but remain sensitive to domain shifts arising from variations in staining, tissue preparation, and scanner hardware. A key limitation is that VFM embeddings entangle biological with domain-specific information, hindering cross-domain generalization. We propose Explainable Probing of Cross-Domain Sparse Embeddings (EXPOSE), a framework that uses Sparse Autoencoders (SAEs) as an explainable bottleneck to identify and suppress domain-specific components in VFM embeddings. We train a sparse representation of VFM features, use a linear classifier to identify domain-specific latent dimensions, and mask these features prior to downstream relapse prediction without retraining the backbone model. Experiments on a large prostate cancer dataset with multiple acquisition domains show that SAE features capture both domain- and task-specific information, which are partially disentangled in the latent space. Removing domain-specific features improves cross-domain performance and increases embedding robustness as measured by the Domain Robustness Index (DoRI). Code is available atthis https URL.
  </details>
