# 🔍 Med_Foundation_Models Papers · 2026-11-16

[![Total Papers](https://img.shields.io/badge/Papers-5-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[When Do Histology Foundation Models Need Geometric Test-Time Augmentation?](https://arxiv.org/abs/2611.21565)**  `arXiv:2611.21565`  `cs.CV` `cs.LG`  
  _Lars Chen, Valentino F. Foit, Dorry Segev, Michal Mankowski_
  <details open><summary>Abstract</summary>
  Test-time augmentation (TTA) aggregates model predictions across multiple transformed views of an input during inference. Because histology images lack a canonical orientation, $D_4$ TTA---pooling across the 8 rotations and reflections of a square---is a standard default in computational pathology. However, the rise of self-supervised histology foundation models (FMs) with inherent rotational invariance calls its continued utility into question. We benchmark 9 histology FMs and 6 general-purpose models across four patch-level and two whole-slide image (WSI) datasets. We find that $D_4$ TTA remains a reliable post hoc improvement, but benefits diminish from $+1.98$ percentage points (pp) for general-purpose backbones to $+0.50$ pp for histology FMs on TCGA-UT, and shrink further for the largest models. To eliminate computational overhead, our experiments demonstrate that entropy routing---applying TTA selectively to uncertain predictions---recovers most of the gain while augmenting only ${\sim}13\%$ of samples. Finally, we show that patch-level TTA improvements do not transfer to slide-level multiple instance learning (MIL). Code:this https URL
  </details>

- **[What Matters for Cross-Modal Alignment](https://arxiv.org/abs/2611.20000)**  `arXiv:2611.20000`  `cs.CV` `cs.AI`  
  _Yipeng Sun, Jiajun Wang, Siyuan Mei, Yan Xia, Siming Bayer, Vincent Christlein, et al._
  <details open><summary>Abstract</summary>
  The Platonic Representation Hypothesis posits that models trained on different modalities converge toward a shared representation. Related work aligns frozen image and text encoders on natural images without paired data. We test zero-pair alignment on five datasets across four modalities: natural images, environmental audio, chest radiographs, and 3D computed tomography (CT). It succeeds only on COCO and fails on the other four. We analyze the failures and find that alignment must first locate the subspace where the modalities co-vary and then orient the mapping within it. Consistent with previous studies, medical imaging is the hardest case: its shared subspace carries the smallest fraction of the variance. When this fraction is small, alignment needs image-text pairs, and random-matrix theory predicts how many pairs are needed. These findings motivate LightAlign: a few pairs let a ridge regression between two frozen encoders locate and orient the mapping simultaneously, and a classifier fitted only on report text then predicts findings from the mapped images. On 3D CT, LightAlign surpasses models trained end to end on image-report pairs without finding-level labels: with only 200 pairs, LightAlign outperforms CT-CLIP on CT-RATE (0.754 vs. 0.733 AUROC), and with only 100 CT-RATE pairs, it does so on RAD-ChestCT, an out-of-distribution dataset from a different hospital. On CheXpert, it reaches 0.862 mean AUROC with only about 5% as many pairs as models trained on MIMIC-CXR.
  </details>

- **[Where slide-level foundation-model classifiers fail on atypical breast lesions](https://arxiv.org/abs/2611.19630)**  `arXiv:2611.19630`  `cs.CV` `cs.AI`  
  _Nerea Hernandez, Luis J. Herrera, Cesar Ramirez, Olga Valenzuela, Ignacio Rojas, Francisco M. Ortuño_
  <details open><summary>Abstract</summary>
  Whether a ductal breast lesion is called atypical hyperplasia or low-grade carcinoma in situ increasingly determines surgery. However, slide-level classifiers built on pathology foundation models (PFMs) perform worst on these lesions. Using four PFMs, cross-validation on BRACS and preregistered hypotheses, we studied where the classification of atypia fails. Because slides are labelled with their most severe lesion, only 39% of the slides with annotated atypical ductal hyperplasia (ADH) were labelled ADH. Attention ranked the lesion high but rarely first, and showing the model only the lesion helped little, whereas classifiers trained per decision with lesion-level labels improved all four atypical boundaries. ADH regions inserted into benign slides raised the probability of malignancy more than that of atypia. In a hospital with pathologist-labelled single-subtype slides and in HISTAI, benign slides were scored closer to lesions and triage specificity fell from 0.48-0.53 to 0.00-0.07 and 0.22.
  </details>

- **[HEmIF-Bench: Benchmarking H&E-to-mIF Models BeyondVirtual-StainFidelity](https://arxiv.org/abs/2611.19905)**  `arXiv:2611.19905`  `cs.CV`  
  _Fuxian Zhao, Hyokeun Park_
  <details open><summary>Abstract</summary>
  Hematoxylin and eosin (H&E)-to-multiplex immunofluorescence (mIF) generators predict spatial protein expression from routine histology, yet pixel-level marker reconstruction does not establish downstream utility. We present HEmIF-Bench, evaluating five frozen generators across eight datasets spanning molecular, cellular, tissue, and patient scales. HEmIF-Bench decouples internal encoder features from generated outputs, benchmarking both against the pathology foundation reference UNI2. Mirroring the clinical workflow where pathologists rely on mIF to define cell phenotypes, delineate tertiary lymphoid structures (TLSs) and germinal centers (GCs), and stratify patient risk, we evaluate external CD3 recovery, single-cell classification, dense nuclear segmentation, TLS/GC segmentation, and patient survival prediction. Across the benchmark, foundation-model-based MIPHEI-ViT leads among the generators, while non-foundation models show task-specific strengths. Comparing the two routes reveals that internal encoder features generally outperform generated outputs, and larger output marker panels do not guarantee stronger downstream utility across datasets. Moreover, neither internal encoder features nor generated outputs consistently surpass frozen UNI2. These findings show that pixel-level stain fidelity does not equate to downstream utility, and that generators trained at current paired-data scales have yet to surpass large-scale pure-H&E foundation models. With the expansion of paired translation cohorts and the advancement of foundation-based generative architectures, HEmIF-Bench establishes a definitive benchmark for tracking when H&E-to-mIF generation crosses the threshold to deliver genuine value beyond routine histology for tumor microenvironment analysis and precision oncology.
  </details>

- **[Unlocking Fine-Grained Cell Representations via Soft-Interior Rim Dense-Grid Pooling in Pathology Foundation Models](https://arxiv.org/abs/2611.19325)**  `arXiv:2611.19325`  `cs.CV`  
  _Wenwen Lou, Mingyi He, Xinyi Guo, Yining Li, Weiming Chen, Jiawen Li, et al._
  <details open><summary>Abstract</summary>
  Fine-grained cell representations are essential for characterizing cellular heterogeneity and tissue organization in computational pathology. Pathology foundation models (PFMs) provide powerful pretrained features for transferable tissue analysis. HoVer-Net uses task-trained segmentation and typing, whereas CellViT++ averages native-grid tokens assigned to detected nuclei. However, the former requires cell-specific training; the latter ignores fractional nuclear coverage and can mix nuclear content with neighbouring tissue. Therefore, we propose SRDP, short for Soft-interior Rim Dense-grid Pooling, a training-free geometry-aware readout. We apply the frozen patch projection at half stride, interleave four offset lattices, map the cell mask to fractional coverage weights, and concatenate whole-cell pooling with two inner boundary pools. Across four datasets and six frozen encoders, SRDP improves mean balanced accuracy by 5.68 percentage points over native token averaging across 24 settings, including 11.22 points on average for CoNIC and Lizard. SRDP converts a coarse frozen PFM lattice into a mask-aligned, fine-grained cell representation without updating the encoder.
  </details>
