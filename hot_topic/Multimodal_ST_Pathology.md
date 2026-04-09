# 🔍 Multimodal_ST_Pathology Papers · 2026-04-08

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[MO-RiskVAE: A Multi-Omics Variational Autoencoder for Survival Risk Modeling in Multiple MyelomaMO-RiskVAE](https://arxiv.org/abs/2604.06267)**  `arXiv:2604.06267`  `cs.LG` `cs.AI`  
  _Zixuan Chen, Heng Zhang, YuPeng Qin, WenPeng Xing, Qiang Wang, Da Wang, et al._
  <details open><summary>Abstract</summary>
  Multimodal variational autoencoders (VAEs) have emerged as a powerful framework for survival risk modeling in multiple myeloma by integrating heterogeneous omics and clinical data. However, when trained under survival supervision, standard latent regularization strategies often fail to preserve prognostically relevant variation, leading to unstable or overly constrained representations. Despite numerous proposed variants, it remains unclear which aspects of latent design fundamentally govern performance in this setting. In this work, we conduct a controlled investigation of latent modeling choices for multimodal survival prediction within a unified extension of the MyeVAE framework. By systematically isolating regularization scale, posterior geometry, and latent space structure under identical architectures and optimization protocols, we show that survival-driven training is primarily sensitive to the magnitude and structure of latent regularization rather than the specific divergence formulation. In particular, moderate relaxation of KL regularization consistently improves survival discrimination, while alternative divergence mechanisms such as MMD and HSIC provide limited benefit without appropriate scaling. We further demonstrate that structuring the latent space can improve alignment between learned representations and survival risk gradients. A hybrid continuous--discrete formulation based on Gumbel--Softmax enhances global risk ordering in the continuous latent subspace, even though stable discrete subtype discovery does not emerge under survival supervision. Guided by these findings, we instantiate a robust multimodal survival model, termed MO-RiskVAE, which consistently improves risk stratification over the original MyeVAE without introducing additional supervision or complex training heuristics.
  </details>
