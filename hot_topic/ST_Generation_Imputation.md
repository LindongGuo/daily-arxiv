# 🔍 ST_Generation_Imputation Papers · 2026-11-02

[![Total Papers](https://img.shields.io/badge/Papers-4-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[CytoWave: Perturbation-Centric Pretraining for Single-Cell Response Prediction](https://arxiv.org/abs/2611.02311)**  `arXiv:2611.02311`  `cs.LG`  
  _Yuwei Miao, Jingquan Yan, Hehuan Ma, Thao M. Dang, Lin Xu, Siyuan Zhang, et al._
  <details open><summary>Abstract</summary>
  Predicting gene expression under perturbations from single-cell data is a fundamental task for modeling cellular responses, with applications in discovering gene function and designing therapeutics. However, existing methods often struggle to generalize across datasets due to differences in experimental protocols, biological contexts, and species. We present \textbf{CytoWave}, a perturbation-centric pretraining framework for single-cell genetic perturbation response prediction. We leverage large-scale cross-species perturbation datasets unified via orthology and train CytoWave in a two-stage manner. In the first stage, we learn reference control cell states via masked gene expression recovery on unperturbed cells. In the second stage, we pretrain the model to predict perturbed gene expression given control states and perturbation signals, together with a contrastive objective that aligns latent representations of perturbation responses with perturbation signals. We perform strict dataset-held-out evaluation across multiple condition combinations and case studies of pathway activity changes, demonstrating consistent and effective performance of CytoWave in predicting single-cell genetic perturbation responses.
  </details>

- **[IsoAlign: Isoform-Aware DNA-Protein Alignment via Joint-Embedding Predictive Architectures](https://arxiv.org/abs/2611.00241)**  `arXiv:2611.00241`  `cs.LG`  
  _Niousha Sadjadi, Arman Seyed-Ahmadi, Tony Tu, Micaela Elisa Consens, Kerr Ding, Alif Munim, et al._
  <details open><summary>Abstract</summary>
  Genomic foundation models (GFMs) have emerged as a powerful paradigm for learning DNA sequence representations, yet existing self-supervised pretraining strategies overlook alternative splicing and underperform compared to specialized models. To address this gap, we introduce IsoAlign, a multimodal framework that grounds genomic pretraining in isoform-aware DNA-protein alignment to learn biologically meaningful representations. IsoAlign aligns transcripts to their corresponding protein isoforms, capturing both coding sequences and broader regulatory contexts, using two Joint-Embedding Predictive Architectures (JEPA): DNA-Protein JEPA (DP-JEPA), which predicts protein representations from DNA using contrastive alignment, and Isoform-Masked JEPA (IM-JEPA), which models relationships among alternative isoforms of the same gene through masked protein prediction. We evaluate the learned DNA representations of these architectures across a multi-metric evaluation suite spanning tasks, including the prediction of pathogenicity, fitness, gene expression, and TF binding. Our results demonstrate that isoform-aware cross-modal alignment using JEPA significantly improves functional representations and downstream performance, establishing a promising direction for GFM pretraining.
  </details>

- **[Training-Time Domain Transfer for Generator-Free Diagnostics on Novel Modalities in Computational Pathology](https://arxiv.org/abs/2611.02931)**  `arXiv:2611.02931`  `cs.CV` `cs.AI`  
  _Julia A. Mielcarz, Andrea Camilloni, Nita Mulliqi, Jessica A. Frank, Anders Blilie, Emilius A.M. Janssen, et al._
  <details open><summary>Abstract</summary>
  Novel imaging modalities promise improved diagnostics, but AI development is constrained by scarce training data. Inference-time domain transfer can address this by mapping novel modalities to established ones, enabling reuse of existing diagnostic models. However, this introduces hallucination risks, computational overhead, and regulatory complexity. Inspired by sim-to-real transfer, we propose training-time domain transfer, generating synthetic target-domain training data from archived routine samples to enable direct diagnosis on real inputs without inference-time generation. Using unstained prostate histopathology as a proof-of-concept, we compare this approach with inference-time virtual staining and conventional H&E-based cancer detection. Training-time transfer achieved higher concordance with the conventional benchmark than virtual staining for both raw (Cohen's $\kappa$=0.59 vs. 0.37; Gwet's AC1=0.73 vs. 0.29) and deparaffinized tissue ($\kappa$=0.66 vs. 0.61; AC1=0.73 vs. 0.64), supporting its potential for emerging diagnostic modalities.
  </details>

- **[CellPlex: Benchmarking Single-Cell Spatial Proteomics Prediction from H&E](https://arxiv.org/abs/2611.02506)**  `arXiv:2611.02506`  `cs.CV`  
  _Zijun Gao, Yijiang Chen, Xiangde Luo, Pheng-Ann Heng_
  <details open><summary>Abstract</summary>
  Spatial proteomics measures tens of proteins in every cell of a tissue section, but its cost confines it to small research cohorts, whereas hematoxylin and eosin (H\&E) slides exist for nearly every patient. Inferring single-cell spatial proteomics from H\&E would bring its analyses to routine pathology, and a growing number of virtual staining models pursue this goal. Each is evaluated on its own cohort, panel and pixel-level metric, and released models transfer poorly to new cohorts, leaving open which approach to build on and which proteins H\&E can reveal. We introduce CellPlex, a benchmark that poses the task at the level of the cell: seven cohorts with same-section H\&E and multiplexed immunofluorescence, from colorectal and breast cancer to lymph-node metastases, bone marrow and glioma, with 717 samples, 44.8 million cells and 149 proteins, processed by one pipeline into per-cell targets. Pathology foundation models (PFMs) are adapted with one cell-level protocol, specialist models are fine-tuned under a matched budget, and all are scored on the same cells. Adapted PFMs are the most accurate models on every cohort, ahead of the specialists even after fine-tuning, but keep less than half of their accuracy on cohorts they were not trained on. Which proteins can be predicted depends on the tissue, not on how many cells were measured for them. By fixing the cells, targets and splits on which predictions are judged, CellPlex sets a common standard for inferring costly molecular measurements from routine H\&E and shows how far H\&E can stand in for spatial proteomics. We will release the data, splits, evaluation code and baselines as a testbed for developing and comparing future pathology foundation models and virtual staining methods.
  </details>
