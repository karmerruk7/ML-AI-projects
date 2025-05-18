<<<<<<< Updated upstream

# ⚡ Watt Wise – Building Energy Forecasting

Forecasts hourly and daily energy usage using MLP with weather, occupancy, and system usage features.

- **Model**: SARIMAX, XGBoost, Random forrest, MLP (Keras)
- **Stack**: Python, pandas, numpy, ski-learn, tensorflow,  Keras, ect
- **Result**: RMSE = 5.5, R² = 0.4978 with MLP model
- [GitHub](https://github.com/karmerruk7/karmerruk7.github.io/tree/main/watt-wise)

---

 +++ ADD MORE LATER
=======
# ⚡ Watt Wise – Building Energy Forecasting

Forecasts hourly and daily energy usage using machine learning and deep learning models with weather, occupancy, and system usage features.

- **Models**: SARIMAX, XGBoost, Random Forest, MLP (Keras), LSTM
- **Stack**: Python, pandas, numpy, scikit-learn, statsmodels, tensorflow, Keras, Streamlit
- **Key Features**:
  - Time-lagged features and cyclical time encodings (`hour_sin`, `dow_cos`)
  - Temperature, humidity, occupancy, HVAC and lighting usage
  - Multi-step forecasting
  - Model explainability and comparison tools
- **Performance**:
  - **Best Model**: MLP
  - **RMSE**: 5.50
  - **R²**: 0.4978

- 📁 **EDA**, **ML**, **MLP**, and **SARIMAX** notebooks included

🔗 [GitHub Repo](https://github.com/karmerruk7/karmerruk7.github.io/tree/main/watt-wise)

---

# 🔋 Watt Wise: Intelligent Energy Forecasting for Smart Buildings

**Watt Wise** is a full-cycle data science project I led to solve a real-world problem: predicting and optimizing building energy consumption. With rising energy costs and sustainability demands, I designed a solution that combines domain knowledge, statistical modeling, and deep learning to forecast energy usage using environmental and operational data.

---

## 🌐 Project Vision

The goal of this project was to develop a scalable, production-ready pipeline that:
- Ingests real-time building sensor data (temperature, humidity, occupancy, etc.)
- Applies advanced time series and machine learning models
- Produces accurate short-term and medium-term energy forecasts

This end-to-end solution highlights my ability to go from raw data to deployed product — independently and effectively.

---

## 📊 Phase 1: Exploratory Data Analysis (EDA)

**Key tools:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`

Tasks:
- Cleaned and aligned timestamped data with multiple sensor feeds
- Identified and handled missing values and time gaps
- Uncovered seasonal patterns and trends using time series decomposition
- Engineered features like rolling stats, lag variables, and cyclical encodings (`hour_sin`, `dayofweek_cos`)

This phase demonstrated my proficiency in wrangling time series data and preparing it for modeling.

---

## 🧠 Phase 2: Predictive Modeling (Classical ML)

**Key tools:** `Scikit-Learn`, `XGBoost`

I built and compared classical models using lagged inputs and environmental variables:
- **Random Forest**: Captured nonlinear interactions
- **XGBoost**: Provided excellent performance through and boosting

I used MAE, RMSE, and R² as evaluation metrics and performed hyperparameter tuning via `GridSearchCV`.

---

## 🔮 Phase 3: Deep Learning Approaches

**Key tools:** `TensorFlow`, `Keras`

I developed two deep learning pipelines:

### 🔹 Multilayer Perceptron (MLP)
- Input: Temperature and Humidity
- Strength: Simpler to train; effective for shorter forecasts

This models taught me how to structure input for sequence learning, manage overfitting, and tune MLP architectures for real-world signals.

---

## 📈 Phase 4: Statistical Time Series Modeling

**Key tools:** `Statsmodels`, `SARIMAX`

I implemented SARIMAX to provide interpretable predictions and benchmark deep models. Notable aspects:
- Modeled daily seasonality and energy inertia
- Included temperature and humidity as external regressors
- Used likelihood ratio tests for statistical model selection

This phase balanced model accuracy with explainability — valuable for enterprise use cases.

---

## 🧰 Technical Stack

- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, XGBoost, Statsmodels, TensorFlow/Keras
- **Deployment Tools:** Streamlit (dashboard), AWS (planned)
- **Notebooks:** Jupyter for development and collaboration

---

## 🚀 Final Phase: Deployment (In Progress)

To showcase the forecasting models and enable real-world use:
- Built a **Streamlit web dashboard** with upload support and visualizations
- Allows users to select forecast horizon (24h or 7-day)
- Includes **live model comparison metrics** and **interactive plots**
- Planned deployment via AWS or Hugging Face Spaces

This phase demonstrates my ability to package, present, and scale solutions for end-users.

---

## 🌍 Results & Impact

Through Watt Wise, I:
- Delivered accurate forecasts of building energy use
- Gained hands-on experience with modeling, interpretability, and deployment
- Learned how to design for both performance and usability
- Strengthened my skills in MLOps and time series forecasting

---

## ✅ Skills Demonstrated

- **Machine Learning & Deep Learning**: MLP, LSTM, XGBoost, SARIMAX
- **Time Series Analysis**: Lag features, seasonality, trend decomposition
- **End-to-End Project Ownership**: From data ingestion to dashboard deployment
- **Technical Communication**: Documented, visualized, and explained insights clearly
- **Deployment-Ready Coding**: Used modular design, reproducible pipelines, and clean code

>>>>>>> Stashed changes

---

[← Back to Home](./index)