# ❤️ Heart Disease Prediction using Machine Learning

This project builds and evaluates machine learning models to predict the presence of heart disease using clinical features. It uses a dataset of patient attributes like age, cholesterol levels, exercise data, and more.

---

## 📌 Project Goals

- Perform Exploratory Data Analysis (EDA)
- Select the most relevant features
- Train classification models: Logistic Regression, Random Forest, XGBoost
- Evaluate and compare model performance
- Visualize key insights and metrics

---

## 📁 Dataset

- **Source:** [Heart Disease UCI Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- **Features Used:**
  - `Age`, `Sex`, `ChestPainType`, `RestingBP`, `Cholesterol`, `FastingBS`
  - `RestingECG`, `MaxHR`, `ExerciseAngina`, `Oldpeak`, `ST_Slope`
  - `HeartDisease` (Target variable)

---

## 🧰 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- XGBoost

---

## 🔬 Exploratory Data Analysis (EDA)

- Box plots and bar charts to understand distribution
- Pairplots to explore feature relationships
- Identified key variables linked to heart disease:
  - **Oldpeak**, **ST_Slope**, **ChestPainType**, **ExerciseAngina**, **MaxHR**

---

## ✅ Feature Selection

Used **SelectKBest (chi-square)** and **Random Forest feature importance** to identify top predictors:
- `Oldpeak`, `ST_Slope`, `ChestPainType`, `MaxHR`, `ExerciseAngina`, `RestingECG`, `Age`

---

## 🤖 Model Building

Trained and compared three models:
- **Logistic Regression**
- **Random Forest**
- **XGBoost**

Used 80/20 train-test split.

---

## 📊 Model Evaluation

| Model                | Accuracy | AUC  |
|---------------------|----------|------|
| Logistic Regression | 85.87%   | 0.91 |
| Random Forest       | 88.59%   | 0.94 |
| XGBoost             | 86.96%   | 0.94 |

- Random Forest performed best overall
- ROC Curve and Confusion Matrix were used to visualize performance
- All models achieved strong results with high precision and recall

---

## 📌 Conclusion

- **ST_Slope** and **Oldpeak** are strong indicators of heart disease.
- **Random Forest** and **XGBoost** are most effective for prediction.
- This model can be extended with more features and deployed in healthcare applications.

---

## ▶️ Run It Yourself

```bash
pip install pandas numpy seaborn matplotlib scikit-learn xgboost
