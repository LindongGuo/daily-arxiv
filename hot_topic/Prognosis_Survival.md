# 🔍 Prognosis_Survival Papers · 2026-05-03

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Prognosis,Deep Learning` `Survival Analysis,WSI` `Survival Prediction,Multimodal` `Risk Stratification,Pathology` `Cox,Neural Network`  
**Filter**: `None`

---

## 📚 Paper List

- **[Structural Prognostic Event Modeling for Multimodal Cancer Survival Analysis](https://arxiv.org/abs/2512.01116)**  `arXiv:2512.01116`  `cs.CV`  
  _Yilan Zhang, Li Nanbo, Changchun Yang, Jürgen Schmidhuber, Xin Gao_
  <details open><summary>Abstract</summary>
  The integration of histology images and gene profiles has shown great promise for improving survival prediction in cancer. However, current approaches often struggle to model intra- and inter-modal interactions efficiently and effectively due to the high dimensionality and complexity of the inputs. A major challenge is capturing critical prognostic events that, though few, underlie the complexity of the observed inputs and largely determine patient outcomes. These events, manifested as high-level structural signals such as spatial histologic patterns or pathway co-activations, are typically sparse, patient-specific, and unannotated, making them inherently difficult to uncover. To address this, we propose SlotSPE, a slot-based framework for structural prognostic event modeling. Specifically, inspired by the principle of factorial coding, we compress each patient's multimodal inputs into compact, modality-specific sets of mutually distinctive slots using slot attention. By leveraging these slot representations as encodings for prognostic events, our framework enables both efficient and effective modeling of complex intra- and inter-modal interactions, while also facilitating seamless incorporation of biological priors that enhance prognostic relevance. Extensive experiments on ten cancer benchmarks show that SlotSPE outperforms existing methods in 8 out of 10 cohorts, achieving an overall improvement of 2.9%. It remains robust under missing genomic data and delivers markedly improved interpretability through structured event decomposition.
  </details>
