# 🔍 ST_Generation_Imputation Papers · 2026-08-31

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Mamba-driven MRI-to-CT Synthesis for MRI-only Radiotherapy Planning](https://arxiv.org/abs/2603.23295)**  `arXiv:2603.23295`  `cs.CV`  
  _Konstantinos Barmpounakis, Theodoros P. Vagenas, Maria Vakalopoulou, George K. Matsopoulos_
  <details open><summary>Abstract</summary>
  Radiotherapy workflows for oncological patients increasingly rely on multi-modal medical imaging, commonly involving both Magnetic Resonance Imaging (MRI) and Computed Tomography (CT). MRI-only treatment planning has emerged as an attractive alternative, as it reduces patient exposure to ionizing radiation and avoids errors introduced by inter-modality registration. While nnU-Net-based frameworks are predominantly used for MRI-to-CT synthesis, we explore Mamba-based architectures for this task to investigate the applicability of state-space modeling for cross-modality medical image translation and assess its performance relative to established convolutional architectures. Specifically, we adapt the SegMamba architecture, originally proposed for segmentation, to perform image-to-image generation. Our 3D Mamba architecture effectively captures complex volumetric features and long-range dependencies, thus allowing accurate CT synthesis while maintaining a relatively low parameter count. Experiments were conducted on a subset of SynthRAD2025 dataset, comprising registered single-channel MRI-CT volume pairs across three anatomical regions. Quantitative evaluation is performed via a combination of image similarity metrics computed in Hounsfield Units (HU) and segmentation-based metrics obtained from TotalSegmentator to ensure geometric consistency is preserved. The findings pave the way for the integration of state-space models into radiotherapy workflows.
  </details>
