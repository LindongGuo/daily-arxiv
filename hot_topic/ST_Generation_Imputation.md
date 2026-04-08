# 🔍 ST_Generation_Imputation Papers · 2026-04-07

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[PRIME: Prototype-Driven Multimodal Pretraining for Cancer Prognosis with Missing Modalities](https://arxiv.org/abs/2604.04999)**  `arXiv:2604.04999`  `cs.LG` `cs.AI`  
  _Kai Yu, Shuang Zhou, Yiran Song, Zaifu Zhan, Jie Peng, Kaixiong Zhou, et al._
  <details open><summary>Abstract</summary>
  Multimodal self-supervised pretraining offers a promising route to cancer prognosis by integrating histopathology whole-slide images, gene expression, and pathology reports, yet most existing approaches require fully paired and complete inputs. In practice, clinical cohorts are fragmented and often miss one or more modalities, limiting both supervised fusion and scalable multimodal pretraining. We propose PRIME, a missing-aware multimodal self-supervised pretraining framework that learns robust and transferable representations from partially observed cohorts. PRIME maps heterogeneous modality embeddings into a unified token space and introduces a shared prototype memory bank for latent-space semantic imputation via patient-level consensus retrieval, producing structurally aligned tokens without reconstructing raw signals. Two complementary pretraining objectives: inter-modality alignment and post-fusion consistency under structured missingness augmentation, jointly learn representations that remain predictive under arbitrary modality subsets. We evaluate PRIME on The Cancer Genome Atlas with label-free pretraining on 32 cancer types and downstream 5-fold evaluation on five cohorts across overall survival prediction, 3-year mortality classification, and 3-year recurrence classification. PRIME achieves the best macro-average performance among all compared methods, reaching 0.653 C-index, 0.689 AUROC, and 0.637 AUROC on the three tasks, respectively, while improving robustness under test-time missingness and supporting parameter-efficient and label-efficient adaptation. These results support missing-aware multimodal pretraining as a practical strategy for prognosis modeling in fragmented clinical data settings.
  </details>

- **[MedShift: Implicit Conditional Transport for X-Ray Domain Adaptation](https://arxiv.org/abs/2508.21435)**  `arXiv:2508.21435`  `cs.CV` `cs.AI`  
  _Francisco Caetano, Christiaan Viviers, Peter H.N. De With, Fons van der Sommen_
  <details open><summary>Abstract</summary>
  Synthetic medical data offers a scalable solution for training robust models, but significant domain gaps limit its generalizability to real-world clinical settings. This paper addresses the challenge of cross-domain translation between synthetic and real X-ray images of the head, focusing on bridging discrepancies in attenuation behavior, noise characteristics, and soft tissue representation. We propose MedShift, a unified class-conditional generative model based on Flow Matching and Schrodinger Bridges, which enables high-fidelity, unpaired image translation across multiple domains. Unlike prior approaches that require domain-specific training or rely on paired data, MedShift learns a shared domain-agnostic latent space and supports seamless translation between any pair of domains seen during training. We introduce X-DigiSkull, a new dataset comprising aligned synthetic and real skull X-rays under varying radiation doses, to benchmark domain translation models. Experimental results demonstrate that, despite its smaller model size compared to diffusion-based approaches, MedShift offers strong performance and remains flexible at inference time, as it can be tuned to prioritize either perceptual fidelity or structural consistency, making it a scalable and generalizable solution for domain adaptation in medical imaging. The code and dataset are available atthis https URL
  </details>

- **[Aleatoric Uncertainty Medical Image Segmentation Estimation via Flow Matching](https://arxiv.org/abs/2507.22418)**  `arXiv:2507.22418`  `cs.CV` `cs.AI`  
  _Phi Van Nguyen, Ngoc Huynh Trinh, Duy Minh Lam Nguyen, Phu Loc Nguyen, Quoc Long Tran_
  <details open><summary>Abstract</summary>
  Quantifying aleatoric uncertainty in medical image segmentation is critical since it is a reflection of the natural variability observed among expert annotators. A conventional approach is to model the segmentation distribution using the generative model, but current methods limit the expression ability of generative models. While current diffusion-based approaches have demonstrated impressive performance in approximating the data distribution, their inherent stochastic sampling process and inability to model exact densities limit their effectiveness in accurately capturing uncertainty. In contrast, our proposed method leverages conditional flow matching, a simulation-free flow-based generative model that learns an exact density, to produce highly accurate segmentation results. By guiding the flow model on the input image and sampling multiple data points, our approach synthesizes segmentation samples whose pixel-wise variance reliably reflects the underlying data distribution. This sampling strategy captures uncertainties in regions with ambiguous boundaries, offering robust quantification that mirrors inter-annotator differences. Experimental results demonstrate that our method not only achieves competitive segmentation accuracy but also generates uncertainty maps that provide deeper insights into the reliability of the segmentation outcomes. The code for this paper is freely available atthis https URL
  </details>
