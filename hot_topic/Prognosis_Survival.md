# 🔍 Prognosis_Survival Papers · 2026-05-18

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[Attention-Aware Transformer-Based Aggregation Network for Video Periocular Recognition](https://arxiv.org/abs/2605.16550)**  `arXiv:2605.16550`  `cs.CV` `cs.LG`  
  _Luiz G F Carreira, Breno A Mariano, Victor H C de Melo, David Menotti, William Robson Schwartz_
  <details open><summary>Abstract</summary>
  Video periocular recognition is the task of recognizing an individual's identity based on the region around an individual's eyes. The periocular area is one of the most discriminative regions of the human face, making it suitable for recognition tasks. Its use as a biometric modality has emerged as an alternative, especially in surveillance scenarios where conventional biometric traits such as face or iris recognition become unfeasible due to unconstrained acquisition conditions. This paper proposes an attention-aware approach for video-based periocular recognition in surveillance environments. The framework consists of two main modules: feature embedding and aggregation. The feature embedding module is a deep convolutional neural network that maps periocular data to feature vectors. The aggregation module is an encoder-only transformer that adaptively learns to aggregate frame-level features into a single video representation and a feature vector for the still reference image. Experiments on the publicly available COX Face dataset show the robustness of the proposed method, consistently outperforming naive aggregation schemes. In the best scenario, the approach achieves $99.8\%$ of TPR@$1e^{-1}$ and $96.6\%$ of Rank-5.
  </details>

- **[SynVA: A Modular Toolkit for Vessel Generation and Aneurysm Editing](https://arxiv.org/abs/2605.17620)**  `arXiv:2605.17620`  `cs.CV` `cs.AI` `cs.LG`  
  _Marten J. Finck, Niklas C. Koser, Sarker M. Mahfuz, Tameem Jahangir, Jon E. Wilhelm, Daniel Behme, et al._
  <details open><summary>Abstract</summary>
  Intracranial aneurysms (IAs), characterized by unpredictable growth and risk of rupture, are a major cause of stroke and can lead to life-threatening hemorrhages with high mortality and long-term disability. With aging populations, the incidence and overall burden of cerebrovascular diseases are expected to increase, highlighting the need for scalable approaches to analyze complex medical data and improve population-level understanding of these conditions. While digital twins and deep learning offer promising avenues for improving diagnosis, prognosis, and treatment, their effectiveness is limited by the scarcity of large-scale, high-quality medical data and corresponding labels. We present Synthetic VAsculature (SynVA), a modular toolkit for vascular mesh generation and anatomically consistent aneurysm synthesis. SynVA combines novel flow-matching-based methods for generating healthy vessel meshes with learning-based approaches for anatomy-conditioned aneurysm mesh generation - aneurysms are computed from pre-existing vascular geometries rather than being generated in isolation. In addition, we introduce the SynVA procedural model for vascular and aneurysm synthesis based solely on physiological principles and statistical priors, which enables the generation of large-scale datasets (e.g., for the training of mesh-based generative models). To this end, we release a dataset of 50,000 fully labeled mesh samples for a variety of downstream vision tasks, such as semantic segmentation. Extensive quantitative and qualitative evaluations demonstrate that SynVA generates realistic vessel geometries and anatomically plausible aneurysms. Specifically, our experiments indicate that some methods produce aneurysm shapes more aligned with expert human perception while others perform better on quantitative similarity metrics with reconstructions of real aneurysms.
  </details>
