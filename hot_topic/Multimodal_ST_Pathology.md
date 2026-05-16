# 🔍 Multimodal_ST_Pathology Papers · 2026-05-15

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[Beyond Instance-Level Self-Supervision in 3D Multi-Modal Medical Imaging](https://arxiv.org/abs/2605.14654)**  `arXiv:2605.14654`  `cs.CV`  
  _Tan Pan, Shuhao Mei, Yixuan Sun, Kaiyu Guo, Chen Jiang, Zhaorui Tan, et al._
  <details open><summary>Abstract</summary>
  Self-supervised pre-training methods in medical imaging typically treat each individual as an isolated instance, learning representations through augmentation-based objectives or masked reconstruction. They often do not adequately capitalize on a key characteristic of physiological features: anatomical structures maintain consistent spatial relationships across individuals (instances), such as the thalamus being medial to the basal ganglia, regardless of variations in brain size, shape, or pathology. We propose leveraging this cross-instance topological consistency as a supervisory signal. The challenge arises from the inherent variability in medical imaging, which can differ significantly across instances and modalities. To tackle this, we focus on two alignment regimes. (i) Intra-instance: with pixel-level correspondences available, a cross-modal triplet objective explicitly preserves local neighborhood topology. (ii) Inter-instance: without such supervision, we derive pseudo-correspondences to control partial neighborhood alignment and prevent topology collapse across modalities. We validate our approach across 7 downstream multi-modal tasks, achieving average improvements of 1.1% and 5.94% in segmentation and classification tasks, respectively, and demonstrating significantly better robustness when modalities are missing at test time.
  </details>

- **[DUET: Dual-Paradigm Adaptive Expert Triage with Single-cell Inductive Prior for Spatial Transcriptomics Prediction](https://arxiv.org/abs/2605.14104)**  `arXiv:2605.14104`  `cs.CV`  
  _Junchao Zhu, Ruining Deng, Junlin Guo, Tianyuan Yao, Chongyu Qu, Juming Xiong, et al._
  <details open><summary>Abstract</summary>
  Inferring spatially resolved gene expression from histology images offers a cost-effective complement to spatial transcriptomics (ST). However, existing methods reduce this task to a simple morphology-to-expression mapping, where visual similarity does not guarantee molecular consistency. Meanwhile, single-cell data has amassed rich resources far surpassing the scale of ST data, yet it remains underexplored in vision-omics modeling. Furthermore, current approaches commit to a monolithic paradigm with bottlenecks, unable to balance expressive flexibility with biological fidelity. To bridge these gaps, we propose DUET, a novel dual-paradigm framework that synergizes parametric prediction and memory-based retrieval under cellular inductive priors. DUET implements a parallel regression-retrieval paradigm, adaptively reconciling the outputs of its complementary pathways. To mitigate aleatoric vision ambiguity, we incorporate large-scale single-cell references to impose molecular states as biological constraints for faithful learning. Building upon structural refinement, we further design a lightweight adapter to dynamically assign branch preference across spatial contexts to achieve optimal performance. Extensive experiments on three public datasets across varied gene scales demonstrate that DUET achieves SOTA performance, with consistent gains contributed by each proposed component. Code is available atthis https URL
  </details>
