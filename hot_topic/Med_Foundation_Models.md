# 🔍 Med_Foundation_Models Papers · 2026-06-03

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[A Pathology Foundation Model for Gastric Cancer with Real-World Validation](https://arxiv.org/abs/2606.04792)**  `arXiv:2606.04792`  `cs.CV`  
  _Ling Liang, Jiabo Ma, Zhengyu Zhang, Fengtao Zhou, Yingxue Xu, Yihui Wang, et al._
  <details open><summary>Abstract</summary>
  Gastric cancer remains a major cause of cancer mortality, yet its histological and molecular heterogeneity complicates diagnosis and risk stratification. General-purpose pathology foundation models (PFMs) often plateau on fine-grained endpoints central to gastric cancer care, and few have undergone rigorous prospective validation or clinical reader studies. We present GRACE, a Gastric-specific foundation model for Real-world Assessment and Clinical dEcision support. GRACE was developed from multicenter gastric pathology datasets totaling 48,364 primarily HE-stained whole-slide images from 37,493 patients. When evaluated on 28 clinically relevant tasks, GRACE consistently outperformed representative pancancer PFMs, achieving a macro-AUC of 0.9188, with strong performance for precancerous lesion diagnosis (macro-AUC 0.9322), tumor histopathological assessment (macro-AUC 0.9119), molecular profiling (macro-AUC 0.8682), and prognostic prediction. Beyond benchmarking, GRACE's translational value was substantiated through a rigorous evidence chain. Under safety-gated criteria requiring 100% NPV for rule-out and 100% PPV for rule-in, GRACE streamlined review for up to 69.6% of malignancy-diagnosis cases and triaged 46.8% of MMR-IHC follow-up requests. This translational feasibility was further strengthened by a randomized crossover reader study of pathologist-AI collaboration. With GRACE assistance, diagnostic accuracy improved from 82.0% to 89.9%, yielding nearly twofold higher adjusted odds of a correct diagnosis (OR 1.987) alongside concurrent gains in sensitivity and specificity. AI assistance also reduced diagnostic time by 14.9%, elevated diagnostic confidence by 9.0%, and markedly improved inter-rater agreement. When calibrated to maintain non-inferior performance to senior pathologists, the AI-assisted workflow could triage 60.7% of atrophy and 82.7% of intestinal metaplasia cases.
  </details>

- **[Do Foundation Models See Biology? Evaluating Attention Coherence with Spatial Transcriptomics in Glioblastoma](https://arxiv.org/abs/2606.04764)**  `arXiv:2606.04764`  `cs.CV`  
  _Dilakshan Srikanthan, Amoon Jamzad, Paul Wilson, Nooshin Maghsoodi, Robert Policelli, Gabor Fichtinger, et al._
  <details open><summary>Abstract</summary>
  Whether attention maps from pathology foundation models capture genuine biology remains unknown, yet this question is critical for clinical trust and regulatory approval. We propose a spatial transcriptomics-based framework for orthogonal, hypothesis-free evaluation of attention and apply it to five pathology foundation models (CONCH v1.5, UNI v2, Virchow2, GigaPath, H-Optimus-1) and a ResNet50 baseline. Using attention-based multiple instance learning, we train single-task and multi-task models to predict five molecular alterations in glioblastoma on the CPTAC cohort, validate on an independent TCGA cohort, and evaluate biological coherence of attention maps against 87 transcriptional signatures using co-registered Visium spatial transcriptomics data from 18 samples. Internally, no single encoder dominates across all tasks, and external validation inverts internal performance rankings. Attention maps show a five-fold enrichment gradient from pathways (Cohen's d=0.329) to individual genes (d=0.055), indicating that attention captures emergent multi-gene transcriptional programs rather than individual molecular events. Spatially smooth attention maps do not imply biological coherence, and different encoders attend to distinct biological compartments. Our framework provides objective, quantitative assessment of what foundation models learn from histopathology, moving the field beyond qualitative saliency map review.
  </details>

- **[Hierarchical Self-Supervised Adversarial Training for Robust Vision Models in Histopathology](https://arxiv.org/abs/2503.10629)**  `arXiv:2503.10629`  `cs.CV`  
  _Hashmat Shadab Malik, Shahina Kunhimon, Muzammal Naseer, Fahad Shahbaz Khan, Salman Khan_
  <details open><summary>Abstract</summary>
  Adversarial attacks pose significant challenges for vision models in critical fields like healthcare, where reliability is essential. Although adversarial training has been well studied in natural images, its application to biomedical and microscopy data remains limited. Existing self-supervised adversarial training methods overlook the hierarchical structure of histopathology images, where patient-slide-patch relationships provide valuable discriminative signals. To address this, we propose Hierarchical Self-Supervised Adversarial Training (HSAT), which exploits these properties to craft adversarial examples using multi-level contrastive learning and integrate it into adversarial training for enhanced robustness. We evaluate HSAT on multiclass histopathology dataset OpenSRH and the results show that HSAT outperforms existing methods from both biomedical and natural image domains. HSAT enhances robustness, achieving an average gain of 54.31% in the white-box setting and reducing performance drops to 3-4% in the black-box setting, compared to 25-30% for the baseline. These results set a new benchmark for adversarial training in this domain, paving the way for more robust models. Our Code for training and evaluation is available atthis https URL.
  </details>
