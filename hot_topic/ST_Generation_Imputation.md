# 🔍 ST_Generation_Imputation Papers · 2026-05-12

[![Total Papers](https://img.shields.io/badge/Papers-4-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[MoLF: Mixture-of-Latent-Flow for Pan-Cancer Spatial Gene Expression Prediction from Histology](https://arxiv.org/abs/2602.02282)**  `arXiv:2602.02282`  `cs.LG`  
  _Susu Hu, Stefanie Speidel_
  <details open><summary>Abstract</summary>
  Inferring spatial transcriptomics (ST) from histology enables scalable histogenomic profiling, yet current methods are largely restricted to single-tissue models. This fragmentation fails to leverage biological principles shared across cancer types and hinders application to data-scarce scenarios. While pan-cancer training offers a solution, the resulting heterogeneity challenges monolithic architectures. To bridge this gap, we introduce MoLF (Mixture-of-Latent-Flow), a generative model for pan-cancer histogenomic prediction. MoLF leverages a conditional Flow Matching objective to map noise to the gene latent manifold, parameterized by a Mixture-of-Experts (MoE) velocity field. By dynamically routing inputs to specialized sub-networks, this architecture effectively decouples the optimization of diverse tissue patterns. Our experiments demonstrate that MoLF establishes a new state-of-the-art, consistently outperforming both specialized and foundation model baselines on pan-cancer benchmarks. Furthermore, MoLF exhibits zero-shot generalization to cross-species data, suggesting it captures fundamental, conserved histo-molecular mechanisms.
  </details>

- **[RNA-FM: Flow-Matching Generative Model for Genome-wide RNA-Seq Prediction](https://arxiv.org/abs/2605.11622)**  `arXiv:2605.11622`  `cs.CV`  
  _Yaxuan Song, Jianan Fan, Tianyi Wang, Qiuyue Hu, Hang Chang, Heng Huang, et al._
  <details open><summary>Abstract</summary>
  Histopathology whole-slide images (WSIs) are routinely acquired in clinical practice and contain rich tissue morphology but lack direct molecular architecture and functional programs defining pathological states, whereas RNA sequencing (RNA-seq) provides genome-wide transcriptional profiles at substantial cost, thereby motivating WSI-based genome-wide transcriptomic prediction. Existing approaches for predicting gene expression from WSIs predominantly rely on deterministic regression with one-to-one mapping, limiting their ability to capture biological heterogeneity and predictive uncertainty. We propose RNA-FM, a flow-matching generative framework for genome-wide bulk RNA-seq prediction from WSIs. RNA-FM formulates transcriptomic prediction as a continuous-time conditional transport problem, learning a velocity field that maps a simple prior to the target gene expression distribution conditioned on morphologies. By integrating pathway-level structure, RNA-FM enables scalable and biologically interpretable genome-wide gene expression imputation. Extensive experiments demonstrate that RNA-FM consistently outperforms state-of-the-art approaches while maintaining biological meaningfulness. Code is available atthis https URL.
  </details>

- **[FlowDIS: Language-Guided Dichotomous Image Segmentation with Flow Matching](https://arxiv.org/abs/2605.05077)**  `arXiv:2605.05077`  `cs.CV`  
  _Andranik Sargsyan, Shant Navasardyan_
  <details open><summary>Abstract</summary>
  Accurate image segmentation is essential for modern computer vision applications such as image editing, autonomous driving, and medical image analysis. In recent years, Dichotomous Image Segmentation (DIS) has become a standard task for training and evaluating highly accurate segmentation models. Existing DIS approaches often fail to preserve fine-grained details or fully capture the semantic structure of the foreground. To address these challenges, we present FlowDIS, a novel dichotomous image segmentation method built on the flow matching framework, which learns a time-dependent vector field to transport the image distribution to the corresponding mask distribution, optionally conditioned on a text prompt. Moreover, with our Position-Aware Instance Pairing (PAIP) training strategy, FlowDIS offers strong controllability through text prompts, enabling precise, pixel-level object segmentation. Extensive experiments demonstrate that our method significantly outperforms state-of-the-art approaches both with and without language guidance. Compared with the best prior DIS method, FlowDIS achieves a 5.5% higher $F_{\beta}^{\omega}$ measure and 43% lower MAE ($\mathcal{M}$) on the DIS-TE test set. The code is available at:this https URL
  </details>

- **[GRASP: Guided Residual Adapters with Sample-wise Partitioning](https://arxiv.org/abs/2512.01675)**  `arXiv:2512.01675`  `cs.CV`  
  _Felix Nützel, Mischa Dombrowski, Bernhard Kainz_
  <details open><summary>Abstract</summary>
  Text-to-image flow matching transformers degrade sharply in long-tail settings: tail-class outputs collapse in fidelity and diversity, limiting their value as synthetic augmentation for rare conditions. We trace this to low head-versus-tail gradient alignment during fine-tuning, an optimization-level pathology that conditioning- and sampling-side interventions do not address. We propose GRASP (Guided Residual Adapters with Sample-wise Partitioning): a deterministic partition of the conditioning space, paired with group-specific residual adapters in the transformer feedforward layers, that leaves the flow-matching objective and the sampler untouched. In conditional flow matching, condition values index distinct sets of probability paths, so partitioning along the conditioning is the structurally correct factorization suitable as gradient alignment proxy. Because the partition is static, every tail sample is guaranteed to update its assigned expert, which bypasses extreme longtail failure modes. Crucially, GRASP is non-invasive and composable: on MIMIC-CXR-LT, combining GRASP with self-guided minority sampling at inference time yields the best all-labels IRS we observe, beyond either intervention alone. GRASP itself reduces overall FID by up to 80\% and lifts tail-class coverage by up to 44\% over full fine-tuning, learned-routing MoE, and minority guidance. Used as training data for a downstream DenseNet classifier on NIH-CXR-LT, GRASP synthetics significantly outperform every non-GRASP alternative on macro F1, match the macro F1 obtained from real training data, and yield nonzero F1 on $9$ of $13$ classes versus $3$ of $13$ from full fine-tuning. Results on ImageNet-LT confirm the mechanism is not tied to medical inductive bias.
  </details>
