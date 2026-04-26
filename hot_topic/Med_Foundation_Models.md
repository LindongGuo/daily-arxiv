# 🔍 Med_Foundation_Models Papers · 2026-04-25

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Attention-based multiple instance learning for predominant growth pattern prediction in lung adenocarcinoma wsi using foundation models](https://arxiv.org/abs/2604.21530)**  `arXiv:2604.21530`  `cs.CV` `cs.AI`  
  _Laura Valeria Perez-Herrera, M.J. Garcia-Gonzalez, Karen Lopez-Linares_
  <details open><summary>Abstract</summary>
  Lung adenocarcinoma (LUAD) grading depends on accurately identifying growth patterns, which are indicators of prognosis and can influence treatment decisions. Common deep learning approaches to determine the predominant pattern rely on patch-level classification or segmentation, requiring extensive annotations. This study proposes an attention-based multiple instance learning (ABMIL) framework to predict the predominant LUAD growth pattern at the whole slide level to reduce annotation burden. Our approach integrates pretrained pathology foundation models as patch encoders, used either frozen or fine-tuned on annotated patches, to extract discriminative features that are aggregated through attention mechanisms. Experiments show that fine-tuned encoders improve performance, with Prov-GigaPath achieving the highest agreement (\k{appa} = 0.699) under ABMIL. Compared to simple patch-aggregation baselines, ABMIL yields more robust predictions by leveraging slide-level supervision and spatial attention. Future work will extend this framework to estimate the full distribution of growth patterns and validate performance on external cohorts.
  </details>

- **[Clinically-Informed Modeling for Pediatric Brain Tumor Classification from Whole-Slide Histopathology Images](https://arxiv.org/abs/2604.21060)**  `arXiv:2604.21060`  `cs.CV`  
  _Joakim Nguyen, Jian Yu, Jinrui Fang, Nicholas Konz, Tianlong Chen, Sanjay Krishnan, et al._
  <details open><summary>Abstract</summary>
  Accurate diagnosis of pediatric brain tumors, starting with histopathology, presents unique challenges for deep learning, including severe data scarcity, class imbalance, and fine-grained morphologic overlap across diagnostically distinct subtypes. While pathology foundation models have advanced patch-level representation learning, their effective adaptation to weakly supervised pediatric brain tumor classification under limited data remains underexplored. In this work, we introduce an expert-guided contrastive fine-tuning framework for pediatric brain tumor diagnosis from whole-slide images (WSI). Our approach integrates contrastive learning into slide-level multiple instance learning (MIL) to explicitly regularize the geometry of slide-level representations during downstream fine-tuning. We propose both a general supervised contrastive setting and an expert-guided variant that incorporates clinically informed hard negatives targeting diagnostically confusable subtypes. Through comprehensive experiments on pediatric brain tumor WSI classification under realistic low-sample and class-imbalanced conditions, we demonstrate that contrastive fine-tuning yields measurable improvements in fine-grained diagnostic distinctions. Our experimental analyses reveal complementary strengths across different contrastive strategies, with expert-guided hard negatives promoting more compact intra-class representations and improved inter-class separation. This work highlights the importance of explicitly shaping slide-level representations for robust fine-grained classification in data-scarce pediatric pathology settings.
  </details>
