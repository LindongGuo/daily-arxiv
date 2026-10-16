# 🔍 Prognosis_Survival Papers · 2026-10-15

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[Morphology-aware deep learning predicts colorectal cancer survival from whole-slide images](https://arxiv.org/abs/2610.17603)**  `arXiv:2610.17603`  `cs.CV` `cs.AI` `cs.LG`  
  _Hikmat Khan, Metin N. Gurcan, Anil Parwani, Wendy L. Frankel, Wei Chen, Muhammad Khalid Khan Niazi_
  <details open><summary>Abstract</summary>
  Background: Five-year survival prediction from hematoxylin-and-eosin whole-slide images could support risk stratification, but the task is weakly supervised, and the tissue morphologies carrying prognostic information remain incompletely characterized.Methods: We conducted a retrospective secondary analysis using TCGA-COAD/READ (n=562) for morphology-specific analysis, Alliance/ CALGB 89803 (n=424) for model development, and SurGen (n=218) for external evaluation. We propose MorphContrast, a morphology-aware contrastive multiple-instance learning framework that uses tissue labels as structural supervision for five-year survival prediction. MorphContrast combines gated-attention pooling with three auxiliary objectives: patch-level morphology labels define within-patient contrasts, outcome concordance or discordance defines cross-patient contrasts within matched morphologies, and diversity regularization discourages representational collapse. Morphology-matched patches from patients with discordant outcomes serve as hard negatives, encouraging prognostic discrimination within comparable histologic contexts.Results: Morphology-specific models show weak but distributed prognostic discrimination: adipose tissue achieves an area under the receiver operating characteristic curve (AUC) of 0.622, stroma achieves 0.604, and both perform comparably to tumor epithelium (0.601-0.605). On Alliance/CALGB 89803, the single model achieves an AUC of 0.642, while the post hoc ensemble reaches a pooled out-of-fold AUC of 0.70 and a risk-group hazard ratio of 3.79 (95% confidence interval: 2.55-5.63). On the external SurGen colon cancer cohort (n=218), the single model and ensemble achieve AUCs of 0.669 and 0.678, respectively.Conclusions: These findings support tissue morphology as structural supervision for outcome-aware representation learning in colorectal cancer prognosis.
  </details>
