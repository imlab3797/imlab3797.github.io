---
type: "Journal Paper"
layout: publication
group: publications

title: "DREAM: Extending Vision-Language Models with Dual-Objective Encoding for Cross-Modal Retrieval"

authors:
  - name: "Kaleem Ullah"
  - name: "Altaf Hussain"
  - name: "Muhammad Munsif"
  - name: "Sung Wook Baik"
    corresponding: true

domestic_or_international: "International"

pub:
  - name: "Pattern Recognition"
    pdf:
    doi:
    vol:
    num:
    pp:
    year: "2026"
    state: "submitted"
    bib:

pub_date: "2026-06-30"

image: "/static/pub/2026-Dream.png"

abstract: >
  In today's media-driven world, the exponential growth of video content across domains such as surveillance, education, and entertainment has made retrieving semantically relevant videos using natural language queries increasingly important. Early video retrieval systems relied on handcrafted features or shallow cross-modal mappings, limiting their ability to capture complex semantics and temporal dynamics. Although large-scale vision-language models have significantly improved cross-modal alignment, challenges remain in modeling fine-grained temporal dependencies and nuanced linguistic structures. In this paper, we introduce DREAM (Dual-path Representation Enhancement and Alignment Model), a novel multimodal framework that addresses these limitations through enhanced visual and textual encoding. DREAM incorporates a hybrid language modeling strategy that combines masked language modeling and permuted language modeling objectives to capture both local and global linguistic semantics. On the visual side, we design a hierarchical vision encoder with cascaded group attention that integrates spatial and temporal information through multi-stage token interaction and coarse-to-fine attention refinement. We validate DREAM through comprehensive evaluations on the widely used MSRVTT, MSVD, and LSMDC benchmark datasets, where it achieves new state-of-the-art R@1 scores of 49.4%, 49.7%, and 27.3%, respectively. Qualitative analyses further demonstrate the model's ability to maintain coherent attention across frames and effectively align complex queries with dynamic video content. These findings highlight the effectiveness of hierarchical attention and dual-objective textual modeling in enabling robust, context-aware video retrieval and pave the way for future advances in cross-modal representation learning.

links:
  - name: "arXiv"
    url: "https://arxiv.org/abs/2606.19062"
---