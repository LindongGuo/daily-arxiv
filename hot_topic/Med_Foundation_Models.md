# 🔍 Med_Foundation_Models Papers · 2026-09-30

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[SCALE: Synthetic Calibration via Agreement Labeling in Embedding Space](https://arxiv.org/abs/2609.38705)**  `arXiv:2609.38705`  `cs.CV`  
  _Wenjun Liu, Saeed Hassanpour_
  <details open><summary>Abstract</summary>
  Foundation models for computational pathology are usually evaluated using AUC and accuracy, while calibration is often left untested. This matters because a model can be accurate on average but still assign overly confident probabilities to cases that are difficult even for pathologists. We study calibration across eight pathology foundation models. Using pathologist agreement as a measure of diagnostic difficulty, we find that calibration error is consistently higher on low-agreement cases than on high-agreement cases. This pattern is not apparent from aggregate expected calibration error (ECE) alone. We then propose synthetic agreement calibration, a method for improving calibration without collecting multi-annotator labels. Given a trained linear probe, we select high-confidence embeddings as class anchors and interpolate between anchors from opposite classes. The interpolation weights encode a continuous notion of diagnostic ambiguity, which we use as a synthetic agreement signal to retrain the probe with agreement-aware label smoothing. On MHIST, which includes annotations from seven pathologists, synthetic agreement calibration recovers most of the calibration improvement obtained by label smoothing based on real pathologist agreement, while substantially reducing low-agreement ECE relative to the uncalibrated baseline. Discrimination metrics are preserved. On PatchCamelyon and BreakHis, public histopathology datasets without multi-annotator labels, the method improves calibration across the evaluated foundation models, whereas annotator-dependent approaches cannot be used without additional expert annotation.
  </details>

- **[SheafStain: Sheaf-Theoretic Schrödinger Bridge for Spatially and Biologically Coherent Virtual Staining](https://arxiv.org/abs/2606.11846)**  `arXiv:2606.11846`  `cs.CV`  
  _Hyeongyeol Lim, Hongjun Yoon, Eunjin Jang, Daeky Jeong, Won June Cho, Hwamin Lee_
  <details open><summary>Abstract</summary>
  Current virtual staining approaches offer the potential for time- and cost-efficient biomarker quantification in cancer diagnostics and prognostics. However, patch-wise inference for gigapixel whole-slide images (WSIs) fails to maintain spatial continuity, yielding artifacts that cause catastrophic mismatches with ground-truth images. Although pathology Vision Foundation Models (VFMs) offer rich representations, their self-attention causes varying global contexts to produce inconsistent embeddings for the same physical region. We formalize and validate this ``context contamination'' as a sheaf-theoretic problem where these embeddings form a presheaf whose sections disagree on overlaps, so no global section restricts to them. To address this, we propose SheafStain, a new approach that reinterprets VFM features as sheaf-like sections for spatially and biologically coherent virtual staining. Specifically, SheafStain integrates class and patch tokens into a Schrödinger Bridge framework as sheaf-like sections. While the class token anchors biological consistency, patch tokens form a per-position spatial map. An encoder co-pretrained on Hematoxylin \& Eosin (H\&E) and Immunohistochemistry (IHC) yields cross-stain sections, so a single VFM feature space supervises both input conditioning and output stain alignment. Departing from prior work that evaluates on isolated $256 \times 256$ patches and either random-crops or resizes the $1024 \times 1024$ ground truth, we translate at $256 \times 256$ and evaluate on the stitched $1024 \times 1024$ outputs across HER2, ER, PR, and Ki-67. SheafStain demonstrates promising results against six prior methods while mitigating patch-boundary stitching artifacts. Code is available atthis https URL.
  </details>
