# 🔍 Med_Foundation_Models Papers · 2026-08-01

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Beyond Classification: Pathology Foundation Models as Detection Encoders for Mitotic Figures](https://arxiv.org/abs/2607.28007)**  `arXiv:2607.28007`  `cs.CV` `cs.AI`  
  _Sweta Banerjee, Alireza Teimoury, Nils Porsche, Alexandra K. Stoll, Viktoria Weiss, Niklas Hargarter, et al._
  <details open><summary>Abstract</summary>
  Pathology foundation models (FMs) are models trained on vast amounts of typically unlabeled data and have been shown to yield regularized latent spaces that can be used effectively in downstream classification tasks. This is also true for the classification of mitotic figures vs. other cells. However, it is so far unclear if the latent space of current FMs provides features that are discriminant and spatially suitably resolved to also serve as a backbone for dense object detection paradigms. In this work, we investigate this question for common current pathology FMs (UNI, UNI2-h, Virchow, Virchow2, H-optimus-0, H-optimus-1) and compare their performance against a fully end-to-end trained baseline based on a ResNet50 architecture. We combine FM backbones with representatives of single stage, dual stage and self-attention-based detectors (RetinaNet, Faster R-CNN, Deformable DETR respectively) on the multi-domain MIDOG++ dataset, and on the TUPAC16 dataset as an out-of-domain case. We show that the H-optimus-0 and Virchow models yielded competitive performance, indicating that the latent spaces of current FMs, all trained on image-level self-supervision, are suitable for direct mitotic figure detection and may be slightly more robust on our out-of-domain test case. All code is made available publicly atthis https URL.
  </details>

- **[CXR-Retrieve: Compositional Text-to-Image Retrieval in Chest Radiography](https://arxiv.org/abs/2607.27779)**  `arXiv:2607.27779`  `cs.CV`  
  _Tomer Erez, Moshe Kimhi, Chaim Baskin, Ehud Rivlin_
  <details open><summary>Abstract</summary>
  Large chest radiography archives are difficult to search because most studies are paired only with free-text reports rather than structured clinical annotations. Vision-language models offer a natural interface for text-to-image retrieval, but current biomedical models are primarily optimized for report-to-image matching rather than for satisfying short clinical search queries. This creates an objective mismatch: a model may retrieve images related to words in the query while failing to satisfy the full clinical constraint, especially for conjunctions and negations such as ``atelectasis and no pneumonia.''We introduce CXR-Retrieve, a structured benchmark for compositional chest X-ray text-to-image retrieval. The benchmark contains 5,159 test images from the official test-split of MIMIC-CXR-JPG and 145 textual queries spanning single and conjunction findings, both positive and negative. Relevance is defined by whether a retrieved image satisfies all asserted pathology constraints, rather than by whether it matches a paired report.We further propose a label-aware contrastive fine-tuning objective for clinical retrieval. Our method attracts image-text pairs with compatible asserted pathology constraints, including shared confirmed absences, while explicitly repelling contradictory pairs. Starting from the in-domain CXR-CLIP checkpoint, our method improves Precision@5 over CXR-CLIP by 8.5 percentage points on two-pathology conjunctions and by 22.0 percentage points on negation queries. These results show that reliable chest X-ray retrieval requires training objectives that model not only which findings are mentioned, but also how they are clinically asserted.
  </details>

- **[A report-grounded vision-language foundation model for colonoscopy from 280000 routine reports](https://arxiv.org/abs/2607.28466)**  `arXiv:2607.28466`  `cs.AI`  
  _Jia Yu, Yan Zhu, Yili He, Zilong Wang, Xinyang Jiang, Peiyao Fu, et al._
  <details open><summary>Abstract</summary>
  Vision-language models remain underused in colonoscopy despite the rich expert descriptions recorded in routine reports. These reports document lesion appearance, size and location but summarise entire procedures rather than caption individual frames, leaving clinical findings only weakly linked to the corresponding images. Here we develop EndoCLIP, a colonoscopy vision-language foundation model trained on 125,756 lesion-level image-text pairs progressively recovered from 280,476 routine colonoscopy records. Across lesion-level image-text retrieval, structured report generation and six multi-centre clinical classification tasks, EndoCLIP outperforms general-purpose and biomedical vision-language encoders in both zero-shot and linear-probe settings. On benign-versus-malignant classification, its linear probe approaches the performance of expert readers in a blinded study involving 12 endoscopists. These results suggest that recovering finding-to-frame correspondence can transform routine documentation into scalable supervision, enabling clinical targets to be specified in language rather than separately annotated for each task.
  </details>
