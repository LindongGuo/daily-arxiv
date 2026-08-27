# 🔍 Med_Foundation_Models Papers · 2026-08-26

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Resolving Multi-Modal Regression by Difference-Quotient-Based Clustering:Fast Coarse Conditional-Label Assignment](https://arxiv.org/abs/2608.25467)**  `arXiv:2608.25467`  `cs.LG`  
  _Huang Weiquan_
  <details open><summary>Abstract</summary>
  Multimodal regression suffers from the mean-collapse pathology: under squared loss, an unconstrained regressor converges to the conditional mean, which for K > 1 lies away from all modes. We attribute this failure to pairwise contradictions--samples with nearly identical inputs but distant outputs--and propose Difference-Quotient Clustering (DQC), which partitions data to minimize intra-cluster output-vs-input discrepancy. Each sample is assigned to the cluster that minimizes its maximum contradiction ratio; a logits generator and a conditional network are then trained on the resulting labels. Since the generating modality is unknown at test time, we evaluate via minimum squared error (minMSE) against all K true outputs. On synthetic benchmarks (K=5, 10), DQC achieves test minMSE 0.19 (K=5, nx=500), versus 0.09 for an oracle, 1.08 for random labels, and 1.33 for mean collapse. We observe two empirical regularities: larger intra-cluster contradictions require deeper networks, and oracle labels generalize from fewer samples than cluster-derived equivalents. The clustering is a hard, parallelizable O(n^2/2) front-end for coarse conditional assignment, reducing the burden of downstream generative refinement. A second-stage re-clustering on residual errors is outlined as future work.
  </details>

- **[Auditable CT Phenotyping Through Report-derived Radiological Observations](https://arxiv.org/abs/2608.25948)**  `arXiv:2608.25948`  `cs.CV`  
  _Riga Wu, Walter Witschey, Yicheng Li, Felix Barajas Ordonez, Keno K. Bressem, Lisa C. Adams, et al._
  <details open><summary>Abstract</summary>
  Medical image foundation models can predict clinical phenotypes from computed tomography (CT), but strong performance leaves open whether they read disease-specific findings or shortcuts that correlate with the diagnosis. We tested this in 221 electronic-health-record (EHR) phenotypes using Auditable CT phenotyping (ACT), built on report-derived radiological observations. We trained ACT on 38,317 patients, mined 376,194 observations and evaluated it in 25,183 held-out patients. ACT exceeded five vision-language baselines on zero-shot annotation, and CT-CLIP across 221 phenotypes from unseen CT pulmonary angiography, both under zero-shot scoring (0.651 versus 0.572) and under linear probing (0.709 versus 0.662). Reading each probe exposes what accuracy conceals: only 97 observations occupy the 221 rank-1 positions, and one phrase describing aortic and coronary calcification ranks first for 20 phenotypes, including osteoporosis, urinary tract infection and major depressive disorder. Restricting the bank to clinician-specified evidence redirects those probes onto phenotype-related observations in 86 phenotypes at no accuracy cost (0.751 versus 0.741). Accurate CT-based EHR phenotyping can therefore rest on observations that are not valid evidence for the coded phenotype and that ACT can identify and intervene on.
  </details>

- **[Label-Free Foundational Model Selection for Medical Image Classification under Distribution Shift via Pseudo Label Discrepancy](https://arxiv.org/abs/2608.25810)**  `arXiv:2608.25810`  `cs.CV`  
  _Juan Iñaki Larrea, Lucas Mansilla, Enzo Ferrante_
  <details open><summary>Abstract</summary>
  Foundation models are increasingly deployed for medical image analysis. However, under the inter-institutional distribution shift typical of deployment, their performance varies widely and cannot be known without target-domain labels, which are rarely available. This leaves a practical question unresolved: given several candidate foundational models and labeled-data from a source domain, which one to deploy in an unlabeled target domain? We propose a label-free selection criterion built on SUDO, a framework for evaluating clinical AI systems without ground-truth annotations. SUDO partitions the unlabeled target data by predicted probability and, for each region, measures a pseudo-label discrepancy reflecting class contamination; aggregated across regions, this yields a score (AURCC) requiring neither target annotation nor fine-tuning. We show that AURCC can be used to rank a variety of vision-language models (BioMedCLIP, CXR-CLIP, CheXzero, MedCLIP, MedImageInsight, CLIP) on chest X-ray classification across three inter-hospital shift scenarios, under zero-shot and MLP-probe regimes. The AURCC ranking recovers the ground-truth ranking with Spearman rho up to 0.943 (p<0.05). Against the natural baseline of ranking by held-out source accuracy, AURCC is competitive when the labeled source is large and yields a more accurate ranking once it is small; the regime of interest in resource-constrained settings.
  </details>
