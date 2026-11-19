# 🛡️ FinGuard AI – Financial Fraud Detection System

### Intelligent Machine Learning-Based Fraud Detection

## 📌 Project Overview

FinGuard AI is a machine learning-based Financial Fraud Detection System designed to identify fraudulent credit card transactions and distinguish them from genuine transactions.

The project uses data analytics, machine learning algorithms, and interactive visualizations to analyze financial transaction patterns and detect suspicious activities.

The main objective is to improve fraud detection and help reduce financial losses through data-driven predictions.

## 🎯 Project Objectives

- Analyze financial transaction data.
- Identify fraudulent and genuine transactions.
- Perform data cleaning and preprocessing.
- Handle imbalanced datasets.
- Train and compare machine learning models.
- Evaluate model performance using classification metrics.
- Develop an interactive dashboard using Streamlit.

## 📊 Dataset Information

The reference report describes a credit card transaction dataset containing:

| Description | Value |
|---|---:|
| Total Transactions | 284,807 |
| Genuine Transactions | 284,315 |
| Fraudulent Transactions | 492 |
| Fraud Percentage | 0.172% |

**Target Variable:**
- `0` – Genuine Transaction
- `1` – Fraudulent Transaction

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Streamlit
- Plotly
- Joblib

## 🤖 Machine Learning Algorithms

The project explores the following algorithms:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K-Nearest Neighbors (KNN)
5. Support Vector Classifier (SVC)

## ⚙️ Project Workflow

1. Dataset Collection
2. Data Inspection
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Handling Imbalanced Data
7. Machine Learning Model Training
8. Model Evaluation
9. Dashboard Development
10. Testing and Deployment

## 📈 Model Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

Since financial fraud datasets are highly imbalanced, special attention is given to precision and recall.

## 📊 Dashboard Features

The Streamlit dashboard is designed to display:

- Total transaction count
- Fraudulent transaction count
- Genuine transaction count
- Fraud percentage
- Transaction distribution charts
- Transaction amount analysis
- Individual transaction prediction

## 📁 Project Structure

```text
FinGuard-AI/
│
├── data/
│   └── creditcard.csv
│
├── notebooks/
│
├── src/
│   ├── data_inspection.py
│   ├── eda.py
│   ├── preprocessing.py
│   ├── model_training.py
│   └── model_evaluation.py
│
├── models/
│   └── fraud_model.pkl
│
├── dashboard/
│   └── app.py
│
├── tests/
│
├── requirements.txt
└── README.md
```

## 🚀 Installation and Execution

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd FinGuard-AI
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the environment

Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run model evaluation

```bash
python src/model_evaluation.py
```

### 6. Launch the dashboard

```bash
streamlit run dashboard/app.py
```

## 📌 Expected Outcome

A machine learning-based financial fraud detection application that analyzes transactions, identifies suspicious activities, evaluates model performance, and presents results through an interactive dashboard.

## 🔮 Future Enhancements

- Real-time fraud detection
- Advanced deep learning models
- Hyperparameter optimization
- Improved fraud risk scoring
- Deployment on cloud platforms

## 👩‍💻 Author

**Sodari Ravali**

B.Tech – Computer Science and Data Science

Interested in Data Analytics, Machine Learning, and Artificial Intelligence.

---

*This project is developed for educational and internship purposes. Model predictions are not a substitute for financial institution fraud review systems.*
