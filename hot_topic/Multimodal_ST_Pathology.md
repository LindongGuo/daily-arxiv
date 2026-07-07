# 🔍 Multimodal_ST_Pathology Papers · 2026-07-06

[![Total Papers](https://img.shields.io/badge/Papers-2-2688EB)]()
[![Last Updated](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/awesome-daily-AI-arxiv/commits/main&query=%24.commit.author.date&label=updated&color=orange)]()

---

## 📌 Filter by Category
**Keywords**: `Spatial Transcriptomics,Histology` `Spatial Transcriptomics,WSI` `Spatial Transcriptomics,Image` `Visium,Pathology` `Xenium,Pathology` `Gene Expression,H&E` `Visual-Omics` `Multimodal,Omics` `Cross-modal,Pathology`  
**Filter**: `review`

---

## 📚 Paper List

- **[DriftST: One-Step Generative Inference of Spatial Transcriptomics from H\&E Histology](https://arxiv.org/abs/2607.04740)**  `arXiv:2607.04740`  `cs.CV`  
  _Yuhang Yang, Yonggan Bu, Shengyuan Zhou, Yiming Luo, Kai Zhang_
  <details open><summary>Abstract</summary>
  Spatial Transcriptomics (ST) measures gene expression while preserving spatial context, but its high cost and low throughput leave public datasets small. Inferring expression directly from widely available Hematoxylin and Eosin (H&E) stained histology offers a cost-effective alternative. However, existing approaches face several limitations: regression methods over-smooth toward the conditional mean, while generative methods are faithful but require slow multi-step inference; most methods treat genes as independent and equally important, ignoring inter-gene dependencies and heterogeneous gene informativeness; and most are tailored to a single resolution, either spot-level or cell-level. To address these issues, we propose DriftST, a unified framework for inferring spatially resolved gene expression from H&E images. DriftST builds on a Cellular Drifting generative model that learns a direct drift from a histology-conditioned source to the expression distribution, retaining generative expressiveness while enabling efficient one-step generation. To capture gene structure, we introduce the STransformer, which combines a co-expression attention module for inter-gene dependencies with a gene residual gate for differential gene importance. Operating on a generic gene-panel representation, DriftST applies directly to both spot-level and cell-level data in one framework, and extensive experiments across diverse tissues and platforms show that it achieves state-of-the-art performance at both resolutions.
  </details>

- **[AI Native Games: A Survey and Roadmap](https://arxiv.org/abs/2607.00527)**  `arXiv:2607.00527`  `cs.AI`  
  _Zhiyue Xu, Fandi Meng, Kaijie Xu, Clark Verbrugge, Simon Lucas, Jian Zhao_
  <details open><summary>Abstract</summary>
  Generative AI now enables games to produce dialogue, quests, characters, images, and worlds at runtime. Yet generation alone does not make a game AI-native, nor does it guarantee playability. This paper defines AI-native games by whether runtime generative AI is constitutive of the core loop: if the AI component were removed or trivially replaced, the central form of play would collapse or become fundamentally different. This counterfactual criterion separates AI-native games from AI-augmented games and adjacent boundary artifacts. Using this definition, we screen candidate artifacts and analyze 53 publicly available AI-native games and prototypes. We introduce a dual-axis G/N taxonomy: the G-axis captures player-facing game type, while the N-axis captures the dominant AI mechanic that makes generative AI indispensable to play. The corpus is concentrated around language-forward designs, especially narrative adventure, epistemic interaction, and generative narrative, while categories such as semantic adjudication, multi-agent simulation, generative construction, and relationship/companion play remain less represented. We argue that the central design problem is organizing semantic openness into stable gameplay. AI-native design depends on mechanical invariants: goals, rules, state, feedback, pacing, and player agency that make open-ended AI outputs interpretable and consequential. We conclude with a roadmap for controllable generation, AI-as-mechanic design, multimodal and multi-agent systems, inference economics, evaluation, safety, and regulation.
  </details>
