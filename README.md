# iGov — EDA & Predictive Modeling

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![MLflow](https://img.shields.io/badge/MLflow-Tracking-blue?logo=mlflow)
![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-20BEFF?logo=kaggle)

## Project Overview

End-to-end data analysis and machine learning project applied to the **iGov dataset**, a public e-government services dataset tracking citizen interactions, response times, resolution rates, and satisfaction scores.

The goal is to **understand what drives citizen satisfaction** with digital government services and build predictive models to support operational decision-making.

**[Access the Interactive iGov Dashboard Here](https://tomassilva5.github.io/iGov-DataAnalysis/)**

---

## What's Inside

| Section | Description |
|---|---|
| **Data Loading & Exploration** | Shape, types, missing values, initial observations |
| **Preprocessing** | Encoding, quantile binning, cleaning |
| **Descriptive Statistics** | Mean, median, IQR, SEM, range |
| **Statistical Dashboard** | Heatmap, KDE, Boxplot, Regression, K-Means, Decision Tree |
| **Probability Distributions** | Normal, Poisson, T-Student, Binomial |
| **Scatterplot Matrix** | Pairwise relationships across all variables |
| **Shape Analysis** | Skewness & Kurtosis interpretation |
| **Automated EDA** | Full report via ydata-profiling |
| **MLflow Modeling** | Linear Regression, Logistic Regression, Random Forest, Decision Tree, Neural Network |
| **Decision Support System (DSS)** | Interactive tool to predict citizen satisfaction from operational inputs |

---

## Technology Stack

- **Machine Learning & Data:** Python, Pandas, NumPy, Scikit-Learn, MLflow, SciPy
- **Data Visualization:** Matplotlib, Seaborn, Plotly, ydata-profiling
- **Dashboard Front-end:** HTML5, CSS3, JavaScript, Chart.js

---

## How to View the Project

### 1. Interactive Dashboard
You can simulate operational scenarios and view the final results without running any code:
👉 [View Live Dashboard](https://tomassilva5.github.io/iGov-DataAnalysis/)

### 2. Kaggle Notebook (Code & Analysis)
To view the complete code, exploratory data analysis, and model training:
👉 [Open on Kaggle: iGov — EDA & Predictive Modeling](https://www.kaggle.com/code/tomassilva5/igov-eda-predictive-modeling)

---

## Key Findings

- **Resolution rate** is the strongest predictor of citizen satisfaction.
- **Technical errors** have a significant negative impact on satisfaction.
- **K-Means clustering** reveals 3 distinct service performance segments.
- **Linear Regression** achieved the best predictive accuracy (R² = 0.878) among the tested models, proving that the relationships between operational features and satisfaction are largely linear.
