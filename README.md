#  SmartAQI-PM2.5-Forecasting-Pollution-Analytics


##  Overview
SmartAQI is a complete Machine Learning project designed to analyze urban air pollution data and predict PM2.5 concentration levels.  
The project includes data consolidation, exploratory data analysis (EDA), baseline modeling, and advanced machine learning model development using LightGBM.

This system helps understand pollution trends and enables predictive insights that can support environmental monitoring and public health planning.

---

##  Features

- Data consolidation from multiple pollution datasets
- Data cleaning and preprocessing pipeline
- Exploratory Data Analysis (EDA) with visualization
- Outlier detection and missing value analysis
- Baseline model implementation for performance benchmarking
- Advanced ML model using LightGBM
- Model evaluation using RMSE, MAE, and R² Score
- Feature importance and model explainability using SHAP
- Structured train / validation / test workflow

---

##  Project Workflow

### 1️ Data Consolidation
- Multiple pollution datasets are merged into a unified dataset
- Standardization of columns like:
  - City
  - Date
  - PM2.5
  - PM10
  - NO
  - NO2
- Handling inconsistent formats and missing records

### 2️ Exploratory Data Analysis (EDA)
- Distribution analysis of pollutants
- Missing value percentage analysis
- Skewness and outlier detection using IQR
- Time-series trend visualization
- City-wise pollution comparison

### 3️ Baseline Model
- Dummy Regressor used to create baseline performance
- Mean prediction strategy for PM2.5
- Helps measure improvement of advanced ML models

### 4️ Machine Learning Model
- LightGBM Regressor used for PM2.5 prediction
- Hyperparameter tuning for performance optimization
- Training on structured feature set
- Model evaluation on validation and test datasets

### 5️ Model Explainability
- SHAP analysis used to interpret feature importance
- Understanding which pollutants most influence PM2.5 levels

---

##  Evaluation Metrics

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score

These metrics help measure prediction accuracy and model reliability.

---

##  Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- LightGBM
- SHAP

---

##  Project Structure

```
SmartAQI/
│
├── DATA_CONSOLIDATION.ipynb
├── EDA.ipynb
├── base_model.ipynb
├── ML_MODEL.ipynb
│
├── train_ml.csv
├── val_ml.csv
├── test_ml.csv
│
├── city_map.json
└── README.md
```

