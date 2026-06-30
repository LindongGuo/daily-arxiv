# 🔍 Multimodal_ST_Pathology Papers · 2026-06-29

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[CellDETR: A Detection-Guided Framework for Scalable Cell Representation Learning from Histopathology Images](https://arxiv.org/abs/2606.29463)**  `arXiv:2606.29463`  `cs.CV`  
  _Shikang Zhang, Guojun Li, Yicong Mao, Chulin Sha_
  <details open><summary>Abstract</summary>
  Recent advances in pathology foundation models have substantially improved patch and slide level representation learning from whole-slide images (WSIs).However, cell-level representations learning remain underexplored, limiting cell resolved interpretability, biological discovery, and clinical translation. We propose CellDETR, a detection-guided framework built on Deformable DETR for scalable cell representation learning from WSIs. By introducing location feature decoupling and box-constrained attention mechanism, CellDETR enables automated extraction of cell-level embeddings, and outperform existing state-of-the-art methods in supervised cell classification on PanNuke data. In addition, by incorporating contrastive learning design, we build a CellDETR-based pretraining model for scalable cell representation learning from unlabeled WSIs, which improves downstream cell classification performance. Furthermore, we show that after pretraining with Xenium spatial transcriptomics-derived cell annotations, CellDETR achieves accurate cross-dataset cell classification, demonstrating the transferability and biological relevance of the learned cell embeddings. Together, CellDETR provides a scalable route toward general cell-level representation learning framework for interpretable computational patholog
  </details>

- **[JASPR: Joint Spatial Representation learning of histology and spatial genomics for improved virtual genomic screening and clinical prognostication](https://arxiv.org/abs/2606.28395)**  `arXiv:2606.28395`  `cs.CV`  
  _Marija Pizurica, Eric Zimmermann, Neil Tenenholtz, James Hall, Olivier Gevaert, Ava P. Amini, et al._
  <details open><summary>Abstract</summary>
  Recent studies have shown that spatial properties of tumors are critical for understanding disease biology and predicting patient outcomes. These spatial properties are increasingly uncovered through complementary modalities: spatial transcriptomics (ST) captures spatially-resolved molecular states, while hematoxylin and eosin-stained whole slide images (HE) reveal tissue morphology. While approaches are emerging to fuse these modalities, effective methods that learn not only joint representations but also incorporate spatial context across modalities are lacking. Here, we present JASPR (Joint Spatial Representation learning), a self-supervised deep learning framework that integrates HE images and ST data through a cross-modal reconstruction objective that incorporates spatial context within HE images and ST profiles. It employs shared modules to capture universal spatial properties across modalities, while modality-specific experts encode features unique to morphological and genomic data. We train and validate JASPR on breast cancer datasets, demonstrating that its learned joint representation substantially improves HE-based prediction of 9,248 genes and provides prognostic value for breast cancer outcomes.
  </details>
