# 🔍 Med_Foundation_Models Papers · 2026-11-11

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Predicting Single-Cell Spatial Gene Expression from H&E using Pathology Foundation Models](https://arxiv.org/abs/2611.13649)**  `arXiv:2611.13649`  `cs.CV`  
  _Ashley P. Tsang, Evan Liu, Conrad Foo, Bob Chen, Hassaan Maan, Donny Chan, et al._
  <details open><summary>Abstract</summary>
  Predicting gene expression directly from hematoxylin and eosin (H&E) images offers a scalable and cost-effective approach to deriving spatial molecular insights from routine histology. Pathology foundation models, typically pretrained using tile-level objectives, may not adequately capture the fine-grained cellular features required for single-cell molecular prediction. In this work, we systematically evaluate and establish domain-informed and task-specific strategies for adapting pathology foundation models to single-cell spatial gene expression prediction. Using paired H&E and Xenium 5K data, our approach improves mean gene-wise Pearson correlation by 2.67x over the standard zero-shot baseline and achieves state-of-the-art performance on this task. We demonstrate strong gene-detection performance across the full gene panel (AUROC = 0.800) and importantly identify that predictive performance varies substantially across biological contexts, with our model achieving its highest Pearson correlation for spatially variable genes (r = 0.643). Our findings demonstrate that, despite the challenges of sparse single-cell measurements, H&E-derived representations can recover biologically meaningful spatial expression patterns, highlighting both the opportunities and limitations of morphology-based molecular inference at cellular resolution.
  </details>

- **[Domain adaptation of a video Foundation model for Heart Failure Diagnosis from Echocardiography](https://arxiv.org/abs/2611.13297)**  `arXiv:2611.13297`  `cs.CV`  
  _Mahyar Bolhassani, Tijana Geroski, Narayana S. Singam, Amir Amini_
  <details open><summary>Abstract</summary>
  The rapid advancement of foundation models has transformed computer vision, yet their adaptation to medical imaging, particularly purpose built foundation models for spatio temporal echocardiography videos, remains limited. In this work, we explore the feasibility of fine tuning a pretrained foundation model for video (TimeSformer) for automated diagnosis of reduced ejection fraction heart failure (HFrEF) from apical four chamber videos. The model is finetuned on the publicly available RVENet A4C dataset with a phase aware clip generation strategy that captures complementary systolic and diastolic dynamics. We employ divided space time attention, layer wise learning rate decay, and multi clip inference to enhance robustness under limited data. Experimental results show that full fine tuning of the proposed model outperforms classifier only tuning and a 3D CNN baseline. These findings highlight the potential of leveraging foundation video models for echocardiography based heart failure diagnosis and motivates further domain adaptation studies in medical imaging.
  </details>
