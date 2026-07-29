# 🔍 Med_Foundation_Models Papers · 2026-07-28

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Beyond Counts: A Distributional Robustness Margin For Pathology Foundation Models](https://arxiv.org/abs/2607.25497)**  `arXiv:2607.25497`  `cs.CV` `cs.AI`  
  _Clément Grisi, Jeroen van der Laak, Geert Litjens_
  <details open><summary>Abstract</summary>
  Pathology foundation models are approaching clinical deployment, yet remain vulnerable to systematic non-biological variation across centres. Differences in tissue preparation, staining and scanning are strongly encoded in their representations, enabling shortcut learning and weakening generalisation across cohorts and institutions. The Robustness Index (RI) quantifies whether local representation geometry is dominated by biology or by non-biological variation, but its count-based formulation discards distance information. We show that adding distance weights changes little because the deeper limitation lies in RI's pooled, fixed-neighbourhood design, which obscures sample-level heterogeneity and effectively evaluates only a model-dependent subset of samples. We introduce the Cross-confounder Robustness Margin (CRoMa), a sample-resolved measure that directly compares distances to cross-confounder biological matches and same-confounder biological distractors. CRoMa recasts robustness as a cohort-wide margin distribution rather than a single pooled score. We evaluated frozen representations from 20 tile-level encoders across three benchmarks and 4 slide-level encoders on a fourth. Rankings by median CRoMa were broadly consistent across datasets, while the underlying distributions revealed substantial within-model heterogeneity. Every tile encoder retained a confounder-dominated lower tail, whose prevalence and severity varied markedly across models. These distinct robustness profiles frame model selection as a Pareto trade-off between typical and lower-tail robustness. Higher CRoMa was also associated with smaller shortcut-induced performance drops after supervised adaptation. By turning representation geometry into a distributional robustness readout that anticipates downstream shortcut susceptibility, CRoMa provides a principled basis for robustness assessment and model selection.
  </details>

- **[Detect Before You Leap: Mirage Detection in Vision-Language Models](https://arxiv.org/abs/2606.00435)**  `arXiv:2606.00435`  `cs.CV` `cs.AI`  
  _Sayeed Shafayet Chowdhury, Md. Shaown Miah, S. M. Taiabul Haque, Syed Ishtiaque Ahmed_
  <details open><summary>Abstract</summary>
  Vision-language models (VLMs) can produce confident visual answers even when the required visual evidence is missing, blank, or unrelated to the question. This failure mode, recently described as mirage (Asadi et al., 2026), is especially concerning in medical and document VQA, where visually ungrounded answers may be mistaken for image-based evidence. We study pre-release mirage detection: given an image-question pair, determine whether a VLM's answer should be released or the system should abstain before the answer reaches the user. We propose Text-Conditioned Layer-wise Internal Alignment (TC-LIA), a model-agnostic method that probes patch-token representations across the layers of a CLIP ViT-H/14 vision encoder. The key idea is to project layer-wise image patch tokens into the final CLIP embedding space and measure their similarity with the question embedding, tracking whether question-relevant visual evidence emerges across vision layers. TC-LIA summarizes this trajectory using final image-text cosine similarity, late-layer top-k patch-text alignment, early-to-late gain, and layer-wise slope. These features are combined with pixel-statistic-based blank/noise detection, zero-shot domain routing, and structured VLM self-assessment in an ensemble classifier. We evaluate on 19,004 samples spanning ten VQA domains, including medical imaging, document understanding, scene text, reasoning, and video understanding, with four input conditions: RELATED, IN-DOMAIN UNRELATED, OUT-OF-DOMAIN UNRELATED, and BLANK/NOISE. Across fourteen VLMs, base prompt mirage rates range from 57.3-75.0%. TC-LIA alone reduces the mirage rate to 7.5% at 83.5% accuracy; ensemble fusion further improves performance to 84.5-88.4% accuracy with 5.7-7.2% mirage rates. The best result, obtained with Qwen2.5-VL-72B, achieves 88.4% accuracy and a 6.4% mirage rate.
  </details>
