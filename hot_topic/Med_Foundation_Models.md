# 🔍 Med_Foundation_Models Papers · 2026-04-21

[![Total Papers](https://img.shields.io/badge/Papers-3-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[3D Foundation Model for Generalizable Disease Detection in Head Computed Tomography](https://arxiv.org/abs/2502.02779)**  `arXiv:2502.02779`  `cs.CV` `cs.AI`  
  _Weicheng Zhu, Haoxu Huang, Huanze Tang, Rushabh Musthyala, Boyang Yu, Long Chen, et al._
  <details open><summary>Abstract</summary>
  Head computed tomography (CT) imaging is a widely-used imaging modality with multitudes of medical indications, particularly in assessing pathology of the brain, skull, and cerebrovascular system. It is commonly the first-line imaging in neurologic emergencies given its rapidity of image acquisition, safety, cost, and ubiquity. Deep learning models may facilitate detection of a wide range of diseases. However, the scarcity of high-quality labels and annotations, particularly among less common conditions, significantly hinders the development of powerful models. To address this challenge, we introduce FM-CT: a Foundation Model for Head CT for generalizable disease detection, trained using self-supervised learning. Our approach pre-trains a deep learning model on a large, diverse dataset of 361,663 non-contrast 3D head CT scans without the need for manual annotations, enabling the model to learn robust, generalizable features. To investigate the potential of self-supervised learning in head CT, we employed both discrimination with self-distillation and masked image modeling, and we construct our model in 3D rather than at the slice level (2D) to exploit the structure of head CT scans more comprehensively and efficiently. The model's downstream classification performance is evaluated using internal and three external datasets, encompassing both in-distribution (ID) and out-of-distribution (OOD) data. Our results demonstrate that the self-supervised foundation model significantly improves performance on downstream diagnostic tasks compared to models trained from scratch and previous 3D CT foundation models on scarce annotated datasets. This work highlights the effectiveness of self-supervised learning in medical imaging and sets a new benchmark for head CT image analysis in 3D, enabling broader use of artificial intelligence for head CT-based diagnosis.
  </details>

- **[Attend what matters: Leveraging vision foundational models for breast cancer classification using mammograms](https://arxiv.org/abs/2604.19350)**  `arXiv:2604.19350`  `cs.CV`  
  _Samyak Sanghvi, Piyush Miglani, Sarvesh Shashikumar, Kaustubh R Borgavi, Veenu Singla, Chetan Arora_
  <details open><summary>Abstract</summary>
  Vision Transformers $(\texttt{ViT})$ have become the architecture of choice for many computer vision tasks, yet their performance in computer-aided diagnostics remains limited. Focusing on breast cancer detection from mammograms, we identify two main causes for this shortfall. First, medical images are high-resolution with small abnormalities, leading to an excessive number of tokens and making it difficult for the softmax-based attention to localize and attend to relevant regions. Second, medical image classification is inherently fine-grained, with low inter-class and high intra-class variability, where standard cross-entropy training is insufficient. To overcome these challenges, we propose a framework with three key components: (1) Region of interest $(\texttt{RoI})$ based token reduction using an object detection model to guide attention; (2) contrastive learning between selected $\texttt{RoI}$ to enhance fine-grained discrimination through hard-negative based training; and (3) a $\texttt{DINOv2}$ pretrained $\texttt{ViT}$ that captures localization-aware, fine-grained features instead of global $\texttt{CLIP}$ representations. Experiments on public mammography datasets demonstrate that our method achieves superior performance over existing baselines, establishing its effectiveness and potential clinical utility for large-scale breast cancer screening. Our code is available for reproducibility here:this https URL
  </details>

- **[Mammo-FM: Breast-specific foundational model for Integrated Mammographic Diagnosis, Prognosis, and Reporting](https://arxiv.org/abs/2512.00198)**  `arXiv:2512.00198`  `cs.CV`  
  _Shantanu Ghosh, Vedant Parthesh Joshi, Rayan Syed, Param Budhraja, Aya Kassem, Katelyn C. Morrison, et al._
  <details open><summary>Abstract</summary>
  Breast cancer is one of the leading causes of death among women worldwide. We introduce Mammo-FM, the first foundation model specifically for mammography, pretrained on the largest and most diverse dataset to date - 140,677 patients (821,326 mammograms) across four U.S. institutions. Mammo-FM provides a unified foundation for core clinical tasks in breast imaging, including cancer diagnosis, pathology localization, structured report generation, and cancer risk prognosis within a single framework. Its alignment between images and text enables both visual and textual interpretability, improving transparency and clinical auditability, which are essential for real-world adoption. We rigorously evaluate Mammo-FM across diagnosis, prognosis, and report-generation tasks in in- and out-of-distribution datasets. Despite operating on native-resolution mammograms and using only one-third of the parameters of state-of-the-art generalist FMs, Mammo-FM consistently outperforms them across multiple public and private benchmarks. These results highlight the efficiency and value of domain-specific foundation models designed around the full spectrum of tasks within a clinical domain and emphasize the importance of rigorous, domain-aligned evaluation.
  </details>
