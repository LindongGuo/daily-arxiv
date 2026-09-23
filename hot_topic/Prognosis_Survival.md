# 🔍 Prognosis_Survival Papers · 2026-09-22

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[Evidential Fusion Network for Multimodal Survival Prediction under Missing Modalities](https://arxiv.org/abs/2606.20757)**  `arXiv:2606.20757`  `cs.LG`  
  _Yucheng Xing, Hailan Mo, Zi Wang, Ling Huang, Mengling Feng_
  <details open><summary>Abstract</summary>
  Recent multimodal survival prediction models have demonstrated strong predictive performance by leveraging complementary information across modalities. However, such models generally assume data completeness and exhibit limited robustness toward missing modalities, which are frequently encountered in real-world clinical settings. We propose the Evidential Missing Modality Survival Fusion (EMMS) model for multimodal survival prediction under missing modalities. EMMS offers a straightforward, computationally effective approach to survival analysis without requiring a generative phase for missing data. By employing Dempster-Shafer theory and Gaussian Random Fuzzy Numbers for multimodal decision fusion, it considers both aleatoric and epistemic uncertainty alongside modality reliability for fusion. Moreover, the model treats missing modalities as vacuous evidence, preventing interference with available inputs and naturally reflecting increased uncertainty and calibrated predictions. Extensive experiments on four cancer datasets demonstrate state-of-the-art performance while providing calibrated and interpretable uncertainty estimates under incomplete multimodal observations, without introducing additional computational overhead.
  </details>

- **[Semantic-Anchored Evidential Fusion for Domain-Robust Whole-Slide Survival Analysis](https://arxiv.org/abs/2606.19966)**  `arXiv:2606.19966`  `cs.CV` `cs.LG`  
  _Yucheng Xing, Ling Huang, Pei Liu, Jingying Ma, Jiaxing Xu, Kai He, et al._
  <details open><summary>Abstract</summary>
  Whole-slide images (WSIs) are widely used for computational cancer prognosis. However, most existing methods primarily focus on in-domain performance and fail to generalize across clinical centers. This limitation stems from their reliance on pixel-derived representations that are highly susceptible to domain-specific artifacts caused by staining protocols and scanner hardware. We hypothesize that high-level pathology semantics, such as tumor grade and micro-environmental architecture, provide a domain-invariant semantic representation that mirrors the robust diagnostic logic of human pathologists. Therefore, we propose a Semantic-Anchored Evidential Fusion Survival (SAEFS) framework, where SAEFS derives semantic anchors from WSIs via Visual Question Answering (VQA), employs a dual-stream WSI evidence extraction architecture, uses Dirichlet-based Subjective Logic to model uncertainty, and fuses semantic and visual evidence through a cautious conjunction rule to avoid overconfident fusion from correlated sources. Trained exclusively on one source domain and evaluated zero-shot across four unseen domains, SAEFS consistently outperforms state-of-the-art models both in prediction accuracy and reliability, improving the average C-index by 10.2%. Quantitative analyses further show that VQA-derived semantic features exhibit significantly lower cross-center divergence than pixel-derived features, highlighting their robustness for cross-center clinical applications.
  </details>
