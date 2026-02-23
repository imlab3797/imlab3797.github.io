---
type: "Conference Paper"
layout: publication
group: publications

title: "Dual Deep Learning Network for Abnormal Action Detection"

authors:
  - name: "Fath U Min Ullah"
  - name: "Zulfiqar Ahmad Khan"
  - name: "Sung Wook Baik"
    corresponding: true
  - name: "Estefania Talavera"
  - name: "Saeed Anwar"
  - name: "Khan Muhammad"

domestic_or_international: "International"

pub:
  - name: "IEEE International Conference on Advanced Video and Signal Based Surveillance (AVSS)"
    doi: "10.1109/AVSS61716.2024.10672568"
    year: "2024"
    state: "published"
    pdf: "https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10672568"

pub_date: "2024-07-01"

image: "/static/pub/2024-abnormal-action.png"

abstract: >
  Neural networks have demonstrated remarkable effectiveness in solving distinct real-world vision problems pertaining to activity recognition and violence detection in surveillance scenarios. The broad reliance on practicing a single network for spatial and motion information collection has made them less effective for long-term dependency analysis in video snippets. Our work solves this issue through a multi-network fusion strategy suitable for real-world surveillance. Initially, the spatial information is accessed from a compound coefficient strategy inspired by a robust convolutional neural network (ConvNet). Next, the pyramidal convolutional features from two consecutive frames are obtained through LiteFlowNet. The output from both the networks (ConvNet and LiteFlowNet) is separately passed into a deep-gated recurrent unit (GRU) assembled with skip connections. The outputs obtained from each GRU are fused and further propagated to the dense layer for final decision. The results on the datasets and ablation study confirm our method’s efficiency, outperforming the state-of-the-art methods.

links:
  - name: "IEEE Xplore"
    url: "https://ieeexplore.ieee.org/document/10672568"
---