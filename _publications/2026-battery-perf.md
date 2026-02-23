---
type: "Journal Paper"
layout: publication
group: publications

title: "A novel deep learning framework for battery performance prediction over the operational lifespan"

authors:
  - name: "Hikmat Yar"
  - name: "Zulfiqar Ahmad Khan"
  - name: "Adnan Hussain"
  - name: "Sang Il Yoon"
  - name: "Seoa Kim"
  - name: "Jungwook Choi"
  - name: "Chan Mi Jeon"
  - name: "Huisu Jeung"
  - name: "Kyungjung Kwon"
  - name: "Sung Wook Baik"
    corresponding: true

domestic_or_international: "International"

pub:
  - name: "Journal of Energy Storage"
    pdf:
    doi: "10.1016/j.est.2025.119359"
    vol: "143"
    num:
    pp: "119359"
    year: "2026"
    state: "published"
    bib:

pub_date: "2026-01-20"

image: "/static/pub/2026-battery-perf.png"

abstract: >
  Lithium-ion batteries are increasingly used in a diverse range of applications, such as electric vehicles, renewable energy storage, and portable electronics. However, accurate prediction of the state of health and capacity degradation remains a significant challenge, due to the complex and nonlinear nature of battery aging. State-of-the-art prediction models often lack robustness and reliability, especially under varying discharge current rates, and the scarcity of comprehensive data covering different discharge currents further hinders the development of accurate models. Although various machine learning methods have been proposed, they still fall short of delivering precise and consistent predictions across a diverse set of conditions. Furthermore, there is a lack of sufficient data to enable an exploration of battery capacity at different discharge current rates, which prevents the development of more robust and reliable prediction models. To address these challenges, we collected a custom dataset based on experimental graphs from 151 research articles reporting battery capacities at different discharge current rates. During the process of data collection for the custom dataset, the challenge of missing values arose, which was handled via preprocessing. We also developed a hybrid model integrating a gated recurrent unit with a long short-term memory network and multi-head latent attention to improve the capacity and state of health prediction results. The gated recurrent unit and long short-term memory network models extracted both short-term and long-term dependencies, whereas the multi-head latent attention mechanisms captured complex relationships by assigning different attention weights to various parts of the input sequence followed by a dense layer for final prediction. The proposed hybrid approach enabled the model to focus on the most relevant features, improving its ability to handle complex interactions and long-range dependencies. The proposed model was evaluated using three different datasets (National Aeronautics and Space Administration battery data, a dataset from the Center for Advanced Life Cycle Engineering, and a newly created dataset) and was found to have significantly improved performance compared to existing methods. Quantitative, qualitative, ablation studies, cross validation were also carried out to confirm the effectiveness of the proposed model in terms of predicting state of health and capacity at different discharge currents rates.

links:
  - name: "ScienceDirect"
    url: "https://www.sciencedirect.com/science/article/pii/S2352152X25040721"
  - name: "DOI"
    url: "https://doi.org/10.1016/j.est.2025.119359"
---