# 🔍 Multimodal_ST_Pathology Papers · 2026-06-25

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Modeling Local, Global, and Cross-Modal Context in Multimodal 3D MRI](https://arxiv.org/abs/2606.26894)**  `arXiv:2606.26894`  `cs.CV`  
  _Minh Duc Do, Tillmann Rheude, Noel Kronenberg, Roland Eils, Benjamin Wild_
  <details open><summary>Abstract</summary>
  Brain MRI poses a fundamental challenge for machine learning: models must learn from high-dimensional 3D data spanning multiple co-registered modalities, despite the limited sample sizes typical of neuroimaging studies relative to the diversity in anatomy, pathology, and acquisition conditions. While multimodal imaging provides complementary information critical for clinical interpretation, effectively integrating these signals remains difficult. We propose Multimodal Intra- and Cross-Context Vision Transformer (MICViT), a 3D vision transformer that explicitly models both modality-specific representations and cross-modal interactions across local and global contexts. Concretely, MICViT combines four attention mechanisms: modality-specific local and global attention for intra-modal feature learning, and cross-modal local and global attention to capture interactions between modalities. We evaluate MICViT on brain age prediction across three heterogeneous datasets (UK Biobank, n=41,404; SOOP, n=1,062; Cam-CAN, n=613) using multiple MRI modalities (e.g. T1, FLAIR, DWI, SWI). MICViT consistently outperforms state-of-the-art CNN and transformer baselines in 3D settings. Notably, it benefits more strongly from multimodal inputs, yielding larger performance gains as additional modalities are incorporated. These results demonstrate that explicitly modeling intra- and cross-modal interactions is key to unlocking the full potential of multimodal brain MRI, highlighting a promising direction for representation learning in neuroimaging.
  </details>
