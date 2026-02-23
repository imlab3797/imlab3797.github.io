---
type: "Journal Paper"
layout: publication
group: publications

title: "Optimal features driven hybrid attention network for effective video summarization"

authors:
  - name: "Habib Khan"
  - name: "Samee Ullah Khan"
  - name: "Waseem Ullah"
  - name: "Sung Wook Baik"
    corresponding: true

domestic_or_international: "International"

pub:
  - name: "Engineering Applications of Artificial Intelligence"
    pdf:
    doi: "10.1016/j.engappai.2025.111211"
    vol: "158"
    num:
    pp: "111211"
    year: "2025"
    state: "published"
    bib:

pub_date: "2025-10-15"

image: "/static/pub/2025-video-summ.png"

abstract: >
  Video summarization (VS) has emerged as an effective method for extracting meaningful content from large video repositories. Recent advancements in visual intelligence have significantly improved the ability to summarize lengthy, raw videos into concise yet representative content. However, existing VS methods extract features from static GoogleNet Pool5 without empirical analysis at an early stage. Moreover, these approaches often lack mechanisms to jointly refine channel-wise and spatial-wise feature interactions, resulting in inadequate learning of complex visual semantics and ultimately suboptimal summarization performance. To address these limitations, we propose the Hybrid-Attention VS Network (HAVSNet), which conceptualizes VS as a keyframe selection task. Our method integrates representative intermediate features early in the network, significantly enhancing feature representation compared to conventional techniques. Furthermore, HAVSNet incorporates a hybrid-attention mechanism for advanced feature refinement: channel attention highlights the most discriminative feature maps, while an optimized spatial attention module captures and refines spatial dependencies. This enables the network to focus on the most informative and visually salient regions. Additionally, explainable AI (XAI) via heatmap visualizations further enhances interpretability by revealing how the model prioritizes salient regions, offering insights into the focus of the model and optimal feature selection. Extensive experiments demonstrate that our network outperforms state-of-the-art methods, achieving notable improvements. Comprehensive quantitative and qualitative analyses further confirm the effectiveness of the proposed network. Moreover, the proposed HAVSNet is evaluated across three training configurations of canonical, augmented, and transfer settings, showing its strong generalization and adaptability.

links:
  - name: "ScienceDirect"
    url: "https://www.sciencedirect.com/science/article/pii/S0952197625012126"
  - name: "DOI"
    url: "https://doi.org/10.1016/j.engappai.2025.111211"
---