# 🔍 Med_Foundation_Models Papers · 2026-04-26

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Foundation Model,Pathology` `Pre-training,Histopathology` `Self-supervised,Pathology` `Contrastive Learning,WSI` `Masked Image Modeling,Pathology` `Generative,Pathology` `PLIP` `CLIP,Medical`  
**Filter**: `LLM`

---

## 📚 Paper List

- **[Beyond Patient Invariance: Learning Cardiac Dynamics via Action-Conditioned JEPAs](https://arxiv.org/abs/2604.22618)**  `arXiv:2604.22618`  `cs.LG`  
  _Jose Geraldo Fernandes, Luiz Facury, Pedro Robles Dutenhefner, Wagner Meira Jr_
  <details open><summary>Abstract</summary>
  Self-supervised learning in healthcare has largely relied on invariance-based objectives, which maximize similarity between different views of the same patient. While effective for static anatomy, this paradigm is fundamentally misaligned with clinical diagnosis, as it mathematically compels the model to suppress the transient pathological changes it is intended to detect. We propose a shift towards Action-Conditioned World Models that learn to simulate the dynamics of disease progression, or Event-Conditioned. Adapting the LeJEPA framework to physiological time-series, we define pathology not as a static label, but as a transition vector acting on a patient's latent state. By predicting the future electrophysiological state of the heart given a disease onset, our model explicitly disentangles stable anatomical features from dynamic pathological forces. Evaluated on the MIMIC-IV-ECG dataset, our approach outperforms fully supervised baselines on the critical triage task. Crucially, we demonstrate superior sample efficiency: in low-resource regimes, our world model outperforms supervised learning by over 0.05 AUROC. These results suggest that modeling biological dynamics provides a dense supervision signal that is far more robust than static classification. Source code is available atthis https URL
  </details>

- **[HFS-TriNet: A Three-Branch Collaborative Feature Learning Network for Prostate Cancer Classification from TRUS Videos](https://arxiv.org/abs/2604.22388)**  `arXiv:2604.22388`  `cs.CV`  
  _Xu Lu, Qianhong Peng, Qihao Zhou, Shaopeng Liu, Xiuqin Ye, Chuan Yang, et al._
  <details open><summary>Abstract</summary>
  Transrectal ultrasound (TRUS) imaging is a cost-effective and non-invasive modality widely used in the diagnosis of prostate cancer. The computer-aided diagnosis (CAD) relying on TRUS images has been extensively investigated recently. Compared to static images, TRUS video provides richer spatial-temporal information, which make it a promising alternative for improving the accuracy and robustness of CAD systems. However, TRUS video analysis also introduces new challenges. These include information redundancy, which increases computational costs; high intra- and inter-class similarity, which complicates feature extraction; and a low signal-to-noise ratio, which hinders the identification of clinically relevant information. To address these problems, we propose a heuristic frame selection (HFS) and a three-branch collaborative feature learning network (HFS-TriNet) for prostate cancer classification from TRUS videos. Specifically, selecting a clip of video frames at intervals for training can mitigate redundancy. The HFS strategy dynamically initializes the starting point of each training clip, which ensures that the sampled clips span the entire video sequence. For better feature extraction, besides a regular ResNet50 branch, we also utilize 1) a large model branch based a pre-trained medical segment anything model (SAM) to extract deep features of each frame and a normalization-based attention module to explore the temporal consistency; and 2) a wavelet transform convolutional residual (WTCR) branch that extracts lesion edge information in the high-frequency domain and performs denoising in the low-frequency domain.
  </details>
