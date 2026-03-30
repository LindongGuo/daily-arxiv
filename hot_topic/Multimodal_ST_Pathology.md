# 🔍 Multimodal_ST_Pathology Papers · 2026-03-29

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[MUST: Modality-Specific Representation-Aware Transformer for Diffusion-Enhanced Survival Prediction with Missing Modality](https://arxiv.org/abs/2603.26071)**  `arXiv:2603.26071`  `cs.CV` `cs.LG`  
  _Kyungwon Kim, Dosik Hwang_
  <details open><summary>Abstract</summary>
  Accurate survival prediction from multimodal medical data is essential for precision oncology, yet clinical deployment faces a persistent challenge: modalities are frequently incomplete due to cost constraints, technical limitations, or retrospective data availability. While recent methods attempt to address missing modalities through feature alignment or joint distribution learning, they fundamentally lack explicit modeling of the unique contributions of each modality as opposed to the information derivable from other modalities. We propose MUST (Modality-Specific representation-aware Transformer), a novel framework that explicitly decomposes each modality's representation into modality-specific and cross-modal contextualized components through algebraic constraints in a learned low-rank shared subspace. This decomposition enables precise identification of what information is lost when a modality is absent. For the truly modality-specific information that cannot be inferred from available modalities, we employ conditional latent diffusion models to generate high-quality representations conditioned on recovered shared information and learned structural priors. Extensive experiments on five TCGA cancer datasets demonstrate that MUST achieves state-of-the-art performance with complete data while maintaining robust predictions in both missing pathology and missing genomics conditions, with clinically acceptable inference latency.
  </details>
