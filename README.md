# Spare Parts Demand Forecasting

## 📌 Project Overview

This project focuses on forecasting spare parts demand for a large-scale industrial manufacturer using time series modeling techniques.

The objective is to:

- Predict future demand for individual spare parts
- Improve inventory planning accuracy
- Reduce stockouts and overstock risks
- Analyze demand seasonality and external drivers

The project simulates a real-world industrial forecasting environment with multiple SKUs and operational constraints.

---

## 🧠 Problem Statement

Spare parts demand is typically:

- Intermittent  
- Highly volatile  
- Seasonal  
- Affected by external operational factors  

Traditional forecasting methods often struggle with such patterns. This project explores modern time-series techniques to handle these challenges effectively.

---

## 📊 Methodology

The forecasting pipeline includes:

### 1️⃣ Data Preprocessing
- Cleaning and restructuring raw order data  
- Handling missing periods  
- Aggregating demand at appropriate time granularity  
- Identifying part changes and corrections  

### 2️⃣ Material Categorization
- Classification of parts based on demand behavior  
- Criticality and movement-based grouping  
- Differentiating slow-moving vs fast-moving items  

### 3️⃣ Time Series Modeling

Implemented models:

- Facebook Prophet
- Seasonality analysis
- Single-part forecasting
- Multi-item forecasting

Model components:

- Trend detection  
- Weekly / Monthly seasonality  
- Holiday effects (where applicable)  
- External regressors (exogenous variables)  

---

## 📈 Exogenous Variable Analysis

The project includes analysis of:

- Operational variables  
- External demand drivers  
- Their correlation with part consumption  

Feature impact was evaluated to improve predictive performance.

---

## 🏗️ Project Structure
├── Data Preprocessing & Cleaning
├── Material Categorization
├── Criticality Analysis
├── Exogenous Variables Analysis
├── Prophet Single Part Forecasting
├── Prophet Multi-Part Forecasting
└── Seasonality Modeling

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Facebook Prophet  
- Scikit-learn  

---

## 📊 Results

- Improved forecasting stability for intermittent demand
- Better seasonal pattern capture
- Enhanced visibility for inventory planning
- Scalable forecasting framework for multiple SKUs

---

## 🚀 Key Takeaways

- Intermittent spare part demand requires specialized handling  
- Feature engineering significantly impacts forecast quality  
- Prophet performs well when seasonality is properly tuned  
- External variables can improve model robustness  

---

## 🔒 Disclaimer

This repository contains a generalized and anonymized version of a real-world industrial forecasting project.  
All data has been modified or simulated to ensure confidentiality.


