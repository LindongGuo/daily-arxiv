# 🔍 Med_Foundation_Models Papers · 2026-09-06

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Conserved Immune Topology Improves Pathology Foundation Model Generalization for Cross-Cancer MSI-H Prediction](https://arxiv.org/abs/2609.05182)**  `arXiv:2609.05182`  `cs.CV`  
  _Dasari Naga Raju_
  <details open><summary>Abstract</summary>
  Pathology foundation models integrated with multiple instance learning achieve competitive accuracy within single-cancer cohorts, yet cross-cancer generalization remains unresolved due to organ-specific histological and architectural differences. In this paper, we propose Conserved Immune Topology (CIT), a lightweight spatial representation for cross-cancer MSI-H prediction that augments foundation-model embeddings with biologically motivated immune descriptors. CIT uses unsupervised clustering to identify immune-associated tiles, then encodes tertiary lymphoid structures, peritumoral immune reactions, multi-scale tumor-infiltrating lymphocyte density, and immune-tumor mixing from frozen foundation-model embeddings and tile coordinates without requiring annotations or target-domain data. The proposed method was evaluated under cross-site and cross-cancer settings using CPTAC-COAD and TCGA-STAD cohorts, which introduce scanner variability, distribution shifts, and organ-specific architectural variations. Zero-shot cross-cancer transfer with CIT increased TransMIL AUC from 0.6627 to 0.7161, an absolute gain of 0.0534 (p=0.003), with consistent improvements across all three MIL aggregators. These results suggest that spatial immune topology provides potentially an organ-invariant representation for MSI-H prediction, supporting cross-cancer generalization of pathology foundation models.
  </details>

- **[Synergistic Information Disentanglement for Omni-modal Slide Representation Learning in Computational Pathology](https://arxiv.org/abs/2609.02118)**  `arXiv:2609.02118`  `cs.CV`  
  _Mingxin Liu, Chengfei Cai, Anwen Lu, Pengbo Xu, Jun Li, Jinze Li, et al._
  <details open><summary>Abstract</summary>
  In computational pathology (CPath), developing omni-modal self-supervised learning (SSL) models that integrate histology, genomics, and clinical reports enables transferable representation learning for whole slide images (WSIs). Existing approaches implicitly force heterogeneous modalities into a uniform latent space by contrastive alignment, causing modality collapse where unique, synergistic diagnostic signals (termed as $\mathrm{\Phi}$) are discarded in favor of trivial redundancy. We hypothesize that the strongest task-agnostic SSL training signal stems from distilling the synergistic interactions over merely aligning shared redundancy. To this end, we introduce \textsc{$\mathrm{\Phi}$-Omni}, a synergistic information disentanglement framework grounded in Partial Information Decomposition (PID) theory for slide representation learning. Unlike standard contrastive approaches, \textsc{$\mathrm{\Phi}$-Omni} employs a Synergistic Information Bottleneck (SIB) regulated by the proposed $\mathrm{\Phi}\text{ID}$ objective, which explicitly suppresses marginal redundancy while maximizing irreducible synergy, thereby distilling high-order cross-modal interactions. Following pretraining on breast ($n$=1031) and lung ($n$=919) cohorts, \textsc{$\mathrm{\Phi}$-Omni} demonstrates superior few-shot performance across five independent external datasets spanning eight tasks compared to supervised and SSL baselines. Source code is available here.
  </details>
