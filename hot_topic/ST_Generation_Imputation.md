# 🔍 ST_Generation_Imputation Papers · 2026-09-01

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Semi-Supervised Virtual Staining via Morphology Preservation and Histopathological Realism Constraints](https://arxiv.org/abs/2609.00984)**  `arXiv:2609.00984`  `cs.CV` `cs.AI`  
  _Baoshun Wang, Weiping Lin, Linwu Wang, Yihuang Hu, Baptiste Magnier, Liansheng Wang_
  <details open><summary>Abstract</summary>
  Virtual staining aims to computationally generate target-stained histopathological images while reducing the cost and time associated with conventional staining procedures. However, existing methods rely predominantly on strictly paired and accurately registered training data, which are difficult and expensive to obtain in routine practice. To reduce this dependence, we propose a stable semi-supervised virtual staining framework that jointly exploits both limited paired data and abundant unpaired source images. Directly incorporating unpaired images is challenging because their generated results lack corresponding targets for supervision, potentially leading to unrealistic staining, morphological degradation, or even training collapse. To obtain reliable supervision from these images, Hessian-derived morphology preservation extracts structural cues from each source image and constrains the generated output to retain tissue morphology. Histopathological realism constraints further guide the output toward plausible target-stain characteristics, preventing the source-derived structural supervision from degenerating into contour enhancement or simple color transformation. Together, the two components suppress structural and appearance drift, stabilize semi-supervised stain translation, and promote the preservation of diagnostically relevant information. Extensive experiments on H&E-to-IHC translation for Ki67 and HER2, as well as FFPE-to-H&E translation, demonstrate consistent improvements in image quality, morphology preservation, robustness, and downstream diagnostic performance. Code will be available.
  </details>

- **[ReBridge-Flow: Re-Coupling Posterior Bridges in Flow Matching for Image Restoration](https://arxiv.org/abs/2609.00811)**  `arXiv:2609.00811`  `cs.CV`  
  _Jiaqi Zhang, Yiqi Wang, Hongjie Wu, Bohan Guo, Xinan Wang, Zichen Luo, et al._
  <details open><summary>Abstract</summary>
  Flow Matching provides an efficient generative prior for image restoration by learning continuous transport between source and data distributions. However, existing methods typically incorporate measurement constraints through local corrections. Such corrections may disrupt the source-clean endpoint coupling implicitly encoded by the pretrained flow, making the corrected endpoint pair incompatible with the current state. To address this issue, we propose ReBridge-Flow, a posterior bridge re-coupling method. Specifically, given the current state, ReBridge-Flow first decodes the corresponding local source and clean endpoints. It then incorporates measurement information through clean-side anchoring and synchronously re-couples the source endpoint, yielding a measurement-aware endpoint pair with improved local bridge compatibility. The re-coupled endpoints further define a posterior-informed transport direction for advancing the sampling process. We also introduce the Posterior Bridge Defect, which jointly characterizes measurement error, deviation from the flow prior, and bridge mismatch, and leads to explicit updates for clean-side anchoring and source-side re-coupling. Extensive experiments on multiple natural and medical image restoration tasks demonstrate that ReBridge-Flow effectively alleviates bridge mismatch and improves the structural consistency of restored images.
  </details>
