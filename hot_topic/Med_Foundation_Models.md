# 🔍 Med_Foundation_Models Papers · 2026-06-29

[![Total Papers](https://img.shields.io/badge/Papers-4-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[SonoCLIP: Mask-Guided Region-Aware Vision-Language Pretraining for Fetal Ultrasound Analysis](https://arxiv.org/abs/2606.29586)**  `arXiv:2606.29586`  `cs.CV` `cs.AI`  
  _Hang Su, Chao Sun, Zhaofan Li, Wei Hu, Juhua Liu, Bo Du_
  <details open><summary>Abstract</summary>
  Vision-language foundation models have shown strong potential in medical image analysis. Although foundation models for ultrasound imaging have recently emerged, the domain remains particularly challenging due to severe speckle noise, acquisition variability, and subtle anatomical boundaries, leading to high inter-observer variability. Existing CLIP-based models rely primarily on global image-text alignment, limiting their sensitivity to clinically decisive local structures. We propose SonoCLIP, the first million-scale region-controllable fetal ultrasound vision-language foundation model that integrates segmentation masks as mask-channel visual prompts within the vision encoder, enabling joint global-local contrastive representation learning. To support scalable region-text alignment, we introduce a sigmoid-based pairwise contrastive loss that improves stability under large-scale supervision. We further curate a 1.44M-image multimodal fetal ultrasound dataset spanning 24 standard planes for large-scale pretraining. Extensive cross-center evaluations demonstrate that SonoCLIP achieves superior zero-shot transfer performance under both global and mask-guided inference, establishing a controllable and clinically oriented foundation model for fetal ultrasound analysis. Our code and data are available atthis https URL.
  </details>

- **[Uncertainty Estimation in Pathology Foundation Models via Deep Mutual Learning](https://arxiv.org/abs/2606.30020)**  `arXiv:2606.30020`  `cs.CV`  
  _Gbègninougbo Aurel Davy Tchokponhoue, Sevda Öğüt, Ali Idri, Dorina Thanou, Pascal Frossard_
  <details open><summary>Abstract</summary>
  Pathology foundation models (PFMs) offer generalizable representations for whole-slide image (WSI) analysis, yet their clinical adoption remains limited. Specifically, their predictions lack reliable confidence estimates, and no single PFM is universally best across tasks, which severely undermines trust in medical settings. To overcome this, we propose $\mathtt{DICE}$, a plug-and-play framework that ensembles $K$ frozen PFMs and models their disagreement as a proxy for uncertainty estimation. To ensure this proxy yields meaningful estimates, we align the ensemble members via deep mutual learning, and theoretically show that this objective upper-bounds the model uncertainty. Additionally, we demonstrate that the ensemble's consensus localizes abnormalities at the patch level without any explicit supervision. We evaluate $\mathtt{DICE}$ on three challenging WSI benchmarks. Notably, our framework provides reliable uncertainty estimates that accurately flag failure-prone cases under in- and out-of-distribution settings, while matching or outperforming SOTA baselines in classification, calibration, and localization. Overall, $\mathtt{DICE}$ takes a crucial step toward translating PFMs into uncertainty-aware decision-support systems.
  </details>

- **[CellDETR: A Detection-Guided Framework for Scalable Cell Representation Learning from Histopathology Images](https://arxiv.org/abs/2606.29463)**  `arXiv:2606.29463`  `cs.CV`  
  _Shikang Zhang, Guojun Li, Yicong Mao, Chulin Sha_
  <details open><summary>Abstract</summary>
  Recent advances in pathology foundation models have substantially improved patch and slide level representation learning from whole-slide images (WSIs).However, cell-level representations learning remain underexplored, limiting cell resolved interpretability, biological discovery, and clinical translation. We propose CellDETR, a detection-guided framework built on Deformable DETR for scalable cell representation learning from WSIs. By introducing location feature decoupling and box-constrained attention mechanism, CellDETR enables automated extraction of cell-level embeddings, and outperform existing state-of-the-art methods in supervised cell classification on PanNuke data. In addition, by incorporating contrastive learning design, we build a CellDETR-based pretraining model for scalable cell representation learning from unlabeled WSIs, which improves downstream cell classification performance. Furthermore, we show that after pretraining with Xenium spatial transcriptomics-derived cell annotations, CellDETR achieves accurate cross-dataset cell classification, demonstrating the transferability and biological relevance of the learned cell embeddings. Together, CellDETR provides a scalable route toward general cell-level representation learning framework for interpretable computational patholog
  </details>

- **[MedP-CLIP: Medical CLIP with Region-Aware Prompt Integration](https://arxiv.org/abs/2604.11197)**  `arXiv:2604.11197`  `cs.CV`  
  _Jiahui Peng, He Yao, Jingwen Li, Yanzhou Su, Sibo Ju, Yujie Lu, et al._
  <details open><summary>Abstract</summary>
  Contrastive Language-Image Pre-training (CLIP) has demonstrated outstanding performance in global image understanding and zero-shot transfer through large-scale text-image alignment. However, the core of medical image analysis often lies in the fine-grained understanding of specific anatomical structures or lesion regions. Therefore, precisely comprehending region-of-interest (RoI) information provided by medical professionals or perception models becomes crucial. To address this need, we propose MedP-CLIP, a region-aware medical vision-language model (VLM). MedP-CLIP innovatively integrates medical prior knowledge and designs a feature-level region prompt integration mechanism, enabling it to flexibly respond to various prompt forms (e.g., points, bounding boxes, masks) while maintaining global contextual awareness when focusing on local regions. We pre-train the model on a meticulously constructed large-scale dataset (containing over 6.4 million medical images and 97.3 million region-level annotations), equipping it with cross-disease and cross-modality fine-grained spatial semantic understanding capabilities. Experiments demonstrate that MedP-CLIP significantly outperforms baseline methods in various medical tasks, including zero-shot recognition, interactive segmentation, and empowering multimodal large language models. This model provides a scalable, plug-and-play visual backbone for medical AI, combining holistic image understanding with precise regional analysis.
  </details>
