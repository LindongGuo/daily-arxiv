# 🔍 Med_Foundation_Models Papers · 2026-03-30

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Central-to-Local Adaptive Generative Diffusion Framework for Improving Gene Expression Prediction in Data-Limited Spatial Transcriptomics](https://arxiv.org/abs/2603.26827)**  `arXiv:2603.26827`  `cs.LG` `cs.AI` `cs.CV`  
  _Yaoyu Fang, Jiahe Qian, Xinkun Wang, Lee A. Cooper, Bo Zhou_
  <details open><summary>Abstract</summary>
  Spatial Transcriptomics (ST) provides spatially resolved gene expression profiles within intact tissue architecture, enabling molecular analysis in histological context. However, the high cost, limited throughput, and restricted data sharing of ST experiments result in severe data scarcity, constraining the development of robust computational models. To address this limitation, we present a Central-to-Local adaptive generative diffusion framework for ST (C2L-ST) that integrates large-scale morphological priors with limited molecular guidance. A global central model is first pretrained on extensive histopathology datasets to learn transferable morphological representations, and institution-specific local models are then adapted through lightweight gene-conditioned modulation using a small number of paired image-gene spots. This strategy enables the synthesis of realistic and molecularly consistent histology patches under data-limited conditions. The generated images exhibit high visual and structural fidelity, reproduce cellular composition, and show strong embedding overlap with real data across multiple organs, reflecting both realism and diversity. When incorporated into downstream training, synthetic image-gene pairs improve gene expression prediction accuracy and spatial coherence, achieving performance comparable to real data while requiring only a fraction of sampled spots. C2L-ST provides a scalable and data-efficient framework for molecular-level data augmentation, offering a domain-adaptive and generalizable approach for integrating histology and transcriptomics in spatial biology and related fields.
  </details>

- **[TabPFN-Wide: Continued Pre-Training for Extreme Feature Counts](https://arxiv.org/abs/2510.06162)**  `arXiv:2510.06162`  `cs.LG`  
  _Christopher Kolberg, Jules Kreuer, Jonas Huurdeman, Sofiane Ouaari, Katharina Eggensperger, Nico Pfeifer_
  <details open><summary>Abstract</summary>
  Revealing novel insights from the relationship between molecular measurements and pathology remains a very impactful application of machine learning in biomedicine. Data in this domain typically contain only a few observations but thousands of potentially noisy features, posing challenges for conventional tabular machine learning approaches. While prior-data fitted networks emerge as foundation models for predictive tabular data tasks, they are currently not suited to handle large feature counts (>500). Although feature reduction enables their application, it hinders feature importance analysis. We propose a strategy that extends existing models through continued pre-training on synthetic data sampled from a customized prior. The resulting model, TabPFN-Wide, matches or exceeds its base model's performance, while exhibiting improved robustness to noise. It seamlessly scales beyond 30,000 categorical and continuous features, regardless of noise levels, while maintaining inherent interpretability, which is critical for biomedical applications. Our results demonstrate that prior-informed adaptation is suitable to enhance the capability of foundation models for high-dimensional data. On real-world omics datasets, we show that many of the most relevant features identified by the model overlap with previous biological findings, while others propose potential starting points for future studies.
  </details>

- **[MOOZY: A Patient-First Foundation Model for Computational Pathology](https://arxiv.org/abs/2603.27048)**  `arXiv:2603.27048`  `cs.CV`  
  _Yousef Kotp, Vincent Quoc-Huy Trinh, Christopher Pal, Mahdi S. Hosseini_
  <details open><summary>Abstract</summary>
  Computational pathology needs whole-slide image (WSI) foundation models that transfer across diverse clinical tasks, yet current approaches remain largely slide-centric, often depend on private data and expensive paired-report supervision, and do not explicitly model relationships among multiple slides from the same patient. We present MOOZY, a patient-first pathology foundation model in which the patient case, not the individual slide, is the core unit of representation. MOOZY explicitly models dependencies across all slides from the same patient via a case transformer during pretraining, combining multi-stage open self-supervision with scaled low-cost task supervision. In Stage 1, we pretrain a vision-only slide encoder on 77,134 public slide feature grids using masked self-distillation. In Stage 2, we align these representations with clinical semantics using a case transformer and multi-task supervision over 333 tasks from 56 public datasets, including 205 classification and 128 survival tasks across four endpoints. Across eight held-out tasks with five-fold frozen-feature probe evaluation, MOOZY achieves best or tied-best performance on most metrics and improves macro averages over TITAN by +7.37%, +5.50%, and +7.83% and over PRISM by +8.83%, +10.70%, and +9.78% for weighted F1, weighted ROC-AUC, and balanced accuracy, respectively. MOOZY is also parameter efficient with 85.77M parameters, 14x smaller than GigaPath. These results demonstrate that open, reproducible patient-level pretraining yields transferable embeddings, providing a practical path toward scalable patient-first histopathology foundation models.
  </details>
