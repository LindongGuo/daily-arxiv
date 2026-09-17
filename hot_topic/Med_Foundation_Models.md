# 🔍 Med_Foundation_Models Papers · 2026-09-16

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Learning Where to Focus: Self-Supervised Multi-Scale ViTs for Histopathology](https://arxiv.org/abs/2609.18578)**  `arXiv:2609.18578`  `cs.CV`  
  _Anabel Stammer, Valay Bundele, Mehran Hosseinzadeh, Hendrik P.A. Lensch_
  <details open><summary>Abstract</summary>
  Pathologists diagnose diseases by first locating suspicious tissue and then examining it at higher magnification, whereas self-supervised vision transformers (ViTs) allocate the same spatial resolution to every image region despite diagnostic evidence being sparse and spanning multiple biological scales. Recent pathology foundation models have substantially improved representation quality by scaling training data and model capacity, but largely retain uniform tokenization. We instead investigate whether pathology representations can be improved by learning where to allocate spatial resolution during self-supervised learning. To this end, we propose CRAFT (Coarse-to-fine Region-Adaptive Feature Tokenization), a DINO-based framework that learns image-dependent mixed-scale representations by using self-supervised attention to selectively refine informative regions while preserving coarse context, together with a symmetric cross-scale regularization objective that encourages complementary coarse and fine representations. Across CAMELYON16, TCGA-Lung subtype classification, and TCGA-LUAD survival prediction, CRAFT consistently outperforms comparable-scale self-supervised methods while requiring lower inference computation. Despite using only a compact 22M parameter backbone trained on comparatively small pathology datasets, CRAFT remains competitive with, and often surpasses, substantially larger pathology foundation models.
  </details>

- **[Lumen: Parameter-Efficient Alignment of Pretrained Vision and Language Encoders for Zero-Shot Computational Pathology](https://arxiv.org/abs/2609.17868)**  `arXiv:2609.17868`  `cs.CV`  
  _Kiarash Tajbakhsh, Abdelrahman Faqieh, Michael Jopiti, Javier Garcia-Baroja, Philipp Zens, Branislav Zagrapan, et al._
  <details open><summary>Abstract</summary>
  Pathology vision-language models are commonly built by pretraining or fine-tuning large encoders on paired image-caption data. We asked whether a pathology vision-language model can instead be assembled by parameter-efficient alignment of frozen unimodal foundation models, leaving their pretrained representations untouched. Here we present Lumen, which aligns frozen Virchow2 and BioMedBERT backbones using rank-4 adapters and projection heads, training only 0.40% of the total parameters on the public QUILT-1M corpus. Across nine public zero-shot patch benchmarks, Lumen achieved the highest mean chance-corrected balanced accuracy, 0.546 versus 0.461 for the strongest baseline (paired difference 0.086, 95% CI 0.042-0.136). On lymph-node metastasis detection, Lumen reached an AUROC of 0.964 (95% CI 0.956-0.971) on 4,214 held-out internal slides and 0.955 (95% CI 0.942-0.966) on 2,368 slides across nine external cohorts and six organs. At the internally calibrated threshold, it outperformed all vision-language baselines, with a balanced accuracy of 0.909 (95% CI 0.896-0.923) internally and 0.915 (95% CI 0.902-0.929) externally. Lumen performed competitively across the evaluations, with the exception of cross-modal retrieval, where it ranked third behind CONCH and PathGen-L/14. Fully fine-tuning both encoders gave Lumen no consistent benefit over low-rank adaptation, although it improved retrieval. Aligning frozen unimodal foundation models therefore yields strong and transferable performance at patch and slide level while training only a small fraction of the parameters.
  </details>
