# 🔍 Med_Foundation_Models Papers · 2026-05-12

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Enabling clinical use of foundation models for computational pathology](https://arxiv.org/abs/2602.22347)**  `arXiv:2602.22347`  `cs.CV` `cs.AI`  
  _Audun L Henriksen, Ole-Johan Skrede, Lisa van der Schee, Enric Domingo, Karolina Cyll, Sepp de Raedt, et al._
  <details open><summary>Abstract</summary>
  Foundation models for computational pathology are expected to facilitate the development of high-performing, generalisable deep learning systems. However, in addition to biologically relevant features, current foundation models also capture pre-analytic and scanner-specific variation that bias the predictions made by downstream task-specific models trained on these features. Here we show that introducing novel robustness losses during downstream model training reduces sensitivity to technical variability. A purpose-designed comprehensive experimentation setup with 27,042 whole-slide images from 6,155 patients is used to train thousands of models from the features of eight well-known foundation models for computational pathology. In addition to a substantial improvement in robustness, our approach improves classification accuracy by focusing on biologically relevant features. It mitigates robustness limitations of foundation models for computational pathology without retraining the foundation models themselves, enabling development of models that are more suitable in real-world clinical use.
  </details>

- **[RNA-FM: Flow-Matching Generative Model for Genome-wide RNA-Seq Prediction](https://arxiv.org/abs/2605.11622)**  `arXiv:2605.11622`  `cs.CV`  
  _Yaxuan Song, Jianan Fan, Tianyi Wang, Qiuyue Hu, Hang Chang, Heng Huang, et al._
  <details open><summary>Abstract</summary>
  Histopathology whole-slide images (WSIs) are routinely acquired in clinical practice and contain rich tissue morphology but lack direct molecular architecture and functional programs defining pathological states, whereas RNA sequencing (RNA-seq) provides genome-wide transcriptional profiles at substantial cost, thereby motivating WSI-based genome-wide transcriptomic prediction. Existing approaches for predicting gene expression from WSIs predominantly rely on deterministic regression with one-to-one mapping, limiting their ability to capture biological heterogeneity and predictive uncertainty. We propose RNA-FM, a flow-matching generative framework for genome-wide bulk RNA-seq prediction from WSIs. RNA-FM formulates transcriptomic prediction as a continuous-time conditional transport problem, learning a velocity field that maps a simple prior to the target gene expression distribution conditioned on morphologies. By integrating pathway-level structure, RNA-FM enables scalable and biologically interpretable genome-wide gene expression imputation. Extensive experiments demonstrate that RNA-FM consistently outperforms state-of-the-art approaches while maintaining biological meaningfulness. Code is available atthis https URL.
  </details>
