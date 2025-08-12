# AI & ML Internship Tasks

This repository contains the work I completed during my **AI & Machine Learning Internship** at **Developers Hub Corporation**.  
Over the course of the internship, I explored a variety of datasets, applied multiple machine learning algorithms, and visualized data insights using popular Python libraries.

---

## 📌 Internship Objectives
- Gain hands-on experience with **data analysis**, **visualization**, and **machine learning models**.
- Work with real-world datasets from **Kaggle** and APIs like **yfinance**.
- Build and evaluate predictive models for different problem statements.
- Interpret and present key findings from data exploration.

---

## 📚 Libraries & Tools Used
- **Python** (core language)
- **NumPy** – numerical computations
- **Pandas** – data manipulation
- **Matplotlib** & **Seaborn** – data visualization
- **yfinance** – fetching stock market data
- **scikit-learn** – ML models & evaluation metrics

---

## 📂 Tasks Overview

### **Task 1: Basic Data Exploration & Visualization**
- **Dataset**: Iris Dataset (Kaggle)
- **Objective**: Perform exploratory data analysis (EDA) and visualize feature relationships.
- **Techniques Used**: Matplotlib & Seaborn for histograms, scatter plots, and pair plots.
- **Findings**:
  - Clear separation between Iris species in certain feature pairs.
  - Petal length and petal width were strong distinguishing features.

---

### **Task 2: Apple Stock Price Prediction**
- **Dataset**: Apple stock data fetched via `yfinance`.
- **Objective**: Predict short-term closing prices for Apple (AAPL).
- **Models Applied**:
  - **Linear Regression**
    - Score: **0.80**
    - R²: **0.80**
    - MAE: **1.3 USD**
  - **Random Forest Regressor**
    - Score: **0.80**
    - R²: **0.80**
    - MAE: **1.1 USD**
- **Findings**:
  - Both models achieved similar R², with Random Forest slightly reducing average error.
  - Predictions followed the actual price trend well in short-term forecasting.

---

### **Task 3: Heart Disease Prediction**
- **Dataset**: Heart Disease Prediction Dataset (Kaggle).
- **Objective**: Classify patients as at risk or not at risk of heart disease.
- **Models Applied**:
  - **Decision Tree Classifier**
    - Accuracy: **0.9854**
    - Precision: **1.0**
    - Recall: **0.9709**
    - F1 Score: **0.9852**
  - **Logistic Regression**
    - Accuracy: **0.7902**
    - Precision: **0.7542**
    - Recall: **0.8641**
    - F1 Score: **0.8054**
- **Findings**:
  - Decision Tree achieved outstanding accuracy and perfect precision.
  - Logistic Regression performed reasonably well but was less accurate than the Decision Tree.

---

### **Task 6: House Price Prediction**
- **Dataset**: House Prices Dataset (Kaggle).
- **Objective**: Predict sale prices of houses based on various features.
- **Model Applied**:
  - **Linear Regression**
    - R²: **0.75**
- **Findings**:
  - Model explained 75% of variance in prices.
  - Location, overall quality, and living area size were key predictors.

---

## 📊 Summary of Datasets
| Task | Dataset Source | Problem Type | Target Variable |
|------|----------------|--------------|-----------------|
| Task 1 | Iris Dataset (Kaggle) | Classification (EDA only) | Species |
| Task 2 | yfinance (AAPL) | Regression | Close Price |
| Task 3 | Heart Disease Dataset (Kaggle) | Classification | Heart Disease Presence |
| Task 6 | House Price Dataset (Kaggle) | Regression | Sale Price |

---

## 🚀 Key Learnings & Achievements
- Learned to clean, preprocess, and visualize diverse datasets.
- Gained experience with **Random Forest, Linear Regression, Decision Trees, and Logistic Regression**.
- Improved skills in model evaluation using **MAE, R² score, Accuracy, Precision, Recall, and F1 score**.
- Produced actionable insights like:
  - Predicting short-term Apple stock movements.
  - Identifying potential heart disease patients from health records.
  - Estimating house prices for real estate purposes.

---

## 🏢 Organization
**Developers Hub Corporation** – AI/ML Internship Program.

---

## 📈 Visual Highlights
- Correlation heatmaps for feature relationships.
- Predicted vs. actual plots for regression models.
- Distribution plots for key features in classification problems.

---

## 💡 Future Work
- Incorporate deep learning models for stock and image datasets.
- Add feature engineering techniques for better predictive performance.
- Automate EDA and report generation.

---

**Author**: Rajajunaid44  
