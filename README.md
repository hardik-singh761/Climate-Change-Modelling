# 🌍 Climate Change Modeling

A machine learning project focused on predicting and analyzing key climate indicators such as temperature anomalies, precipitation patterns, and sea-level changes using historical datasets and predictive modeling techniques.

## 📌 Project Objective

To use machine learning and time-series analysis for modeling climate change effects over time. The goal is to understand past climate patterns and predict future trends that could influence environmental policy and sustainability efforts.

## 🔗 Project Link

👉 [GitHub Repository](https://github.com/hardik-singh761/Climate-Change-Modelling)

---

## 📁 Dataset Overview

Dataset includes multiple indicators across regions and years such as:

- **Global Temperature Trends**
- **Sea Level Rise Measurements**
- **Precipitation Anomalies**
- **CO₂ Emission Trends**
- **Social Media Sentiment on Climate**

> Source: Merged public datasets + custom collected social media data  
> 📂 Shape Example: 522 rows × 5 columns

---

## 🧹 Workflow

### 1. Data Cleaning
- Removed invalid timestamps and missing entries
- Standardized temperature units and formatted text fields

### 2. EDA & Visualization
- Trend plots, correlation heatmaps, anomaly detection
- Regional impact comparisons

### 3. Feature Engineering
- Built NLP features using VADER, SpaCy, Gensim for social sentiment
- Created rolling averages and lag features for time series

### 4. Modeling
- **Sentiment Analysis**: `SentimentIntensityAnalyzer` from VADER
- **Time Series Forecasting**: ARIMA model for temperature anomaly prediction

---

## 🛠️ Technologies Used

- Python, Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Sklearn, re, SpaCy, Gensim
- VADER Sentiment, ARIMA (statsmodels)

---

## 📊 Key Results

- **Sentiment polarity** aligned with global temperature spikes
- **ARIMA** captured warming trends with R² ~ 0.89
- Significant anomalies detected post-2000

---

## 🚀 Future Work

- Incorporate satellite imagery and remote sensing data
- Use LSTM or Prophet for multivariate forecasting
- Integrate climate policy timeline for impact analysis

---

## 🤝 Contributors

- **Hardik Singh**  
  Data Science Intern @ Unified Mentor  
  [GitHub](https://github.com/hardik-singh761)

---

## 📃 License

Licensed under the MIT License.
