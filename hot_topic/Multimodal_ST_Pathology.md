# 🔍 Multimodal_ST_Pathology Papers · 2026-09-16

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Generalist-Specialist Mixture-of-Experts for Rare Pathology Detection in Multimodal Imaging](https://arxiv.org/abs/2609.18688)**  `arXiv:2609.18688`  `cs.CV` `cs.AI`  
  _Johannes Kaiser, Florian Braunmiller, Daniel Rückert, Georgios Kaissis_
  <details open><summary>Abstract</summary>
  AI models for multimodal medical imaging must balance modality-specific specialization with cross-modal shared representations, a trade-off that pure Mixture-of-Experts (MoE) architectures currently fail to satisfy. Expert-based routing improves in-domain learning but may sacrifice cross-modal signals, which appear particularly important for rare (low-prevalence) pathologies in our experiments. To resolve this, we introduce Generalist-Specialist-MoE (GS-MoE), a two-branch (MoE) architecture that couples a cross-modal generalist model with distinct modality-specific specialists (experts) via domain-constrained feature fusion. On RadImageNet (1.35M images, 165 pathologies, three modalities), GS-MoE recovers detection of six low-prevalence pathologies on which every baseline scores F1 $=$ 0, with per-class gains up to +0.60 F1. It attains this while even slightly exceeding dense and specialist-only MoE aggregate baselines (MCC 0.770), while using ${\sim}53\%$ fewer active parameters at inference than the strongest investigated dense model.
  </details>

- **[Lumen: Parameter-Efficient Alignment of Pretrained Vision and Language Encoders for Zero-Shot Computational Pathology](https://arxiv.org/abs/2609.17868)**  `arXiv:2609.17868`  `cs.CV`  
  _Kiarash Tajbakhsh, Abdelrahman Faqieh, Michael Jopiti, Javier Garcia-Baroja, Philipp Zens, Branislav Zagrapan, et al._
  <details open><summary>Abstract</summary>
  Pathology vision-language models are commonly built by pretraining or fine-tuning large encoders on paired image-caption data. We asked whether a pathology vision-language model can instead be assembled by parameter-efficient alignment of frozen unimodal foundation models, leaving their pretrained representations untouched. Here we present Lumen, which aligns frozen Virchow2 and BioMedBERT backbones using rank-4 adapters and projection heads, training only 0.40% of the total parameters on the public QUILT-1M corpus. Across nine public zero-shot patch benchmarks, Lumen achieved the highest mean chance-corrected balanced accuracy, 0.546 versus 0.461 for the strongest baseline (paired difference 0.086, 95% CI 0.042-0.136). On lymph-node metastasis detection, Lumen reached an AUROC of 0.964 (95% CI 0.956-0.971) on 4,214 held-out internal slides and 0.955 (95% CI 0.942-0.966) on 2,368 slides across nine external cohorts and six organs. At the internally calibrated threshold, it outperformed all vision-language baselines, with a balanced accuracy of 0.909 (95% CI 0.896-0.923) internally and 0.915 (95% CI 0.902-0.929) externally. Lumen performed competitively across the evaluations, with the exception of cross-modal retrieval, where it ranked third behind CONCH and PathGen-L/14. Fully fine-tuning both encoders gave Lumen no consistent benefit over low-rank adaptation, although it improved retrieval. Aligning frozen unimodal foundation models therefore yields strong and transferable performance at patch and slide level while training only a small fraction of the parameters.
  </details>
