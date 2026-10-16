# 🔍 ST_Generation_Imputation Papers · 2026-10-15

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Semantic Latent Alignment for Flow Matching with Invertible Bi-Lipschitz Adapters](https://arxiv.org/abs/2610.21332)**  `arXiv:2610.21332`  `cs.CV` `cs.LG`  
  _Felix Nützel, Mischa Dombrowski, Luca Hagen, Bernhard Kainz_
  <details open><summary>Abstract</summary>
  Pretrained latent spaces trade compression, reconstruction, and the learnability of the coordinates a downstream generator has to work in, which complicates adapting these spaces to different domains or tasks: continued training is expensive, and without a new alignment objective it often fails to improve downstream generation. We instead leave the encoder and decoder fixed and change only the coordinates between them, using an invertible bi-Lipschitz adapter aligned offline to a semantic teacher and frozen during class-conditional flow matching. Invertibility preserves compatibility with the pretrained autoencoder, while the bi-Lipschitz constraint limits how far alignment can distort its latent geometry. This provides a simple way to improve semantic organization while retaining the compression and reconstruction properties of the original latent space. On two medical imaging datasets, constrained latent adaptation improves feature metrics, seed stability and counterfactual edit strength, while remaining competitive on downstream classification. In contrast, unconstrained adaptation can become highly anisotropic and sensitive despite remaining invertible, highlighting the importance of controlling geometric distortion. Our results suggest that carefully constrained post-hoc adaptation offers a parameter-efficient and tuning-free alternative to jointly modifying the representation during generative training.
  </details>
