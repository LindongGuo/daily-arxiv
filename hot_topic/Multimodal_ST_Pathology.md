# 🔍 Multimodal_ST_Pathology Papers · 2026-08-20

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[CADRE: Stable, Parameter Efficient Adaptation of Medical Vision Language Models with Bounded Forgetting and Prior Drift](https://arxiv.org/abs/2606.23487)**  `arXiv:2606.23487`  `cs.AI`  
  _Rishabh Jha, Amrita Singh, Prashanna Chudal_
  <details open><summary>Abstract</summary>
  Medical vision-language models (VLMs) such as BiomedCLIP generalize broadly, but adapting them to a clinical service is as much a safety problem as an accuracy one. Updating a deployed model for a new imaging modality can fail silently in two ways that harm patients: it can forget modalities it already handled (catastrophic forgetting), and it can drift from its trustworthy pretrained prior toward modality-specific shortcuts. We study parameter-efficient continual adaptation through these two properties rather than leaderboard accuracy, presenting CADRE: a frozen-backbone framework combining low-rank adaptation (LoRA) with an online, self-scaling, similarity-aware elastic weight consolidation term that bounds retained-competence loss, and an anchor-to-prior penalty bounding embedding drift from the frozen prior. Two short guarantees, a bound on total consolidation mass and a scale-invariance property, remove the scale-related sources of vanilla EWC's order fragility. Using breast cancer across three maximally dissimilar modalities (histopathology, ultrasound, chest radiography) as a controlled cross-modality stress test, under a multi-seed, multi-order protocol with paired significance testing and training approximately 0.23% of parameters, CADRE attains the highest accuracy, SPQ, and backward transfer and the lowest forgetting among adapting methods, reducing forgetting roughly sevenfold versus the strongest regularized baseline (0.075 to 0.011; paired p=0.023) and achieving positive backward transfer where every baseline is negative. We frame these as stability properties aligned with clinical-safety desiderata, not a deployment guarantee; robustness to distribution shift and adversarial inputs is out of scope.
  </details>
