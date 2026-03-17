# 🔍 Multimodal_ST_Pathology Papers · 2026-03-16

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[BiTro: Bidirectional Transfer Learning Enhances Bulk and Spatial Transcriptomics Prediction in Cancer Pathological Images](https://arxiv.org/abs/2603.14897)**  `arXiv:2603.14897`  `cs.LG`  
  _Jingkun Yu, Guangkai Shang, Changtao Li, Xun Gong, Tianrui Li, Yazhou He, et al._
  <details open><summary>Abstract</summary>
  Cancer pathological analysis requires modeling tumor heterogeneity across multiple modalities, primarily through transcriptomics and whole slide imaging (WSI), along with their spatial relations. On one hand, bulk transcriptomics and WSI images are largely available but lack spatial mapping; on the other hand, spatial transcriptomics (ST) data can offer high spatial resolution, yet facing challenges of high cost, low sequencing depth, and limited sample sizes. Therefore, the data foundation of either side is flawed and has its limit in accurately finding the mapping between the two modalities. To this end, we propose BiTro, a bidirectional transfer learning framework that can enhance bulk and spatial transcriptomics prediction from pathological images. Our contributions are twofold. First, we design a universal and transferable model architecture that works for both bulk+WSI and ST data. A major highlight is that we model WSI images on the cellular level to better capture cells' visual features, morphological phenotypes, and their spatial relations; to map cells' features to their transcriptomics measured in bulk or ST, we adopt multiple instance learning. Second, by using LoRA, our model can be efficiently transferred between bulk and ST data to exploit their complementary information. To test our framework, we conducted comprehensive experiments on five cancer datasets. Results demonstrate that 1) our base model can achieve better or competitive performance compared to existing models on bulk or spatial transcriptomics prediction, and 2) transfer learning can further improve the base model's performance.
  </details>

- **[Spatial Transcriptomics as Images for Large-Scale Pretraining](https://arxiv.org/abs/2603.13432)**  `arXiv:2603.13432`  `cs.CV` `cs.AI`  
  _Yishun Zhu, Jiaxin Qi, Jian Wang, Yuhua Zheng, Jianqiang Huang_
  <details open><summary>Abstract</summary>
  Spatial Transcriptomics (ST) profiles thousands of gene expression values at discrete spots with precise coordinates on tissue sections, preserving spatial context essential for clinical and pathological studies. With rising sequencing throughput and advancing platforms, the expanding data volumes motivate large-scale ST pretraining. However, the fundamental unit for pretraining, i.e., what constitutes a single training sample, remains ill-posed. Existing choices fall into two camps: (1) treating each spot as an independent sample, which discards spatial dependencies and collapses ST into single-cell transcriptomics; and (2) treating an entire slide as a single sample, which produces prohibitively large inputs and drastically fewer training examples, undermining effective pretraining. To address this gap, we propose treating spatial transcriptomics as croppable images. Specifically, we define a multi-channel image representation with fixed spatial size by cropping patches from raw slides, thereby preserving spatial context while substantially increasing the number of training samples. Along the channel dimension, we define gene subset selection rules to control input dimensionality and improve pretraining stability. Extensive experiments show that the proposed image-like dataset construction for ST pretraining consistently improves downstream performance, outperforming conventional pretraining schemes. Ablation studies verify that both spatial patching and channel design are necessary, establishing a unified, practical paradigm for organizing ST data and enabling large-scale pretraining.
  </details>
