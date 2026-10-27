# 🔍 ST_Generation_Imputation Papers · 2026-10-26

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Biology-Guided Context-Aware Residual Propagation for Spatial Gene Expression Prediction from Histology](https://arxiv.org/abs/2610.35167)**  `arXiv:2610.35167`  `cs.LG`  
  _Vu Van An, Long D. Nguyen, Ho Viet Duc Luong, Binh P. Nguyen_
  <details open><summary>Abstract</summary>
  Spatial transcriptomics provides spatially resolved molecular profiling, but its cost, limited throughput and experimental complexity hinder routine large-scale use. Predicting spatial gene expression from hematoxylin-and-eosin-stained histology images offers a scalable alternative, yet remains challenging because histology provides only an indirect morphological view of molecular activity. Existing methods typically decode expression from visual features in a single stage, even when enhanced with spatial aggregation, retrieval or multi-resolution fusion. This formulation is restrictive because spot-level expression reflects not only local morphology but also cellular identity, neighborhood composition and tissue-level organization. We propose BCARP, a Biology-guided Context-Aware Residual Propagation framework for histology-guided spatial transcriptomics prediction. Instead of directly predicting gene expression from histology embeddings, BCARP treats them as morphology visual priors and progressively refines spot representations in a transcriptomics-oriented latent space. Each refinement step integrates nuclei-guided local cellular context with prototype-guided global context propagation, enabling information exchange across both neighboring and spatially distant spots. A pattern-scale decoder further separates spatial expression into pattern prediction from raw expression with scale calibration. Evaluated on three ST datasets and ten HEST-1k cohorts, BCARP achieves the highest mean correlation-based performance against other baselines. Numerical results support biology-guided local-global residual propagation as an effective alternative to visual decoding for histology-to-transcriptomics prediction.
  </details>

- **[StaX-Net: Stackelberg Interleaved Asymmetric Network for Cross-Modality Medical Image Translation](https://arxiv.org/abs/2610.34214)**  `arXiv:2610.34214`  `cs.CV` `cs.AI`  
  _Amin Golnari, Saeid Sanei_
  <details open><summary>Abstract</summary>
  Cross-modality medical image translation is challenged by anatomically inconsistent synthesis that can compromise clinical diagnosis. We propose StaX-Net, a Stackelberg interleaved asymmetric network that incorporates a partially coupled encoder-discriminator structure, and a 2D feature aggregation and spatial transformation (FAST) layer that distills target-supervised priors under the learning using privileged information paradigm. The shared blocks between the generator and discriminator enhance architectural feature alignment. To stabilize the leader-follower training, a Stackelberg-inspired asymmetric optimization scheme employs explicit shared-parameter freezing and asymmetric learning rates. The FAST layer distills target-domain priors during training and applies a source-only transform at inference. This constrains the synthesis process through target-informed feature representations relative to standard generative architectures. The code is available on GitHub for public use.
  </details>

- **[GRASP: Guided Residual Adapters with Sample-wise Partitioning](https://arxiv.org/abs/2512.01675)**  `arXiv:2512.01675`  `cs.CV`  
  _Felix Nützel, Mischa Dombrowski, Bernhard Kainz_
  <details open><summary>Abstract</summary>
  Text-to-image flow matching transformers degrade sharply in long-tail settings: tail-class outputs collapse in fidelity and diversity, limiting their value as synthetic augmentation for rare conditions. We trace this to low head-versus-tail gradient alignment during fine-tuning, an optimization-level pathology that conditioning- and sampling-side interventions do not address. We propose GRASP (Guided Residual Adapters with Sample-wise Partitioning): a deterministic partition of the conditioning space, paired with group-specific residual adapters in the transformer feedforward layers, that leaves the flow-matching objective and the sampler untouched. In conditional flow matching, condition values index distinct sets of probability paths, which makes the conditioning a structurally natural axis along which to factorize residual updates. Because the partition is static, every tail sample is guaranteed to update its assigned expert, which bypasses extreme long-tail failure modes. GRASP is non-invasive and composable: on MIMIC-CXR-LT, combining GRASP with self-guided minority sampling at inference outperforms its learned counterpart on 10 of 12 metrics. Performance is stable across random reassignments of labels to experts and across expert counts, as long as no expert is starved of samples. Used as training data for a downstream DenseNet classifier on NIH-CXR-LT, GRASP synthetics significantly outperform every non-GRASP alternative on macro F1 and yield nonzero F1 on 9 of 13 classes versus 3 of 13 from real data, while maintaining comparable macro F1. Results on ImageNet-LT confirm the mechanism is not tied to medical inductive bias. Code is available atthis https URL
  </details>
