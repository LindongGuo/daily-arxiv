# 🔍 Med_Foundation_Models Papers · 2026-07-04

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Towards Cellular-Scale Interpretability in Pathology Foundation Models for Biomarker Assessment](https://arxiv.org/abs/2511.05150)**  `arXiv:2511.05150`  `cs.CV` `cs.AI`  
  _Jingsong Liu, Han Li, Zhengyang Xu, Franz-Leonard Klaus, Fabian Stögbauer, Shihui Zu, et al._
  <details open><summary>Abstract</summary>
  Molecular biomarker testing in pathology is often costly and tissue-consuming, limiting scalable clinical deployment. Artificial intelligence applied to hematoxylin and eosin (HE)-stained histology could enable rapid biomarker screening, but clinical translation requires models that are both accurate and interpretable. Here we introduce Hireca, a biomarker-focused pathology foundation model pretrained on more than 80,000 whole-slide images spanning 38 organ types from three medical centers, together with CytoMap, an interpretability module that localizes cellular-scale evidence underlying predictions. Across 10 biomarker tasks encompassing morphological, molecular, genetic, and spatial-transcriptomic-proxy readouts, Hireca ranked first in five tasks and outperformed comparable models overall. In evaluation by eight pathologists from two countries, CytoMap was consistently preferred over alternative visualization approaches and revealed error patterns in difficult cases. These results position Hireca and CytoMap as a transparent framework for clinically reviewable biomarker assessment directly from routine HE histology.
  </details>

- **[BRIGHT: A Collaborative Generalist-Specialist Foundation Model for Breast Pathology](https://arxiv.org/abs/2603.03030)**  `arXiv:2603.03030`  `cs.CV`  
  _Xiaojing Guo, Jiatai Lin, Yumian Jia, Jingqi Huang, Zeyan Xu, Weidong Li, et al._
  <details open><summary>Abstract</summary>
  Generalist pathology foundation models (PFMs), pretrained on large-scale multi-organ datasets, have demonstrated remarkable predictive capabilities across diverse clinical applications. However, their proficiency on the full spectrum of clinically essential tasks within a specific organ system remains an open question due to the lack of large-scale validation cohorts for a single organ as well as the absence of a tailored training paradigm that can effectively translate broad histomorphological knowledge into the organ-specific expertise required for specialist-level interpretation. In this study, we propose BRIGHT, the first PFM specifically designed for breast pathology, trained on over 51,000 breast whole-slide images derived from a cohort of over 40,000 patients across 19 hospitals. BRIGHT employs a collaborative generalist-specialist framework to capture both universal and organ-specific features. To comprehensively evaluate the performance of PFMs on breast oncology, we curate the largest multi-institutional cohorts to date for downstream task development and evaluation, comprising over 25,000 WSIs across 10 hospitals. The validation cohorts cover the full spectrum of breast pathology across 25 distinct clinical tasks spanning diagnosis, biomarker prediction, treatment response and survival prediction. Extensive experiments demonstrate that BRIGHT outperforms five leading generalist PFMs, achieving state-of-the-art (SOTA) performance in 25 of 25 internal validation tasks and in 4 of 11 external validation tasks with excellent heatmap interpretability. By evaluating on large-scale validation cohorts, this study not only demonstrates BRIGHT's clinical utility in breast oncology but also validates a collaborative generalist-specialist paradigm, providing a scalable template for developing PFMs on a specific organ system, accelerating the translation of foundation models into ...
  </details>

- **[NEARL: Interacted Query Adaptation with Orthogonal Regularization for Medical Vision-Language Understanding](https://arxiv.org/abs/2508.04101)**  `arXiv:2508.04101`  `cs.CV`  
  _Zelin Peng, Yichen Zhao, Yu Huang, Piao Yang, Feilong Tang, Zhengqin Xu, et al._
  <details open><summary>Abstract</summary>
  Computer-aided medical image analysis is crucial for disease diagnosis and treatment planning. While vision-language models (VLMs) such as CLIP exhibit strong generalization ability, their direct application to medical imaging remains hindered by a substantial domain gap. Existing methods for bridging this gap, including prompt learning and unidirectional modality interaction, typically introduce domain knowledge into only one modality. However, such approaches fail to fully exploit CLIP's inherent dual-modality structure and overlook the synergistic effect of bidirectional cross-modal interaction, resulting in persistent modality misalignment. In this paper, we propose NEARL (iNteracted quEry Adaptation with oRthogonaL Regularization), a novel parameter-efficient VLM framework for bidirectional cross-modal interaction. NEARL consists of two key components: (1) the Unified Synergy Embedding Transformer (USEformer), which dynamically generates compact cross-modal queries to facilitate interaction; and (2) the Orthogonal Cross-Attention Adapter (OCA), which decouples new knowledge into truly novel and incremental components through orthogonal regularization. This design reduces interference from incremental components, enabling more focused learning of novel information and improving modality interaction in VLMs. Notably, NEARL introduces only 1.46M learnable parameters. Extensive experiments on three medical imaging modalities demonstrate state-of-the-art performance (e.g., a 2.3% relative improvement on the pneumonia dataset), along with fast inference and low memory overhead, highlighting its effectiveness for real-world medical vision-language understanding.
  </details>
