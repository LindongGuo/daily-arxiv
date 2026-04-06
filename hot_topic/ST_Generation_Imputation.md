# 🔍 ST_Generation_Imputation Papers · 2026-04-05

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Beyond Fixed Inference: Quantitative Flow Matching for Adaptive Image Denoising](https://arxiv.org/abs/2604.02392)**  `arXiv:2604.02392`  `cs.CV`  
  _Jigang Duan, Genwei Ma, Xu Jiang, Wenfeng Xu, Ping Yang, Xing Zhao_
  <details open><summary>Abstract</summary>
  Diffusion and flow-based generative models have shown strong potential for image restoration. However, image denoising under unknown and varying noise conditions remains challenging, because the learned vector fields may become inconsistent across different noise levels, leading to degraded restoration quality under mismatch between training and inference. To address this issue, we propose a quantitative flow matching framework for adaptive image denoising. The method first estimates the input noise level from local pixel statistics, and then uses this quantitative estimate to adapt the inference trajectory, including the starting point, the number of integration steps, and the step-size schedule. In this way, the denoising process is better aligned with the actual corruption level of each input, reducing unnecessary computation for lightly corrupted images while providing sufficient refinement for heavily degraded ones. By coupling quantitative noise estimation with noise-adaptive flow inference, the proposed method improves both restoration accuracy and inference efficiency. Extensive experiments on natural, medical, and microscopy images demonstrate its robustness and strong generalization across diverse noise levels and imaging conditions.
  </details>
