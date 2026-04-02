# 🔍 ST_Generation_Imputation Papers · 2026-04-01

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[SANA I2I: A Text Free Flow Matching Framework for Paired Image to Image Translation with a Case Study in Fetal MRI Artifact Reduction](https://arxiv.org/abs/2604.00298)**  `arXiv:2604.00298`  `cs.CV` `cs.AI`  
  _Italo Felix Santos, Gilson Antonio Giraldi, Heron Werner Junior_
  <details open><summary>Abstract</summary>
  We propose SANA-I2I, a text-free high-resolution image-to-image generation framework that extends the SANA family by removing textual conditioning entirely. In contrast to SanaControlNet, which combines text and image-based control, SANA-I2I relies exclusively on paired source-target images to learn a conditional flow-matching model in latent space. The model learns a conditional velocity field that maps a target image distribution to another one, enabling supervised image translation without reliance on language prompts. We evaluate the proposed approach on the challenging task of fetal MRI motion artifact reduction. To enable paired training in this application, where real paired data are difficult to acquire, we adopt a synthetic data generation strategy based on the method proposed by Duffy et al., which simulates realistic motion artifacts in fetal magnetic resonance imaging (MRI). Experimental results demonstrate that SANA-I2I effectively suppresses motion artifacts while preserving anatomical structure, achieving competitive performance few inference steps. These results highlight the efficiency and suitability of our proposed flow-based, text-free generative models for supervised image-to-image tasks in medical imaging.
  </details>
