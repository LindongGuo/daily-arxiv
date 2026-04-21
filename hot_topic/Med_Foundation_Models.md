# 🔍 Med_Foundation_Models Papers · 2026-04-20

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[ProtoCLIP: Prototype-Aligned Latent Refinement for Robust Zero-Shot Chest X-Ray Classification](https://arxiv.org/abs/2604.18444)**  `arXiv:2604.18444`  `cs.LG` `cs.AI` `cs.CV`  
  _Florian Kittler, Sheethal Bhat, Andreas Maier_
  <details open><summary>Abstract</summary>
  Zero-shot vision-language models (VLMs) have shown promise for chest radiograph classification, but their performance is often limited by confounding label co-occurrence, long-tail class imbalance, and transfer instability under domain shift. We propose ProtoCLIP, a refinement strategy for CLIP-style VLMs that improves zero-shot discrimination through targeted data curation and distilled anchor alignment. Specifically, we construct pathology-focused training subsets with curated negative samples to reduce co-occurrence bias. We also introduce a representation-preserving distillation objective to stabilize adaptation while maintaining semantic structure and improving discrimination of clinically relevant co-occurring pathologies. Evaluated on an unseen dataset VinDr-CXR, ProtoCLIP improves AUC by 2-10 percentage points over a strong CLIP-based baseline across multiple findings. For pneumothorax specifically, ProtoCLIP achieves a state-of-the-art AUC of 0.94. These results demonstrate that anchor-guided refinement, coupled with curated supervision and controlled adaptation, can mitigate common zero-shot transfer failures in medical VLMs without requiring large-scale retraining.
  </details>

- **[Mammo-FM: Breast-specific foundational model for Integrated Mammographic Diagnosis, Prognosis, and Reporting](https://arxiv.org/abs/2512.00198)**  `arXiv:2512.00198`  `cs.CV`  
  _Shantanu Ghosh, Vedant Parthesh Joshi, Rayan Syed, Aya Kassem, Abhishek Varshney, Payel Basak, et al._
  <details open><summary>Abstract</summary>
  Breast cancer is one of the leading causes of death among women worldwide. We introduce Mammo-FM, the first foundation model specifically for mammography, pretrained on the largest and most diverse dataset to date - 140,677 patients (821,326 mammograms) across four U.S. institutions. Mammo-FM provides a unified foundation for core clinical tasks in breast imaging, including cancer diagnosis, pathology localization, structured report generation, and cancer risk prognosis within a single framework. Its alignment between images and text enables both visual and textual interpretability, improving transparency and clinical auditability, which are essential for real-world adoption. We rigorously evaluate Mammo-FM across diagnosis, prognosis, and report-generation tasks in in- and out-of-distribution datasets. Despite operating on native-resolution mammograms and using only one-third of the parameters of state-of-the-art generalist FMs, Mammo-FM consistently outperforms them across multiple public and private benchmarks. These results highlight the efficiency and value of domain-specific foundation models designed around the full spectrum of tasks within a clinical domain and emphasize the importance of rigorous, domain-aligned evaluation.
  </details>

- **[Beyond the Failures: Rethinking Foundation Models in Pathology](https://arxiv.org/abs/2510.23807)**  `arXiv:2510.23807`  `cs.AI` `cs.CV`  
  _Hamid R. Tizhoosh_
  <details open><summary>Abstract</summary>
  Despite their successes in vision and language, foundation models have stumbled in pathology, revealing low accuracy, instability, and heavy computational demands. These shortcomings stem not from tuning problems but from deeper conceptual mismatches: dense embeddings cannot represent the combinatorial richness of tissue, and current architectures inherit flaws in self-supervision, patch design, and noise-fragile pretraining. Biological complexity and limited domain innovation further widen the gap. The evidence is clear-pathology requires models explicitly designed for biological images rather than adaptations of large-scale natural-image methods whose assumptions do not hold for tissue.
  </details>
