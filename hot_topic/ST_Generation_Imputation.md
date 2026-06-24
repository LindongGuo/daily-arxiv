# 🔍 ST_Generation_Imputation Papers · 2026-06-23

[![Total Papers](https://img.shields.io/badge/Papers-1-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Gene Expression,Prediction` `Spatial Transcriptomics,Imputation` `Spatial Transcriptomics,Super-resolution` `Virtual Staining` `Cross-modality,Translation` `Flow Matching,Medical`  
**Filter**: `None`

---

## 📚 Paper List

- **[MedPCFM: Improving Medical Point Cloud Completion by Integrating Point Transformers and Flow Matching](https://arxiv.org/abs/2606.24433)**  `arXiv:2606.24433`  `cs.CV` `cs.AI` `cs.LG`  
  _Kamil Kwarciak, Marek Wodzinski_
  <details open><summary>Abstract</summary>
  Medical point cloud completion is important for anatomical reconstruction and downstream clinical workflows, yet generative modeling in this setting remains insufficiently studied. We investigate completion through continuous-time generative modeling and introduce PCFM, a PTv3-backed flow matching approach for medical point cloud completion. We evaluate on SkullFix and SkullBreak, and additionally on the more recent Mandibular Defect dataset. We build strong baselines by adapting PTv3 to a deterministic encoder-decoder completion model and by instantiating diffusion completion (PCDiff) with both PVCNN and PTv3 denoisers. PCFM with PTv3 is competitive with the deterministic PTv3 baseline and achieves state-of-the-art generative performance across datasets, while requiring substantially fewer sampling steps than diffusion. At the best operating points, PTv3 also yields clear throughput gains, providing up to a 7$\times$ speed-up for PCFM compared to a PVCNN backbone. Finally, we study empirical scaling trends by varying model size and point cardinality, showing consistent gains with higher point resolution and informative trade-offs across model scales.
  </details>
