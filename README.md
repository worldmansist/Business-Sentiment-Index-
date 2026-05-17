# ifoPredict - Forecasting German Business Sentiment with NLP

## Repository Link

https://github.com/worldmansist/ifoPredict

---

# 📖 Description

This project focuses on predicting the future direction of the German **ifo Business Climate Index** using Natural Language Processing (NLP) and Machine Learning techniques.

The objective is to determine whether the next release of the ifo index will show an **increase** or **decrease** based on German economic news articles and textual sentiment extracted from media sources.

The project combines:
- macroeconomic forecasting,
- sentiment analysis,
- text mining,
- and machine learning models
to investigate whether media narratives can anticipate changes in German business expectations.

The ifo Business Climate Index is one of the most important leading indicators for the German economy and is based on monthly surveys of approximately 9,000 German firms across multiple sectors.

---

# 🎯 Task Type

**Binary Classification**
- **Increase** in the ifo Business Climate Index
- **Decrease** in the ifo Business Climate Index

---

# 📊 Planned Methodology

## Data Sources
- German economic news articles
- ifo Business Climate Index releases
- Macroeconomic and sentiment-related indicators

## NLP Techniques
- Sentiment Analysis
- Topic Modeling (LDA)
- Text Embeddings
- Feature Extraction

## Machine Learning Models
- LSTM
- BERT-based models

---

# 📚 Documentation

1. **[Literature Review](0_LiteratureReview/README.md)**
2. **[Data Collection and Preprocessing](1_DataPreparation/data_preparation.ipynb)**
3. **[Exploratory Data Analysis](2_EDA/exploratory_data_analysis.ipynb)**
4. **[Baseline Models](3_BaselineModels/baseline_models.ipynb)**
5. **[Model Development](4_Model/model_training.ipynb)**
6. **[Evaluation and Results](5_Evaluation/evaluation.ipynb)**
7. **[Presentation](6_Presentation/README.md)**

---

# 🧠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- PyTorch
- Hugging Face Transformers
- NLTK / spaCy

---

# 🚀 Project Goal

The main objective of this project is to explore whether textual information from economic news can improve short-term forecasting of German business sentiment.

We aim to:
- preprocess and analyze German economic news,
- extract sentiment and semantic information from text,
- train machine learning models for directional forecasting,
- and compare NLP-based approaches against traditional baseline models.

The project is inspired by recent research on text-based macroeconomic forecasting and business sentiment analysis.
