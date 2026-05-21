# 🔍 Prognosis_Survival Papers · 2026-05-20

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[HDMoE: A Hierarchical Decoupling-Fusion Mixture-of-Experts Framework for Multimodal Cancer Survival Prediction](https://arxiv.org/abs/2605.20891)**  `arXiv:2605.20891`  `cs.CV`  
  _Huayi Wang, Haochao Ying, Yuyang Xu, Qiyao Zheng, jun wang, Cheng Zhang, et al._
  <details open><summary>Abstract</summary>
  Multimodal survival prediction, a crucial yet challenging task, demands the integration of multimodal medical data (\eg Whole Slide Images (WSIs) and Genomic Profiles) to achieve accurate prognostic modeling. Given the inherent heterogeneity across modalities, the feature decoupling-fusion paradigm has emerged as a dominant approach. However, these methods have the following shortcomings: (1) fail to reduce the redundant information of modality features before decoupling, which negatively affects the feature decoupling and fusion effect;(2) lack the ability to model the fine-grained relationships of the features and capture the local information interactions between intra- and inter-modality features. To address these issues, we propose a \underline{H}ierarchical \underline{D}ecoupling-Fusion \underline{M}ixture-\underline{o}f-\underline{E}xperts (HDMoE) framework with two levels of MoE and \underline{R}andom \underline{F}eature \underline{R}eorganization (RFR)this http URLthe first-level MoE, shared experts and routed experts are employed to remove redundant information and extract fine-grained specific features within each modality, while the second-level MoE facilitates fine-grained inter-modality feature decoupling. Besides, we design two RFR modules following each level of MoE to finely fuse intra- and inter-modality features, which can help the model capture more fine-grained relationships between modalities. Extensive experimental results on our private Liver Cancer (LC) and three TCGA public datasets confirm the effectiveness of our proposed method. Codes are available atthis https URL.
  </details>
