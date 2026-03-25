# 🔍 Multimodal_ST_Pathology Papers · 2026-03-24

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Cross-Slice Knowledge Transfer via Masked Multi-Modal Heterogeneous Graph Contrastive Learning for Spatial Gene Expression Inference](https://arxiv.org/abs/2603.22821)**  `arXiv:2603.22821`  `cs.CV`  
  _Zhiceng Shi, Changmiao Wang, Jun Wan, Wenwen Min_
  <details open><summary>Abstract</summary>
  While spatial transcriptomics (ST) has advanced our understanding of gene expression in tissue context, its high experimental cost limits its large-scale application. Predicting ST from pathology images is a promising, cost-effective alternative, but existing methods struggle to capture complex cross-slide spatial relationships. To address the challenge, we propose SpaHGC, a multi-modal heterogeneous graph-based model that captures both intra-slice and inter-slice spot-spot relationships from histology images. It integrates local spatial context within the target slide and cross-slide similarities computed from image embeddings extracted by a pathology foundation model. These embeddings enable inter-slice knowledge transfer, and SpaHGC further incorporates Masked Graph Contrastive Learning to enhance feature representation and transfer spatial gene expression knowledge from reference to target slides, enabling it to model complex spatial dependencies and significantly improve prediction accuracy. We conducted comprehensive benchmarking on seven matched histology-ST datasets from different platforms, tissues, and cancer subtypes. The results demonstrate that SpaHGC significantly outperforms the existing nine state-of-the-art methods across all evaluation metrics. Additionally, the predictions are significantly enriched in multiple cancer-related pathways, thereby highlighting its strong biological relevance and application potential.
  </details>

- **[Momentum Memory for Knowledge Distillation in Computational Pathology](https://arxiv.org/abs/2602.21395)**  `arXiv:2602.21395`  `cs.CV`  
  _Yongxin Guo, Hao Lu, Onur C. Koyun, Zhengjie Zhu, Muhammet Fatih Demir, Metin Nafi Gurcan_
  <details open><summary>Abstract</summary>
  Multimodal learning that integrates genomics and histopathology has shown strong potential in cancer diagnosis, yet its clinical translation is hindered by the limited availability of paired histology-genomics data. Knowledge distillation (KD) offers a practical solution by transferring genomic supervision into histopathology models, enabling accurate inference using histology alone. However, existing KD methods rely on batch-local alignment, which introduces instability due to limited within-batch comparisons and ultimately degrades performance.To address these limitations, we propose Momentum Memory Knowledge Distillation (MoMKD), a cross-modal distillation framework driven by a momentum-updated memory. This memory aggregates genomic and histopathology information across batches, effectively enlarging the supervisory context available to each mini-batch. Furthermore, we decouple the gradients of the genomics and histology branches, preventing genomic signals from dominating histology feature learning during training and eliminating the modality-gap issue at inference time.Extensive experiments on the TCGA-BRCA benchmark (HER2, PR, and ODX classification tasks) and an independent in-house testing dataset demonstrate that MoMKD consistently outperforms state-of-the-art MIL and multimodal KD baselines, delivering strong performance and generalization under histology-only inference. Overall, MoMKD establishes a robust and generalizable knowledge distillation paradigm for computational pathology.
  </details>
