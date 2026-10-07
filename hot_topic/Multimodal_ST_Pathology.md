# 🔍 Multimodal_ST_Pathology Papers · 2026-10-06

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Multimodal Knowledge Distillation for Gastric Adenocarcinoma Classification from Whole-Slide Images](https://arxiv.org/abs/2610.07913)**  `arXiv:2610.07913`  `cs.CV` `cs.AI`  
  _Shrihari Dumbre, Bikash Santra_
  <details open><summary>Abstract</summary>
  Gastric adenocarcinoma (GA) is a leading cause of cancer-related mortality worldwide, and accurate histopathological subtype classification from whole-slide images (WSIs) is essential for effective treatment planning. While multimodal approaches that integrate pathology report text with WSIs can improve classification, existing methods often depend on computationally expensive transformer architectures and large language models. We propose a multimodal knowledge distillation (MKD) framework that combines a pretrained WSI image encoder and a clinical text encoder using Low-Rank Multimodal Fusion (LMF) to efficiently model cross-modal interactions during training. Each WSI is represented as a bag of patches paired with a slide-level diagnostic caption. The teacher model learns fused image-text representations for subtype classification, while the student model distills this knowledge to enable accurate image-only inference. We evaluate our method on the PatchGastric benchmark dataset and achieve at least 3.35% higher mean accuracy than state-of-the-art approaches, without relying on transformer-based fusion, multi-task learning, or large language models. The source code is available atthis https URL.
  </details>

- **[Anchor-driven Multi-modal Multi-scale Expert Selection for Survival Prediction](https://arxiv.org/abs/2610.07694)**  `arXiv:2610.07694`  `cs.CV`  
  _Tao Zhou, Ying Hu, Huazhu Fu, Yi Zhou, Xiao-Jun Wu, Haibin Ling_
  <details open><summary>Abstract</summary>
  The integrative analysis of histopathological Whole-Slide Images (WSIs) and transcriptomic profiles holds significant promise for cancer survival prediction. However, existing methods typically project multi-modal features directly into a shared latent space without explicit alignment, leading to the entanglement of mismatched morphological cues and molecular signals. Furthermore, current fusion strategies often treat the extreme spatial heterogeneity of WSIs uniformly, lacking mechanisms to adaptively prioritize clinically relevant tissue scales for individual patients. To address these limitations, we propose an Anchor-driven Multi-modal Multi-scale Expert Selection (AM$^2$ES) framework for survival prediction. Specifically, we present an Anchor-driven Multi-modal Fusion (AMF) module, which introduces learnable semantic anchors as cross-modal mediators to bridge the semantic gap by enforcing a structurally regularized alignment between transcriptomic features and multi-scale pathology representations. Built upon this aligned semantic space, we further design a Hierarchical Mixture-of-Experts (H-MoE) selection module to decouple the hierarchical prognostic selection process. Mimicking the pathologist's diagnostic workflow, H-MoE performs (i) Intra-scale Expert Filtering to discriminatively identify salient tumor regions within each magnification, and (ii) Inter-scale Hierarchy Routing to dynamically weight and select the most informative resolution levels. Extensive experiments on multiple TCGA cancer cohorts demonstrate that our AM$^2$ES achieves state-of-the-art performance while offering fine-grained interpretability by visualizing how specific molecular pathways drive the expert routing decisions across tissue scales. The code will be released atthis https URL.
  </details>
