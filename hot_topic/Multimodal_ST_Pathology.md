# 🔍 Multimodal_ST_Pathology Papers · 2026-09-14

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Weakly Supervised Spatial Grounding for Discriminative Attention-Based Ultrasound-Histopathology Alignment in Prostate Cancer Grading](https://arxiv.org/abs/2609.15150)**  `arXiv:2609.15150`  `cs.CV`  
  _Obed Korshie Dzikunu, Emma Willis, Mohammad Mahdi Abootorabi, Mohamed Harmanani, Zhuoxin Guo, Ferdinand Luger, et al._
  <details open><summary>Abstract</summary>
  Unpaired cross-modal distillation transfers grade structure from histopathology into a micro-ultrasound (micro-US) encoder by aligning a pooled needle-region embedding to a frozen histopathology teacher under grade-group correspondence alone. A single objective is thereby required to serve two distinct functions: rendering patch features discriminative of tissue state, and selecting which patches enter the pooled representation. We decouple them. Weak spatial supervision derived from percentage involvement, recorded routinely at biopsy, constrains the predicted proportion of malignant tissue within each core, acting on the encoder features independently of the alignment objective. The alignment loss then operates on features that differ across a core, and attention concentrates on a subset of patches rather than remaining near-uniform. On 7,166 biopsy cores from 811 patients across seven centers under patient-level 5-fold cross-validation, the method reaches 67.1 macro AUC and 68.5 csPCa AUC, against 61.2 and 52.8 for the existing unpaired alignment method and 63.1 and 62.6 for the strongest unimodal baselines. Ablation against existing attention regularizers designed to prevent attention-uniformity collapse shows that such regularizers do not substitute for label-derived supervision: they constrain the attention distribution, whereas the signal required acts on the features that attention reads.
  </details>
