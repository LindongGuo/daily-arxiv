# 🔍 Multimodal_ST_Pathology Papers · 2026-10-13

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[MIST: Multi-Scale Spatial Context for Gene Expression Prediction from Histology](https://arxiv.org/abs/2610.18769)**  `arXiv:2610.18769`  `cs.CV`  
  _Koushik Howlader, Tirtho Roy, Md Tauhidul Islam, Wei Le_
  <details open><summary>Abstract</summary>
  Predicting spatial gene expression from standard H&E images could extend molecular analysis to tissues without spatial transcriptomic measurements. A standard Transformer applies self-attention over spots but ignores where each spot sits in the tissue, whereas a spot's molecular state depends on tissue context at multiple spatial scales. Building on this insight, we introduce MIST, a Multi-context Spatial Transformer that augments the self-attention backbone with two context pathways applied in every layer: a coordinate-invariant local pathway that attends over spatial k-nearest-neighbor spots, and a slide pathway that broadcasts a whole-slide summary to every spot; the model predicts all spots in a single forward pass. Because coordinates enter only through pairwise distances, the local pathway is invariant to translations, rotations, and reflections when image features are fixed. In intra-cohort evaluation across six human organ cohorts from HEST-1k, MIST improves mean Pearson correlation over the strongest evaluated baseline by 9.7%, 11.6%, and 11.4% for 10-, 50-, and 100-gene panels, respectively, with the lowest average MSE and MAE. MIST further improves leave-one-organ-out transfer by 6.0% over the next strongest baseline, attains the best expression-derived domain recovery (highest mean ARI and NMI at every clustering resolution, and higher NMI than the closest baseline on 84% of held-out slides), and reproduces spatial expression patterns of selected cancer-marker genes. Together, these results show that adding local and slide context to a vanilla Transformer backbone is an effective approach to spatial gene expression prediction from histology.
  </details>

- **[From Classification to Cross-Modal Understanding: Leveraging Vision-Language Models for Fine-Grained Renal Pathology](https://arxiv.org/abs/2511.11984)**  `arXiv:2511.11984`  `cs.CV`  
  _Zhenhao Guo, Rachit Saluja, Tianyu Shi, Tianyuan Yao, Quan Liu, Junchao Zhu, et al._
  <details open><summary>Abstract</summary>
  Fine-grained glomerular subtyping is essential for kidney biopsy interpretation, yet it presents a harder setting than the broad organ- or disease-level recognition tasks commonly used in vision-language model (VLM) evaluation. In this task, all categories arise within the same renal microanatomic unit, and clinically meaningful subtypes often differ by subtle, overlapping, and continuum-like morphological cues. Clinically valuable labels are also scarce, making fully supervised image-only paradigms difficult to translate to practice. Although VLMs are promising for data-efficient pathology learning, it remains unclear how their cross-modal representations should be adapted and evaluated for such within-structure discrimination under realistic few-shot constraints. To our knowledge, this study establishes the first fine-grained renal pathology benchmark for few-shot VLM adaptation and systematically examines how supervision level, model design, and adaptation strategy shape both classification performance and multimodal representation structure. Beyond accuracy, AUC, and F1, we assess image-text alignment, positive-negative similarity separation, embedding geometry, and calibration (ECE), asking when performance gains reflect more reliable cross-modal understanding. Across renal pathology cohorts, additional supervision consistently improves discrimination, but reliable adaptation is not explained by alignment alone; stronger performance is associated with larger class separation, more coherent embedding organization, and better awareness of confidence-related failure modes under domain variation. Within this retrospective two-cohort evaluation, these findings move assessment beyond coarse classification and accuracy alone and provide comparative evidence to inform model selection and future translational validation. Code:this https URL
  </details>
