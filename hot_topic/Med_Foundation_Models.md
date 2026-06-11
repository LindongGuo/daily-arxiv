# 🔍 Med_Foundation_Models Papers · 2026-06-10

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Atlas H&E-TME: Scalable AI-Based Tissue Profiling at Expert Pathologist-Level Accuracy](https://arxiv.org/abs/2606.12346)**  `arXiv:2606.12346`  `cs.CV` `cs.AI` `cs.LG`  
  _Kai Standvoss, Miriam Hägele, Rosemarie Krupar, Julika Ribbat-Idel, Jennifer Altschüler, Gerrit Erdmann, et al._
  <details open><summary>Abstract</summary>
  Hematoxylin and eosin (H&E) staining is the cornerstone of histopathology, yet scalable, quantitative analysis of H&E whole-slide images (WSIs) remains a central challenge in computational pathology. We present Atlas H&E-TME, an AI-based system built on the Atlas family of pathology foundation models that predicts tissue quality, tissue region, and cell type labels across multiple cancer types, yielding over 4,500 quantitative readouts per slide at cell-level resolution. A key challenge to validating such systems is overcoming morphological ambiguity inherent to H&E-only ground truth and the limited scalability of more informed references drawing on modalities such as immunohistochemistry (IHC). We address this with a dual validation framework combining biologically grounded depth with technical and morphological breadth. For depth, we propose an IHC-informed multi-pathologist consensus protocol that substantially improves inter-rater agreement over conventional H&E-only annotation. This yields a molecularly grounded reference against which we compare Atlas H&E-TME and pathologists working from H&E alone. For breadth, we benchmark Atlas H&E-TME on over 200,000 high-confidence H&E-only pathologist annotations across 1,500+ cases spanning eight cancer types and their most common metastatic sites, with subtypes covering >90% of clinical cases per cancer type, drawn from 25+ sources and 8+ scanner models. Benchmarked against the IHC-informed consensus, Atlas H&E-TME matches or exceeds pathologist H&E-only performance and generalizes consistently and robustly across this broad morphological and technical scope. In doing so, Atlas H&E-TME turns the H&E slide -- the most ubiquitous data in pathology -- into a scalable, quantitative window into the tumor and its microenvironment, laying a foundation for the next generation of tissue-based biomarkers in translational and clinical research.
  </details>

- **[SheafStain: Sheaf-Theoretic Schrödinger Bridge for Spatially and Biologically Coherent Virtual Staining](https://arxiv.org/abs/2606.11846)**  `arXiv:2606.11846`  `cs.CV`  
  _Hyeongyeol Lim, Hongjun Yoon, Eunjin Jang, Daeky Jeong, Won June Cho, Hwamin Lee_
  <details open><summary>Abstract</summary>
  Current virtual staining approaches offer the potential for time- and cost-efficient biomarker quantification in cancer diagnostics and prognostics. However, patch-wise inference for gigapixel whole slide images (WSIs) fails to maintain spatial continuity, yielding artifacts that cause catastrophic mismatches with ground-truth images. Although pathology Vision Foundation Models (VFMs) offer rich representations, their self-attention causes varying global contexts to produce inconsistent embeddings for the same physical region. We formalize and validate this ``context contamination'' as a sheaf-theoretic problem where these embeddings form a presheaf that violates the gluing axiom. To address this, we propose SheafStain, a new approach that reinterprets VFM features as sheaf-like sections for spatially and biologically coherent virtual staining. Specifically, SheafStain integrates class and patch tokens into a Schrödinger Bridge framework as sheaf-like sections. While the class token anchors biological consistency, patch tokens form a per-position spatial map. A backbone co-pretrained on Hematoxylin \& Eosin (H\&E) and Immunohistochemistry (IHC) yields non-degenerate cross-stain stalks, so a single VFM feature space supervises both input conditioning and output stain alignment. Departing from prior work that evaluates on isolated $256 \times 256$ patches and either random-crops or resizes the $1024 \times 1024$ ground truth, we translate at $256 \times 256$ and evaluate on the stitched $1024 \times 1024$ outputs across HER2, ER, PR, and Ki-67. SheafStain demonstrates promising results against six prior methods while mitigating patch-boundary stitching artifacts. Code will soon be released.
  </details>
