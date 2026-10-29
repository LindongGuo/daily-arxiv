# 🔍 Med_Foundation_Models Papers · 2026-10-28

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[PRISM: Pathology Reliability In Scarce-label Medicine. A Tile-level Benchmark of Pathology Foundation Models](https://arxiv.org/abs/2610.36517)**  `arXiv:2610.36517`  `cs.LG` `cs.CV`  
  _Alicem Koyun_
  <details open><summary>Abstract</summary>
  Pathology foundation models are typically benchmarked on classification performance at full label availability and on in-distribution test sets, while calibration, behavior at low label budgets, and robustness under cross-institutional shift are seldom evaluated jointly. We introduce PRISM, a tile-level benchmark that measures the reliability of pathology foundation models along four axes: model choice, label fraction, calibration, and out-of-distribution transfer. PRISM evaluates eight foundation models (CLIP, PLIP, CONCH, UNI, Virchow2, GigaPath, H-Optimus-0, Midnight) on six tile-level datasets at six label fractions (1% to 100%) with three seeds (864 linear probe runs), extended with a five-hospital Camelyon17 study of 20 directed transfer pairs. Four phenomena emerge. (i) Under full supervision, AUROC rank predicts post-temperature calibration rank consistently across datasets (Spearman rho = 0.52, I^2 = 0%), whereas at 1% labels the relationship becomes dataset-specific (rho = -0.24, I^2 = 67%). (ii) On harder datasets the linear probe collapses to a single predicted class below a dataset-specific label fraction. (iii) Whether additional source-domain labels help or harm target calibration tracks how well the probe transfers: below a transfer AUROC of roughly 0.85, more labels worsen target ECE in 86-88% of combinations. (iv) Temperature scaling fails to reduce ECE in 49 of 288 cells, miscalibration is predominantly under-confidence, and a source-fitted temperature is harmful under failing transfer. PRISM is released as a pip-installable package with reference results for all 288 cells. Code and data:this https URL
  </details>

- **[FOCUS: A Subspecialty Foundation Model for Intraoperative Central Nervous System Pathology](https://arxiv.org/abs/2610.16914)**  `arXiv:2610.16914`  `cs.CV`  
  _Xing Liu, Yifan Guo, Hongtai Lv, Lei Lou, Yuyi Tan, Jiang Du, et al._
  <details open><summary>Abstract</summary>
  Intraoperative frozen-section diagnosis of central nervous system (CNS) lesions guides surgical decisions but is challenged by artefacts, diagnostic complexity and time constraints. Most pathology foundation models have limited exposure to CNS frozen tissue. Here we present FOCUS, a subspecialty foundation model pretrained on 27,930 frozen-section whole-slide images enriched for CNS tissue. FOCUS ranked first across all 11 diagnostic and 12 biomarker-prediction tasks in the internal test cohort, achieving mean AUCs of 0.969 and 0.877, respectively. This advantage was retained in the temporal and external test cohorts. We further organized a WHO-aligned diagnostic hierarchy, where FOCUS also outperformed comparator models. In a reader study, FOCUS assistance enabled junior readers to approach or exceed unassisted senior readers in hierarchical diagnostic accuracy and granularity. More importantly, FOCUS assistance enabled readers to correctly identify a mean of 63.0% of initially missed lymphoma cases (73.2% among junior readers), potentially avoiding unnecessary extensive resection. These findings highlight the potential of FOCUS to provide clinically actionable support for intraoperative CNS pathology and inform surgical decisions.
  </details>
