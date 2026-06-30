---
type: "Journal Paper"
layout: publication
group: publications

title: "Differential attention transformer-enhanced graph neural network for accurate material property prediction"

authors:
  - name: "Kaleem Ullah"
  - name: "Altaf Hussain"
  - name: "Muhammad Munsif"
  - name: "Kee-Sun Sohn"
  - name: "Sung Wook Baik"
    corresponding: true

domestic_or_international: "International"

pub:
  - name: "Engineering Applications of Artificial Intelligence"
    pdf:
    doi: "10.1016/j.engappai.2026.114749"
    vol:
    num:
    pp:
    year: "2026"
    state: "published"
    bib:

pub_date: "2026-04-15"

image: "/static/pub/2026-D_Atten.png"

abstract: >
  Accurate prediction of material properties is critical for accelerating materials discovery and design. Machine learning methods, particularly graph neural networks (GNNs), have recently demonstrated promising performance in modeling the structural and electronic characteristics of crystalline materials. However, the performance of deep architectures can degrade when handling structurally complex materials, and capturing subtle structural dependencies remains challenging. In this work, we introduce a Differential Attention Transformer-enhanced Graph Neural Network (DAT-GNN) that integrates chemically informed structural features with a dual-attention mechanism. Our approach follows a structured framework, beginning with the collection and preprocessing of crystal structures and incorporating a learning architecture that combines self-attention, differential attention, residual graph convolutions, and chemically informed positional encodings to model complex atomic interactions. Experimental evaluations on benchmark Materials Project datasets for bandgap and formation energy prediction demonstrate that the proposed method achieves up to an 8% reduction in mean absolute error for formation energy prediction and a 5% reduction for bandgap prediction compared with recent graph neural network-based approaches. These results indicate that the proposed framework provides an accurate and scalable solution for crystal-structure-informed material property prediction, contributing to continued advances in data-driven materials informatics.

links:
  - name: "ScienceDirect"
    url: "https://www.sciencedirect.com/science/article/pii/S0952197626010316?dgcid=author"
---