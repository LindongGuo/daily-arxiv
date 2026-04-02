# 🔍 Med_Foundation_Models Papers · 2026-04-01

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Maximizing T2-Only Prostate Cancer Localization from Expected Diffusion Weighted Imaging](https://arxiv.org/abs/2604.00985)**  `arXiv:2604.00985`  `cs.CV`  
  _Weixi Yi, Yipei Wang, Wen Yan, Hanyuan Zhang, Natasha Thorley, Alexander Ng, et al._
  <details open><summary>Abstract</summary>
  Multiparametric MRI is increasingly recommended as a first-line noninvasive approach to detect and localize prostate cancer, requiring at minimum diffusion-weighted (DWI) and T2-weighted (T2w) MR sequences. Early machine learning attempts using only T2w images have shown promising diagnostic performance in segmenting radiologist-annotated lesions. Such uni-modal T2-only approaches deliver substantial clinical benefits by reducing costs and expertise required to acquire other sequences. This work investigates an arguably more challenging application using only T2w at inference, but to localize individual cancers based on independent histopathology labels. We formulate DWI images as a latent modality (readily available during training) to classify cancer presence at local Barzell zones, given only T2w images as input. In the resulting expectation-maximization algorithm, a latent modality generator (implemented using a flow matching-based generative model) approximates the latent DWI image posterior distribution in the E-steps, while in M-steps a cancer localizer is simultaneously optimized with the generative model to maximize the expected likelihood of cancer presence. The proposed approach provides a novel theoretical framework for learning from a privileged DWI modality, yielding superior cancer localization performance compared to approaches that lack training DWI images or existing frameworks for privileged learning and incomplete modalities. The proposed T2-only methods perform competitively or better than baseline methods using multiple input sequences (e.g., improving the patient-level F1 score by 14.4\% and zone-level QWK by 5.3\% over the T2w+DWI baseline). We present quantitative evaluations using internal and external datasets from 4,133 prostate cancer patients with histopathology-verified labels.
  </details>

- **[MOOZY: A Patient-First Foundation Model for Computational Pathology](https://arxiv.org/abs/2603.27048)**  `arXiv:2603.27048`  `cs.CV`  
  _Yousef Kotp, Vincent Quoc-Huy Trinh, Christopher Pal, Mahdi S. Hosseini_
  <details open><summary>Abstract</summary>
  Computational pathology needs whole-slide image (WSI) foundation models that transfer across diverse clinical tasks, yet current approaches remain largely slide-centric, often depend on private data and expensive paired-report supervision, and do not explicitly model relationships among multiple slides from the same patient. We present MOOZY, a patient-first pathology foundation model in which the patient case, not the individual slide, is the core unit of representation. MOOZY explicitly models dependencies across all slides from the same patient via a case transformer during pretraining, combining multi-stage open self-supervision with scaled low-cost task supervision. In Stage 1, we pretrain a vision-only slide encoder on 77,134 public slide feature grids using masked self-distillation. In Stage 2, we align these representations with clinical semantics using a case transformer and multi-task supervision over 333 tasks from 56 public datasets, including 205 classification and 128 survival tasks across four endpoints. Across eight held-out tasks with five-fold frozen-feature probe evaluation, MOOZY achieves best or tied-best performance on most metrics and improves macro averages over TITAN by +7.37%, +5.50%, and +7.83% and over PRISM by +8.83%, +10.70%, and +9.78% for weighted F1, weighted ROC-AUC, and balanced accuracy, respectively. MOOZY is also parameter efficient with 85.77M parameters, 14x smaller than GigaPath. These results demonstrate that open, reproducible patient-level pretraining yields transferable embeddings, providing a practical path toward scalable patient-first histopathology foundation models.
  </details>
