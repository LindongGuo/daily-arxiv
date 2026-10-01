# 🔍 ST_Generation_Imputation Papers · 2026-09-30

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
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
  Current virtual staining approaches offer the potential for time- and cost-efficient biomarker quantification in cancer diagnostics and prognostics. However, patch-wise inference for gigapixel whole-slide images (WSIs) fails to maintain spatial continuity, yielding artifacts that cause catastrophic mismatches with ground-truth images. Although pathology Vision Foundation Models (VFMs) offer rich representations, their self-attention causes varying global contexts to produce inconsistent embeddings for the same physical region. We formalize and validate this ``context contamination'' as a sheaf-theoretic problem where these embeddings form a presheaf whose sections disagree on overlaps, so no global section restricts to them. To address this, we propose SheafStain, a new approach that reinterprets VFM features as sheaf-like sections for spatially and biologically coherent virtual staining. Specifically, SheafStain integrates class and patch tokens into a Schrödinger Bridge framework as sheaf-like sections. While the class token anchors biological consistency, patch tokens form a per-position spatial map. An encoder co-pretrained on Hematoxylin \& Eosin (H\&E) and Immunohistochemistry (IHC) yields cross-stain sections, so a single VFM feature space supervises both input conditioning and output stain alignment. Departing from prior work that evaluates on isolated $256 \times 256$ patches and either random-crops or resizes the $1024 \times 1024$ ground truth, we translate at $256 \times 256$ and evaluate on the stitched $1024 \times 1024$ outputs across HER2, ER, PR, and Ki-67. SheafStain demonstrates promising results against six prior methods while mitigating patch-boundary stitching artifacts. Code is available atthis https URL.
  </details>

- **[GATE-ST: Gene-Aware Text-image Encoder for Spatial Transcriptomics](https://arxiv.org/abs/2609.38690)**  `arXiv:2609.38690`  `cs.AI`  
  _Lucas Ni, Jian Luo, Wentao Huang, Chao Chen_
  <details open><summary>Abstract</summary>
  Spatial transcriptomics enables spatially resolved gene expression analysis from slide-level images while preserving morphological features, providing valuable information for studying disease mechanisms and developing treatments. However, spatial gene expression profiling typically requires expensive and time-consuming tests. While existing image-based prediction optimizations mostly revolve around including positional embeddings and further image-based changes, text-based optimizations remain relatively unexplored. We present GATE-ST, which incorporates text-based inputs into image-based spatial gene expression predictions. With this approach, generated text descriptions of genes are utilized to better spatial transcriptomics prediction results. Gene summaries are put through a text encoder, generating embeddings that integrate with image embeddings through cross-attention layers to align with morphological features. We demonstrate the effectiveness of such text inputs by benchmarking performance against random gene embeddings and multiple other image-text fusion architectures, and show that GATE-ST outperforms these alternatives. Our results demonstrate the effectiveness of GATE-ST in pathology imaging, which may greatly reduce the time and cost of accurate spatial transcriptomic predictions, proving the potential of text-guided spatial gene expression prediction.
  </details>
