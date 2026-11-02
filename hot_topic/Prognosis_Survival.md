# 🔍 Prognosis_Survival Papers · 2026-11-01

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[From WSIs to Bulk, Spatial and Single-Cell Transcriptomics via Multi-Scale Graph Neural Networks](https://arxiv.org/abs/2610.41692)**  `arXiv:2610.41692`  `cs.LG`  
  _Miguel Andrade, José Almeida, Carlos Santiago, Catarina Barata_
  <details open><summary>Abstract</summary>
  Understanding the spatial distribution of gene expression is key to studying complex diseases like cancer. While Spatial Transcriptomics (ST) and Single-Cell Transcriptomics (scT) provide high-resolution insights, they remain expensive and scarce. In contrast, standard histopathology Whole-Slide Images (WSIs) paired with bulk RNA sequencing are widely available. This work introduces a Multi-Scale Graph Neural Network (GNN) capable of simultaneously predicting bulk, spatial, and single-cell transcriptomics directly from WSIs. By extracting morphological features using a Pathology Foundation Model (PFM) (UNI2-h) and constructing spatial graphs at both patch and cell levels, the model learns the hierarchical relationships within the tissue. The network is trained on a combined dataset of The Cancer Genome Atlas Program (TCGA), Visium, and Xenium samples across lung, kidney, and breast tissues. A hybrid training strategy is employed, leveraging direct supervision alongside weakly supervised consistency losses to ensure predictions align across biological scales. Results show the model accurately predicts gene expression at the slide level and moderately at the patch level (strongest on Xenium), and achieves moderate correlation at the challenging single-cell level. Furthermore, downstream tasks explore the clinical relevance of these predictions, demonstrating their utility in survival analysis, spatial hazard mapping, and tumor classification via molecular signatures.
  </details>
