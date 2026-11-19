# 🔍 Med_Foundation_Models Papers · 2026-11-18

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[ProtoBridge-CLIP: Observation-Masked Finding Prototypes for Medical Image--Report Representation Learning](https://arxiv.org/abs/2611.24002)**  `arXiv:2611.24002`  `cs.CV` `cs.AI`  
  _Jinrui Wu, Yun Peng_
  <details open><summary>Abstract</summary>
  Radiology reports distinguish affirmed findings, explicit negations, and unmentioned concepts, but conventional global image--report contrastive learning often compresses these different evidence states into a single study-level target. We introduce \model{}, which combines symmetric global image--report alignment with observation-masked finding supervision and a soft relation objective over affirmed report concepts. Text-derived finding prototypes are aligned with local visual tokens, while uncertain and unmentioned concepts are excluded from direct finding labels. We evaluate the framework on three CT benchmarks and five chest-radiograph benchmarks, together with component ablations, paired and clinical retrieval, localization, perturbation robustness, calibration, and per-finding analyses. \model{} achieves macro-AUROC values of 73.6%, 66.5\%, and 68.8% on CT-RATE, RAD-ChestCT, and INSPECT, and 80.2%, 91.4%, 78.5%, 86.5%, and 90.8% on ChestXray14, CheXpert, PadChest, RSNA, and SIIM-ACR, respectively. Relative to the matched global-only controls, the findings and relation objectives yield consistent gains across the evaluated datasets. These results demonstrate the practical value of treating observed and unobserved report concepts differently during medical image--text representation learning.
  </details>

- **[SCOUT: Risk-Guided Foundation-Model Escalation for Robust Tissue Detection in Whole-Slide Images](https://arxiv.org/abs/2611.24366)**  `arXiv:2611.24366`  `cs.CV`  
  _Cristian Tommasino, Antonio M. Rinaldi_
  <details open><summary>Abstract</summary>
  Reliable tissue detection is essential for whole-slide image analysis, yet high average segmentation accuracy can conceal failures involving pale tissue, small fragments, and heterogeneous staining. Pathology foundation models offer transferable representations, but exhaustive inference is computationally demanding and may introduce false-positive tissue predictions. We propose SCOUT (Selective Correction of Uncertain Tissue), a risk-guided cascade that selectively refines an initial thumbnail-based tissue mask. A lightweight audit network estimates the spatial distribution of segmentation errors and prioritizes candidate regions for processing by a frozen pathology foundation model. An asymmetric consensus rule integrates the resulting predictions with the initial mask to recover missed tissue while limiting false positives. A calibrated slide-level review score additionally controls the marginal rate of unflagged case-group failures under the calibration assumptions. Evaluation on a public multi-source, multi-stain benchmark shows that SCOUT reduces the proportion of case groups requiring mask correction from 38.1% for the best released detector to 18.6%, with particularly pronounced improvements in immunohistochemistry. Source-held-out experiments demonstrate better generalization than a segmentation network trained on the same annotations, while selective inference achieves an observed failure rate no higher than processing all candidate regions. Downstream, lymph-node classification with SCOUT masks is non-inferior to that obtained with two of the three released detectors evaluated. A variant built on an openly licensed foundation model is publicly released as an installable Python package with trained weights. These results support risk-guided foundation-model inference as an effective approach to tissue detection across heterogeneous histopathology data.
  </details>
