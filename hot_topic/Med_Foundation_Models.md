# 🔍 Med_Foundation_Models Papers · 2026-10-12

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[A4-MR: Abnormality-aware Anatomical Alignment for MR](https://arxiv.org/abs/2610.13056)**  `arXiv:2610.13056`  `cs.CV`  
  _Noel D'souza, Zhijian Yang, Nishank Singla, Pranay Doshi, Krisztian Koos, Fei Tan, et al._
  <details open><summary>Abstract</summary>
  Recent advances in large-scale foundation models have enabled strong generalization across a wide range of clinical and research tasks in magnetic resonance imaging (MRI). However, existing vision-language MRI models remain limited in anatomy-specific localization and pathology-aware representation, particularly in real-world settings. We introduce A4-MR, a 3D vision-language foundation model trained on approximately 50,000 MRI studies comprising 491,000 series, roughly half of which are paired with radiology reports. A4-MR is designed to: (1) learn anatomy localization through large-scale pretraining with noisy labels; (2) align image and text representations at the anatomical level; and (3) learn distinct representations of healthy and abnormal anatomy. Across a diverse set of downstream tasks, A4-MR outperforms existing foundation models, including a +1.7 AUROC improvement over MedSigLIP for abnormality detection. Using a frozen encoder, A4-MR also surpasses an end-to-end task-specific MedNeXt model for knee segmentation by +1.4 Dice and performs comparably to the best task-specific model for abdominal organ segmentation on AMOS, within 0.4 Dice. Finally, without anatomical prompts, A4-MR localizes 3D anatomy comparably to MedSAM2 provided with ground-truth bounding boxes. Together, these results demonstrate that anatomy-level multimodal alignment and abnormality-aware representation learning can enable a single MRI foundation model to support localization, segmentation, and pathology-related tasks.
  </details>

- **[Scaling Multi-Teacher Distillation for Digital Pathology](https://arxiv.org/abs/2610.12574)**  `arXiv:2610.12574`  `cs.CV`  
  _Sofiène Boutaj, Pierre Marza, Varun Belagali, Dimitris Samaras, Maria Vakalopoulou, Stergios Christodoulidis_
  <details open><summary>Abstract</summary>
  Multi-teacher distillation allows transferring knowledge from multiple "teacher" networks to a single "student" network. This method is promising in fields such as digital pathology, where many powerful foundation models were proposed recently. However, as we show in this paper, the standard multi-teacher distillation approach reacts poorly to an increase in the number of teachers used to train a student encoder. We demonstrate that learning teacher-specific representations is a key to scaling in MTD. Importantly, different design choices, such as learnable teacher tokens, a tailored attention scheme, additional mixture-of-experts layers and a contrastive loss, are proposed to better learn such teacher-specific representations. We show that our method better scales with respect to the number of considered teachers, allowing us to train compact student encoders, up to 10x more efficient than larger teacher foundation models, while matching their performance and even outperforming them on a large set of tile-level and slide-level tasks. We conduct a thorough empirical validation, evaluating more than 10 foundation models on 39 tasks spanning tile and slide levels. As a result, we release a new collection of strong and efficient foundation models, named OMNI, trained from the knowledge of 10 state-of-the-art foundation models. We finally conduct an analysis of the learned teacher-specific representations, highlighting their complementarity and explaining why they can be easily aggregated at downstream time.
  </details>
