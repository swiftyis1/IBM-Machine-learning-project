# IBM Machine Learning Project: Employee Attrition Prediction

This project is a machine learning classification task using HR data to predict employee attrition. It was completed as part of the IBM Professional Data Science Certificate.

## Project Overview

The goal is to predict whether an employee will leave the company based on various features such as job satisfaction, environment, income, and other HR metrics. This project demonstrates an end-to-end ML workflow including data preprocessing, model training, and evaluation.

## Dataset

- Source: IBM HR Analytics Employee Attrition dataset
- Size: 1,470 records
- Features: Demographic, employment, and satisfaction-level data

## Methodology

1. Data cleaning and preprocessing
2. Label encoding for categorical variables
3. Feature scaling using StandardScaler
4. Model training using:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Support Vector Machines (SVM)
   - Decision Tree Classifier
5. Evaluation with metrics such as F1-score and Jaccard index

## Tools and Libraries

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Results

- The Support Vector Machine model achieved the highest accuracy and F1-score.
- Proper preprocessing and use of pipelines improved overall model performance.

## How to Run

1. Install dependencies listed in `requirements.txt`
2. Run the Jupyter Notebook `Employee-Attrition.ipynb` to reproduce the analysis

## Next Steps

- Hyperparameter tuning
- Feature importance visualization
- Model deployment using Flask or Streamlit

---

Created by [@swiftyis1](https://github.com/swiftyis1)
