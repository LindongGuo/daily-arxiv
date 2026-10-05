# 🔍 Med_Foundation_Models Papers · 2026-10-04

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[HERO: Histology Encoder for Robust Representation in Oncology](https://arxiv.org/abs/2609.35943)**  `arXiv:2609.35943`  `cs.CV`  
  _Zhi Li, Eghbal Amidi, Yating Cheng, Tyson Dawson, Gorkem Can Ates, Shuzhen Kuang, et al._
  <details open><summary>Abstract</summary>
  Foundation models trained on large pathology image corpora now provide strong, transferable representations for computational pathology. Over the past few years a series of such models has been released, each trained on more slides than the last; on standard classification and segmentation benchmarks, the leading models are now separated by small margins. In clinical use, however, the foundation model is applied to images from hospitals, scanners, and staining protocols outside its training data. Encoders generally embed these acquisition factors alongside biological information, which may introduce downstream errors and hinder safe clinical adoption. A pathology foundation model should therefore be robust to acquisition shift without giving up representation quality, yet robustness is seldom the axis along which models are compared. In this report, we introduce HERO (Histology Encoder for Robust Representation in Oncology), a ViT-G/14 pathology foundation model trained with the DINO and iBOT objectives and refined with high-resolution Gram anchoring on a morphology-balanced corpus of 500 million tiles from approximately 575,000 clinical whole-slide images. Across the evaluated public benchmarks, HERO shows the strongest robustness to center, scanner, and stain variation among the compared state-of-the-art foundation models, performs comparably on tile-level classification, segmentation, and gene-expression prediction, ranks first on average across 39 evaluated slide-level clinical tasks, and, under an equal-weighted framework-level analysis, has the best average rank across the six benchmark frameworks.
  </details>

- **[Uncertainty Estimation in Pathology Foundation Models via Deep Mutual Learning](https://arxiv.org/abs/2606.30020)**  `arXiv:2606.30020`  `cs.CV`  
  _Gbègninougbo Aurel Davy Tchokponhoue, Sevda Öğüt, Ali Idri, Dorina Thanou, Pascal Frossard_
  <details open><summary>Abstract</summary>
  Pathology foundation models (PFMs) offer generalizable representations for whole-slide image (WSI) analysis, yet their clinical adoption remains limited. Specifically, their predictions lack reliable confidence estimates, and no single PFM is universally best across tasks, which severely undermines trust in medical settings. To overcome this, we propose DICE, a plug-and-play framework that ensembles $K$ frozen PFMs and estimates uncertainty based on their consensus. We align the ensemble members via deep mutual learning and theoretically show that this objective controls an upper bound on epistemic uncertainty. Additionally, we demonstrate that the ensemble localizes abnormalities at the patch level without any explicit supervision. We evaluate DICE on three challenging WSI benchmarks. Notably, our framework provides reliable uncertainty estimates that accurately flag failure-prone cases under in- and out-of-distribution settings, while matching or outperforming SOTA baselines in classification, calibration, and localization. Overall, DICE takes a crucial step toward translating PFMs into uncertainty-aware decision-support systems.
  </details>
