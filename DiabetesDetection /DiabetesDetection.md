# 🧬 Diabetes Detection – Predicting Risk from Health Data

Predicts the likelihood of diabetes using medical and lifestyle features through machine learning models.

- **Models**: Logistic Regression, Random Forest, XGBoost, MLP (Keras)
- **Stack**: Python, pandas, numpy, scikit-learn, tensorflow, Keras
- **BestResult**: F1 Score = 0.81, PR-AUC = 0.891 (XGBoost model)
- 🔗 [GitHub Repo](https://github.com/karmerruk7/karmerruk7.github.io/tree/main/DiabetesDetection%20)

---

## 🩺 Project Summary

**Diabetes Detection** is a machine learning classification project designed to predict the onset of diabetes using structured clinical and demographic data. The goal is to build interpretable, accurate models that support early diagnosis and preventive care.

---

## 🌐 Project Goals

- Clean and explore clinical datasets (e.g., glucose, insulin, BMI, age)
- Build and compare multiple supervised classification models
- Use feature engineering and resampling techniques to improve accuracy
- Package results for interpretability and future deployment

---

## 📊 Phase 1: Exploratory Data Analysis (EDA)

**Tools:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`

- Handled missing data and validated column integrity
- Explored feature distributions (e.g., glucose, insulin, BMI, age)
- Identified outliers and class imbalance
- Engineered new features: BMI category, age groups
- Used violin plots, pairplots, and correlation heatmaps

---

## 🧠 Phase 2: Predictive Modeling

**Tools:** `Scikit-Learn`, `XGBoost`, `TensorFlow/Keras`

### 🔹 Logistic Regression
- Fast, interpretable baseline
- PR-AUC: 0.812

### 🔹 XGBoost
- Tuned with `GridSearchCV` for optimal precision-recall
- PR-AUC: 0.891

### 🔹 MLP (Keras)
- Feedforward neural network trained on scaled data
- PR-AUC: 0.883

Used inbuilt tools to address class imbalance.

---

## 📈 Evaluation Metrics

- Accuracy
- Precision & Recall
- PR-AUC
- Confusion Matrix

Custom thresholds were selected to optimize F1 and Recall in medical context.

---

## 🔍 Model Insights

- **Feature Importance**: HbA1c_level, Glucose, BMI, and Age consistently ranked highest.
- **Best Model**: XGBoost 

---

## 🧰 Technical Stack

- **Languages**: Python  
- **Libraries**: pandas, NumPy, scikit-learn, XGBoost, TensorFlow/Keras, matplotlib, seaborn  
- **Notebooks**:  
  - `EDA.ipynb`  
  - `LinearModels.ipynb`  
  - `Non-LinearModels.ipynb`  
  - `NeuralNetwork.ipynb`  
- **Environment**: Jupyter

---

## 🚀 Phase 3: Deployment (Planned)

- Streamlit dashboard for diabetes risk prediction  
- Real-time form-based interface for new patient data  
- Backend: AWS Lambda or Hugging Face Spaces  
- Visual summaries: prediction, feature impact (via SHAP)

---

## 🌍 Results & Impact

- Delivered a robust classification pipeline for diabetes detection
- Learned real-world techniques for data cleaning, feature engineering, and model evaluation
- Strengthened skills in EDA, ML modeling, class imbalance handling, and interpretability
- Built a foundation for clinical decision-support tools using open data

---

## ✅ Skills Demonstrated

- **Machine Learning**: Logistic Regression, Random Forest, XGBoost, MLP  
- **Data Preprocessing**: Outlier handling, missing value imputation 
- **Evaluation & Tuning**: PR-AUC, ROC-AUC, GridSearchCV, threshold optimization  
- **Explainability**: Feature importance
- **End-to-End Workflow**: EDA → Modeling → Evaluation → Deployment-ready structure

---

[← Back to Home](./index)