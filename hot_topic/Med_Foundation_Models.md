# 🔍 Med_Foundation_Models Papers · 2026-06-09

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[From Patches to Patients: A study of the tile-to-slide performance transferability in Digital Pathology](https://arxiv.org/abs/2606.10778)**  `arXiv:2606.10778`  `cs.CV`  
  _Sofiène Boutaj, Leo Fillioux, Maria Vakalopoulou, Stergios Christodoulidis, Pierre Marza_
  <details open><summary>Abstract</summary>
  Foundation Models (FMs) have recently redefined the state-of-the-art in histopathology by providing robust representations for whole-slide image (WSI) analysis. However, selecting the optimal foundation model (FM) for a specific clinical cohort currently requires multiple preprocessing steps, followed by computationally expensive feature extraction and the training of a Multiple Instance Learning (MIL) aggregator for every model. In this work, we investigate whether efficient tile-level linear probing can serve as a reliable proxy for slide-level performance, reducing the need to run full slide-level pipelines for every candidate encoder. We benchmark 19 state-of-the-art FMs on 42 slide-level and 16 tile-level tasks, comparing tile probing metrics against slide-level outcomes using ABMIL and Mean Pooling aggregations. We observe a high correlation between tile and slide performance across varying task difficulties, indicating that encoder representation quality is the primary determinant of WSI success. Sensitivity analyses show that transferability is stable across models and is more influenced by cohort sizes and numbers of tiles per slide than by average task difficulty. We also measure the agreement in best performing models between tile and slide-level tasks, showing tile benchmarks reliably shortlist strong candidates. Overall, our study indicates that tile-level benchmarking provides an efficient and practical first step for narrowing down candidate models, while slide-level evaluation remains essential for final validation on clinical tasks.
  </details>

- **[Enabling Progressive Whole-slide Image Analysis with Multi-scale Pyramidal Network](https://arxiv.org/abs/2602.01951)**  `arXiv:2602.01951`  `cs.CV`  
  _Shuyang Wu, Yifu Qiu, Ines P Nearchou, Sandrine Prost, Jonathan A Fallowfield, Hakan Bilen, et al._
  <details open><summary>Abstract</summary>
  Multiple-instance Learning (MIL) is commonly used for computational pathology (CPath), where multi-scale features are essential for capturing both fine cellular details and broad tissue architecture. However, existing multi-scale MIL approaches typically rely on the inflexible multi-magnification inputs or the computationally expensive architectures. As pre-trained foundation models (FMs) become the trend for feature extraction and boost lightweight models, we rethink and explore a more efficient multi-scale MIL method. In this paper, we propose the Multi-scale Pyramidal Network (MSPN), a plug-and-play module for attention-based MIL. MSPN introduces progressive multi-scale whole-slide image analysis using only a single high-magnification input. It consists of (1) grid-based remapping that aggregates high-magnification features to derive spatially-aware coarse feature maps, and (2) the Coarse Guidance Network (CGN) that learns coarse contexts. We benchmark MSPN as an add-on module to 4 attention-based frameworks on 5 clinically relevant tasks with 2 foundation models, and a pre-trained MIL framework. Our results demonstrate that MSPN consistently improves MIL across the compared configurations and tasks, while being lightweight and easy-to-use.
  </details>
