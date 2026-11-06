# 🔍 Multimodal_ST_Pathology Papers · 2026-11-05

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Preserving DEG Rankings for Gene Discovery in Histology-Based Spatial Gene Expression Prediction](https://arxiv.org/abs/2609.33928)**  `arXiv:2609.33928`  `cs.CV`  
  _Kaito Shiku, Kazuya Nishimura, Yasuhiro Kojima, Ryoma Bise_
  <details open><summary>Abstract</summary>
  Predicting spatial gene expression from histology images could scale spatial transcriptomics (ST) to image-only cohorts, but conventional histology-based ST prediction is trained and evaluated mainly by per-gene spatial-profile reconstruction. This objective is misaligned with a key downstream use of ST: differentially expressed gene (DEG) discovery, where genes are ranked for a biological or morphology-defined contrast by evidence of between-group expression differences. We formulate image-based differential expression ranking (IDER), which asks whether predicted expression profiles preserve the contrast-specific ranked gene list obtained from measured profiles. IDER compares gene rankings induced by differential-expression statistics, rather than raw expression magnitudes or per-gene spatial correlations. We further introduce a differentiable IDER objective that aligns these statistics across genes and can be trained with morphology-derived proxy contrasts without predefined biological group labels. Experiments on public ST datasets show improved DEG-ranking agreement and pathway-enrichment overlap over conventional reconstruction objectives, including morphology-derived and pathologist-annotated tissue-region evaluations.
  </details>
