---
type: "Journal Paper"
layout: publication
group: publications

title: "Class-incremental learning network for real-time anomaly recognition in surveillance environments"

authors:
  - name: "Adnan Hussain"
  - name: "Waseem Ullah"
  - name: "Noman Khan"
  - name: "Zulfiqar Ahmad Khan"
  - name: "Hikmat Yar"
  - name: "Sung Wook Baik"
    corresponding: true

domestic_or_international: "International"

pub:
  - name: "Pattern Recognition"
    pdf:
    doi: "10.1016/j.patcog.2025.112064"
    vol: "170"
    num:
    pp: "112064"
    year: "2026"
    state: "published"
    bib:

pub_date: "2026-02-01"

image: "/static/pub/2026-class-inc.png"

abstract: >
  The rise in crime rates has become a significant cause of property and life losses, necessitating the development of intelligent video surveillance systems for enhanced monitoring in law enforcement, transportation, and environmental contexts. However, the accurate identification of abnormal activities in real-time video surveillance systems remains a challenging task. Existing surveillance systems struggle with the vast amount of video streaming, making manual 24/7 monitoring impractical and error-prone. Traditional anomaly detection methods often process the entire dataset’s feature set, which can be limiting in complex scenarios, leading to incorrect predictions, especially with challenging patterns or inter-class similarities. Therefore, this paper addresses the limitations of automatic video anomaly recognition systems by developing a vision transformer based class-incremental learning network (CILAR-Net). The CILAR-Net leverages a vision transformer to extract spatiotemporal features from surveillance video frames, followed by a GRU network for anomaly recognition. The incremental learning approach enables the model to adapt to new classes without retraining. The CILAR-Net is validated on challenging anomaly recognition datasets, including UCF-Crime, LAD-2000, and RWF-2000, showcasing a state-of-the-art performance. Comparative analysis with existing methods demonstrates the effectiveness of CILAR-Net, which achieves an accuracy of 53.03%, 79.07%, and 93.46%, with improvements of 2.03%, 9.67%, and 0.20% from state-of-the-art methods on the UCF-Crime, LAD-2000, and RWF-2000 datasets, respectively. These results highlight the practical advantage and robustness of our method in enhancing anomaly recognition performance across diverse datasets. This article addresses significant research gaps in anomaly recognition by providing a robust and efficient solution for real-world surveillance applications.

links:
  - name: "ScienceDirect"
    url: "https://www.sciencedirect.com/science/article/pii/S0031320325007241"
  - name: "DOI"
    url: "https://doi.org/10.1016/j.patcog.2025.112064"
---