# 🔍 Med_Foundation_Models Papers · 2026-05-20

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Clinically-Informed Modeling for Pediatric Brain Tumor Classification from Whole-Slide Histopathology Images](https://arxiv.org/abs/2604.21060)**  `arXiv:2604.21060`  `cs.CV`  
  _Joakim Nguyen, Jian Yu, Jinrui Fang, Nicholas Konz, Tianlong Chen, Sanjay Krishnan, et al._
  <details open><summary>Abstract</summary>
  Accurate diagnosis of pediatric brain tumors, starting with histopathology, presents unique challenges for deep learning, including severe data scarcity, class imbalance, and fine-grained morphologic overlap across diagnostically distinct subtypes. While pathology foundation models have advanced patch-level representation learning, their effective adaptation to weakly supervised pediatric brain tumor classification under limited data remains underexplored. In this work, we introduce an expert-guided contrastive fine-tuning framework for pediatric brain tumor diagnosis from whole-slide images (WSI). Our approach integrates contrastive learning into slide-level multiple instance learning (MIL) to explicitly regularize the geometry of slide-level representations during downstream fine-tuning. We propose both a general supervised contrastive setting and an expert-guided variant that incorporates clinically informed hard negatives targeting diagnostically confusable subtypes. Through comprehensive experiments on pediatric brain tumor WSI classification under realistic low-sample and class-imbalanced conditions, we demonstrate that contrastive fine-tuning yields measurable improvements in fine-grained diagnostic distinctions. Our experimental analyses reveal complementary strengths across different contrastive strategies, with expert-guided hard negatives promoting more compact intra-class representations and improved inter-class separation. This work highlights the importance of explicitly shaping slide-level representations for robust fine-grained classification in data-scarce pediatric pathology settings.
  </details>

- **[CardioBench: Do Echocardiography Foundation Models Generalize Beyond the Lab?](https://arxiv.org/abs/2510.00520)**  `arXiv:2510.00520`  `cs.CV`  
  _Darya Taratynova, Ahmed Aly, Numan Saeed, Mohammad Yaqub_
  <details open><summary>Abstract</summary>
  Foundation models are reshaping medical imaging, yet their application in echocardiography remains limited, hindered by a heavy reliance on private datasets that prevent reproducible comparison. Echocardiography poses unique challenges, including noisy acquisitions, high frame redundancy, and limited diverse public datasets. To address this, we introduce CardioBench, a comprehensive benchmark for echocardiography foundation models. Specifically, CardioBench unifies eight publicly available datasets into a standardized suite spanning four regression and five classification tasks, covering functional, structural, diagnostic, and view recognition endpoints. Leveraging this framework, we evaluate several leading foundation models, including cardiac-specific, biomedical, and general-purpose encoders, under consistent zero-shot, probing, and alignment protocols. Our analysis reveals that while general-purpose encoders transfer well and often close the gap with probing, they struggle significantly with fine-grained distinctions like view classification and subtle pathology recognition. Results indicate that models capturing temporal cardiac dynamics perform best on functional tasks, while retrieval-based approaches generalize more consistently across datasets. By releasing preprocessing, splits, and public evaluation pipelines, CardioBench establishes a reproducible reference point to guide the architectural design of future echocardiography and possibly other medical imaging foundation models.
  </details>
