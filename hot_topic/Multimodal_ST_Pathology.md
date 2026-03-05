# 🔍 Multimodal_ST_Pathology Papers · 2026-03-04

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[CoRe-BT: A Multimodal Radiology-Pathology-Text Benchmark for Robust Brain Tumor Typing](https://arxiv.org/abs/2603.03618)**  `arXiv:2603.03618`  `cs.CV`  
  _Juampablo E. Heras Rivera, Daniel K. Low, Xavier Xiong, Jacob J. Ruzevick, Daniel D. Child, Wen-wai Yim, et al._
  <details open><summary>Abstract</summary>
  Accurate brain tumor typing requires integrating heterogeneous clinical evidence, including magnetic resonance imaging (MRI), histopathology, and pathology reports, which are often incomplete at the time of diagnosis. We introduce CoRe-BT, a cross-modal radiology-pathology-text benchmark for brain tumor typing, designed to study robust multimodal learning under missing modality conditions. The dataset comprises 310 patients with multi-sequence brain MRI (T1, T1c, T2, FLAIR), including 95 cases with paired H&E-stained whole-slide pathology images and pathology reports. All cases are annotated with tumor type and grade, and MRI volumes include expert-annotated tumor masks, enabling both region-aware modeling and auxiliary learning tasks. Tumors are categorized into six clinically relevant classes capturing the heterogeneity of common and rare glioma subtypes. We evaluate tumor typing under variable modality availability by comparing MRI-only models with multimodal approaches that incorporate pathology information when present. Baseline experiments demonstrate the feasibility of multimodal fusion and highlight complementary modality contributions across clinically relevant typing tasks. CoRe-BT provides a grounded testbed for advancing multimodal glioma typing and representation learning in realistic scenarios with incomplete clinical data.
  </details>

- **[Momentum Memory for Knowledge Distillation in Computational Pathology](https://arxiv.org/abs/2602.21395)**  `arXiv:2602.21395`  `cs.CV`  
  _Yongxin Guo, Hao Lu, Onur C. Koyun, Zhengjie Zhu, Muhammet Fatih Demir, Metin Nafi Gurcan_
  <details open><summary>Abstract</summary>
  Multimodal learning that integrates genomics and histopathology has shown strong potential in cancer diagnosis, yet its clinical translation is hindered by the limited availability of paired histology-genomics data. Knowledge distillation (KD) offers a practical solution by transferring genomic supervision into histopathology models, enabling accurate inference using histology alone. However, existing KD methods rely on batch-local alignment, which introduces instability due to limited within-batch comparisons and ultimately degrades performance.To address these limitations, we propose Momentum Memory Knowledge Distillation (MoMKD), a cross-modal distillation framework driven by a momentum-updated memory. This memory aggregates genomic and histopathology information across batches, effectively enlarging the supervisory context available to each mini-batch. Furthermore, we decouple the gradients of the genomics and histology branches, preventing genomic signals from dominating histology feature learning during training and eliminating the modality-gap issue at inference time.Extensive experiments on the TCGA-BRCA benchmark (HER2, PR, and ODX classification tasks) and an independent in-house testing dataset demonstrate that MoMKD consistently outperforms state-of-the-art MIL and multimodal KD baselines, delivering strong performance and generalization under histology-only inference. Overall, MoMKD establishes a robust and generalizable knowledge distillation paradigm for computational pathology.
  </details>
