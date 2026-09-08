# 🔍 Multimodal_ST_Pathology Papers · 2026-09-07

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Synergistic Information Disentanglement for Omni-modal Slide Representation Learning in Computational Pathology](https://arxiv.org/abs/2609.02118)**  `arXiv:2609.02118`  `cs.CV`  
  _Mingxin Liu, Chengfei Cai, Anwen Lu, Pengbo Xu, Jun Li, Jinze Li, et al._
  <details open><summary>Abstract</summary>
  In computational pathology (CPath), developing omni-modal self-supervised learning (SSL) models that integrate histology, genomics, and clinical reports enables transferable representation learning for whole slide images (WSIs). Existing approaches implicitly force heterogeneous modalities into a uniform latent space by contrastive alignment, causing modality collapse where unique, synergistic diagnostic signals (termed as $\mathrm{\Phi}$) are discarded in favor of trivial redundancy. We hypothesize that the strongest task-agnostic SSL training signal stems from distilling the synergistic interactions over merely aligning shared redundancy. To this end, we introduce \textsc{$\mathrm{\Phi}$-Omni}, a synergistic information disentanglement framework grounded in Partial Information Decomposition (PID) theory for slide representation learning. Unlike standard contrastive approaches, \textsc{$\mathrm{\Phi}$-Omni} employs a Synergistic Information Bottleneck (SIB) regulated by the proposed $\mathrm{\Phi}\text{ID}$ objective, which explicitly suppresses marginal redundancy while maximizing irreducible synergy, thereby distilling high-order cross-modal interactions. Following pretraining on breast ($n$=1031) and lung ($n$=919) cohorts, \textsc{$\mathrm{\Phi}$-Omni} demonstrates superior few-shot performance across five independent external datasets spanning eight tasks compared to supervised and SSL baselines. Source code is available here.
  </details>
