# 🔍 Multimodal_ST_Pathology Papers · 2026-11-01

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[From WSIs to Bulk, Spatial and Single-Cell Transcriptomics via Multi-Scale Graph Neural Networks](https://arxiv.org/abs/2610.41692)**  `arXiv:2610.41692`  `cs.LG`  
  _Miguel Andrade, José Almeida, Carlos Santiago, Catarina Barata_
  <details open><summary>Abstract</summary>
  Understanding the spatial distribution of gene expression is key to studying complex diseases like cancer. While Spatial Transcriptomics (ST) and Single-Cell Transcriptomics (scT) provide high-resolution insights, they remain expensive and scarce. In contrast, standard histopathology Whole-Slide Images (WSIs) paired with bulk RNA sequencing are widely available. This work introduces a Multi-Scale Graph Neural Network (GNN) capable of simultaneously predicting bulk, spatial, and single-cell transcriptomics directly from WSIs. By extracting morphological features using a Pathology Foundation Model (PFM) (UNI2-h) and constructing spatial graphs at both patch and cell levels, the model learns the hierarchical relationships within the tissue. The network is trained on a combined dataset of The Cancer Genome Atlas Program (TCGA), Visium, and Xenium samples across lung, kidney, and breast tissues. A hybrid training strategy is employed, leveraging direct supervision alongside weakly supervised consistency losses to ensure predictions align across biological scales. Results show the model accurately predicts gene expression at the slide level and moderately at the patch level (strongest on Xenium), and achieves moderate correlation at the challenging single-cell level. Furthermore, downstream tasks explore the clinical relevance of these predictions, demonstrating their utility in survival analysis, spatial hazard mapping, and tumor classification via molecular signatures.
  </details>

- **[scAnyOmics: Foundation-Model Distillation for Any-to-Any Completion of Multi-omics Virtual Cells](https://arxiv.org/abs/2610.41399)**  `arXiv:2610.41399`  `cs.AI`  
  _Zhaoqi Song, Ye Du, Yusuke Iwasawa, Yutaka Matsuo, Qian Niu_
  <details open><summary>Abstract</summary>
  Recent advances in single-cell technologies have enabled the profiling of multiple molecular modalities, including transcriptomics, proteomics, and chromatin accessibility, providing a more comprehensive understanding of cellular states. However, integrating heterogeneous modalities and predicting missing molecular information remain challenging, particularly when paired measurements are limited. Here, we introduce scAnyOmics, a generative framework that distills knowledge from a frozen single-cell foundation model into a multimodal student model. scAnyOmics integrates scRNA-seq, protein-marker measurements, and scATAC-seq into a shared representation, enabling cross-modal prediction and reconstruction of missing modalities. We assembled 690,880 cells from six publicly available studies, covering both paired and partially paired multi-omics measurements, to systematically evaluate its predictive performance. We further evaluated scAnyOmics on held-out donor data, where it outperformed baseline methods across multiple evaluation metrics. Beyond cross-modal reconstruction, we explored its applications in cell-type annotation, perturbation-response prediction, and biological age estimation. Overall, scAnyOmics provides a unified framework for integrating incomplete single-cell multi-omics data and transferring pretrained biological knowledge, supporting the development of virtual cell models across diverse cellular contexts and experimental platforms.
  </details>
