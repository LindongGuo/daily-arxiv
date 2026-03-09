# 🔍 Med_Foundation_Models Papers · 2026-03-08

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Prompt Group-Aware Training for Robust Text-Guided Nuclei Segmentation](https://arxiv.org/abs/2603.06384)**  `arXiv:2603.06384`  `cs.CV` `cs.AI`  
  _Yonghuang Wu, Zhenyang Liang, Wenwen Zeng, Xuan Xie, Jinhua Yu_
  <details open><summary>Abstract</summary>
  Foundation models such as Segment Anything Model 3 (SAM3) enable flexible text-guided medical image segmentation, yet their predictions remain highly sensitive to prompt formulation. Even semantically equivalent descriptions can yield inconsistent masks, limiting reliability in clinical and pathology workflows. We reformulate prompt sensitivity as a group-wise consistency problem. Semantically related prompts are organized into \emph{prompt groups} sharing the same ground-truth mask, and a prompt group-aware training framework is introduced for robust text-guided nuclei segmentation. The approach combines (i) a quality-guided group regularization that leverages segmentation loss as an implicit ranking signal, and (ii) a logit-level consistency constraint with a stop-gradient strategy to align predictions within each group. The method requires no architectural modification and leaves inference unchanged. Extensive experiments on multi-dataset nuclei benchmarks show consistent gains under textual prompting and markedly reduced performance variance across prompt quality levels. On six zero-shot cross-dataset tasks, our method improves Dice by an average of 2.16 points. These results demonstrate improved robustness and generalization for vision-language segmentation in computational pathology.
  </details>

- **[WMoE-CLIP: Wavelet-Enhanced Mixture-of-Experts Prompt Learning for Zero-Shot Anomaly Detection](https://arxiv.org/abs/2603.06313)**  `arXiv:2603.06313`  `cs.CV`  
  _Peng Chen, Chao Huang_
  <details open><summary>Abstract</summary>
  Vision-language models have recently shown strong generalization in zero-shot anomaly detection (ZSAD), enabling the detection of unseen anomalies without task-specific supervision. However, existing approaches typically rely on fixed textual prompts, which struggle to capture complex semantics, and focus solely on spatial-domain features, limiting their ability to detect subtle anomalies. To address these challenges, we propose a wavelet-enhanced mixture-of-experts prompt learning method for ZSAD. Specifically, a variational autoencoder is employed to model global semantic representations and integrate them into prompts to enhance adaptability to diverse anomaly patterns. Wavelet decomposition extracts multi-frequency image features that dynamically refine textual embeddings through cross-modal interactions. Furthermore, a semantic-aware mixture-of-experts module is introduced to aggregate contextual information. Extensive experiments on 14 industrial and medical datasets demonstrate the effectiveness of the proposed method.
  </details>
