---
type: "Journal Paper"
layout: publication
group: publications

title: "Deep hybrid network with additive attention for accurate population forecasting"

authors:
  - name: "Hikmat Yar"
  - name: "Adnan Hussain"
  - name: "Zulfiqar Ahmad Khan"
  - name: "Min Je Kim"
  - name: "Sung Wook Baik"
    corresponding: true

domestic_or_international: "International"

pub:
  - name: "Soft Computing"
    pdf:
    doi: "10.1007/s00500-025-10975-4"
    vol:
    num:
    pp: "1-18"
    year: "2026"
    state: "published"
    bib:

pub_date: "2026-02-17"

image: "/static/pub/2026-pop_forecasting.png"

abstract: >
  Population forecasting is crucial for informed decision-making and strategic planning in government and business, as it supports effective resource allocation, infrastructure development, and service provision to meet future demands. However, accurate population forecasting for small regions is challenging due to complex demographic processes, data sparsity, and the nonlinear nature of population growth. Despite advancements in time series forecasting methods, limited research has applied machine learning to small-area population forecasting, highlighting the need for models capable of capturing complex demographic trends to improve accuracy. To tackle these limitations, we propose a dual-stream architecture combining convolutional neural network (CNN) and bidirectional LSTM (BiLSTM) layers with additive attention mechanisms (Dual-CBA) for small-area population forecasting. The first stream utilizes CNN layers for spatial feature extraction, while the second stream employs a multilayered BiLSTM network to model temporal dependencies, capturing demographic trends and changes over time. The integration of additive attention allows the model to focus on relevant features in both spatial and temporal dimensions, enhancing its ability to learn complex demographic patterns and improve forecasting accuracy. The Dual-CBA is evaluated on five datasets namely Australia, New Zealand, Japan, United States, and South Korea. Results demonstrate that the proposed model achieves superior performance in terms of MAPE and MedAPE compared to the baselines. The model performance is also examined for 5- and 10-year population forecasts, showing optimal performance across these timeframes. Additionally, we also use the XAI method LIME to assess feature importance by region, providing insights into the key factors influencing population projections.

links:
  - name: "Springer Link"
    url: "https://link.springer.com/article/10.1007/s00500-025-10975-4"
---