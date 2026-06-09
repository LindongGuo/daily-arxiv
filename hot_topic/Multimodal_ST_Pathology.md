# 🔍 Multimodal_ST_Pathology Papers · 2026-06-08

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[SNR-ST-Mix: Sample-specific Neighborhood Regression Mixup for Augmented Spatial Transcriptomics Imputation with Deep Neural Network](https://arxiv.org/abs/2606.08712)**  `arXiv:2606.08712`  `cs.LG` `cs.AI` `cs.CV`  
  _Hongyi Yu, Yaoyu Fang, Jiahe Qian, Xinkun Wang, Lee A. Cooper, Bo Zhou_
  <details open><summary>Abstract</summary>
  Purpose: Spatial transcriptomics (ST) enables gene expression measurements within the tissue context. However, these measurements are often noisy, low-resolution, and sparsely sampled, which limits the recovery of fine spatial structure. Deep neural networks have become powerful tools for expression imputation from histology, but their performance remains constrained by limited sample sizes and a lack of biologically informed augmentation. Most of the existing augmentation strategies for learning are designed for classification tasks rather than regression, which neglect spatial and transcriptomic relationships, leading to biologically implausible interpolations that hinder prediction performance. Approach: To address these limitations, we propose SNR-ST-Mix, a geometry- and expression-aware data augmentation framework designed specifically for ST data. It constrains mixing to a spot's k-nearest spatial neighbors and adaptively weights interpolation coefficients based on expression similarity, generating augmented samples that preserve local biological structure while ensuring spatial smoothness. This dual conditioning yields synthetic examples that expand the effective training manifold, promote generalization, and enhance prediction stability under sample-specific training. Results: Extensive experiments with various tissue types demonstrate that SNR-ST-Mix consistently outperforms conventional augmentation methods without requiring architectural changes or additional computation. Conclusions: SNR-ST-Mix provides an effective and biologically principled augmentation strategy for spatial transcriptomics regression tasks. By explicitly leveraging spatial geometry and transcriptomic similarity, it expands the effective training manifold and improves predictive performance without increasing model complexity.
  </details>
