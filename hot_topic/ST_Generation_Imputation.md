# 🔍 ST_Generation_Imputation Papers · 2026-08-11

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[Flow-Based Generative Modeling for Optimizing Sampling Policies in Compressed Sensing Applications](https://arxiv.org/abs/2606.00078)**  `arXiv:2606.00078`  `cs.CV` `cs.AI`  
  _Roman Pavelkin, Luis A. Zavala-Mondragon, Christiaan G. A. Viviers, Fons van der Sommen_
  <details open><summary>Abstract</summary>
  Numerous modern applications in signal processing and medical imaging necessitate acquiring high-dimensional signals under tight resource constraints. Traditional sampling theory suggests that accurate signal reconstruction requires a number of measurements proportional to the signal's ambient dimension, a requirement often too expensive or impractical. Compressed sensing challenges this notion by demonstrating that sparse signals can be recovered with fewer measurements, provided the measurement operator meets certain conditions. This proof-of-concept study presents a task-aware flow-based generative framework -- a reformulation of the conventional Flow Matching training paradigm with a flow model trained to optimize subsampling in compressed sensing applications. We establish the fundamental feasibility of the proposed framework of learning subsampling masks that substantially enhance the performance of compressed sensing for image classification, image reconstruction, and MRI acceleration. For the image reconstruction task, our method demonstrated state-of-the-art performance, achieving Peak Signal-to-Noise Ratio of 25.17 dB at the subsampling rate of 5\% on the CelebA dataset and 29.24 dB when reconstructing $8\times$ accelerated MRI measurements (fastMRI dataset) with the minimal computational overhead. These results highlight the effectiveness of task-conditioning within generative flow models and reveal a promising direction for representation learning strategies. Overall, the proposed framework offers a unified, flexible approach to designing data- and task-driven sensing schemes that can be potentially adapted to a broad range of inverse problems.
  </details>
