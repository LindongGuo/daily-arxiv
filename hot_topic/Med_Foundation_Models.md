# 🔍 Med_Foundation_Models Papers · 2026-04-14

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[MorphDistill: Distilling Unified Morphological Knowledge from Pathology Foundation Models for Colorectal Cancer Survival Prediction](https://arxiv.org/abs/2604.06390)**  `arXiv:2604.06390`  `cs.CV` `cs.AI`  
  _Hikmat Khan, Usama Sajjad, Metin N. Gurcan, Anil Parwani, Wendy L. Frankel, Wei Chen, et al._
  <details open><summary>Abstract</summary>
  Background: Colorectal cancer (CRC) remains a leading cause of cancer-related mortality worldwide. Accurate survival prediction is essential for treatment stratification, yet existing pathology foundation models often overlook organ-specific features critical for CRC prognostication.Methods: We propose MorphDistill, a two-stage framework that distills complementary knowledge from multiple pathology foundation models into a compact CRC-specific encoder. In Stage I, a student encoder is trained using dimension-agnostic multi-teacher relational distillation with supervised contrastive regularization on large-scale colorectal datasets. This preserves inter-sample relationships from ten foundation models without explicit feature alignment. In Stage II, the encoder extracts patch-level features from whole-slide images, which are aggregated via attention-based multiple instance learning to predict five-year survival.Results: On the Alliance/CALGB 89803 cohort (n=424, stage III CRC), MorphDistill achieves an AUC of 0.68 (SD 0.08), an approximately 8% relative improvement over the strongest baseline (AUC 0.63). It also attains a C-index of 0.661 and a hazard ratio of 2.52 (95% CI: 1.73-3.65), outperforming all baselines. On an external TCGA cohort (n=562), it achieves a C-index of 0.628, demonstrating strong generalization across datasets and robustness across clinical subgroups.Conclusion: MorphDistill enables task-specific representation learning by integrating knowledge from multiple foundation models into a unified encoder. This approach provides an efficient strategy for prognostic modeling in computational pathology, with potential for broader oncology applications. Further validation across additional cohorts and disease stages is warranted.
  </details>
