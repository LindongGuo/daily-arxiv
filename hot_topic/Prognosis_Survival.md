# 🔍 Prognosis_Survival Papers · 2026-07-13

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[ShapKO: Shapley-Adaptive Modality Knockout for Robust Multimodal Learning](https://arxiv.org/abs/2607.09884)**  `arXiv:2607.09884`  `cs.CV` `cs.LG`  
  _Nusrat Binta Nizam, Fengbei Liu, Sunwoo Kwak, Minh Nguyen, Ruining Deng, Mert R. Sabuncu_
  <details open><summary>Abstract</summary>
  Multimodal medical models often degrade when inputs are missing, a common scenario in real-world clinical workflows. Separately, even when all modalities are present, modality dominance is observed during training, where optimization over-relies on a highly predictive modality and undertrains complementary sources, resulting in poor robustness under partial availability. While training-time modality knockout improves missing-modality robustness, existing approaches use static masking rates that cannot adapt to evolving modality utility during training. We introduce ShapKO (Shapley-Adaptive Modality Knockout), a dynamic training strategy that learns modality-specific knockout probabilities based on validation utility. ShapKO periodically evaluates performance across modality subsets, estimates modality importance via Shapley values, and updates masking probabilities to suppress dominant modalities more frequently. This adaptive process promotes complementary representations, while requiring no architectural modifications. We evaluate ShapKO on three datasets covering multitask clinical classification, survival prediction, and cancer detection. ShapKO consistently improves performance under modality absence and yields interpretable trajectories of learned masking behavior. Code is available at:this https URL
  </details>
