# 🔍 ST_Generation_Imputation Papers · 2026-03-24

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Uncertainty Quantification for Distribution-to-Distribution Flow Matching in Scientific Imaging](https://arxiv.org/abs/2603.21717)**  `arXiv:2603.21717`  `cs.LG`  
  _Dongxia Wu, Yuhui Zhang, Serena Yeung-Levy, Emma Lundberg, Emily B. Fox_
  <details open><summary>Abstract</summary>
  Distribution-to-distribution generative models support scientific imaging tasks ranging from modeling cellular perturbation responses to translating medical images across conditions. Trustworthy generation requires both reliability (generalization across labs, devices, and experimental conditions) and accountability (detecting out-of-distribution cases where predictions may be unreliable). Uncertainty quantification (UQ) based approaches serve as promising candidates for these tasks, yet UQ for distribution-to-distribution generative models remains underexplored. We present a unified UQ framework, Bayesian Stochastic Flow Matching (BSFM), that disentangles aleatoric and epistemic uncertainty. The Stochastic Flow Matching (SFM) component augments deterministic flows with a diffusion term to improve model generalization to unseen scenarios. For UQ, we develop a scalable Bayesian approach -- MCD-Antithetic -- that combines Monte Carlo Dropout with sample-efficient antithetic sampling to produce effective anomaly scores for out-of-distribution detection. Experiments on cellular imaging (BBBC021, JUMP) and brain fMRI (Theory of Mind) across diverse scenarios show that SFM improves reliability while MCD-Antithetic enhances accountability.
  </details>

- **[Mamba-driven MRI-to-CT Synthesis for MRI-only Radiotherapy Planning](https://arxiv.org/abs/2603.23295)**  `arXiv:2603.23295`  `cs.CV`  
  _Konstantinos Barmpounakis, Theodoros P. Vagenas, Maria Vakalopoulou, George K. Matsopoulos_
  <details open><summary>Abstract</summary>
  Radiotherapy workflows for oncological patients increasingly rely on multi-modal medical imaging, commonly involving both Magnetic Resonance Imaging (MRI) and Computed Tomography (CT). MRI-only treatment planning has emerged as an attractive alternative, as it reduces patient exposure to ionizing radiation and avoids errors introduced by inter-modality registration. While nnU-Net-based frameworks are predominantly used for MRI-to-CT synthesis, we explore Mamba-based architectures for this task, aiming to showcase the advantages of state-space modeling for cross-modality translation compared to standard convolutional neural networks. Specifically, we adapt both the U-Mamba and the SegMamba architecture, originally proposed for segmentation, to perform cross-modality image generation. Our 3D Mamba architecture effectively captures complex volumetric features and long-range dependencies, thus allowing accurate CT synthesis while maintaining fast inference times. Experiments were conducted on a subset of SynthRAD2025 dataset, comprising registered single-channel MRI-CT volume pairs across three anatomical regions. Quantitative evaluation is performed via a combination of image similarity metrics computed in Hounsefield Units (HU) and segmentation-based metrics obtained from TotalSegmentator to ensure geometric consistency is preserved. The findings pave the way for the integration of state-space models into radiotherapy workflows.
  </details>

- **[Cross-Slice Knowledge Transfer via Masked Multi-Modal Heterogeneous Graph Contrastive Learning for Spatial Gene Expression Inference](https://arxiv.org/abs/2603.22821)**  `arXiv:2603.22821`  `cs.CV`  
  _Zhiceng Shi, Changmiao Wang, Jun Wan, Wenwen Min_
  <details open><summary>Abstract</summary>
  While spatial transcriptomics (ST) has advanced our understanding of gene expression in tissue context, its high experimental cost limits its large-scale application. Predicting ST from pathology images is a promising, cost-effective alternative, but existing methods struggle to capture complex cross-slide spatial relationships. To address the challenge, we propose SpaHGC, a multi-modal heterogeneous graph-based model that captures both intra-slice and inter-slice spot-spot relationships from histology images. It integrates local spatial context within the target slide and cross-slide similarities computed from image embeddings extracted by a pathology foundation model. These embeddings enable inter-slice knowledge transfer, and SpaHGC further incorporates Masked Graph Contrastive Learning to enhance feature representation and transfer spatial gene expression knowledge from reference to target slides, enabling it to model complex spatial dependencies and significantly improve prediction accuracy. We conducted comprehensive benchmarking on seven matched histology-ST datasets from different platforms, tissues, and cancer subtypes. The results demonstrate that SpaHGC significantly outperforms the existing nine state-of-the-art methods across all evaluation metrics. Additionally, the predictions are significantly enriched in multiple cancer-related pathways, thereby highlighting its strong biological relevance and application potential.
  </details>
