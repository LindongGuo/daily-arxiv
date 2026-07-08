# 🔍 Med_Foundation_Models Papers · 2026-07-07

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Multi-Teacher Contrastive Distillation for Edge-Efficient Pathology Foundation Models](https://arxiv.org/abs/2607.05533)**  `arXiv:2607.05533`  `cs.CV`  
  _Tim Lenz, Maurice Heide, Marco Gustav, Nic G. Reitsam, Jakob Nikolas Kather_
  <details open><summary>Abstract</summary>
  Computational pathology foundation models (PFMs) have advanced whole-slide image analysis. However, their size and inference cost hinder local deployment in pathology departments. We propose MuCoDi, a pretraining framework that distills frozen tile embeddings from multiple PFMs into compact edge-oriented encoders. Instead of regressing individual teacher features, MuCoDi trains lightweight MobileOne and RepViT students with a contrastive distillation objective adapted from MoCo v3, where cached Virchow2, UNI2, and H-Optimus-1 embeddings replace momentum-encoder keys. We pretrain students on 14.3M TCGA tiles from only 11.8K WSIs and evaluate frozen encoders on 23 clinically curated downstream classification tasks. RepViT-based MuCoEdge students retain near-teacher performance while reducing model size by orders of magnitude: MuCoEdge-R2.3 and MuCoEdge-R1.5 reach 71.0% external AUROC, within 0.8 percentage points of the best teacher (Virchow2, 71.8%), while MuCoEdge-R2.3 obtains the best external F1 and the second-best AUPRC (51.8% and 53.3%). MuCoEdge-R1.0 reaches 70.9% AUROC with only 6.4M parameters and 1.12 GFLOPs. On a Raspberry Pi 5, sub-million-parameter MobileOne students achieve up to 605-fold single-tile speedup over Virchow2 while retaining 66.5% to 66.9% external AUROC, demonstrating that PFM-quality pathology representations can be moved toward practical edge deployment. Code is available atthis https URL.
  </details>
