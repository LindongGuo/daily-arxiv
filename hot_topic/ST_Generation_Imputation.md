# 🔍 ST_Generation_Imputation Papers · 2026-07-21

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Posterior Samplings are Missing Modalities Generators for Medical Image Translation](https://arxiv.org/abs/2607.18763)**  `arXiv:2607.18763`  `cs.CV`  
  _Jonghun Kim_
  <details open><summary>Abstract</summary>
  Magnetic resonance imaging comes in various modality contrasts that provide complementary anatomical and pathological information. Complete multimodal acquisitions are often unavailable due to time and protocol constraints. This leads to real-world datasets with missing modalities, where conventional medical image translation methods are typically limited to fixed source-target settings or require retraining for each observed source-target pair. We propose a unified framework that formulates missing-modality generation as a linear inverse problem under a joint distribution and solves it via posterior sampling with a flow matching model. By learning a joint prior over the complete modality set, our method can reconstruct arbitrary missing modalities at inference time by guiding the sampling trajectory to enforce measurement consistency with observed modalities. We further mitigate inter-modality error propagation in multi-target generation by adopting a many-to-one sampling strategy. Experiments on BraTS and IXI datasets show that our method achieves the best performance over baselines across most missing-modality scenarios. In downstream tumor segmentation, synthesized images from our method result in higher segmentation performance, indicating better preservation of clinically relevant structures.
  </details>
