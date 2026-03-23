# 🔍 Multimodal_ST_Pathology Papers · 2026-03-22

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[HiPath: Hierarchical Vision-Language Alignment for Structured Pathology Report Prediction](https://arxiv.org/abs/2603.19957)**  `arXiv:2603.19957`  `cs.CV` `cs.AI` `cs.LG`  
  _Ruicheng Yuan, Zhenxuan Zhang, Anbang Wang, Liwei Hu, Xiangqian Hua, Yaya Peng, et al._
  <details open><summary>Abstract</summary>
  Pathology reports are structured, multi-granular documents encoding diagnostic conclusions, histological grades, and ancillary test results across one or more anatomical sites; yet existing pathology vision-language models (VLMs) reduce this output to a flat label or free-form text. We present HiPath, a lightweight VLM framework built on frozen UNI2 and Qwen3 backbones that treats structured report prediction as its primary training objective. Three trainable modules totalling 15M parameters address complementary aspects of the problem: a Hierarchical Patch Aggregator (HiPA) for multi-image visual encoding, Hierarchical Contrastive Learning (HiCL) for cross-modal alignment via optimal transport, and Slot-based Masked Diagnosis Prediction (Slot-MDP) for structured diagnosis generation. Trained on 749K real-world Chinese pathology cases from three hospitals, HiPath achieves 68.9% strict and 74.7% clinically acceptable accuracy with a 97.3% safety rate, outperforming all baselines under the same frozen backbone. Cross-hospital evaluation confirms generalisation with only a 3.4pp drop in strict accuracy while maintaining 97.1% safety.
  </details>

- **[Adapting a Pre-trained Single-Cell Foundation Model to Spatial Gene Expression Generation from Histology Images](https://arxiv.org/abs/2603.19766)**  `arXiv:2603.19766`  `cs.CV`  
  _Donghai Fang, Yongheng Li, Zhen Wang, Yuansong Zeng, Wenwen Min_
  <details open><summary>Abstract</summary>
  Spatial transcriptomics (ST) enables spot-level in situ expression profiling, but its high cost and limited throughput motivate predicting expression directly from HE-stained histology. Recent advances explore using score- or flow-based generative models to estimate the conditional distribution of gene expression from histology, offering a flexible alternative to deterministic regression approaches. However, most existing generative approaches omit explicit modeling of gene-gene dependencies, undermining biological coherence. Single-cell foundation models (sc-FMs), pre-trained across diverse cell populations, capture these critical gene relationships that histology alone cannot reveal. Yet, applying expression-only sc-FMs to histology-conditioned expression modeling is nontrivial due to the absence of a visual pathway, a mismatch between their pre-training and conditional ST objectives, and the scarcity of mixed-cell ST supervision. To address these challenges, we propose HINGE (HIstology-coNditioned GEneration), which retrofits a pre-trained sc-FM into a conditional expression generator while mostly preserving its learned gene relationships. We achieve this by introducing SoftAdaLN, a lightweight, identity-initialized modulation that injects layer-wise visual context into the backbone, coupled with an expression-space masked diffusion objective and a warm-start curriculum to ensure objective alignment and training stability. Evaluated on three ST datasets, ours outperforms state-of-the-art baselines on mean Pearson correlation and yields more accurate spatial marker expression patterns and higher pairwise co-expression consistency, establishing a practical route to adapt pre-trained sc-FMs for histology-conditioned spatial expression generation.
  </details>
