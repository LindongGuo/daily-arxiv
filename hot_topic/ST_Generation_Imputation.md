# 🔍 ST_Generation_Imputation Papers · 2026-05-23

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[From Snapshots to Trajectories: Learning Single-Cell Gene Expression Dynamics via Conditional Flow Matching](https://arxiv.org/abs/2605.22340)**  `arXiv:2605.22340`  `cs.LG`  
  _Siyu Pu, Qingqing Long, Xiaohan Huang, Haotian Chen, Jiajia Wang, Meng Xiao, et al._
  <details open><summary>Abstract</summary>
  Single-cell RNA sequencing (scRNA-seq) provides high-dimensional profiles of cellular states, enabling data-driven modeling of cellular dynamics over time. In practice, time-resolved scRNA-seq is collected at only a few discrete time points as unpaired snapshot populations, leaving substantial temporal gaps. This motivates trajectory inference at unmeasured time points. Existing methods mainly follow two directions, optimal-transport (OT) alignment provides distribution-level matching between observed snapshots, while continuous-time generative models support forecasting via learned dynamics. However, two challenges remain: (i) unpaired snapshots render local transitions between adjacent time points ambiguous, leading to unstable supervision; and (ii) long-horizon prediction relies on repeated integration, where small modeling errors compound and cause distribution drift. To address these challenges, we propose single-cell Flow Matching (scFM), a latent generative framework based on coupling-conditioned flow matching. First, we compute entropically regularized OT couplings between adjacent snapshots and use them to construct soft, weighted flow-matching targets for learning time-dependent velocity fields. Second, we learn bidirectional velocity fields and leverage their consistency to refine couplings and improve temporal coherence under sparse supervision. Third, we introduce distribution-level alignment and latent dynamic regularization to anchor long rollouts and mitigate drift. Experiments on real-world time-series scRNA-seq datasets show that scFM consistently improves distributional prediction performance for both temporal interpolation and extrapolation. Moreover, scFM yields more accurate trajectory reconstruction and temporally coherent visualizations where intermediate time points are absent, indicating a more faithful recovery of underlying temporal gene expression dynamics.
  </details>

- **[Uncertainty-Aware Distribution-to-Distribution Flow Matching for Scientific Imaging](https://arxiv.org/abs/2603.21717)**  `arXiv:2603.21717`  `cs.LG`  
  _Dongxia Wu, Yuhui Zhang, Serena Yeung-Levy, Emma Lundberg, Emily B. Fox_
  <details open><summary>Abstract</summary>
  Distribution-to-distribution generative models support scientific imaging tasks ranging from modeling cellular perturbation responses to translating medical images across conditions. Trustworthy generation requires reliability, or generalization across labs, devices, and experimental conditions, and accountability, or detecting out-of-distribution cases where predictions may be unreliable. We leverage Stochastic Flow Matching (SFM), a marginal-preserving stochastic extension of flow matching for improved generalization under distribution shift. SFM augments deterministic flows with a diffusion term together with a learned score-based drift correction, retaining the learned transport marginals while modeling conditional variability. Building on this SFM framework, we introduce Bayesian Stochastic Flow Matching (BSFM) as a companion uncertainty quantification mechanism and develop AVUQ (Antithetic Variance-reduction Uncertainty Quantification) to approximately estimate epistemic and aleatoric uncertainty via sample-efficient antithetic sampling with approximate posterior inference. We further use AVUQ to yield anomaly scores for unreliable generation detection. Experiments on cellular imaging (BBBC021, JUMP) and brain fMRI (Theory of Mind) across diverse unseen scenarios show that SFM improves generalization while AVUQ provides effective uncertainty-based anomaly scores under practical sampling budgets.
  </details>

- **[Virtual 3D H&E Staining from Phase-contrast Back-illumination Interference Tomography](https://arxiv.org/abs/2605.22000)**  `arXiv:2605.22000`  `cs.CV` `cs.AI`  
  _Anthony Song, Boyan Zhou, Mayank Golhar, Marisa Morakis, Alex Baras, Nicholas Durr_
  <details open><summary>Abstract</summary>
  Three-dimensional (3D) histopathology of unprocessed tissues has the potential to transform disease management by enabling volumetric characterization of tissue microarchitecture and in-vivo assessment. Back-illumination Interference Tomography (BIT) is a new phase microscopy technology that provides rapid, non-destructive volumetric imaging of unprocessed tissues. However, translating BIT volumes into clinically interpretable H&E images remains challenging, particularly due to shift-variant contrast and the absence of quantitative validation benchmarks. We introduce HistoBIT3D, the first voxel-wise paired BIT and fluorescence-labeled nuclei dataset, enabling quantitative evaluation of structural preservation in unsupervised virtual staining against ground-truth nuclear distributions. Using this dataset, we present a novel virtual staining framework that translates BIT volumes with shift-variant contrast into realistic H&E volumes by leveraging bidirectional multiscale content consistency and cross-domain style reuse to enhance structural fidelity and perceptual realism. Our method achieves state-of-the-art realism metrics while significantly improving 3D nuclei segmentation accuracy and boundary preservation under zero-shot Cellpose evaluation. Together, these contributions establish a quantitatively validated, structurally faithful, and scalable pipeline for 3D virtual H&E staining, advancing the paradigm of slide-free, volumetric computational histopathology. Our data and code are available at:this https URL.
  </details>
