# 🔍 Multimodal_ST_Pathology Papers · 2026-03-20

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Translating MRI to PET through Conditional Diffusion Models with Enhanced Pathology Awareness](https://arxiv.org/abs/2603.18896)**  `arXiv:2603.18896`  `cs.CV` `cs.AI`  
  _Yitong Li, Igor Yakushev, Dennis M. Hedderich, Christian Wachinger_
  <details open><summary>Abstract</summary>
  Positron emission tomography (PET) is a widely recognized technique for diagnosing neurodegenerative diseases, offering critical functional insights. However, its high costs and radiation exposure hinder its widespread use. In contrast, magnetic resonance imaging (MRI) does not involve such limitations. While MRI also detects neurodegenerative changes, it is less sensitive for diagnosis compared to PET. To overcome such limitations, one approach is to generate synthetic PET from MRI. Recent advances in generative models have paved the way for cross-modality medical image translation; however, existing methods largely emphasize structural preservation while neglecting the critical need for pathology awareness. To address this gap, we propose PASTA, a novel image translation framework built on conditional diffusion models with enhanced pathology awareness. PASTA surpasses state-of-the-art methods by preserving both structural and pathological details through its highly interactive dual-arm architecture and multi-modal condition integration. Additionally, we introduce a novel cycle exchange consistency and volumetric generation strategy that significantly enhances PASTA's ability to produce high-quality 3D PET images. Our qualitative and quantitative results demonstrate the high quality and pathology awareness of the synthesized PET scans. For Alzheimer's diagnosis, the performance of these synthesized scans improves over MRI by 4%, almost reaching the performance of actual PET. Our code is available atthis https URL.
  </details>

- **[Cell-Type Prototype-Informed Neural Network for Gene Expression Estimation from Pathology Images](https://arxiv.org/abs/2603.18461)**  `arXiv:2603.18461`  `cs.CV`  
  _Kazuya Nishimura, Ryoma Bise, Shinnosuke Matsuo, Haruka Hirose, Yasuhiro Kojima_
  <details open><summary>Abstract</summary>
  Estimating slide- and patch-level gene expression profiles from pathology images enables rapid and low-cost molecular analysis with broad clinical impact. Despite strong results, existing approaches treat gene expression as a mere slide- or spot-level signal and do not incorporate the fact that the measured expression arises from the aggregation of underlying cell-level expression. To explicitly introduce this missing cell-resolved guidance, we propose a Cell-type Prototype-informed Neural Network (CPNN) that leverages publicly available single-cell RNA-sequencing datasets. Since single-cell measurements are noisy and not paired with histology images, we first estimate cell-type prototypes-mean expression profiles that reflect stable gene-gene co-variationthis http URLthen learns cell-type compositional weights directly from images and models the relationship between prototypes and observed bulk or spatial expression, providing a biologically grounded and structurally regularized prediction framework. We evaluate CPNN on three slide-level datasets and three patch-level spatial transcriptomics datasets. Across all settings, CPNN achieves the highest performance in terms of Spearman correlation. Moreover, by visualizing the inferred compositional weights, our framework provides interpretable insights into which cell types drive the predicted expression. Code is publicly available atthis https URL.
  </details>
