# 🔍 Med_Foundation_Models Papers · 2026-07-20

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[GigaPath-Flash and GigaTIME-Flash: Efficient Pathology Foundation Models for Whole-Slide and Tumor Microenvironment Analysis](https://arxiv.org/abs/2607.18218)**  `arXiv:2607.18218`  `cs.CV` `cs.AI`  
  _Naoto Usuyama, Jeya Maria Jose Valanarasu, Sicong Yao, Hanwen Xu, Jaspreet Bagga, Guanghui Qin, et al._
  <details open><summary>Abstract</summary>
  Foundation models have emerged as a driving force in computational pathology, with the potential to transform cancer diagnosis, prognosis, and treatment selection by learning transferable representations from large-scale histopathology data. A growing landscape of pathology foundation models now spans diverse data sources, architectures, and downstream applications. However, most pretrained models operate only at the image-tile level, use restrictive licenses, and remain computationally expensive, limiting large-scale slide-level clinical and research use.Here, we introduce GigaPath-Flash and GigaTIME-Flash, efficient models for whole-slide pathology AI and spatial proteomics prediction. GigaPath-Flash combines a 22M-parameter ViT-S tile encoder with a 21M-parameter LongNet slide encoder, both pretrained on large-scale real-world histopathology data. Its compact tile encoder is distilled from the billion-parameter GigaPath (ViT-g) teacher and shared by both models. GigaPath-Flash retains 97% of GigaPath's average slide-level performance with 50x less compute. GigaTIME-Flash extends this backbone to predict the tumor immune microenvironment directly from routine H&E images. It surpasses the original CNN-based GigaTIME in prediction quality while running 6x faster and using 8x less GPU memory.Together with GigaPath and GigaTIME, these models form an open-weight, Apache-2.0-licensed family pretrained on large-scale real-world clinical data. By releasing all models and weights, we provide accessible building blocks for computational pathology, immuno-oncology, and precision health.
  </details>

- **[FedDP-PALD: A Privacy-Preserving Federated Latent Diffusion Framework with Prototype Aggregation for Medical Data Synthesis](https://arxiv.org/abs/2607.16300)**  `arXiv:2607.16300`  `cs.CV`  
  _Md. Sajeebul Islam Sk., Khan Enaet Hossain, Md. Mehedi Hasan Shawon_
  <details open><summary>Abstract</summary>
  Medical images and physiological signals provide valuable information for accurate diagnosis. Developing diagnostic models often requires patient data from multiple institutions, although strict privacy regulations limit the sharing of sensitive clinical records. Federated learning enables multiple hospitals to train a shared model without exchanging raw data. However, existing methods face two problems: the information exchanged during training can reveal whether a patient's data were used, and synthetic data meant to replace real records often fail to preserve their predictive structure, which limits clinical use. To address this issue, we propose FedDP-PALD, a privacy-preserving federated latent diffusion framework for multimodal medical data synthesis under formal privacy guarantees. It jointly processes chest X-ray images and electrocardiogram (ECG) signals through gated multi-head attention with modality-availability masks, remaining effective even when a modality is missing. We also introduce Differentially Private Prototype Mixture Aggregation (DP-PMA), which clips class-level latent prototypes and adds calibrated Gaussian noise before combining them on the server to maintain $(\epsilon, \delta)$ differential privacy. We evaluate FedDP-PALD on PneumoniaMNIST, ChestMNIST, and MIT-BIH datasets, where differential privacy reduced summary-level attack AUROC from 0.6229 $\pm$ 0.0026 to between 0.5016 and 0.5093 for privacy budgets from $\epsilon = 1$ to $\epsilon = 8$. On the test data, synthetic-latent training achieved an F1 score of 0.8993 $\pm$ 0.0006 and an AUROC of 0.9057 $\pm$ 0.0503, close to the 0.9747 $\pm$ 0.0132 real-latent training. These results show that FedDP-PALD generates private synthetic representations that preserve useful decision performance while strongly resisting membership inference.
  </details>

- **[Prompt-Guided Foundation Model Tuning for Pathology Image Classification](https://arxiv.org/abs/2403.12537)**  `arXiv:2403.12537`  `cs.CV`  
  _Yi Lin, Zhengjie Zhu, Kwang-Ting Cheng, Hao Chen_
  <details open><summary>Abstract</summary>
  Foundation models have become pivotal in advancing computational pathology, particularly for whole slide image (WSI) classification. However, prevailing methodologies often rely on frozen, pre-trained models for feature extraction, overlooking the pronounced domain shift and task discrepancy between the pre-training and downstream tasks. To address this challenge, we propose PAMT, a novel Prompt-guided Adaptive Model Transformation framework that enables precise adaptation of general foundation models to the distinct domain of histopathology. To encapsulate the intricate distributions characteristic of histopathological data, we introduce Representative Patch Sampling (RPS) and Prototypical Visual Prompt (PVP), which reconstruct the input into compact yet highly informative representations. Further, to effectively bridge the domain gap, we incorporate Adaptive Model Transformation (AMT) via adapter modules within the feature extraction pipeline, facilitating the acquisition of domain-specific features by the foundation model. We conduct rigorous evaluation across 14 publicly available datasets and demonstrate consistent, substantial improvements in classification accuracy. These results establish PAMT as a compelling new benchmark for pathology image classification and underscore the critical value of targeted model adaptation within computational pathology.
  </details>
