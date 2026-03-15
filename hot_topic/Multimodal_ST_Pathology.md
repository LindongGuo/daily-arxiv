# 🔍 Multimodal_ST_Pathology Papers · 2026-03-14

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[MedMO: Grounding and Understanding Multimodal Large Language Model for Medical Images](https://arxiv.org/abs/2602.06965)**  `arXiv:2602.06965`  `cs.CV`  
  _Ankan Deria, Komal Kumar, Adinath Madhavrao Dukre, Eran Segal, Salman Khan, Imran Razzak_
  <details open><summary>Abstract</summary>
  Multimodal large language models have advanced rapidly, but their adoption in medicine is constrained by limited domain coverage, imperfect modality alignment, and insufficient grounded reasoning. We introduce MedMO, a medical multimodal foundation model built on a general MLLM architecture and trained exclusively on large-scale domain-specific data. MedMO uses a multi-stage training recipe that includes cross-modal pretraining to align heterogeneous visual encoders with a medical language backbone, instruction tuning with multi-task supervision spanning captioning, VQA, report generation, retrieval, and bounding-box disease localization, and reinforcement learning with verifiable rewards that combine factuality checks with a box-level GIoU signal to improve spatial grounding and step-by-step reasoning in challenging clinical settings. Across modalities and tasks, MedMO surpasses strong open-source medical baselines. MedMO-8B-Next achieves consistent gains on VQA benchmarks, improving by 6.6% on average over Fleming-VL-8B, including gains of 6.0% on MMMU-Med, 9.8% on PMC-VQA, and 21.3% on MedXpertQA. On text-based QA, it improves by 14.4% over Fleming-VL-8B, driven by gains of 8.4% on MMLU-Med and 30.1% on MedQA. For medical report generation, it improves by 6.7% on MIMIC-CXR. MedMO-8B-Next also demonstrates strong grounding performance, reaching 56.1 IoU on Bacteria, which is a 47.8 IoU gain over Fleming-VL-8B. At smaller scale, MedMO-4B-Next remains competitive and exceeds Fleming-VL-8B across VQA, QA, and report generation. Evaluations spanning radiology, ophthalmology, and pathology microscopy further confirm broad cross-modality generalization. Project is available atthis https URL
  </details>
