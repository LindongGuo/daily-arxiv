# 🔍 ST_Generation_Imputation Papers · 2026-03-28

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[FEAST: Fully Connected Expressive Attention for Spatial Transcriptomics](https://arxiv.org/abs/2603.25247)**  `arXiv:2603.25247`  `cs.CV` `cs.AI`  
  _Taejin Jeong, Joohyeok Kim, Jinyeong Kim, Chanyoung Kim, Seong Jae Hwang_
  <details open><summary>Abstract</summary>
  Spatial Transcriptomics (ST) provides spatially-resolved gene expression, offering crucial insights into tissue architecture and complex diseases. However, its prohibitive cost limits widespread adoption, leading to significant attention on inferring spatial gene expression from readily available whole slide images. While graph neural networks have been proposed to model interactions between tissue regions, their reliance on pre-defined sparse graphs prevents them from considering potentially interacting spot pairs, resulting in a structural limitation in capturing complex biological relationships. To address this, we propose FEAST (Fully connected Expressive Attention for Spatial Transcriptomics), an attention-based framework that models the tissue as a fully connected graph, enabling the consideration of all pairwise interactions. To better reflect biological interactions, we introduce negative-aware attention, which models both excitatory and inhibitory interactions, capturing essential negative relationships that standard attention often overlooks. Furthermore, to mitigate the information loss from truncated or ignored context in standard spot image extraction, we introduce an off-grid sampling strategy that gathers additional images from intermediate regions, allowing the model to capture a richer morphological context. Experiments on public ST datasets show that FEAST surpasses state-of-the-art methods in gene expression prediction while providing biologically plausible attention maps that clarify positive and negative interactions. Our code is available atthis https URLFEAST.
  </details>

- **[MedShift: Implicit Conditional Transport for X-Ray Domain Adaptation](https://arxiv.org/abs/2508.21435)**  `arXiv:2508.21435`  `cs.CV` `cs.AI`  
  _Francisco Caetano, Christiaan Viviers, Peter H.N. de With, Fons van der Sommen_
  <details open><summary>Abstract</summary>
  Synthetic medical data offers a scalable solution for training robust models, but significant domain gaps limit its generalizability to real-world clinical settings. This paper addresses the challenge of cross-domain translation between synthetic and real X-ray images of the head, focusing on bridging discrepancies in attenuation behavior, noise characteristics, and soft tissue representation. We propose MedShift, a unified class-conditional generative model based on Flow Matching and Schrodinger Bridges, which enables high-fidelity, unpaired image translation across multiple domains. Unlike prior approaches that require domain-specific training or rely on paired data, MedShift learns a shared domain-agnostic latent space and supports seamless translation between any pair of domains seen during training. We introduce X-DigiSkull, a new dataset comprising aligned synthetic and real skull X-rays under varying radiation doses, to benchmark domain translation models. Experimental results demonstrate that, despite its smaller model size compared to diffusion-based approaches, MedShift offers strong performance and remains flexible at inference time, as it can be tuned to prioritize either perceptual fidelity or structural consistency, making it a scalable and generalizable solution for domain adaptation in medical imaging. The code and dataset are available atthis https URL
  </details>
