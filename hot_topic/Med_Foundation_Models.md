# 🔍 Med_Foundation_Models Papers · 2026-05-30

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[On the Role of Inductive Bias in Time-Series Pretraining: A Case Study in Learning Generalizable Representations for Clinical Time Series](https://arxiv.org/abs/2605.26194)**  `arXiv:2605.26194`  `cs.LG`  
  _Sharmita Dey, Diego Paez-Granados_
  <details open><summary>Abstract</summary>
  Clinical time-series learning is routinely constrained by small, heterogeneous cohorts and protocol drift, while its downstream use spans both classification (e.g., pathology diagnosis) and regression (e.g., temporal forecasting). These constraints make foundation-model pretraining appealing, but raises an important question of which inductive biases should the pretraining objective impose so that representations transfer across task types and subjects. We study this question in pathological gait analysis for spinal cord injury (SCI) via PathoFM, an encoder-centric transformer pretrained on multivariate gait windows with three complementary objectives: Local Completion (reconstruct contiguous masked spans to enforce local structure), Temporal Continuity (predict a masked mid-horizon continuation from an observed prefix to enforce smoothness and causal consistency), and Unsupervised In-Context Dynamics (support-query reconstruction conditioned on subject exemplar windows via attention). Empirically comparing objective families (grouping/contrastive, dynamics-based, and generative reconstruction), we find that dynamics-centric mixtures produce the most balanced transfer: grouping objectives favor discriminative margins but can degrade magnitude fidelity needed for continuous targets, whereas reconstruction-only objectives preserve waveform structure but may underperform on classification. Overall, combining local reconstruction with temporal continuity, and adding in-context conditioning when exemplar access is realistic, yields robust subject-generalizing representations.
  </details>

- **[Genetically Aligned Patient Representations Improve Hematological Diagnosis](https://arxiv.org/abs/2605.29980)**  `arXiv:2605.29980`  `cs.CV` `cs.AI` `cs.LG`  
  _Muhammed Furkan Dasdelen, Fatih Ozlugedik, Ilaria Looser, Rao Muhammad Umer, Christian Pohlkamp, Carsten Marr_
  <details open><summary>Abstract</summary>
  Multimodal alignment of histopathology encoders with transcriptomic and genomic data has been shown to significantly improve performance in downstream diagnostic tasks. Hematological cytology is unique in that visual single-cell evaluation is often paired with cytogenetics and molecular genetics for blood cancer diagnosis. In this study, we present a framework to align single white blood cell images with chromosomal aberrations (karyotype) and somatic mutations from targeted gene panels. Our training strategy follows a two-stage approach: (i) self-supervised, vision-only pretraining of a transformer aggregator using an iBOT head on a cohort of over 1500 patients, and (ii) genetic alignment via supervised contrastive loss on acute myeloid leukemia patients. Our genetically aligned patient encoder improves hematological diagnostic tasks, outperforming slide-level histopathology foundation models. Additionally, the model provides off-the-shelf retrieval capabilities for diseases and genetic alterations. Incorporating genetic data into patient encoders increases the quality of patient representations, providing a framework that aligns with clinical diagnostic workflows and paves the way for future multimodal hematology-specific AI. The code and model weights are available atthis https URL.
  </details>

- **[One Click per Cell Type Suffices: Training-free Group Interaction for Cell Instance Segmentation](https://arxiv.org/abs/2605.29429)**  `arXiv:2605.29429`  `cs.CV`  
  _Sanghyun Jo, Seo Jin Lee, Seohyung Hong, Yoorim Gang, Hyeongsub Kim, Hyungseok Seo, et al._
  <details open><summary>Abstract</summary>
  Cell instance segmentation models trained on cell-specific datasets suffer severe performance drops on out-of-distribution cell types, while interactive foundation models overcome this through per-instance prompting at a cost that is prohibitively expensive for histopathology images containing hundreds to thousands of densely packed instances. We introduce Group Prompting, a new paradigm that shifts interactive segmentation from per-instance $O(N)$ to per-type $O(T)$, where a single click per cell type suffices to segment all instances of that type. Our key observation is that the frozen image encoder of the Segment Anything Model (SAM) already clusters same-type cells in its feature space before any prompt is given. Exploiting this property, we propose Chain-of-Prompts (CoP), a training-free framework that recursively expands a single user click by (1) identifying reliable same-type locations through non-parametric gating of multi-scale encoder features, and (2) selecting the most spatially distant reliable point as the next prompt to maximize coverage. On three cell-type-annotated benchmarks, CoP with one click per type retains over 90% of per-instance performance and surpasses fully-supervised methods without any additional training. On four morphologically homogeneous benchmarks, a single click retains over 99%. Project Page:this https URL
  </details>
