# Hospital Readmission Prediction

## Project Overview
A machine learning project focused on predicting whether a patient will be readmitted to a hospital within 30 days of discharge.

The objective was to explore patient and hospital-related data, identify patterns associated with readmission, and develop predictive models that can support data-driven healthcare analysis.

## Problem Statement
Hospital readmissions within 30 days can indicate gaps in patient care and create additional pressure on healthcare resources.

This project approaches the problem as a binary classification task:

- **0:** No readmission within 30 days
- **1:** Readmission within 30 days

## Dataset Overview
- Training records: 76,975
- Test records: 32,812
- Features after preprocessing: 19
- Target variable: `readmit_30d`
- Readmission rate: 10.07%

The dataset presented a class imbalance challenge, making model evaluation particularly important.

## Methodology

### 1. Data Preprocessing
- Data inspection and exploratory analysis
- Feature selection and preparation
- Handling categorical and numerical variables
- Train-validation split
- Machine learning pipeline development

### 2. Model Development

The following classification algorithms were implemented:

- Logistic Regression
- Random Forest Classifier

### 3. Model Evaluation

Models were evaluated using the ROC-AUC metric to assess their ability to distinguish between patients who were readmitted and those who were not.

## Results

| Model | Validation ROC-AUC |
|---|---:|
| Logistic Regression | 0.7062 |
| Random Forest | 0.6939 |

**Best Kaggle leaderboard position: 54**

Logistic Regression achieved the stronger validation ROC-AUC among the two baseline models evaluated.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- Kaggle

## Key Learnings
- Working with imbalanced classification datasets
- Building preprocessing and machine learning pipelines
- Comparing different classification algorithms
- Evaluating models using ROC-AUC
- Preparing predictions for Kaggle submissions

## Project Repository
The complete implementation, experiments, and analysis are available in this repository.

**Author:** Safia Hussain
