# 🎯 Sentiment Analysis - IMDb Movie Reviews

## 📝 Overview

This project applies **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques to analyze IMDb movie reviews and predict their sentiment—**positive** or **negative**. The pipeline includes text preprocessing, feature extraction, model building, evaluation, and insightful visualizations.

---

## 📁 Dataset

- **Name**: IMDb Movie Review Dataset  
- **Source**: [AI Stanford IMDb Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)
- **Size**: 50,000 reviews (25,000 positive, 25,000 negative)
- **Columns**:
  - `review`: The textual review
  - `sentiment`: `positive` or `negative`

---

## 🧰 Tools & Libraries

- **Google Colab** (for coding & GPU support)
- **Libraries**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `nltk`, `re`, `bs4`, `wordcloud`
  - `scikit-learn` (TF-IDF, ML models)
  - `xgboost`

---

## 🚦 Project Steps

### ✅ Step 1: Data Loading
- Load IMDb dataset using `pandas`.

### ✅ Step 2: Text Preprocessing
- Remove HTML tags with `BeautifulSoup`
- Lowercase text
- Remove punctuation and stopwords
- Tokenize and lemmatize with `nltk`

### ✅ Step 3: Feature Extraction
- Transform clean text into vectors using **TF-IDF**

### ✅ Step 4: Model Building
- Split data into train and test
- Train three models:
  - **Logistic Regression**
  - **Random Forest**
  - **XGBoost**

### ✅ Step 5: Evaluation
- Calculate:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix
- Compare models using bar charts

### ✅ Step 6: Insights & Visualization
- **Word Clouds** for positive and negative reviews
- **Sentiment Distribution** bar chart

---

## 📊 Model Performance Summary

| Model               | Accuracy | Precision | Recall | F1-score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression| 87.3%    | 87%       | 87%    | 87%      |
| Random Forest       | 89.1%    | 89%       | 89%    | 89%      |
| XGBoost             | 90.4%    | 90%       | 90%    | 90%      |

🔵 **XGBoost** provided the best overall performance.

---

## 📂 Folder Structure

