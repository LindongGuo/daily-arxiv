# 🔍 Med_Foundation_Models Papers · 2026-09-13

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Bridging Vision Foundation Model Priors with CLIP for Spatial-aware Few-shot Anomaly Detection in Medical Images](https://arxiv.org/abs/2609.12454)**  `arXiv:2609.12454`  `cs.CV` `cs.AI` `cs.LG`  
  _Juzheng Miao, Yuchen Yuan, Cheng Chen, Pheng-Ann Heng_
  <details open><summary>Abstract</summary>
  Vision-Language Models such as CLIP enable effective few-shot medical anomaly detection (AD) via strong image-text semantic alignment. However, their globally contrastive pretraining lacks explicit spatial supervision, limiting precise lesion localization. In contrast, Vision Foundation Models (VFMs) such as DINO learn spatially coherent patch representations via self-distillation and local-to-global consistency, better capturing fine-grained anatomical structures. Leveraging this complementarity, we propose Spatial-FAD, a spatial-aware few-shot medical AD framework that improves lesion localization by combining VFM spatial priors with CLIP semantics. Specifically, we introduce a VFM-enhanced adapter that injects a structural affinity prior derived from DINO into CLIP features. This structure-guided refinement encourages visual embeddings to better adhere to lesion boundaries while maintaining semantic alignment. To address the loss of spatial detail from patchification and the limited input resolution of CLIP, we adopt a sliding-window aggregation strategy. This generates high-resolution, spatially dense embeddings to further enhance localization granularity. Moreover, we introduce a prototype-enhanced support memory scheme to efficiently exploit the few-shot support set. This module stores compact prototypes for normal and abnormal patterns, reducing memory costs while boosting performance by fusing patch-to-prototype and image-text similarities. Extensive experiments on three benchmark datasets, including Liver CT, Retinal OCT, and Brain MRI, demonstrate that Spatial-FAD significantly outperforms state-of-the-art methods, especially in lesion segmentation. Notably, in the 4-shot scenario, our method achieves an average improvement of over 11.4% in Dice score and 1.8% in AUC. Code is available at:this https URL.
  </details>
