# 📊 Customer Churn Prediction using Machine Learning

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Machine%20Learning-CatBoost-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LightGBM-Gradient%20Boosting-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Optuna-Hyperparameter%20Optimization-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>
</p>

---

# 📌 Overview

Customer churn is one of the biggest challenges faced by telecom companies. Losing existing customers directly impacts revenue and significantly increases customer acquisition costs.

This project leverages **Machine Learning**, **CatBoost**, and **LightGBM** to accurately predict customers who are likely to discontinue telecom services. By identifying high-risk customers early, businesses can launch targeted retention campaigns, improve customer satisfaction, and maximize customer lifetime value.

The project analyzes over **7,000 telecom customer records**, performs comprehensive exploratory data analysis (EDA), engineers meaningful features, trains multiple gradient boosting models, and generates accurate churn predictions with explainable insights.

---

# 🎯 Business Problem

Telecommunication companies lose millions of dollars every year because customers switch to competitors.

Traditional retention strategies react **after customers leave**, making them costly and inefficient.

This project predicts customer churn **before it happens**, allowing organizations to:

- Identify customers at high risk of leaving
- Understand why customers churn
- Improve customer retention
- Reduce acquisition costs
- Increase customer lifetime value
- Support data-driven business decisions

---

# 🚀 Features

- Customer Churn Prediction
- Customer Risk Scoring
- Exploratory Data Analysis
- Feature Engineering
- Data Preprocessing Pipeline
- CatBoost Model
- LightGBM Model
- Hyperparameter Optimization using Optuna
- Feature Importance Analysis
- ROC Curve
- Precision-Recall Curve
- Confusion Matrix
- Cross Validation
- Business Insights Dashboard
- Interactive Visualizations

---

# 🏗 Project Architecture

```
Customer Dataset
        │
        ▼
Data Preprocessing
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Train-Test Split
        │
        ▼
Model Training
 ├── CatBoost
 └── LightGBM
        │
        ▼
Hyperparameter Optimization
        │
        ▼
Model Evaluation
        │
        ▼
Customer Churn Prediction
        │
        ▼
Business Insights
```

---

# 📂 Dataset Information

**Dataset:** Telco Customer Churn Dataset

### Dataset Statistics

| Property | Value |
|-----------|--------|
| Records | 7043 |
| Features | 21 |
| Target | Churn |
| Domain | Telecommunications |

### Important Features

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Online Security
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges

---

# 🛠 Technology Stack

## Programming Language

- Python 3.10

## Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- CatBoost
- LightGBM
- Optuna
- Graphviz

---

# ⚙ Machine Learning Workflow

## 1. Data Collection

- Load Telco Customer Dataset
- Verify dataset quality

---

## 2. Data Cleaning

- Handle missing values
- Remove duplicates
- Data type conversion
- Data validation

---

## 3. Exploratory Data Analysis

- Churn Distribution
- Customer Demographics
- Correlation Analysis
- Service Usage Analysis
- Contract Analysis
- Monthly Charges Analysis

---

## 4. Feature Engineering

- Encoding categorical variables
- Scaling numerical features
- Feature transformation
- Feature selection

---

## 5. Model Training

Models used:

- CatBoost Classifier
- LightGBM Classifier

---

## 6. Hyperparameter Optimization

Optimized using:

- Optuna

Optimized Parameters:

- Learning Rate
- Tree Depth
- Number of Estimators
- Regularization
- Iterations

---

## 7. Model Evaluation

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- PR-AUC
- Cross Validation Score

---

# 📈 Visualizations

The project generates various business-focused visualizations including:

- Dataset Preview
- Dataset Information
- Churn Distribution
- Correlation Heatmap
- Contract Analysis
- Streaming Services Analysis
- Demographic Analysis
- Feature Importance
- Precision Recall Curve
- ROC Curve
- Cross Validation Comparison

---

# 📊 Key Insights

The model identified several important churn drivers:

- Contract Type
- Customer Tenure
- Monthly Charges
- Online Security
- Tech Support
- Internet Service
- Payment Method

Business findings include:

- Customers with month-to-month contracts are more likely to churn.
- Longer-tenure customers have lower churn rates.
- Customers without online security or technical support are more likely to leave.
- Monthly charges significantly influence customer retention.
- Value-added services improve customer loyalty.

---

# 📌 Model Performance

| Metric | Performance |
|---------|-------------|
| Accuracy | 80%+ |
| ROC-AUC | 0.85+ |
| PR-AUC | 0.659 |
| Cross Validation | Stable Across Models |

---

# 📂 Project Structure

```
Customer-Churn-Prediction/
│
├── data/
│   └── Telco-Customer-Churn.csv
│
├── notebooks/
│   └── Telco-Customer-Churn-Prediction.ipynb
│
├── models/
│
├── images/
│
├── requirements.txt
│
├── README.md
│
└── LICENSE
```

---

# 💻 Installation

Clone the repository

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
```

Move into the project directory

```bash
cd customer-churn-prediction
```

Create a virtual environment

```bash
python -m venv venv
```

Activate virtual environment

### Windows

```bash
venv\Scripts\activate
```

### Linux / Mac

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# ▶ Run the Project

Open

```
Telco-Customer-Churn-Prediction.ipynb
```

Run all notebook cells.

The notebook will automatically:

- Load the dataset
- Perform preprocessing
- Generate EDA
- Train machine learning models
- Evaluate performance
- Predict customer churn
- Display business insights

---

# 📈 Business Value

This solution enables telecom organizations to:

- Predict customer churn proactively
- Improve customer retention strategies
- Reduce revenue loss
- Increase customer lifetime value
- Lower acquisition costs
- Improve customer satisfaction
- Support data-driven decision making

---

# 🔮 Future Enhancements

- Deep Learning Models
- Explainable AI (SHAP/LIME)
- Real-Time Prediction API
- Customer Retention Recommendation Engine
- Streamlit Dashboard
- Power BI Dashboard
- Automated Model Retraining
- Cloud Deployment
- Docker Support
- CI/CD Pipeline

---

# 👨‍💻 Skills Demonstrated

- Machine Learning
- Predictive Analytics
- Classification Models
- Data Preprocessing
- Feature Engineering
- Hyperparameter Optimization
- Exploratory Data Analysis
- Business Intelligence
- Statistical Analysis
- Data Visualization
- Model Evaluation
- Customer Analytics

---

# 📚 References

- Scikit-learn Documentation
- CatBoost Documentation
- LightGBM Documentation
- Optuna Documentation
- Pandas Documentation
- NumPy Documentation

---

# ⭐ If you found this project useful, consider giving it a Star!

```

---

This README was created from the complete **Customer Churn Prediction PRD (22 pages)** and includes the project's objectives, architecture, ML workflow, technology stack, dataset details, evaluation metrics, business value, and setup instructions. :contentReference[oaicite:1]{index=1}
