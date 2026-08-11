# 🔍 ST_Generation_Imputation Papers · 2026-08-10

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Uncertainty in a Single Pass: A Closed-Form Identity for One-Step Flow Matching](https://arxiv.org/abs/2605.00941)**  `arXiv:2605.00941`  `cs.LG` `cs.CV`  
  _Jiarui Xing, Song Wang, Jian Wang_
  <details open><summary>Abstract</summary>
  Flow matching provides a highly effective framework for generative modeling, yet estimating the uncertainty of its generated samples remains a fundamental challenge. Existing methods rely on auxiliary variance heads, model ensembles, or iterative covariance propagation, which invariably introduce accumulated errors and structural interference along the noise-to-image trajectory. We resolve these limitations by adapting Tweedie's formula to the linear flow matching interpolant, yielding an exact, closed-form identity for the posterior covariance. Because this identity relies exclusively on the divergence of the learned velocity field, it can be evaluated post hoc on pretrained models without any architectural modifications. This analytical formulation proves exceptionally powerful for single-step generative frameworks. By computing the end-to-end posterior covariance in one forward pass, our approach completely bypasses the compounding errors inherent to sequential integration. This mechanism fundamentally enhances robustness, providing highly accurate and stable uncertainty estimates while preventing the numerical degradation typical of multi-step approximations. We validate our framework across benchmark datasets, including CIFAR-10 and real brain MRI scans. The resulting divergence-based uncertainty maps are highly interpretable and tightly correlated with empirical reconstruction errors. Crucially, in medical imaging, this precise localization of structural ambiguity provides essential decision support for high-stakes clinical tasks such as tumor boundary delineation and neurosurgical planning.
  </details>

- **[Compositional Cross-Modality Translation via Whole-Volume Multitask Latent Flow Matching](https://arxiv.org/abs/2608.08135)**  `arXiv:2608.08135`  `cs.CV` `cs.AI`  
  _Daniele Molino, Alessio Zoboli, Camillo Maria Caruso, Valerio Guarrasi, Paolo Soda_
  <details open><summary>Abstract</summary>
  Cross-modality medical image translation can reduce the burden of multi-modal acquisitions, yet the field remains constrained by two coupled limitations: methods operate on 2D slices or 3D patches rather than whole volumes, and train a separate model for each translation task. Both stem from a single cause, the absence of a sufficiently strong volumetric prior, which forces generative models to learn anatomical appearance and cross-modality mapping simultaneously, an ill-posed problem at the scale of available paired datasets. We propose to decouple these objectives. A large-scale pretrained 3D variational autoencoder provides a compact latent representation of volumetric appearance, reducing translation to a conditional flow-matching problem. This compression makes whole-volume processing tractable, while a resolution-aware sampling strategy preserves native anatomical scale. We train a single model jointly across inter-modality (MRI$\to$CT, CBCT$\to$CT) and intra-modality (MRI$\to$MRI) tasks over three multi-center datasets. Across all tasks, whole-volume processing outperforms its patch-based counterpart, and the multi-task model matches task-specific baselines while replacing $N$ networks with one. Crucially, joint training unlocks capabilities inaccessible to task-specific approaches: zero-shot generalization to anatomical regions unseen during training, within 0.15 SSIM of the fully supervised model, and compositional cross-dataset translation along paths never directly supervised. These results suggest that combining a strong volumetric prior with multitask training is a scalable route toward synthesis systems that generalize beyond their training distribution. Code is available atthis https URL.
  </details>
