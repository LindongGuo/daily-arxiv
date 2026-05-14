# 🔍 ST_Generation_Imputation Papers · 2026-05-13

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Cross Modality Image Translation In Medical Imaging Using Generative Frameworks](https://arxiv.org/abs/2605.13686)**  `arXiv:2605.13686`  `cs.CV` `cs.AI`  
  _Giulia Romoli, Alessia Capoccia, Filippo Ruffini, Francesco Di Feola, Luca Boldrini, Arturo Chiti, et al._
  <details open><summary>Abstract</summary>
  Medical image-to-image (I2I) translation enables virtual scanning, i.e. the synthesis of a target imaging modality from a source one without additional acquisitions. Despite growing interest, most proposed methods operate on 2D slices, are evaluated on isolated tasks with different experimental set-ups and lack clinical validation. The primary contribution of this work is a reproducible, standardized comparative evaluation of 3D I2I translation methods in oncological imaging, designed to standardize preprocessing, splitting, inference, and multi-level evaluation across heterogeneous clinical tasks. Within this framework, we compare seven generative models, three Generative Adversarial Networks (GANs: Pix2Pix, CycleGAN, SRGAN) and four latent generative models (Latent Diffusion Model, Latent Diffusion Model+ControlNet, Brownian Bridge, Flow Matching), across eleven datasets spanning three anatomical regions (head/neck, lung, pelvis) and four translation directions (cone-beam CT to CT, MRI to CT, CT to PET, MRI T2-weighted to T2-FLAIR), for a total of 77 experiments under uniform training, inference, and evaluation conditions. The results show that GANs outperform latent generative models across all tasks, with SRGAN achieving statistically significant superiority. Our lesion-level analysis reveals that all models struggle with small lesions and that, in CT to PET synthesis, models reproduce lesion shape more reliably than absolute uptake-related intensity. We also performed a Visual Turing test administered to 17 physicians, including 15 radiologists, which shows near-chance classification accuracy (56.7%), confirming that synthetic volumes are largely indistinguishable from real acquisitions, while exposing a dissociation between quantitative metrics and clinical preference.
  </details>
