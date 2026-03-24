# 🔍 ST_Generation_Imputation Papers · 2026-03-23

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
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

- **[LatentFM: A Latent Flow Matching Approach for Generative Medical Image Segmentation](https://arxiv.org/abs/2512.04821)**  `arXiv:2512.04821`  `cs.CV`  
  _Huynh Trinh Ngoc, Hoang Anh Nguyen Kim, Toan Nguyen Hai, Long Tran Quoc_
  <details open><summary>Abstract</summary>
  Generative models have achieved remarkable progress with the emergence of flow matching (FM). It has demonstrated strong generative capabilities and attracted significant attention as a simulation-free flow-based framework capable of learning exact data densities. Motivated by these advances, we propose LatentFM, a flow-based model operating in the latent space for medical image segmentation. To model the data distribution, we first design two variational autoencoders (VAEs) to encode both medical images and their corresponding masks into a lower-dimensional latent space. We then estimate a conditional velocity field that guides the flow based on the input image. By sampling multiple latent representations, our method synthesizes diverse segmentation outputs whose pixel-wise variance reliably captures the underlying data distribution, enabling both highly accurate and uncertainty-aware predictions. Furthermore, we generate confidence maps that quantify the model certainty, providing clinicians with richer information for deeper analysis. We conduct experiments on two datasets, ISIC-2018 and CVC-Clinic, and compare our method with several prior baselines, including both deterministic and generative approach models. Through comprehensive evaluations, both qualitative and quantitative results show that our approach achieves superior segmentation accuracy while remaining highly efficient in the latent space.
  </details>
