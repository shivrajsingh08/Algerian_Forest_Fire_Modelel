# 🔥 Algerian Forest Fire Classification - ML Mini Project

This project builds a machine learning model to classify the presence of forest fires in Algerian regions using meteorological data. It covers the full ML pipeline: from data cleaning to feature engineering, modeling, evaluation, and model deployment using Pickle.

---

## 🧠 Objective

Predict the FWI(Fire Weather Index) based on environmental conditions like temperature, humidity, wind speed, and drought indices.

---

## 📊 Dataset

- *Source:* Algerian Forest Fires Dataset (UCI ML Repository)
- *File Used:* Algerian_forest_fires_dataset_UPDATE.csv
- *Total Samples:* 247
- *Features:* 12 (e.g., Temperature, RH, WS, FFMC, DMC, DC, ISI, BUI, FWI)
- *Target Variable:* FWI

---

## ⚙ Project Workflow

1. *Data Loading & Cleaning*
   - Remove redundant header rows
   - Handle missing values

2. *Exploratory Data Analysis*
   - Correlation heatmaps
   - Class distribution
   - Feature histograms

3. *Feature Engineering*
   - Label Encoding for target variable
   - Standardization using StandardScaler

4. *Model Training*
   - Logistic Regression
   - Lasso Regression
   - Ridge Regression
   - Elastic Net Regression
   - Train-test split (typically 80/20)

5. *Evaluation*
   - R2 Score
   - Erroe Matrices

6. *Model Deployment*
   - Save model and scaler using pickle
   - model.pkl and scaler.pkl files included

---

## 💻 Project Structure

📁 Algerian-Forest-Fire-ML/
├── algerian_forest_fire_model_prediction.ipynb        # Main notebook: EDA, feature engineering, model building, prediction
├── Algerian_forest_fires_dataset_UPDATE.csv           # Raw dataset (original data source)
├── Algerian_forest_fires_model_cleaned_dataset.csv    # Cleaned dataset used for training the ML model
├── model.pkl                                          # Trained machine learning model saved using pickle
├── scaler.pkl                                         # Feature scaler object saved for future use 
├── README.md                                          # Project documentation and instructions
└── requirements.txt                                   # List of Python libraries used in the project

