# 🔍 ST_Generation_Imputation Papers · 2026-09-08

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Latent-to-Latent Flow for Volumetric Stochastic Segmentation](https://arxiv.org/abs/2609.07460)**  `arXiv:2609.07460`  `cs.CV` `cs.AI` `cs.LG`  
  _Omar Todd, Sooha Kim, Raghav Mehta, Katherine Mackay, David Bernstein, Alexandra Taylor, et al._
  <details open><summary>Abstract</summary>
  Uncertainty arising from inter-observer variability in medical image segmentation plays an important role in developing treatment plans. Research in this area is inhibited by the lack of multiple annotations for large-scale medical datasets, especially for volumetric data, which suffers from additional scaling and computational complexity challenges. Flow matching has emerged as a powerful framework for generative modelling and has also been demonstrated to maintain strong performance when working with latent representations of images. In this work, we introduce a latent-to-latent flow technique for stochastic segmentation of medical volumes via encoded representations of both the image and label space. We evaluate our method on two challenging applications covering delineation uncertainty for radiotherapy planning and multiple organ structure segmentation, improving efficiency up to 14x compared with full resolution models while maintaining clinically relevant performance.
  </details>

- **[LatentFM: A Latent Flow Matching Approach for Generative Medical Image Segmentation](https://arxiv.org/abs/2512.04821)**  `arXiv:2512.04821`  `cs.CV`  
  _Ngoc Huynh Trinh, Hoang Anh Nguyen Kim, Hai Toan Nguyen, Quoc Long Tran_
  <details open><summary>Abstract</summary>
  Generative models have achieved remarkable progress with the emergence of flow matching (FM). It has demonstrated strong generative capabilities and attracted significant attention as a simulation-free flow-based framework capable of learning exact data densities. Motivated by these advances, we propose LatentFM, a flow-based model operating in the latent space for medical image segmentation. To model the data distribution, we first design two variational autoencoders (VAEs) to encode both medical images and their corresponding masks into a lower-dimensional latent space. We then estimate a conditional velocity field that guides the flow based on the input image. By sampling multiple latent representations, our method synthesizes diverse segmentation outputs whose pixel-wise variance reliably captures the underlying data distribution, enabling both highly accurate and uncertainty-aware predictions. Furthermore, we generate confidence maps that quantify the model certainty, providing clinicians with richer information for deeper analysis. We conduct experiments on two datasets, ISIC-2018 and CVC-Clinic, and compare our method with several prior baselines, including both deterministic and generative approach models. Through comprehensive evaluations, both qualitative and quantitative results show that our approach achieves superior segmentation accuracy while remaining highly efficient in the latent space.
  </details>
