# 🔍 Med_Foundation_Models Papers · 2026-08-11

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[P3CA: Encoder-Agnostic Interpretation of Vision Foundation Model Embeddings via Spatial Probing](https://arxiv.org/abs/2608.10131)**  `arXiv:2608.10131`  `cs.CV` `cs.LG`  
  _Amoon Jamzad, Dilakshan Srikanthan, Faranak Akbarifar, Nooshin Maghsoodi, Parvin Mousavi_
  <details open><summary>Abstract</summary>
  Vision foundation models are increasingly used as reusable encoders in medical image computing, yet their high-dimensional spatial embeddings are difficult to inspect beyond downstream task performance or global dimensionality reduction. We propose position-prompted PCA (P3CA), an encoder-agnostic method for local probing of channel-rich spatial tensors. Given a user-selected spatial prompt, P3CA estimates the feature normalization and dominant covariance directions within that region, then applies the resulting projection to the full tensor to visualize where locally informative directions are expressed. This produces a region-conditioned representation lens without modifying the encoder, retraining, or requiring task-specific labels. We implement P3CA in EmbedVision, an interactive 3D Slicer-based workflow, and evaluate it across natural images, colorectal pathology foundation-model embeddings, and spatial transcriptomic tensors. Across these settings, prompted projections reveal local structure suppressed by global PCA, improve prompt-matched pathology discrimination from frozen three-dimensional projections, and support comparison between learned and measured spatial representations.
  </details>
