# 🔍 ST_Generation_Imputation Papers · 2026-07-13

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[FlowPET: Physics-Informed Symplectic Flow Matching for Low-Count PET Reconstruction](https://arxiv.org/abs/2607.11104)**  `arXiv:2607.11104`  `cs.CV`  
  _Zheng Zhang, Hao Tang, Yingying Hu, Zhanli Hu, Jing Qin_
  <details open><summary>Abstract</summary>
  Low-count Positron Emission Tomography (PET) reconstruction is severely hindered by the dissipative nature of prevailing generative models, where the inherent phase-space contraction leads to the numerical extinction (``wash-out'') of weak but diagnostically critical lesion signals. To overcome this geometric limitation, we propose \textbf{FlowPET}, a physics-informed framework that reformulates reconstruction as volume-preserving transport in a symplectic phase space. By parameterizing the posterior dynamics via a Separable Hamiltonian System, our approach guarantees a divergence-free vector field by construction, theoretically immunizing weak signals against probability mass collapse. To steer this conservative flow, we introduce conjugate boundary conditions based on the Range-Null space decomposition of the PET operator; this strictly enforces data consistency in the range space while confining stochastic uncertainty injection to the unobserved null space. We train the model via symplectic flow matching and perform inference using a symplectic leapfrog integrator. Extensive experiments on BrainWeb, clinical pediatric, and UDPET datasets demonstrate that \textbf{FlowPET} not only surpasses state-of-the-art deterministic and stochastic baselines in SSIM and PSNR but, more crucially, exhibits superior recovery of low-contrast lesions. The results confirm that imposing Hamiltonian structural constraints offers a robust geometric safeguard for medical inverse problems in high-noise regimes.
  </details>
