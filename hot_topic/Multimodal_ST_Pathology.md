# 🔍 Multimodal_ST_Pathology Papers · 2026-04-13

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[SIMPLER: H&E-Informed Representation Learning for Structured Illumination Microscopy](https://arxiv.org/abs/2604.10334)**  `arXiv:2604.10334`  `cs.CV`  
  _Abu Zahid Bin Aziz, Syed Fahim Ahmed, Gnanesh Rasineni, Mei Wang, Olcaytu Hatipoglu, Marisa Ricci, et al._
  <details open><summary>Abstract</summary>
  Structured Illumination Microscopy (SIM) enables rapid, high-contrast optical sectioning of fresh tissue without staining or physical sectioning, making it promising for intraoperative and point-of-care diagnostics. Recent foundation and large-scale self-supervised models in digital pathology have demonstrated strong performance on section-based modalities such as Hematoxylin and Eosin (H&E) and immunohistochemistry (IHC). However, these approaches are predominantly trained on thin tissue sections and do not explicitly address thick-tissue fluorescence modalities such as SIM. When transferred directly to SIM, performance is constrained by substantial modality shift, and naive fine-tuning often overfits to modality-specific appearance rather than underlying histological structure. We introduce SIMPLER (Structured Illumination Microscopy-Powered Learning for Embedding Representations), a cross-modality self-supervised pretraining framework that leverages H&E as a semantic anchor to learn reusable SIM representations. H&E encodes rich cellular and glandular structure aligned with established clinical annotations, while SIM provides rapid, nondestructive imaging of fresh tissue. During pretraining, SIM and H&E are progressively aligned through adversarial, contrastive, and reconstruction-based objectives, encouraging SIM embeddings to internalize histological structure from H&E without collapsing modality-specific characteristics. A single pretrained SIMPLER encoder transfers across multiple downstream tasks, including multiple instance learning and morphological clustering, consistently outperforming SIM models trained from scratch or H&E-only pretraining. Importantly, joint alignment enhances SIM performance without degrading H&E representations, demonstrating asymmetric enrichment rather
  </details>
