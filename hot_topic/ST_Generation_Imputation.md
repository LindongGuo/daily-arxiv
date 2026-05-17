# 🔍 ST_Generation_Imputation Papers · 2026-05-16

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[DUET: Dual-Paradigm Adaptive Expert Triage with Single-cell Inductive Prior for Spatial Transcriptomics Prediction](https://arxiv.org/abs/2605.14104)**  `arXiv:2605.14104`  `cs.CV`  
  _Junchao Zhu, Ruining Deng, Junlin Guo, Tianyuan Yao, Chongyu Qu, Juming Xiong, et al._
  <details open><summary>Abstract</summary>
  Inferring spatially resolved gene expression from histology images offers a cost-effective complement to spatial transcriptomics (ST). However, existing methods reduce this task to a simple morphology-to-expression mapping, where visual similarity does not guarantee molecular consistency. Meanwhile, single-cell data has amassed rich resources far surpassing the scale of ST data, yet it remains underexplored in vision-omics modeling. Furthermore, current approaches commit to a monolithic paradigm with bottlenecks, unable to balance expressive flexibility with biological fidelity. To bridge these gaps, we propose DUET, a novel dual-paradigm framework that synergizes parametric prediction and memory-based retrieval under cellular inductive priors. DUET implements a parallel regression-retrieval paradigm, adaptively reconciling the outputs of its complementary pathways. To mitigate aleatoric vision ambiguity, we incorporate large-scale single-cell references to impose molecular states as biological constraints for faithful learning. Building upon structural refinement, we further design a lightweight adapter to dynamically assign branch preference across spatial contexts to achieve optimal performance. Extensive experiments on three public datasets across varied gene scales demonstrate that DUET achieves SOTA performance, with consistent gains contributed by each proposed component. Code is available atthis https URL
  </details>

- **[ImmuVis: Hyperconvolutional Foundation Model for Imaging Mass Cytometry](https://arxiv.org/abs/2602.04585)**  `arXiv:2602.04585`  `cs.CV`  
  _Dawid Uchal, Marcin Możejko, Krzysztof Gogolewski, Piotr Kupidura, Szymon Łukasik, Jakub Giezgała, et al._
  <details open><summary>Abstract</summary>
  We present ImmuVis, a family of efficient foundation models for imaging mass cytometry (IMC), a high-throughput multiplex imaging technology that handles molecular marker measurements as image channels and enables large-scale spatial tissue profiling. Unlike natural images, multiplex imaging lacks a fixed channel space, as real-world marker sets vary across studies, violating a core assumption of standard vision backbones. To address this, ImmuVis introduces marker-adaptive hyperconvolutions that generate convolutional kernels from learned marker embeddings, enabling a single model to operate on arbitrary measured marker subsets without retraining. We pretrain ImmuVis on the largest dataset to date, IMC17M (28 cohorts, 24,405 images, 265 markers, over 17M patches), using self-supervised masked reconstruction. ImmuVis outperforms state-of-the-art baselines and ablations in virtual staining and downstream classification tasks at substantially lower compute cost than transformer-based alternatives, and is the sole model that provides calibrated uncertainty via a heteroscedastic likelihood objective. These results position ImmuVis as a practical framework for real-world IMC modeling.
  </details>
