# Breast Cancer Survival Prediction using Machine Learning

## Overview

This project applies machine learning techniques to predict:

1. Breast cancer mortality status (Alive vs Dead)
2. Patient survival months

The project was developed as part of the University of Westminster module:

**5DATA002W.2 – Machine Learning & Data Mining** :contentReference[oaicite:0]{index=0}

The implementation follows a complete machine learning workflow including:
- Data preprocessing
- Feature engineering
- Classification modelling
- Hyperparameter tuning
- Ensemble learning
- Regression modelling
- Model evaluation and interpretation

---

# Project Structure

```text
breast-cancer-survival-prediction/
│
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_classification_models_and_tuning.ipynb
│   └── 03_ensemble_and_regression_models.ipynb
│
├── images/
│   ├── confusion_matrices/
│   ├── roc_curves/
│   └── decision_trees/
│
├── report/
│   └── final_analysis_report.pdf
│
├── data/
│   └── README.md
│
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
```

---

# Objectives

The main objectives of this project are:

- Predict whether a breast cancer patient will survive or not
- Estimate survival duration in months for terminal patients
- Compare multiple machine learning algorithms
- Evaluate classification and regression performance
- Improve predictive performance using ensemble learning and hyperparameter tuning

---

# Dataset

The dataset used in this project was provided as part of university coursework.

According to the coursework specification, the dataset originates from the:

- SEER Program (Surveillance, Epidemiology, and End Results)
- National Cancer Institute (NCI)

Reference:
- https://ieee-dataport.org/open-access/seer-breast-cancer-data

The raw dataset is not publicly redistributed in this repository.

---

# Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

# Machine Learning Models

## Classification Models
- Logistic Regression
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Voting Ensemble Classifier

## Regression Models
- Decision Tree Regressor (Fully Grown)
- Decision Tree Regressor (Pruned)

---

# Evaluation Metrics

## Classification Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

## Regression Metrics
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

---

# Workflow

## Notebook 1 – Data Preprocessing
- Dataset exploration
- Data cleaning
- Missing value handling
- Encoding categorical variables
- Feature preparation
- Data transformation

## Notebook 2 – Classification Models and Tuning
- Logistic Regression modelling
- Naive Bayes modelling
- KNN modelling
- Confusion matrices
- Classification reports
- ROC-AUC analysis
- Hyperparameter tuning using GridSearchCV

## Notebook 3 – Ensemble and Regression Models
- Voting ensemble classifier
- Decision Tree regression models
- Fully grown vs pruned trees
- Survival month prediction
- Decision tree visualization
- Regression model evaluation

---

# Key Features

- End-to-end machine learning pipeline
- Healthcare predictive analytics
- Classification and regression modelling
- Ensemble learning implementation
- Hyperparameter optimization
- Data visualization and model interpretation

---

# How to Run the Project

## 1. Clone the repository

```bash
git clone https://github.com/your-username/breast-cancer-survival-prediction.git
```

## 2. Navigate into the project folder

```bash
cd breast-cancer-survival-prediction
```

## 3. Install dependencies

```bash
pip install -r requirements.txt
```

## 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# Results

The project evaluates multiple machine learning approaches for predicting:
- Breast cancer mortality status
- Patient survival duration

The implementation includes:
- Confusion matrices
- ROC curves
- Classification reports
- Decision tree visualizations
- Regression performance analysis

---

# Academic Context

This project was completed for educational and research purposes as part of a university machine learning coursework assignment. :contentReference[oaicite:1]{index=1}

---

# License

This project is licensed under the MIT License.

---

# Author

Y.M.Hanwella

```

 
