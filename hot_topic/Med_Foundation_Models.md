# 🔍 Med_Foundation_Models Papers · 2026-07-25

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[M$^3$-Gen: Interpretable Multimodal Generation of Gene Expression Profiles Using Clinical and Imaging Data](https://arxiv.org/abs/2607.21343)**  `arXiv:2607.21343`  `cs.LG` `cs.AI` `cs.CV`  
  _Francesca Pia Panaccione, Carlo Sgaravatti, Marco Venere_
  <details open><summary>Abstract</summary>
  Integrating heterogeneous biomedical data, including clinical metadata, histopathology images, and molecular profiles, is crucial for comprehensive disease understanding. However, gene expression data acquisition remains constrained by high costs and privacy concerns, limiting its use in multimodal research and AI-driven applications. We present MultiModal Molecular Generation (M$^3$-Gen), a novel framework for the generation of gene expression profiles by conditioning a Generative Adversarial Network on histopathology images and clinical metadata. M$^3$-Gen learns a unified latent representation from the clinical variables and the images, leveraging contrastive learning, and exploits the embeddings of the two modalities to guide a generative model in producing biologically coherent gene expression profiles. Evaluations on the TCGA dataset demonstrate that M$^3$-Gen generates realistic and functionally meaningful gene expression data. Importantly, by integrating multiple modalities in an attention-based mechanism, M$^3$-Gen provides intrinsic explainability: it allows the identification of which regions of the histopathology images most strongly influenced the generation of specific gene expression profiles, making the model's decisions interpretable by design.
  </details>

- **[GigaPath-Flash and GigaTIME-Flash: Efficient Pathology Foundation Models for Whole-Slide and Tumor Microenvironment Analysis](https://arxiv.org/abs/2607.18218)**  `arXiv:2607.18218`  `cs.CV` `cs.AI`  
  _Naoto Usuyama, Jeya Maria Jose Valanarasu, Sicong Yao, Hanwen Xu, Jaspreet Bagga, Guanghui Qin, et al._
  <details open><summary>Abstract</summary>
  Foundation models have emerged as a driving force in computational pathology, with the potential to transform cancer diagnosis, prognosis, and treatment selection by learning transferable representations from large-scale histopathology data. A growing landscape of pathology foundation models now spans diverse data sources, architectures, and downstream applications. However, most pretrained models operate only at the image-tile level, use restrictive licenses, and remain computationally expensive, limiting large-scale slide-level clinical and research use.Here, we introduce GigaPath-Flash and GigaTIME-Flash, efficient models for whole-slide pathology AI and spatial proteomics prediction. GigaPath-Flash combines a 22M-parameter ViT-S tile encoder with a 21M-parameter LongNet slide encoder, both pretrained on large-scale real-world histopathology data. Its compact tile encoder is distilled from the billion-parameter GigaPath (ViT-g) teacher and shared by both models. GigaPath-Flash retains 97% of GigaPath's average slide-level performance with 50x less compute. GigaTIME-Flash extends this backbone to predict the tumor immune microenvironment directly from routine H&E images. It surpasses the original CNN-based GigaTIME in prediction quality while running 6x faster and using 8x less GPU memory.Together with GigaPath and GigaTIME, these models form an open-weight, Apache-2.0-licensed family pretrained on large-scale real-world clinical data. By releasing all models and weights, we provide accessible building blocks for computational pathology, immuno-oncology, and precision health.
  </details>
