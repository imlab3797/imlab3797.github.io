---
type: "Journal Paper"
layout: publication
group: publications

title: "Edge-assisted framework for instant anomaly detection and cloud-based anomaly recognition in smart surveillance"

authors:
  - name: "Adnan Hussain"
  - name: "Noman Khan"
  - name: "Zulfiqar Ahmad Khan"
  - name: "Hikmat Yar"
  - name: "Sung Wook Baik"
    corresponding: true

domestic_or_international: "International"

pub:
  - name: "Engineering Applications of Artificial Intelligence"
    pdf:
    doi: "10.1016/j.engappai.2025.111936"
    vol: "160"
    num:
    pp: "111936"
    year: "2025"
    state: "published"
    bib:

pub_date: "2025-11-23"

image: "/static/pub/2025-edge-anomaly.png"

abstract: >
  Anomaly detection in surveillance systems, identifying events such as fighting, shooting, or vandalism, remains challenging due to limited anomalous occurrences impacting model generalization and accuracy. Additionally, the significant variability in anomalies compared to normal actions complicates precise detection. Current state-of-the-art methods typically process all frames captured by surveillance cameras using resource-intensive, centralized systems, resulting in high computational costs and network bandwidth usage unsuitable for real-time, edge-based Artificial Intelligence of Things environments. Moreover, unclear anomaly definitions and computationally demanding real-time analyses hinder effective monitoring. To address these challenges, we propose an efficient Artificial Intelligence of Things-based anomaly detection framework employing a two-phase approach. Initially, a lightweight neural architecture search network classifies events as normal or anomalous directly on edge devices. When an anomaly is detected, the edge device alerts relevant authorities and transmits the relevant video frames to the cloud for further evaluation. In the second phase, a next-generation convolutional neural network extracts spatial features, refined by Spatial Attention Modules and further processed using a transformer-based multi-head attention network to capture contextual relationships. A Multi-Scale Feature module then classifies the anomalies into specific types. Extensive experiments conducted on the University of Central Florida Crime, Large-scale Anomaly Detection-2000, and Real-world Fighting-2000 datasets demonstrate that our method achieves accuracy of 53.60%, 80.02%, and 94.05%, with improvements of 1.8%, 1.2%, and 0.8%, respectively. Moreover, we report area under the curve scores of 0.76, 0.98, and 0.98 for all datasets, highlighting the method’s effectiveness and robustness in enhancing anomaly detection and recognition across various datasets.

links:
  - name: "ScienceDirect"
    url: "https://www.sciencedirect.com/science/article/pii/S0952197625019384"
  - name: "DOI"
    url: "https://doi.org/10.1016/j.engappai.2025.111936"
---