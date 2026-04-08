# 🔍 Prognosis_Survival Papers · 2026-04-07

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[PRIME: Prototype-Driven Multimodal Pretraining for Cancer Prognosis with Missing Modalities](https://arxiv.org/abs/2604.04999)**  `arXiv:2604.04999`  `cs.LG` `cs.AI`  
  _Kai Yu, Shuang Zhou, Yiran Song, Zaifu Zhan, Jie Peng, Kaixiong Zhou, et al._
  <details open><summary>Abstract</summary>
  Multimodal self-supervised pretraining offers a promising route to cancer prognosis by integrating histopathology whole-slide images, gene expression, and pathology reports, yet most existing approaches require fully paired and complete inputs. In practice, clinical cohorts are fragmented and often miss one or more modalities, limiting both supervised fusion and scalable multimodal pretraining. We propose PRIME, a missing-aware multimodal self-supervised pretraining framework that learns robust and transferable representations from partially observed cohorts. PRIME maps heterogeneous modality embeddings into a unified token space and introduces a shared prototype memory bank for latent-space semantic imputation via patient-level consensus retrieval, producing structurally aligned tokens without reconstructing raw signals. Two complementary pretraining objectives: inter-modality alignment and post-fusion consistency under structured missingness augmentation, jointly learn representations that remain predictive under arbitrary modality subsets. We evaluate PRIME on The Cancer Genome Atlas with label-free pretraining on 32 cancer types and downstream 5-fold evaluation on five cohorts across overall survival prediction, 3-year mortality classification, and 3-year recurrence classification. PRIME achieves the best macro-average performance among all compared methods, reaching 0.653 C-index, 0.689 AUROC, and 0.637 AUROC on the three tasks, respectively, while improving robustness under test-time missingness and supporting parameter-efficient and label-efficient adaptation. These results support missing-aware multimodal pretraining as a practical strategy for prognosis modeling in fragmented clinical data settings.
  </details>
