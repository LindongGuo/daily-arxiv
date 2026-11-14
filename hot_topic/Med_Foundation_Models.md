# 🔍 Med_Foundation_Models Papers · 2026-11-13

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Beyond Instance-Level Self-Supervision in 3D Multi-Modal Medical Imaging](https://arxiv.org/abs/2605.14654)**  `arXiv:2605.14654`  `cs.CV`  
  _Tan Pan, Shuhao Mei, Yixuan Sun, Kaiyu Guo, Chen Jiang, Zhaorui Tan, et al._
  <details open><summary>Abstract</summary>
  Self-supervised pre-training methods in medical imaging typically treat each individual as an isolated instance, learning representations through augmentation-based objectives or masked reconstruction. They often do not adequately capitalize on a key characteristic of physiological features: anatomical structures maintain consistent spatial relationships across individuals (instances), such as the thalamus being medial to the basal ganglia, regardless of variations in brain size, shape, or pathology. We propose leveraging this cross-instance topological consistency as a supervisory signal. The challenge arises from the inherent variability in medical imaging, which can differ significantly across instances and modalities. To tackle this, we focus on two alignment regimes. (i) Intra-instance: with pixel-level correspondences available, a cross-modal triplet objective explicitly preserves local neighborhood topology. (ii) Inter-instance: without such supervision, we derive pseudo-correspondences to control partial neighborhood alignment and prevent topology collapse across modalities. We validate our approach across 7 downstream multi-modal tasks, achieving average improvements of 1.1% and 5.94% in segmentation and classification tasks, respectively, and demonstrating significantly better robustness when modalities are missing at test time.
  </details>

- **[Do Pathology Foundation Models Encode Disease Progression? A Pseudotime Analysis of Visual Representations](https://arxiv.org/abs/2601.21334)**  `arXiv:2601.21334`  `cs.CV`  
  _Pritika Vig, Ren-Chin Wu, William Lotter_
  <details open><summary>Abstract</summary>
  Vision foundation models trained on discretely sampled images achieve strong performance on classification benchmarks, yet whether their representations encode the continuous processes underlying their training data remains unclear. This question is especially pertinent in computational pathology, where we posit that models whose latent representations implicitly capture ordinal disease progression may better reflect underlying biology, support more robust generalization, and enable quantitative analyses of features associated with disease transitions. Using diffusion pseudotime, a method developed to infer developmental trajectories from single-cell transcriptomics, we probe whether foundation models organize disease states along coherent progression directions in representation space. Across four cancer progressions and six models, we find that all pathology-specific models recover trajectory orderings significantly exceeding null baselines, with pathology vision-only models achieving the highest average fidelities. Model rankings by trajectory fidelity on reference diseases predict few-shot classification performance on held-out diseases ($\rho = 0.91$), and exploratory analysis shows cell-type composition varies along inferred trajectories in patterns consistent with known stromal remodeling. Together, these results suggest that vision foundation models can implicitly learn to represent continuous processes from independent static observations, and that trajectory fidelity provides a complementary measure of representation quality beyond downstream performance. While demonstrated in pathology, this framework could be applied to other domains where continuous processes are observed through static snapshots.
  </details>
