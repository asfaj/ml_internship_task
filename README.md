# DevelopersHub Corporation - AI/ML Engineering Internship Tasks

## Overview
This repository contains the AI/ML Engineering Internship tasks completed as part of the DevelopersHub Corporation Internship Program.  
The goal is to build practical skills in data analysis, machine learning, and AI applications using real-world datasets.

---

## Tasks Completed

### Task 1: Exploring and Visualizing a Simple Dataset
- **Objective:** Load, inspect, and visualize a dataset to understand data trends and distributions.
- **Dataset:** Iris Dataset (CSV / seaborn)
- **Approach:** 
  - Loaded dataset using `pandas`
  - Explored dataset with `.head()`, `.info()`, and `.describe()`
  - Visualized relationships between features using scatter plots, histograms, and box plots
- **Skills Gained:** Data loading, descriptive statistics, visualization (`matplotlib`, `seaborn`)

---

### Task 2: Predict Future Stock Prices (Short-Term)
- **Objective:** Predict the next day's stock closing price.
- **Dataset:** Stock data via `yfinance` (e.g., Apple, Tesla)
- **Approach:** 
  - Fetched historical stock data using `yfinance`
  - Trained Linear Regression and Random Forest models
  - Plotted actual vs predicted closing prices
- **Skills Gained:** Time series handling, regression modeling, API usage, visualization

---

### Task 3: Heart Disease Prediction
- **Objective:** Predict risk of heart disease based on health data.
- **Dataset:** Heart Disease UCI Dataset (Kaggle)
- **Approach:** 
  - Cleaned dataset and handled missing values
  - Performed Exploratory Data Analysis (EDA)
  - Trained Logistic Regression and Decision Tree models
  - Evaluated using accuracy, ROC curve, confusion matrix
- **Skills Gained:** Binary classification, medical data interpretation, feature importance

---

### Task 4: General Health Query Chatbot
- **Objective:** Build a chatbot answering general health questions.
- **Tools:**  google/flan-t5-small

- **Approach:** 
  - Python script to send queries to LLM
  - Prompt engineering for clear, friendly responses
  - Added safety filters
- **Example Queries:** "What causes a sore throat?", "Is paracetamol safe for children?"
- **Skills Gained:** Prompt design, API usage, conversational agent building

---


### Task 5: House Price Prediction
- **Objective:** Predict house prices using property features.
- **Dataset:** House Price Dataset (Kaggle)
- **Approach:** 
  - Preprocessed features (size, bedrooms, location)
  - Trained Linear Regression and Gradient Boosting models
  - Visualized predicted vs actual prices
  - Evaluated using MAE and RMSE
- **Skills Gained:** Regression modeling, feature scaling, evaluation metrics, real estate data analysis


---

## Submission
- Each task includes a Jupyter Notebook with:
  - Problem statement
  - Dataset loading & preprocessing
  - Analysis & visualization
  - Model training & evaluation
  - Explanation of results
- Code is clean, modular, and commented.

---
