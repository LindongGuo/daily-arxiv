# 🔍 Med_Foundation_Models Papers · 2026-09-20

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Beyond Benchmark Scores: Auditing Medical Vision-Language Models for Chest X-Ray Tuberculosis Screening](https://arxiv.org/abs/2609.21763)**  `arXiv:2609.21763`  `cs.CV` `cs.LG`  
  _Mushir Akhtar, M. Tanveer, Mohd. Arshad_
  <details open><summary>Abstract</summary>
  A medical model's benchmark score does not establish that the same conclusion holds under a different evaluation. This study tests whether claims about model ranking, score reliability and screening performance survive changes in cohort, prompt, negative spectrum, specified prevalence and operating threshold. We audit three medical vision-language models (BioMedCLIP, CheXficient, and MedSigLIP) and a general-domain OpenCLIP comparator on 12,200 chest radiograph records from four datasets (Montgomery, Shenzhen, TBX11K, and VinDr-CXR). Five fixed prompt families yield 244,000 model--image--prompt scores. No model leads every cohort and reliability criterion. Prompt-family changes alter AUROC in 21 of 48 multiplicity-controlled comparisons. Replacing healthy controls with sick non-tuberculosis controls reduces AUROC by 0.075--0.306 across all four models. On VinDr-CXR, the three medical models distinguish tuberculosis from no-finding controls substantially better than from pneumonia or lung tumor; their AUROC point estimates for both named diseases fall below 0.5. CheXficient has documented VinDr-CXR pretraining exposure, which limits the interpretation of its results. Thresholds chosen for 95\% sensitivity on TBX11K training retain that constraint by point estimate in only four of sixteen target evaluations. A five-seed supervised source model reaches 0.999 AUROC on TBX11K validation but 0.629 on each of two external cohorts. Conservative exclusion of perceptual-overlap candidates narrows this gap without closing it. These retrospective, single-task results show that discrimination, score reliability and threshold retention support different portability claims. Evidence for chest X-ray tuberculosis screening should identify the complete evaluation specification rather than attribute clinical portability to a checkpoint alone.
  </details>

- **[A Principled Approach to Unsupervised Anomaly Detection](https://arxiv.org/abs/2609.21800)**  `arXiv:2609.21800`  `cs.CV`  
  _James Myles, Matthew Baugh, Johanna P. Müller, Bernhard Kainz, Yingzhen Li_
  <details open><summary>Abstract</summary>
  Traditional unsupervised anomaly detection (UAD) methods are designed to flag or localise deviations from a normative distribution, ignoring the underlying generative mechanisms of the anomalies. Yet the nature of an anomaly is often as important as its presence. We reformulate UAD as a Bayesian inverse problem, in which the objective is to infer the most probable corruption responsible for each observation. Our framework yields a probabilistic anomaly score as the energy of the inferred corruption parameters, and serves as a principled recipe for developing new UAD algorithms. We derive several existing methods as instances of the general framework, each corresponding to the same energy score under different modelling choices. Experimentally, we study the framework's components in a controlled setting, and improve object-class AUROC on the MVTec AD dataset by 2.3% by adapting the underlying corruption model. Finally, we validate the framework on a brain MRI benchmark, achieving strong detection performance while producing estimates of pathology intensity, bias, and geometry. Code is available atthis https URL.
  </details>
