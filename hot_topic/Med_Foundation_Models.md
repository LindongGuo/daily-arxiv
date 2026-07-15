# 🔍 Med_Foundation_Models Papers · 2026-07-14

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[The Geometry of Memorization: Finite-Time Spectral Sensitivity as a Diagnostic for Flow Matching Models](https://arxiv.org/abs/2607.12616)**  `arXiv:2607.12616`  `cs.LG`  
  _Shuchan Wang_
  <details open><summary>Abstract</summary>
  Continuous-time generative frameworks construct probability paths between base and target domains by optimizing time-dependent velocity fields. While theoretical targets favor straight trajectories, empirical networks develop complex path deformations. This paper presents the Finite-Time Spectral Sensitivity (FTSS) g(t), a gradient-free, forward-pass metric that exposes flow geometry by tracking the root-mean-square singular value of the state-transition matrix. Serving as a continuous proxy for stable rank, g(t) reveals a distinct geometric pathology under data scarcity: while generalizing models maintain stable effective dimensions, overfitting causes a spectral collapse. We leverage this structural phenomenon to develop an internal geometric audit based on g(t). Our framework detects generative memorization using purely internal trajectory dynamics, removing the need for external membership queries or baseline data comparison.
  </details>

- **[Atlas H&E-TME: Scalable AI-Based Tissue Profiling at Expert Pathologist-Level Accuracy](https://arxiv.org/abs/2606.12346)**  `arXiv:2606.12346`  `cs.CV` `cs.AI` `cs.LG`  
  _Kai Standvoss, Miriam Hägele, Rosemarie Krupar, Julika Ribbat-Idel, Jennifer Altschüler, Gerrit Erdmann, et al._
  <details open><summary>Abstract</summary>
  Hematoxylin and eosin (H&E) staining is the cornerstone of histopathology, yet scalable, quantitative analysis of H&E whole-slide images (WSIs) remains a central challenge in computational pathology. We present Atlas H&E-TME, an AI-based system built on the Atlas family of pathology foundation models that predicts tissue quality, tissue region, and cell type labels across multiple cancer types, yielding over 4,500 quantitative readouts per slide at cell-level resolution. A key challenge to validating such systems is overcoming morphological ambiguity inherent to H&E-only ground truth and the limited scalability of more informed references drawing on modalities such as immunohistochemistry (IHC). We address this with a dual validation framework combining biologically grounded depth with technical and morphological breadth. For depth, we propose an IHC-informed multi-pathologist consensus protocol that substantially improves inter-rater agreement over conventional H&E-only annotation. This yields a molecularly grounded reference against which we compare Atlas H&E-TME and pathologists working from H&E alone. For breadth, we benchmark Atlas H&E-TME on over 200,000 high-confidence H&E-only pathologist annotations across 1,500+ cases spanning eight cancer types and their most common metastatic sites, with subtypes covering >90% of clinical cases per cancer type, drawn from 25+ sources and 8+ scanner models. Benchmarked against the IHC-informed consensus, Atlas H&E-TME matches or exceeds pathologist H&E-only performance and generalizes consistently and robustly across this broad morphological and technical scope. In doing so, Atlas H&E-TME turns the H&E slide -- the most ubiquitous data in pathology -- into a scalable, quantitative window into the tumor and its microenvironment, laying a foundation for the next generation of tissue-based biomarkers in translational and clinical research.
  </details>
