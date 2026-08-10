# 🔍 Med_Foundation_Models Papers · 2026-08-09

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Explanation Stability of Test-Time Adaptation in Computational Pathology: A Large-Scale Benchmark](https://arxiv.org/abs/2608.07062)**  `arXiv:2608.07062`  `cs.CV`  
  _R. G. Bahumanya, Harshith V. M., Shreyank N. Gowda, Anala M. R_
  <details open><summary>Abstract</summary>
  Test-time adaptation (TTA) has become a practical way to adapt deployed models to unlabeled target data, a setting that is especially relevant in computational pathology where staining, scanner, and cohort shifts are routine. While most TTA methods are evaluated by their effect on accuracy, clinical use also depends on whether the model's explanations remain reliable after adaptation. In this paper, we take a closer look at this largely unmeasured effect. We study explanation stability under TTA across two histopathology benchmarks, Camelyon17 and NCT CRC-HE, using five architectures ranging from convolutional networks to vision transformers and a pathology foundation model, seventeen TTA methods, and four attribution families. Across 2,958 adaptation runs, we observe a clear and systematic pattern: TTA methods differ sharply in how much they move model explanations, with frozen-backbone methods leaving attributions almost unchanged and continual methods such as CoTTA and RoTTA causing the largest drift. This effect is not uniform. Convolutional networks are substantially more sensitive than transformer and foundation-model backbones, and explanation drift increases with adaptation strength while remaining largely insensitive to batch size. Surprisingly, explanation stability is only weakly coupled to adaptation quality. Some methods preserve explanations almost perfectly while degrading calibration or accuracy, producing silent failures that would be missed by accuracy-only or explanation-only evaluation. These findings show that explanation stability is a distinct reliability axis for TTA in computational pathology. We release the metric, protocol, and full benchmark to support future work on adaptation methods that are not only accurate, but also stable and clinically auditable. Code:this https URL
  </details>

- **[Pathryoshka: Compressing Pathology Foundation Models via Multi-Teacher Knowledge Distillation with Nested Embeddings](https://arxiv.org/abs/2511.23204)**  `arXiv:2511.23204`  `cs.CV`  
  _Christian Grashei, Christian Brechenmacher, Rao Muhammad Umer, Jingsong Liu, Carsten Marr, Ewa Szczurek, et al._
  <details open><summary>Abstract</summary>
  Pathology foundation models (FMs) have driven significant progress in computational pathology. However, these high-performing models can easily exceed a billion parameters and produce high-dimensional embeddings, thus limiting their applicability for research or clinical use when computing resources are tight. Here, we introduce Pathryoshka, a multi-teacher distillation framework inspired by RADIO distillation and Matryoshka Representation Learning to reduce pathology FM sizes while allowing for adaptable embedding dimensions. We evaluate our framework with a distilled model on ten public pathology benchmarks with varying downstream tasks. Compared to its much larger teachers, Pathryoshka reduces the model size by 86-92% at on-par performance. It outperforms state-of-the-art single-teacher distillation models of comparable size by a median margin of 7.0 in accuracy. By enabling efficient local deployment without sacrificing accuracy or representational richness, Pathryoshka democratizes access to state-of-the-art pathology FMs for the broader research and clinical community.
  </details>
