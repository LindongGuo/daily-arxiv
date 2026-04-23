# 🔍 Med_Foundation_Models Papers · 2026-04-22

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[CXR-LanIC: Language-Grounded Interpretable Classifier for Chest X-Ray Diagnosis](https://arxiv.org/abs/2510.21464)**  `arXiv:2510.21464`  `cs.CV`  
  _Yiming Tang, Wenjia Zhong, Rushi Shah, Dianbo Liu_
  <details open><summary>Abstract</summary>
  Deep learning models have achieved remarkable accuracy in chest X-ray diagnosis, yet their widespread clinical adoption remains limited by the black-box nature of their predictions. Clinicians require transparent, verifiable explanations to trust automated diagnoses and identify potential failure modes. We introduce CXR-LanIC (Language-Grounded Interpretable Classifier for Chest X-rays), a novel framework that addresses this interpretability challenge through task-aligned pattern discovery. Our approach trains transcoder-based sparse autoencoders on a BiomedCLIP diagnostic classifier to decompose medical image representations into interpretable visual patterns. By training an ensemble of 100 transcoders on multimodal embeddings from the MIMIC-CXR dataset, we discover approximately 5,000 monosemantic patterns spanning cardiac, pulmonary, pleural, structural, device, and artifact categories. Each pattern exhibits consistent activation behavior across images sharing specific radiological features, enabling transparent attribution where predictions decompose into 20-50 interpretable patterns with verifiable activation galleries. CXR-LanIC achieves competitive diagnostic accuracy on five key findings while providing the foundation for natural language explanations through planned large multimodal model annotation. Our key innovation lies in extracting interpretable features from a classifier trained on specific diagnostic objectives rather than general-purpose embeddings, ensuring discovered patterns are directly relevant to clinical decision-making, demonstrating that medical AI systems can be both accurate and interpretable, supporting safer clinical deployment through transparent, clinically grounded explanations.
  </details>
