# 🔍 Prognosis_Survival Papers · 2026-04-08

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[MO-RiskVAE: A Multi-Omics Variational Autoencoder for Survival Risk Modeling in Multiple MyelomaMO-RiskVAE](https://arxiv.org/abs/2604.06267)**  `arXiv:2604.06267`  `cs.LG` `cs.AI`  
  _Zixuan Chen, Heng Zhang, YuPeng Qin, WenPeng Xing, Qiang Wang, Da Wang, et al._
  <details open><summary>Abstract</summary>
  Multimodal variational autoencoders (VAEs) have emerged as a powerful framework for survival risk modeling in multiple myeloma by integrating heterogeneous omics and clinical data. However, when trained under survival supervision, standard latent regularization strategies often fail to preserve prognostically relevant variation, leading to unstable or overly constrained representations. Despite numerous proposed variants, it remains unclear which aspects of latent design fundamentally govern performance in this setting. In this work, we conduct a controlled investigation of latent modeling choices for multimodal survival prediction within a unified extension of the MyeVAE framework. By systematically isolating regularization scale, posterior geometry, and latent space structure under identical architectures and optimization protocols, we show that survival-driven training is primarily sensitive to the magnitude and structure of latent regularization rather than the specific divergence formulation. In particular, moderate relaxation of KL regularization consistently improves survival discrimination, while alternative divergence mechanisms such as MMD and HSIC provide limited benefit without appropriate scaling. We further demonstrate that structuring the latent space can improve alignment between learned representations and survival risk gradients. A hybrid continuous--discrete formulation based on Gumbel--Softmax enhances global risk ordering in the continuous latent subspace, even though stable discrete subtype discovery does not emerge under survival supervision. Guided by these findings, we instantiate a robust multimodal survival model, termed MO-RiskVAE, which consistently improves risk stratification over the original MyeVAE without introducing additional supervision or complex training heuristics.
  </details>

- **[Time-driven Survival Analysis from FDG-PET/CT in Non-Small Cell Lung Cancer](https://arxiv.org/abs/2604.06885)**  `arXiv:2604.06885`  `cs.CV`  
  _Sambit Tarai, Ashish Chauhan, Elin Lundström, Johan Öfverstedt, Therese Sjöholm, Veronica Sanchez Rodriguez, et al._
  <details open><summary>Abstract</summary>
  Purpose: Automated medical image-based prediction of clinical outcomes, such as overall survival (OS), has great potential in improving patient prognostics and personalized treatment planning. We developed a deep regression framework using tissue-wise FDG-PET/CT projections as input, along with a temporal input representing a scalar time horizon (in days) to predict OS in patients with Non-Small Cell Lung Cancer (NSCLC).Methods: The proposed framework employed a ResNet-50 backbone to process input images and generate corresponding image embeddings. The embeddings were then combined with temporal data to produce OS probabilities as a function of time, effectively parameterizing the predictions based on time. The overall framework was developed using the U-CAN cohort (n = 556) and evaluated by comparing with a baseline method on the test set (n = 292). The baseline utilized the ResNet-50 architecture, processing only the images as input and providing OS predictions at pre-specified intervals, such as 2- or 5-year.Results: The incorporation of temporal data with image embeddings demonstrated an advantage in predicting OS, outperforming the baseline method with an improvement in AUC of 4.3%. The proposed model using clinical + IDP features achieved strong performance, and an ensemble of imaging and clinical + IDP models achieved the best overall performance (0.788), highlighting the complementary value of multimodal inputs. The proposed method also enabled risk stratification of patients into distinct categories (high vs low risk). Heat maps from the saliency analysis highlighted tumor regions as key structures for the prediction.Conclusion: Our method provided an automated framework for predicting OS as a function of time and demonstrates the potential of combining imaging and tabular data for improved survival prediction.
  </details>
