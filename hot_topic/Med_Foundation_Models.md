# 🔍 Med_Foundation_Models Papers · 2026-03-23

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Interpretable Cross-Domain Few-Shot Learning with Rectified Target-Domain Local Alignment](https://arxiv.org/abs/2603.17655)**  `arXiv:2603.17655`  `cs.CV` `cs.AI`  
  _Yaze Zhao, Yixiong Zou, Yuhua Li, Ruixuan Li_
  <details open><summary>Abstract</summary>
  Cross-Domain Few-Shot Learning (CDFSL) adapts models trained with large-scale general data (source domain) to downstream target domains with only scarce training data, where the research on vision-language models (e.g., CLIP) is still in the early stages. Typical downstream domains, such as medical diagnosis, require fine-grained visual cues for interpretable recognition, but we find that current fine-tuned CLIP models can hardly focus on these cues, albeit they can roughly focus on important regions in source domains. Although current works have demonstrated CLIP's shortcomings in capturing local subtle patterns, in this paper, we find that the domain gap and scarce training data further exacerbate such shortcomings, much more than that of holistic patterns, which we call the local misalignment problem in CLIP-based CDFSL. To address this problem, due to the lack of supervision in aligning local visual features and text semantics, we turn to self-supervision information. Inspired by the translation task, we propose the CC-CDFSL method with cycle consistency, which translates local visual features into text features and then translates them back into visual features (and vice versa), and constrains the original features close to the translated back features. To reduce the noise imported by richer information in the visual modality, we further propose a Semantic Anchor mechanism, which first augments visual features to provide a larger corpus for the text-to-image mapping, and then shrinks the image features to filter out irrelevant image-to-text mapping. Extensive experiments on various benchmarks, backbones, and fine-tuning methods show we can (1) effectively improve the local vision-language alignment, (2) enhance the interpretability of learned patterns and model decisions by visualizing patches, and (3) achieve state-of-the-art performance.
  </details>

- **[Multi-Stage Fine-Tuning of Pathology Foundation Models with Head-Diverse Ensembling for White Blood Cell Classification](https://arxiv.org/abs/2603.20383)**  `arXiv:2603.20383`  `cs.CV`  
  _Antony Gitau, Martin Paulson, Bjørn-Jostein Singstad, Karl Thomas Hjelmervik, Ola Marius Lysaker, Veralia Gabriela Sanchez_
  <details open><summary>Abstract</summary>
  The classification of white blood cells (WBCs) from peripheral blood smears is critical for the diagnosis of leukemia. However, automated approaches still struggle due to challenges including class imbalance, domain shift, and morphological continuum confusion, where adjacent maturation stages exhibit subtle, overlapping features. We present a multi-stage fine-tuning methodology for 13-class WBC classification in the WBCBench 2026 Challenge (ISBI 2026). Our best-performing model is a fine-tuned DINOBloom-base, on which we train multiple classifier head families (linear, cosine, and multilayer perceptron (MLP)). The cosine head performed best on the mature granulocyte boundary (Band neutrophil (BNE) F1 = 0.470), the linear head on more immature granulocyte classes (Metamyelocyte (MMY) F1 = 0.585), and the MLP head on the most immature granulocyte (Promyelocyte (PMY) F1 = 0.733), revealing class-specific specialization. Based on this specialization, we construct a head-diverse ensemble, where the MLP head acts as the primary predictor, and its predictions within the four predefined confusion pairs are replaced only when two other head families agree. We further show that cases consistently misclassified by all models are substantially enriched for probable labeling errors or inherent morphological ambiguity.
  </details>
