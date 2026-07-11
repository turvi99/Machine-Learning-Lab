<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Labs-10%20Experiments-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Topics-12%2B%20Algorithms-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Streamlit-Dashboard-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
</p>

<h1 align="center">🧠 Machine Learning Lab — Experiment Portfolio</h1>

<p align="center">
  <strong>A comprehensive collection of 10 machine learning lab experiments covering NumPy fundamentals, data wrangling, preprocessing, regression, classification, NLP, data visualization, and interactive dashboards — implemented in Python with Jupyter Notebooks.</strong>
</p>

<p align="center">
  <em>Academic Lab Work — Machine Learning Course (AP23110010391)</em>
</p>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Lab Experiments](#-lab-experiments)
- [Algorithms & Techniques](#-algorithms--techniques-covered)
- [Datasets Used](#-datasets-used)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)

---

## 🎯 Overview

This repository contains **10 lab experiments** spanning the complete machine learning lifecycle — from NumPy array operations and data preprocessing to building classification/regression models and deploying interactive dashboards.

### Key Highlights

| Metric | Value |
|:--|:--|
| **Total Experiments** | 10 |
| **ML Algorithms** | 12+ (Logistic Regression, Linear Regression, Naive Bayes, SMOTE, PCA, etc.) |
| **Datasets** | 6 (Titanic, Breast Cancer, Bike Sharing, Churn, Resume, US Airlines Tweets) |
| **Best Accuracy** | 97.2% (Logistic Regression on Breast Cancer) |
| **NLP Project** | Resume Classifier with Naive Bayes (76% accuracy) |
| **Dashboard** | Streamlit Sentiment Analysis of US Airline Tweets |

---

## 🧪 Lab Experiments

### Lab 1 — NumPy Fundamentals
**File**: `Lab1AP23110010391.ipynb` (16 cells)

| Topic | Details |
|:------|:--------|
| **Focus** | NumPy array operations and linear algebra |
| **Concepts** | Array creation (`zeros`, `ones`, `full`, `eye`, `arange`), indexing & slicing, element-wise arithmetic, matrix multiplication (`dot`), aggregation (`max`, `min`, `sum`, `cumsum`), trigonometric functions, matrix inverse (`linalg.inv`), file I/O (`loadtxt`) |

---

### Lab 2 — Data Wrangling with Pandas
**File**: `Copy_of_Lab2_AP23110010391.ipynb` (39 cells)

| Topic | Details |
|:------|:--------|
| **Focus** | Pandas data manipulation and analysis |
| **Dataset** | Tips dataset (Seaborn — 244 rows × 7 columns) |
| **Concepts** | `iloc`/`loc` selection, boolean filtering, `query()`, sorting, `assign()` for new columns, type casting to `category`, column renaming, `groupby` aggregation, feature engineering (`tip_pct`, `tip_per_person`, `bill_per_person`) |

---

### Lab 3 — Data Preprocessing & Feature Engineering
**File**: `Lab3_AP23110010391.ipynb` (26 cells)

| Topic | Details |
|:------|:--------|
| **Focus** | Complete preprocessing pipeline with exercises |
| **Dataset** | Titanic (Kaggle — 891 rows × 12 columns) |
| **Techniques** | Missing value handling (drop, mean/median imputation, KNN imputation), `StandardScaler`, `MinMaxScaler`, `Normalizer`, `OrdinalEncoder`, `OneHotEncoder`, `PowerTransformer` (Yeo-Johnson), `PolynomialFeatures`, **PCA** (dimensionality reduction to 2 components) |

---

### Lab 4 — Breast Cancer Classification (Logistic Regression)
**File**: `Breast_Cancer_Lab4_AP23110010391.ipynb` (27 cells)

| Topic | Details |
|:------|:--------|
| **Focus** | Binary classification — Malignant (M) vs. Benign (B) |
| **Dataset** | Breast Cancer Wisconsin (Kaggle — 569 rows × 32 columns) |
| **Model** | Logistic Regression |
| **Preprocessing** | LabelEncoder, StandardScaler, 75/25 train-test split |
| **Accuracy** | **97.2%** |
| **Confusion Matrix** | `[[85, 0], [4, 54]]` — only 4 misclassifications |

---

### Lab 5 — Breast Cancer Regression Analysis
**File**: `Breast_Cancer_Lab5_AP23110010391.ipynb` (25 cells)

| Topic | Details |
|:------|:--------|
| **Focus** | Regression approach to breast cancer diagnosis |
| **Dataset** | Breast Cancer Wisconsin (Kaggle — 569 rows × 32 columns) |
| **Model** | Linear Regression (treating diagnosis as continuous) |
| **Metrics** | MSE: 0.059, RMSE: 0.243, MAE: 0.188, R²: 0.748 |

---

### Lab 6 — Regression & Classification Deep Dive
**File**: `AP23110010391_Lab6.ipynb` (231 cells)

| Topic | Details |
|:------|:--------|
| **Focus** | Comprehensive regression and classification on Bike Sharing dataset |
| **Dataset** | Bike Sharing dataset |
| **Techniques** | Univariate & Multivariate Linear Regression, MinMaxScaler, SMOTE (class balancing), Logistic Regression for classification |

**Regression Results:**

| Model | MSE | RMSE |
|:------|:----|:-----|
| Univariate (temp only) | 0.2488 | 0.4988 |
| Multivariate | 0.2446 | 0.4946 |

**Classification Results (Logistic Regression with SMOTE):**

| Split | Accuracy |
|:------|:---------|
| Training | 91.6% |
| Validation | 91.0% |
| Test | 91.0% |
| F1 Score | 0.903 |

---

### Lab 7 — Bivariate Analysis & Visualization
**File**: `AP23110010391_Bivariate_analysis.ipynb` (59 cells)

| Topic | Details |
|:------|:--------|
| **Focus** | Bivariate data visualization techniques |
| **Dataset** | Churn Modelling dataset |
| **Visualizations** | Line plots (tenure distribution, avg credit score by tenure), multi-line plots with legends, styled plots (colors, markers, labels, grids), axis range customization, subplots, scatter plots |
| **Libraries** | Matplotlib, Seaborn |

---

### Lab 8 — Univariate Data Visualization
**File**: `AP23110010391_Lab8.ipynb` (32 cells)

| Topic | Details |
|:------|:--------|
| **Focus** | Univariate visualization for categorical and numerical data |
| **Dataset** | Telecom Churn dataset |
| **Visualizations** | Bar charts, count plots, pie charts (Churn, ContractRenewal, DataPlan), histograms (AccountWeeks), Matplotlib anatomy |
| **Libraries** | Matplotlib, Seaborn |

---

### Lab 9 — Resume Selector with Naive Bayes (NLP)
**File**: `AP23110010391_Resume Selector with Naive Bayes.ipynb` (95 cells)

| Topic | Details |
|:------|:--------|
| **Focus** | NLP-based resume classification — Flagged vs. Not Flagged |
| **Dataset** | Resume dataset (125 resumes, 2 columns: `resume_text`, `class`) |
| **NLP Pipeline** | Text cleaning, NLTK tokenization, stopword removal, lemmatization, stemming (PorterStemmer, WordNetLemmatizer) |
| **Vectorization** | CountVectorizer (Bag of Words) |
| **Model** | Multinomial Naive Bayes |
| **Accuracy** | **76%** (80/20 split) and **74%** (70/30 split) |
| **Visualizations** | Word clouds (flagged vs. not flagged), count plots, confusion matrix heatmaps |

**Classification Report (80/20 split):**

| Class | Precision | Recall | F1 Score |
|:------|:----------|:-------|:---------|
| Not Flagged (0) | 0.89 | 0.81 | 0.85 |
| Flagged (1) | 0.33 | 0.50 | 0.40 |
| **Accuracy** | | | **0.76** |

---

### Lab 10 — Interactive Streamlit Dashboard
**File**: `AP23110010391_Create Interactive Dashboards with Streamlit and Python`

| Topic | Details |
|:------|:--------|
| **Focus** | Sentiment Analysis Dashboard for US Airline Tweets |
| **Dataset** | Tweets.csv (US Airlines sentiment data) |
| **Framework** | Streamlit + Plotly |
| **Features** | Random tweet viewer by sentiment, tweet count visualization (histogram/pie chart), geolocation map by hour, airline breakdown by sentiment, word cloud generator |

**Dashboard Components:**

| Component | Description |
|:----------|:------------|
| 🎯 **Sentiment Filter** | Radio buttons: positive / neutral / negative |
| 📊 **Tweet Count** | Bar chart or Pie chart (user selectable) |
| 🗺️ **Location Map** | Tweets plotted on map by hour of day |
| ✈️ **Airline Breakdown** | Multi-select filter for 6 airlines with faceted histograms |
| ☁️ **Word Cloud** | Generated per sentiment (filters URLs and @mentions) |

---

## 🔧 Algorithms & Techniques Covered

| Category | Algorithms / Techniques |
|:---------|:-----------------------|
| **Supervised — Classification** | Logistic Regression, Multinomial Naive Bayes |
| **Supervised — Regression** | Linear Regression (Univariate & Multivariate) |
| **Preprocessing** | StandardScaler, MinMaxScaler, Normalizer, LabelEncoder, OrdinalEncoder, OneHotEncoder |
| **Imputation** | Mean, Median, KNN Imputer |
| **Feature Engineering** | PolynomialFeatures, PowerTransformer (Yeo-Johnson), PCA |
| **Class Balancing** | SMOTE |
| **NLP** | Tokenization, Stopword Removal, Stemming, Lemmatization, CountVectorizer |
| **Evaluation** | Accuracy, Precision, Recall, F1 Score, MSE, RMSE, MAE, R², Confusion Matrix |
| **Visualization** | Matplotlib, Seaborn, Plotly, WordCloud |

---

## 📊 Datasets Used

| # | Dataset | Source | Size | Used In |
|:-:|:--------|:-------|:-----|:--------|
| 1 | Tips | Seaborn built-in | 244 × 7 | Lab 2 |
| 2 | Titanic | Kaggle / GitHub | 891 × 12 | Lab 3 |
| 3 | Breast Cancer Wisconsin | Kaggle (UCI) | 569 × 32 | Lab 4, Lab 5 |
| 4 | Bike Sharing | Google Drive | — | Lab 6 |
| 5 | Churn Modelling | Google Drive | — | Lab 7 |
| 6 | Telecom Churn | Google Drive | — | Lab 8 |
| 7 | Resumes | CSV (125 resumes) | 125 × 2 | Lab 9 |
| 8 | US Airline Tweets | Local CSV | — | Lab 10 |

---

## 🛠️ Tech Stack

| Category | Technology |
|:---------|:-----------|
| **Language** | Python 3.8+ |
| **ML Framework** | Scikit-Learn |
| **Data Processing** | Pandas, NumPy, SciPy |
| **NLP** | NLTK, Gensim |
| **Visualization** | Matplotlib, Seaborn, Plotly, WordCloud |
| **Dashboard** | Streamlit |
| **Development** | Google Colab, Jupyter Notebook |
| **Data Source** | Kaggle API |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook or Google Colab

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/turvi99/Machine-Learning-Lab.git
cd Machine-Learning-Lab

# 2. Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn nltk gensim wordcloud plotly streamlit

# 3. Open any notebook
jupyter notebook
```

### Run the Streamlit Dashboard

```bash
# Navigate to the project directory
streamlit run "AP23110010391_Create Interactive Dashboards with Streamlit and Python"
```

---

## 📁 Project Structure

```
Machine-Learning-Lab/
│
├── Lab1AP23110010391.ipynb                    # Lab 1  — NumPy Fundamentals
├── Copy_of_Lab2_AP23110010391.ipynb           # Lab 2  — Pandas Data Wrangling (Tips)
├── Lab3_AP23110010391.ipynb                   # Lab 3  — Preprocessing & PCA (Titanic)
├── Breast_Cancer_Lab4_AP23110010391.ipynb     # Lab 4  — Logistic Regression (97.2%)
├── Breast_Cancer_Lab5_AP23110010391.ipynb     # Lab 5  — Linear Regression (R²=0.748)
├── Scratch_Lab5_AP23110010391.ipynb           # Lab 5  — Scratch/draft notebook
├── AP23110010391_Lab6.ipynb                   # Lab 6  — Regression + SMOTE (91% acc)
├── AP23110010391_Bivariate_analysis.ipynb     # Lab 7  — Bivariate Visualization
├── AP23110010391_Lab8.ipynb                   # Lab 8  — Univariate Visualization
├── AP23110010391_Resume Selector...ipynb      # Lab 9  — NLP Resume Classifier (76%)
├── AP23110010391_Create Interactive...         # Lab 10 — Streamlit Dashboard (Python)
├── AP23110010391_Create Interactive...pdf      # Lab 10 — Dashboard documentation (PDF)
│
└── README.md                                  # 📖 This file
```

---

## 📈 Results Summary

| Lab | Task | Model / Technique | Key Metric |
|:---:|:-----|:-------------------|:-----------|
| 1 | NumPy Operations | — | Fundamentals |
| 2 | Data Wrangling | Pandas | EDA |
| 3 | Preprocessing | PCA, Scalers, Imputers | Pipeline |
| 4 | Breast Cancer Classification | Logistic Regression | **97.2% Accuracy** |
| 5 | Breast Cancer Regression | Linear Regression | **R² = 0.748** |
| 6 | Bike Sharing | Linear Reg + Logistic Reg + SMOTE | **91.0% Accuracy** |
| 7 | Bivariate Analysis | Matplotlib, Seaborn | Visualization |
| 8 | Univariate Analysis | Matplotlib, Seaborn | Visualization |
| 9 | Resume Classification | Multinomial Naive Bayes | **76% Accuracy** |
| 10 | Tweet Sentiment Dashboard | Streamlit + Plotly | Interactive App |

---

<p align="center">
  <strong>Built with ❤️ for mastering Machine Learning fundamentals</strong><br/>
  <sub>If you found this useful, consider giving it a ⭐</sub>
</p>
