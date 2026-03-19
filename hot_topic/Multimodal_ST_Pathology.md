# 🔍 Multimodal_ST_Pathology Papers · 2026-03-18

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Spatial Transcriptomics as Images for Large-Scale Pretraining](https://arxiv.org/abs/2603.13432)**  `arXiv:2603.13432`  `cs.CV` `cs.AI`  
  _Yishun Zhu, Jiaxin Qi, Jian Wang, Yuhua Zheng, Jianqiang Huang_
  <details open><summary>Abstract</summary>
  Spatial Transcriptomics (ST) profiles thousands of gene expression values at discrete spots with precise coordinates on tissue sections, preserving spatial context essential for clinical and pathological studies. With rising sequencing throughput and advancing platforms, the expanding data volumes motivate large-scale ST pretraining. However, the fundamental unit for pretraining, i.e., what constitutes a single training sample, remains ill-posed. Existing choices fall into two camps: (1) treating each spot as an independent sample, which discards spatial dependencies and collapses ST into single-cell transcriptomics; and (2) treating an entire slide as a single sample, which produces prohibitively large inputs and drastically fewer training examples, undermining effective pretraining. To address this gap, we propose treating spatial transcriptomics as croppable images. Specifically, we define a multi-channel image representation with fixed spatial size by cropping patches from raw slides, thereby preserving spatial context while substantially increasing the number of training samples. Along the channel dimension, we define gene subset selection rules to control input dimensionality and improve pretraining stability. Extensive experiments show that the proposed image-like dataset construction for ST pretraining consistently improves downstream performance, outperforming conventional pretraining schemes. Ablation studies verify that both spatial patching and channel design are necessary, establishing a unified, practical paradigm for organizing ST data and enabling large-scale pretraining.
  </details>

- **[HGP-Mamba: Integrating Histology and Generated Protein Features for Mamba-based Multimodal Survival Risk Prediction](https://arxiv.org/abs/2603.16421)**  `arXiv:2603.16421`  `cs.CV`  
  _Jing Dai, Chen Wu, Ming Wu, Qibin Zhang, Zexi Wu, Jingdong Zhang, et al._
  <details open><summary>Abstract</summary>
  Recent advances in multimodal learning have significantly improved cancer survival risk prediction. However, the joint prognostic potential of protein markers and histopathology images remains underexplored, largely due to the high cost and limited availability of protein expression profiling. To address this challenge, we propose HGP-Mamba, a Mamba-based multimodal framework that efficiently integrates histological with generated protein features for survival risk prediction. Specifically, we introduce a protein feature extractor (PFE) that leverages pretrained foundation models to derive high-throughput protein embeddings directly from Whole Slide Images (WSIs), enabling data-efficient incorporation of molecular information. Together with histology embeddings that capture morphological patterns, we further introduce the Local Interaction-aware Mamba (LiAM) for fine-grained feature interaction and the Global Interaction-enhanced Mamba (GiEM) to promote holistic modality fusion at the slide level, thus capture complex cross-modal dependencies. Experiments on four public cancer datasets demonstrate that HGP-Mamba achieves state-of-the-art performance while maintaining superior computational efficiency compared with existing methods. Our source code is publicly available atthis https URL.
  </details>
