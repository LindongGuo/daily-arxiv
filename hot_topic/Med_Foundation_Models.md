# 🔍 Med_Foundation_Models Papers · 2026-09-14

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Solving the Needle-in-a-Haystack Problem in Mammography Vision-Language Model with Differentiable Subset Sampling](https://arxiv.org/abs/2609.03085)**  `arXiv:2609.03085`  `cs.CV`  
  _Young Seok Jeon, Beatrice Brown-Mulry, Rohan Satya Isaac, Anjana Dissanayaka, Theo Dapamede, Mohammadreza Chavoshi, et al._
  <details open><summary>Abstract</summary>
  There is growing interest in adopting CLIP-style vision--language model (VLM) pretraining for mammography. However, models that directly employ the standard CLIP architecture and training objective exhibit limited zero-shot performance in clinically important tasks such as cancer, finding-type, and BI-RADS predictions. We argue that this underwhelming performance is due to neglecting two characteristics of mammography data: (1) its high-res nature, and (2) homogeneity of radiology reports, largely driven by a predominance of negative/benign findings on examinations. We propose TopKSigLIP, a VLM designed to address these two limitations through a novel architecture and learning objectives. Instead of downscaling high-res mammography images to satisfy GPU memory constraints, TopKSigLIP introduces TopK-Patch module that learns to sample a sparse set of high-res patches likely to contain lesions, sidestepping the resolution--batch size tradeoff of VLM training. The sampled patch locations additionally serve as a built-in localization tool. To address report homogeneity, we replace the contrastive loss, which falsely repels semantically similar pairs, with a Sup-sigmoid loss. Sup-sigmoid loss extends the sigmoid loss from SigLIP with soft labels derived from structured data. TopKSigLIP outperforms existing open-source mammography and general medical VLMs on both internal and external benchmarks on density assessment, BI-RADS classification, finding subtyping, and cancer prediction under zero-shot evaluation. TopKSigLIP remains competitive under linear probing despite using a significantly smaller vision encoder and smaller training batches than baselines. The TopK-Patch module additionally achieves superior lesion localization over post-hoc Grad-CAM. Code and weights are made public:this https URL.
  </details>

- **[Designing UNICORN: a Unified Benchmark for Imaging in Computational Pathology, Radiology, and Natural Language](https://arxiv.org/abs/2603.02790)**  `arXiv:2603.02790`  `cs.CV`  
  _Michelle Stegeman, Lena Philipp, Fennie van der Graaf, Marina D'Amato, Clément Grisi, Luc Builtjes, et al._
  <details open><summary>Abstract</summary>
  Foundation models are changing the way we develop medical artificial intelligence. By learning broadly generalizable features across diverse data modalities, a single model can be rapidly adapted to address multiple modalities and tasks with minimal supervision. This potential comes with the urgent need to reliably benchmark, understand and compare the performance and clinical impact of foundation models across data modalities and clinical tasks. We introduce UNICORN, a fundamentally new benchmarking concept for medical foundation models. UNICORN brings four main contributions to medical artificial intelligence. First, a framework that enables a one-to-many benchmarking approach, where a single foundation model is tested across multiple tasks and data modalities. Here, we populate it with 20 tasks across radiology, pathology, and clinical text, covering classification, detection, segmentation, regression, and vision-language generation. Second, a publicly available evaluation platform that implements, for the first time, a two-step approach to run foundation models for data encoding followed by custom task-specific adaptation via few-shot learning and linear probing mechanisms. Third, we create a meta-model that combines state-of-the-art foundation models in pathology, radiology and language with novel task-specific adapters that address all UNICORN tasks, which we refer to as Unicorn Model-0 (UM-0). Finally, we design a novel UNICORN score to benchmark and compare model performance across all tasks. We present the results of UM-0 using sequestered test data from over 2,400 patients, 3,700 vision cases, and 2,400 clinical reports from 17 institutions across eight countries, spanning eight anatomical regions and four imaging modalities. Data, baselines, and evaluation platform are publicly accessible atthis http URL.
  </details>
