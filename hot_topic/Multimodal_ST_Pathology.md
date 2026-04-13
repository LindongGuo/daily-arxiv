# 🔍 Multimodal_ST_Pathology Papers · 2026-04-12

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[UniSemAlign: Text-Prototype Alignment with a Foundation Encoder for Semi-Supervised Histopathology Segmentation](https://arxiv.org/abs/2604.09169)**  `arXiv:2604.09169`  `cs.CV`  
  _Le-Van Thai, Tien Dat Nguyen, Hoai Nhan Pham, Lan Anh Dinh Thi, Duy-Dong Nguyen, Ngoc Lam Quang Bui_
  <details open><summary>Abstract</summary>
  Semi-supervised semantic segmentation in computational pathology remains challenging due to scarce pixel-level annotations and unreliable pseudo-label supervision. We propose UniSemAlign, a dual-modal semantic alignment framework that enhances visual segmentation by injecting explicit class-level structure into pixel-wise learning. Built upon a pathology-pretrained Transformer encoder, UniSemAlign introduces complementary prototype-level and text-level alignment branches in a shared embedding space, providing structured guidance that reduces class ambiguity and stabilizes pseudo-label refinement. The aligned representations are fused with visual predictions to generate more reliable supervision for unlabeled histopathology images. The framework is trained end-to-end with supervised segmentation, cross-view consistency, and cross-modal alignment objectives. Extensive experiments on the GlaS and CRAG datasets demonstrate that UniSemAlign substantially outperforms recent semi-supervised baselines under limited supervision, achieving Dice improvements of up to 2.6% on GlaS and 8.6% on CRAG with only 10% labeled data, and strong improvements at 20% supervision. Code is available at:this https URL
  </details>

- **[Cross-Modal Knowledge Distillation from Spatial Transcriptomics to Histology](https://arxiv.org/abs/2604.09076)**  `arXiv:2604.09076`  `cs.CV`  
  _Arbel Hizmi, Artemii Bakulin, Shai Bagon, Nir Yosef_
  <details open><summary>Abstract</summary>
  Spatial transcriptomics provides a molecularly rich description of tissue organization, enabling unsupervised discovery of tissue niches -- spatially coherent regions of distinct cell-type composition and function that are relevant to both biological research and clinical interpretation. However, spatial transcriptomics remains costly and scarce, while H&E histology is abundant but carries a less granular signal. We propose to leverage paired spatial transcriptomics and H&E data to transfer transcriptomics-derived niche structure to a histology-only model via cross-modal distillation. Across multiple tissue types and disease contexts, the distilled model achieves substantially higher agreement with transcriptomics-derived niche structure than unsupervised morphology-based baselines trained on identical image features, and recovers biologically meaningful neighborhood composition as confirmed by cell-type analysis. The resulting framework leverages paired spatial transcriptomic and H&E data during training, and can then be applied to held-out tissue regions using histology alone, without any transcriptomic input at inference time.
  </details>
