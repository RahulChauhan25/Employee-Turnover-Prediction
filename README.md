# Employee Turnover Prediction

## Overview
This project focuses on predicting employee turnover using Machine Learning. It uses Logistic Regression to identify employees who are likely to leave an organization based on factors such as job satisfaction, salary, work-life balance, age, training hours, and annual bonuses.

## Objectives
- Build a baseline Logistic Regression model.
- Apply L1 (Lasso) and L2 (Ridge) regularization.
- Compare model performance and identify the best-performing approach.
- Understand the impact of employee-related factors on turnover.

## Dataset
The dataset contains employee-related features, including:
- Job Satisfaction and Performance Rating
- Years at Company and Work-Life Balance
- Monthly Income and Annual Bonus
- Age, Education Level, and Training Hours
- Employee Turnover (Target: 1 = Left, 0 = Stayed)

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Models
1. Logistic Regression (Baseline)
2. Logistic Regression with L1 Regularization
3. Logistic Regression with L2 Regularization

## Evaluation Metrics
The models are evaluated using classification metrics such as Accuracy, Precision, Recall, F1-score, Confusion Matrix, and ROC-AUC, where applicable.

## Project Workflow
1. Data loading and exploration
2. Data preprocessing and feature preparation
3. Model training
4. L1 and L2 regularization
5. Model evaluation and comparison
6. Selection of the best-performing model

## How to Run
1. Clone this repository.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Run the notebook cells sequentially.

## Conclusion
This project demonstrates the application of Logistic Regression and regularization techniques to employee turnover prediction, with a focus on model evaluation and comparison.

---
**Note:** This project was developed as part of a Supervised Machine Learning assignment.
