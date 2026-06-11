# 🔍 ST_Generation_Imputation Papers · 2026-06-10

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[SheafStain: Sheaf-Theoretic Schrödinger Bridge for Spatially and Biologically Coherent Virtual Staining](https://arxiv.org/abs/2606.11846)**  `arXiv:2606.11846`  `cs.CV`  
  _Hyeongyeol Lim, Hongjun Yoon, Eunjin Jang, Daeky Jeong, Won June Cho, Hwamin Lee_
  <details open><summary>Abstract</summary>
  Current virtual staining approaches offer the potential for time- and cost-efficient biomarker quantification in cancer diagnostics and prognostics. However, patch-wise inference for gigapixel whole slide images (WSIs) fails to maintain spatial continuity, yielding artifacts that cause catastrophic mismatches with ground-truth images. Although pathology Vision Foundation Models (VFMs) offer rich representations, their self-attention causes varying global contexts to produce inconsistent embeddings for the same physical region. We formalize and validate this ``context contamination'' as a sheaf-theoretic problem where these embeddings form a presheaf that violates the gluing axiom. To address this, we propose SheafStain, a new approach that reinterprets VFM features as sheaf-like sections for spatially and biologically coherent virtual staining. Specifically, SheafStain integrates class and patch tokens into a Schrödinger Bridge framework as sheaf-like sections. While the class token anchors biological consistency, patch tokens form a per-position spatial map. A backbone co-pretrained on Hematoxylin \& Eosin (H\&E) and Immunohistochemistry (IHC) yields non-degenerate cross-stain stalks, so a single VFM feature space supervises both input conditioning and output stain alignment. Departing from prior work that evaluates on isolated $256 \times 256$ patches and either random-crops or resizes the $1024 \times 1024$ ground truth, we translate at $256 \times 256$ and evaluate on the stitched $1024 \times 1024$ outputs across HER2, ER, PR, and Ki-67. SheafStain demonstrates promising results against six prior methods while mitigating patch-boundary stitching artifacts. Code will soon be released.
  </details>
