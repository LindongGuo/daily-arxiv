# 🔍 Multimodal_ST_Pathology Papers · 2026-07-14

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Together, Then Apart: Balancing Alignment and Distinctiveness for Multimodal Survival Analysis](https://arxiv.org/abs/2511.18089)**  `arXiv:2511.18089`  `cs.CV`  
  _Wenjing Liu, Qin Ren, Wen Zhang, Yuewei Lin, Chenyu You_
  <details open><summary>Abstract</summary>
  Multimodal survival analysis aims to improve cancer prognosis using heterogeneous biomedical data, such as histopathology images and genomic profiles. A common strategy is to align representations across modalities so that shared signals can be captured. However, strong cross-modal alignment can also remove modality-specific evidence that is critical for survival prediction. In this paper, we revisit multimodal survival learning from a simple observation: effective models should first discover shared patterns across modalities, and then preserve modality-specific signals. This motivates a representation learning principle that we refer to as Together Then Apart. Based on this idea, we propose TTA, a framework that balances cross-modal alignment and representation distinctiveness. TTA first performs prototype-based alignment to capture shared survival-related structures between modalities. It then encourages modality-specific distinctiveness through an anchor-guided contrastive objective. To further account for modality imbalance and noisy correspondences, we model cross-modal interactions using unbalanced optimal transport. We evaluate the proposed approach on multiple TCGA cancer cohorts with paired histopathology and genomic data. TTA consistently improves survival prediction over recent multimodal survival models. Moreover, the learned prototype structures reveal interpretable cross-modal patterns associated with clinical outcomes.
  </details>
