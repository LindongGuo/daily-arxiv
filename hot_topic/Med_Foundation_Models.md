# 🔍 Med_Foundation_Models Papers · 2026-09-29

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Towards Scalable Context-Aware Single-Cell Spatial Transcriptomics Prediction from Histology Images](https://arxiv.org/abs/2609.36429)**  `arXiv:2609.36429`  `cs.CV`  
  _Zijun Gao, Chunbin Gu, Jinxi Xiang, Xiangde Luo, Pheng-Ann Heng_
  <details open><summary>Abstract</summary>
  Predicting gene expression from H&E-stained histology images offers a scalable alternative to costly spatial transcriptomics, yet most existing methods operate at the spot level, where signals from multiple cells are aggregated and critical cellular heterogeneity is obscured. Extending this paradigm to single-cell resolution is non-trivial. Naively applying pathology foundation models faces a scale mismatch: their patch-level representations mix multiple cells, whereas per-cell cropping or resizing distorts morphology and removes local context. Conversely, segmentation-based models without strong pretrained visual encoders often lack the morphological representation capacity needed for accurate molecular prediction and inherit errors from imperfect cell boundary masks. Here, we present CELLO, an efficient end-to-end framework that performs a single pathology foundation model forward pass per image and uses grid sampling to extract location-specific features for all cells simultaneously. We further introduce a distance-decay cross-attention module that refines each cell representation using spatially biased local morphological context. Using 52 public Xenium-H&E pairs from HEST-1k that span 12 organs and approximately 10 million cells, CELLO improves the average predictive accuracy over the evaluated baselines while reducing the mean whole-slide inference time compared to DeepSpot2Cell, a 14.0x speed-up on average that excludes upstream cell segmentation. Our work establishes a scalable foundation for single-cell gene expression prediction from H&E images.
  </details>

- **[FD-AA: A Lightweight Focal-Diffuse And Attenuation-Aware Head for Incidental Abdominal Abnormality Detection in Chest CT](https://arxiv.org/abs/2609.36189)**  `arXiv:2609.36189`  `cs.CV`  
  _Haoyan Ding, Kritika Iyer, Halid Yerebakan, Zhenyu Bu, Chushu Shen, Peiyu Duan, et al._
  <details open><summary>Abstract</summary>
  Routine chest CT captures upper-abdominal structures that may contain clinically relevant incidental abnormalities. Detecting these findings requires feature extraction from organs with different spatial extents and attenuation patterns. We propose FD-AA, a lightweight organ-aware classification head adaptable for frozen 3-D CT encoders. Within each organ, an attenuation-aware module preserves sparse focal evidence, while masked generalized-mean pooling captures diffuse anomaly patterns. In seven abdominal organs, FD-AA with Pillar-0 achieved state-of-the-art (SOTA) performance in both the CT-RATE test set (AUC = 0.798) and the external RAD-ChestCT dataset (AUC = 0.713). More specifically, FD-AA improved macro AUC/AP from 0.763/0.346 to 0.798/0.405 over direct classification using frozen Pillar-0 only (p = 0.034/0.016). Such performance gain generalizes across multiple frozen encoders (AUC improvement on MedicalNet +9.8%, CT-CLIP +14.7%, ResNet +3.7%), demonstrating the effectiveness of FD-AA across different feature representations. These results support the effectiveness of integrating focal-diffuse aggregation with explicit HU evidence for incidental abdominal abnormality detection.
  </details>

- **[HERO: Histology Encoder for Robust Representation in Oncology](https://arxiv.org/abs/2609.35943)**  `arXiv:2609.35943`  `cs.CV`  
  _Zhi Li, Eghbal Amidi, Yating Cheng, Tyson Dawson, Gorkem Can Ates, Shuzhen Kuang, et al._
  <details open><summary>Abstract</summary>
  Foundation models trained on large pathology image corpora now provide strong, transferable representations for computational pathology. Over the past few years a series of such models has been released, each trained on more slides than the last; on standard classification and segmentation benchmarks, the leading models are now separated by small margins. In clinical use, however, the foundation model is applied to images from hospitals, scanners, and staining protocols outside its training data. Encoders generally embed these acquisition factors alongside biological information, which may introduce downstream errors and hinder safe clinical adoption. A pathology foundation model should therefore be robust to acquisition shift without giving up representation quality, yet robustness is seldom the axis along which models are compared. In this report, we introduce HERO (Histology Encoder for Robust Representation in Oncology), a ViT-G/14 pathology foundation model trained with the DINO and iBOT objectives and refined with high-resolution Gram anchoring on a morphology-balanced corpus of 500 million tiles from approximately 575,000 clinical whole-slide images. Across the evaluated public benchmarks, HERO shows the strongest robustness to center, scanner, and stain variation among the compared state-of-the-art foundation models, performs comparably on tile-level classification, segmentation, and gene-expression prediction, ranks first on average across 39 evaluated slide-level clinical tasks, and, under an equal-weighted framework-level analysis, has the best average rank across the six benchmark frameworks.
  </details>
