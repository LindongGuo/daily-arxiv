# 🔍 Med_Foundation_Models Papers · 2026-10-17

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Pathology foundation models for training-free case retrieval in salivary gland tumors](https://arxiv.org/abs/2610.22087)**  `arXiv:2610.22087`  `cs.CV`  
  _Maximilian J. Roesel, Niklas Kiermeyer, Philipp Keyl, Frederick Klauschen_
  <details open><summary>Abstract</summary>
  In pathology, pattern recognition relies on a frame of reference built through extensive training and experience, which may still fall short when encountering rare cancer subtypes. Archives of previously diagnosed tumors often contain relevant precedents, yet identifying the most relevant cases remains challenging. Here we explore whether content-based retrieval with current pathology foundation models facilitates rare cancer diagnostics without any task-specific training. Pathologists can query a digitized archive using a region of interest (ROI) from a whole slide image (WSI) and retrieve morphologically similar cases, along with their ICD-O codes and corresponding WSIs. The ROI can be selected manually or automatically using a gated attention-based multiple instance learning model. We evaluate our approach by leave-one-case-out on an imbalanced dataset of 137 salivary gland tumor cases spanning 12 ICD-O morphology categories, comparing four pathology foundation models (Atlas2, Atlas2-B, Atlas2-S, and UNI2h). Top-1/3/5 retrieval was 62.5%/76.7%/81.3% for Atlas2, 50.2/66.6/72.9% for UNI2h, 52.3%/71.5%/77.6% for Atlas2-B and 54.4/65.2/73.7% for Atlas2-S. Macro-averaged F1 ranged from 69.0% for the smallest model Atlas2-S to 76.6% for the largest model Atlas2 across the five classes with at least ten cases. Our modified Chamfer similarity separated correct from incorrect matches among the Top-5 more reliably for Atlas2 (AUC 0.754) than for Atlas2-B (0.679, p = 0.020) and Atlas2-S (0.653, p = 0.003), but not UNI2h (0.697, p = 0.196). Requiring no additional training or manual annotation, this approach makes departmental archives searchable with pathology foundation models, providing a low-barrier route to case-based differential diagnosis and extending the individual frame of reference to the collective experience of the department.
  </details>

- **[Beyond Sparse Captions: Aligning Slide-Level Text and Patch-Level Vision in Pathology](https://arxiv.org/abs/2610.17233)**  `arXiv:2610.17233`  `cs.CV`  
  _Daniel Shao, Dongmin Bang, Luca L. Weishaupt, Sophia J. Wagner, Nic G. Reitsam, Ming Y. Lu, et al._
  <details open><summary>Abstract</summary>
  Contrastive vision-language (VL) pretraining in computational pathology has generally relied on curated image-caption datasets sourced from social media, educational videos, and research publications. These corpora are sparse relative to the diversity of tissue morphology and difficult to scale further, as pathologists do not routinely produce descriptive captions in clinical practice. We propose to instead leverage slide-level pathology reports which can be generated during routine diagnostic workflows in a scalable manner. A key challenge in this weakly-supervised setting is that pathology reports describe macroscopic, diagnostic findings while patch-level visual features describe microscopic findings. We introduce Locked Image Multiple Instance PreTraining (LIMIT), which addresses this gap by freezing a pretrained vision encoder and fine-tuning only the text encoder: report embeddings serve as cross-attention queries over bags of patch features, producing report-conditioned slide representations optimized via InfoNCE. Using LIMIT, we establish CONCH-Z, which aligns the text encoder of CONCH v1.5 to 335k clinical reports. Evaluated across 22 tasks spanning patch-level classification, tumor detection, and slide-level subtyping, CONCH-Z establishes state-of-the-art zero-shot performance over VL encoders trained on curated caption datasets, while simultaneously closing the gap with slide-level foundation models trained with substantially more parameters and compute. The code and model is available atthis https URL.
  </details>
