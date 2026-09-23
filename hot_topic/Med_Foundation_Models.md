# 🔍 Med_Foundation_Models Papers · 2026-09-22

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Foundation model embeddings capture pre-diagnostic changes on screening mammograms](https://arxiv.org/abs/2609.26605)**  `arXiv:2609.26605`  `cs.CV` `cs.LG`  
  _Kalina P. Slavkova, Eric Brattain, Aditya Gowd, Akash Pattnaik, Jean-Benoit Delbrouck, Matthew Morgan, et al._
  <details open><summary>Abstract</summary>
  Foundation model embeddings of screening mammograms may encode pre-diagnostic tissue change without task-specific adaptation. We tested whether embeddings move faster along a data-derived "cancer direction" in women later biopsied for cancer than in matched screen-negative controls, and whether this depends on pretraining domain. We studied 1,773 biopsied women (785 malignant, 988 biopsy-negative) and 1,773 matched controls, each with at least two annual screening exams before their index exam. An identical pipeline was applied to four 2D models: Mammo-CLIP (MC, out-of-distribution mammography), HOPPR (in-distribution mammography), MedImageInsight (MII, general medical imaging), and BiomedCLIP (biomedical vision-language pretraining on literature figures). Breast-level embeddings quantified longitudinal movement along the cancer direction. We compared cases and controls using a between-patient design with complementary mixed-effects analysis, and biopsied versus healthy contralateral breasts within patients. Under matched modality in MII embedding space, malignant cases drifted significantly faster than controls in the first two screening intervals preceding the index exam; biopsy-negative cases showed significance only in the first. MC differences were significant in the first interval for both biopsy groups. Within-patient comparisons showed a broadly similar pattern, with MC significance extending to the second interval in both groups and HOPPR showing significance at interval 1. BiomedCLIP showed no significant differences in either design or biopsy group. Overall, directional embedding velocity emerges as a property of clinically grounded rather than general biomedical pretraining, showing that foundation model embeddings can encode pre-diagnostic mammographic change without task-specific adaptation.
  </details>

- **[Cellular-Communication-Level Interpretability for Pathology Foundation Models via Graph Distillation on Microenvironment](https://arxiv.org/abs/2609.26073)**  `arXiv:2609.26073`  `cs.CV`  
  _Yuxiang Xiao, Zhiwei Chen, Dan Dai, Wei Li, Tianyang Zhang, Yakun Ju, et al._
  <details open><summary>Abstract</summary>
  Pathology foundation models (PFMs) provide strong tile-level representations but remain difficult to interpret at the cellular and microenvironmental scales that underpin clinical reasoning. We introduce Graph-Interpreter (G-Interp), a graph-distillation framework that equips a frozen PFM teacher with a cellular-communication-level "plug-in" interpreter, without modifying the teacher. For each tile, we segment cells as graph nodes and construct a microenvironment graph based on spatial adjacency. Graph neural network (GNN) students distil the PFM embedding, whilst learning attention-based message passing that yields node- and edge-level importances. We interpret these importances as cell-cell communication evidence, providing fine-grained explanations of how PFMs encode microenvironmental context. To stabilise distillation when graph abstraction is imperfect, we employ a lightweight auxiliary student to supply complementary visual cues and condition graph message passing, while keeping the primary interpretability signal graph-derived. We evaluate explanation faithfulness by mapping graph-selected evidence back to the image using instance masks and measuring teacher sensitivity under targeted vs non-target occlusions. Across multiple histopathology tasks, G-Interp produces highly scalable, microenvironment-aware explanations, while maintaining competitive predictive performance.
  </details>
