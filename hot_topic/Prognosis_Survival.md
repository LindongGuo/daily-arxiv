# 🔍 Prognosis_Survival Papers · 2026-10-11

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[Efficient Learning of Survival Analysis Models Under Outcome-Dependent Truncation and Censoring](https://arxiv.org/abs/2610.12538)**  `arXiv:2610.12538`  `cs.LG`  
  _Itai Zilberstein, Ioannis Anagnostides, Arman Kilic, Tuomas Sandholm_
  <details open><summary>Abstract</summary>
  Modern machine learning models are typically trained on data assumed to be representative of the predictive tasks the model will face in the future, but practical datasets violate this assumption. We focus on outcome-dependent truncation in which an observation appears in the training data depending on its label. Our work connects two largely distinct literatures: efficient learning under truncation and survival analysis. Existing methods for truncated survival analysis do not characterize the optimization landscape and instead rely on iterative procedures such as expectation maximization. We address this gap and prove that Cox regression can be efficiently learned under truncated and right-censored data using first-order optimization when the baseline hazard is known (despite nonconvexity). In contrast, when the baseline hazard is learned jointly, we construct identifiable and correctly specified models whose negative log-likelihood contains strict suboptimal local minima. On experiments with four survival datasets, we show that accounting for truncation reduces the prediction bias induced by naive Cox regression and extends to neural networks. We also show orders of magnitude speedups compared to standard expectation maximization.
  </details>
