# 🔍 Prognosis_Survival Papers · 2026-04-23

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[Attention-based multiple instance learning for predominant growth pattern prediction in lung adenocarcinoma wsi using foundation models](https://arxiv.org/abs/2604.21530)**  `arXiv:2604.21530`  `cs.CV` `cs.AI`  
  _Laura Valeria Perez-Herrera, M.J. Garcia-Gonzalez, Karen Lopez-Linares_
  <details open><summary>Abstract</summary>
  Lung adenocarcinoma (LUAD) grading depends on accurately identifying growth patterns, which are indicators of prognosis and can influence treatment decisions. Common deep learning approaches to determine the predominant pattern rely on patch-level classification or segmentation, requiring extensive annotations. This study proposes an attention-based multiple instance learning (ABMIL) framework to predict the predominant LUAD growth pattern at the whole slide level to reduce annotation burden. Our approach integrates pretrained pathology foundation models as patch encoders, used either frozen or fine-tuned on annotated patches, to extract discriminative features that are aggregated through attention mechanisms. Experiments show that fine-tuned encoders improve performance, with Prov-GigaPath achieving the highest agreement (\k{appa} = 0.699) under ABMIL. Compared to simple patch-aggregation baselines, ABMIL yields more robust predictions by leveraging slide-level supervision and spatial attention. Future work will extend this framework to estimate the full distribution of growth patterns and validate performance on external cohorts.
  </details>
