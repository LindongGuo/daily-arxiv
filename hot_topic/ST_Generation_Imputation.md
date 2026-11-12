# 🔍 ST_Generation_Imputation Papers · 2026-11-11

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[The BRIDGE dataset: paired brightfield whole-slide images of prostate core-needle biopsies in paraffin, after deparaffinization and H&E staining](https://arxiv.org/abs/2611.13883)**  `arXiv:2611.13883`  `cs.CV`  
  _Julia A. Mielcarz, Justyna Durślewicz, Marek Zdrenka, Ahmad Abbadi, Martin Eklund, Mateusz Matusiak, et al._
  <details open><summary>Abstract</summary>
  Computational approaches are increasingly being explored to streamline histopathology workflows, including label-free methods that aim to reduce reliance on chemical staining. Among these, deep learning-based label-free virtual staining uses images of unstained tissue to computationally generate stained images. Despite growing interest, model development and validation remain constrained by the scarcity of paired, clinically annotated whole-slide imaging datasets. We present BRIDGE, a dataset of prostate core-needle biopsies collected at the Prof. Franciszek Lukaszczyk Oncology Centre in Bydgoszcz, Poland. The dataset comprises 869 glass slides from 169 patients, each digitized sequentially after sectioning, deparaffinization, and hematoxylin and eosin staining, yielding in total 2607 whole-slide images. The dataset supports the development and external validation of label-free virtual staining, virtual unstaining, image-registration and segmentation methods. Each slide is accompanied by a Gleason score, enabling downstream analyses of cancer classification and grading concordance. The stained images can be used independently for color normalization and cross-scanner robustness studies. All images are de-identified, distributed in their native scanner format and will be available through the BioImage Archive.
  </details>

- **[Predicting Single-Cell Spatial Gene Expression from H&E using Pathology Foundation Models](https://arxiv.org/abs/2611.13649)**  `arXiv:2611.13649`  `cs.CV`  
  _Ashley P. Tsang, Evan Liu, Conrad Foo, Bob Chen, Hassaan Maan, Donny Chan, et al._
  <details open><summary>Abstract</summary>
  Predicting gene expression directly from hematoxylin and eosin (H&E) images offers a scalable and cost-effective approach to deriving spatial molecular insights from routine histology. Pathology foundation models, typically pretrained using tile-level objectives, may not adequately capture the fine-grained cellular features required for single-cell molecular prediction. In this work, we systematically evaluate and establish domain-informed and task-specific strategies for adapting pathology foundation models to single-cell spatial gene expression prediction. Using paired H&E and Xenium 5K data, our approach improves mean gene-wise Pearson correlation by 2.67x over the standard zero-shot baseline and achieves state-of-the-art performance on this task. We demonstrate strong gene-detection performance across the full gene panel (AUROC = 0.800) and importantly identify that predictive performance varies substantially across biological contexts, with our model achieving its highest Pearson correlation for spatially variable genes (r = 0.643). Our findings demonstrate that, despite the challenges of sparse single-cell measurements, H&E-derived representations can recover biologically meaningful spatial expression patterns, highlighting both the opportunities and limitations of morphology-based molecular inference at cellular resolution.
  </details>

- **[3D-Guided Scalable Flow Matching for Generating Volumetric Tissue Spatial Transcriptomics from Serial Histology](https://arxiv.org/abs/2511.14613)**  `arXiv:2511.14613`  `cs.CV`  
  _Mohammad Vali Sanian, Arshia Hemmat, Amirhossein Vahidi, Jonas Maaskola, Jimmy Tsz Hang Lee, Martin Prete, et al._
  <details open><summary>Abstract</summary>
  A 3D transcriptomic profile of a tissue can give a holistic view of its organization in health and disease, but spatial transcriptomics (ST) is costly, so usually only some serial sections are profiled, while H&E is available for all. Most methods that infer ST from histology treat each section independently and ignore 3D structure, while existing 3D-aware approaches are not generative and do not scale well. We present Holographic Tissue Expression Inpainting and Analysis (HoloTea), a 3D-aware flow-matching framework that imputes spot-level gene expression on an unprofiled section from its H&E and the measured expression of adjacent profiled sections. Our key idea is to take the measured expression at the same registered position on neighboring sections and feed this cross-section context to the flow model through a lightweight ControlNet, so that predictions follow anatomical continuity along z. To capture the discrete, zero-inflated nature of counts, the flow starts from a learned zero-inflated negative binomial (ZINB) prior that, on an unprofiled section, is predicted from the measured expression of the nearest profiled section. A global attention block with a small set of inducing tokens adds whole-slide context at a cost linear in the number of spots, so training and inference scale to large 3D ST datasets. Across three ST datasets spanning different tissue types and resolutions, HoloTea consistently improves 3D expression accuracy and generalization compared to 2D and 3D baselines. We envision HoloTea advancing the creation of accurate 3D virtual tissues, ultimately accelerating biomarker discovery and deepening our understanding of disease. Code is available atthis https URL.
  </details>
