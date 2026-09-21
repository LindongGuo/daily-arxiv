# 🔍 Prognosis_Survival Papers · 2026-09-20

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[MIST: Multimodal Survival Prediction with Genomic-Guided Histology Attention](https://arxiv.org/abs/2609.21811)**  `arXiv:2609.21811`  `cs.AI` `cs.CV`  
  _Muhammet Sami Yavuz, Sabri Mustafa Kahya, Richard R. Chen, Jana Lipkova, Benedikt Wiestler_
  <details open><summary>Abstract</summary>
  Multimodal survival models can combine complementary prognostic information from whole-slide images and genomic profiles, but effective fusion remains challenging amid external cohort shift and computational complexity. To address these challenges, we propose MIST, multimodal survival prediction with genomic-guided histology attention. MIST represents genomic features as tokens and allows them to query compact foundation-model-derived histology context tokens before survival prediction. This design enriches molecular information with histology context rather than merging separately encoded modalities only at the final stage. Training combines discrete-time survival prediction with genomic feature masking, WSI dropout, and paired WSI-genomics contrastive alignment. Across four external evaluations in colon, renal, lung, and glioblastoma cohorts, MIST improves external C-index over standard fusion baselines in the primary comparisons. These results support genomic-guided histology attention as a compact and effective strategy for multimodal oncology outcome prediction. Our code is available atthis https URL.
  </details>
