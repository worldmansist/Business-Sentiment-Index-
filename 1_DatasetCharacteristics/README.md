# 📖 Data Preprocessing

This notebook contains the preprocessing pipeline for the project.

The goal of the preprocessing stage is to prepare German economic news articles and align them with future releases of the **ifo Business Climate Index** in order to create a dataset for machine learning classification tasks.

---

# 📰 Current Dataset Status

At the current stage, only a **sample dataset** has been processed to test the preprocessing workflow and validate the data pipeline.

The full dataset will be collected and processed later.

### Planned Dataset
- Approximately **18,000 German economic news articles**
- Time period: **2023–2026** amd earlier
- ifo Business Climate Index releases for the same period

---

# ⚙️ Preprocessing Steps

The preprocessing pipeline currently includes:

- Date parsing and formatting
- Sorting articles chronologically
- Matching news articles with future ifo index releases
- Creation of binary target labels:
  - increase in the ifo index
  - decrease in the ifo index
- Initial text cleaning and preprocessing
- Preparation of structured datasets for NLP models

---

# 🎯 Objective

The purpose of preprocessing is to create a clean and temporally consistent dataset that can later be used for:
- sentiment analysis,
- feature extraction,
- topic modeling,
- and machine learning forecasting models.

The final objective is to predict the future movement of the German ifo Business Climate Index using economic news data.
