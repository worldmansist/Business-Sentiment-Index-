# 📚 Literature Review

## 🔹 Source 1: [Nowcasting German GDP with Text Data](https://www.cesifo.org/en/publications/2024/working-paper/nowcasting-german-gdp-text-data)

- **Objective**: Investigate whether textual information from German news media can improve short-term macroeconomic forecasting.

- **Methods**:  
  The authors analyzed a corpus of **12.4 million German newspaper articles** from 1991–2018 using:
  - sentiment analysis,
  - Latent Dirichlet Allocation (LDA),
  - Long Short-Term Memory (LSTM) neural networks,
  - Dynamic Factor Models (DFM),
  - and MIDAS forecasting models.

  Business-cycle-related sentiment was extracted from news articles and transformed into forecasting variables.

- **Outcomes**:
  - Text-derived variables improved GDP nowcasting performance compared to models relying only on traditional macroeconomic indicators.
  - Combining text-based information with hard economic data consistently outperformed standard benchmark models, especially for nowcasts.

- **Relation to the Project**:  
  This paper directly motivates our project, since we also aim to use textual news information to predict economic expectations. Instead of forecasting GDP growth, our project focuses on predicting the **direction of change (increase/decrease)** in the German **ifo Business Climate Index**. The paper demonstrates that newspaper sentiment and topic extraction can capture forward-looking economic signals before official releases.

---

## 🔹 Source 2: [Media’s role in agenda-setting: Exploring media coverage of the German Baltic fishery discourse](https://link.springer.com/article/10.1007/s13280-026-02371-5)

- **Objective**: Examine how German newspapers frame and discuss the Baltic fishery crisis using computational linguistics and machine learning methods.

- **Methods**:
  - Analysis of nearly **1,800 German newspaper articles**,
  - BERT-based sentiment classification,
  - named entity recognition,
  - stakeholder analysis,
  - topic modeling and media sentiment aggregation.

- **Outcomes**:
  - Political events strongly influenced media attention.
  - Sentiment analysis revealed systematic shifts in media tone following policy changes.
  - Different stakeholder groups exhibited distinct sentiment and framing patterns.

- **Relation to the Project**:  
  This study demonstrates how NLP methods such as BERT sentiment classification can extract meaningful signals from economic and political news coverage. The methodology is highly relevant for forecasting movements in the ifo index because business expectations are strongly influenced by media narratives and economic sentiment.

---

## 🔹 Source 3: [ifo Business Climate Index](https://www.ifo.de/en/survey/ifo-business-climate-index-germany)

- **Objective**: Measure the current business situation and expectations of German firms.

- **Methodology**:
  - Monthly survey of approximately **9,000 companies** across manufacturing, services, trade, and construction sectors.
  - Firms evaluate:
    - their current business situation,
    - and expectations for the next six months.

- **Outcomes**:
  - The ifo Business Climate Index is considered one of the most important leading indicators for the German economy.
  - It is widely used to assess economic conditions and predict turning points in business cycles.

- **Relation to the Project**:  
  Since the index reflects economic expectations and sentiment, newspaper articles and macroeconomic news may contain predictive information about future increases or decreases in the index. Our project aims to leverage machine learning and NLP techniques to classify whether the next release of the ifo index will move upward or downward based on recent economic news coverage.

---

# 🧠 Technology Comparison

| **Model / Technique** | **Advantages** | **Relevant Applications** |
|---|---|---|
| **Sentiment Analysis** | Captures positive/negative economic tone from text | Economic forecasting, business confidence prediction |
| **LSTM Networks** | Effective for sequential textual information | News-based macroeconomic forecasting |
| **BERT Models** | Context-aware language understanding | Financial news classification, sentiment extraction |
| **Topic Modeling (LDA)** | Identifies hidden themes in news articles | Economic topic extraction |
| **Dynamic Factor Models (DFM)** | Combines multiple time-series indicators efficiently | GDP and macroeconomic nowcasting |
| **MIDAS Regression** | Integrates mixed-frequency data | High-frequency economic forecasting |
| **Feature Extraction / Embeddings** | Converts textual information into numerical representations | NLP forecasting pipelines |
| **Transfer Learning** | Uses pretrained language knowledge | Improves performance on smaller datasets |
| **Classification Models** | Predict binary outcomes such as increase/decrease | ifo index direction prediction |

---

# 🎯 Project Goal

The objective of this project is to develop a machine learning framework capable of predicting whether the German **ifo Business Climate Index** will increase or decrease in its next release using textual information extracted from economic news articles.

We aim to:
- collect and preprocess German economic news,
- extract sentiment and semantic features using NLP techniques,
- train classification models such as BERT, LSTM, and traditional ML algorithms,
- and compare their predictive performance against baseline approaches.

The project combines:
- **Natural Language Processing (NLP)**,
- **Macroeconomic Forecasting**,
- and **Machine Learning**
to explore whether media sentiment can anticipate changes in business expectations in Germany.
