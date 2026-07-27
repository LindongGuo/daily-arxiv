# 🔍 Med_Foundation_Models Papers · 2026-07-26

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Atlas 2 -- Foundation models for clinical deployment](https://arxiv.org/abs/2601.05148)**  `arXiv:2601.05148`  `cs.CV` `cs.AI` `cs.LG`  
  _Maximilian Alber, Timo Milbich, Alexandra Carpen-Amarie, Stephan Tietz, Jonas Dippel, Lukas Muttenthaler, et al._
  <details open><summary>Abstract</summary>
  Pathology foundation models substantially advanced the possibilities in computational pathology --- yet tradeoffs in terms of performance, robustness, and computational requirements remained, which limited their clinical deployment. In this report, we present Atlas 2, Atlas 2-B, and Atlas 2-S, three pathology vision foundation models which bridge these shortcomings by showing state-of-the-art prediction performance, robustness, and resource efficiency in a comprehensive evaluation across eighty public benchmarks. Our models were trained on the largest pathology foundation model dataset to date comprising 5.5 million histopathology whole slide images, collected from three medical institutions Charité - Universitätsmedizin Berlin, LMU Munich, and Mayo Clinic.
  </details>

- **[TextSLIP: Text Self-Supervised CLIP for Medical Report Generation](https://arxiv.org/abs/2607.21970)**  `arXiv:2607.21970`  `cs.CV` `cs.AI`  
  _Haoyu Jiang, Ziping Cong_
  <details open><summary>Abstract</summary>
  Automating radiology report generation is important for improving reporting consistency and clinical workflows . While Contrastive Language--Image Pretraining (CLIP) has advanced medical vision language modeling, existing CLIP-style approaches may still provide insufficient fine-grained semantic supervision for complex report generation. Standard CLIP primarily optimizes cross-modal alignment, without explicitly structuring the textual embedding space that guides visual representation learning. To address this limitation, we propose TextSLIP, a general medical vision-language pretraining framework that augments CLIP with intra-modal text contrastive learning. By improving textual embedding discriminability through self-supervised augmented text pairs, TextSLIP is designed to provide finer-grained linguistic supervision to the visual encoder. As an initial validation, we pretrain TextSLIP on a curated dataset of 7 million brain MRI image-text pairs and fine-tune the pretrained visual encoder within a report generation architecture. In controlled comparisons with CLIP-style baselines, TextSLIP shows consistent improvements on report generation metrics. Ablation studies further suggest that text-side self-supervision contributes to the observed gains. These results indicate that text-level contrastive learning is a promising direction for improving medical visual-textual alignment, while broader validation across additional medical domains remains an important next step.
  </details>
