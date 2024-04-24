# Employee Satisfaction Repository
## About
- This is a mini project for SC1015 (Introduction to Data Science and Artificial Intelligence).
- [Employee Satisfaction Dataset](https://www.kaggle.com/datasets/redpen12/employees-satisfaction-analysis) is obtained from Kaggle.
- Please download the [csv](https://github.com/AmelynSiew/Employee-Satisfaction/blob/main/Employee.csv) file before running the codes.
- You may need to install pydotplus before running the codes. You may do so by typing "!pip install pydotplus" into a cell and running it.
- Please view/run the files in the following order:
  1. Data Preparation & Cleaning
  2. Exploratory Data Analysis
  3. Random Forest Regression
  4. Gradient Boosting Regression

## Motivation
- Staggering rates of employee dissatisfaction since the Covid-19 pandemic, largely caused by lack of engagement and unhappiness.

## Problem Definition
- Which are the most important factors in determining employee satisfaction?
- Variables under employee performance: last performance evaluation score, whether employee has received promotion within last 5 years
- Variables under employee workload: number of projects, average monthly hours worked
- Varibales under employee experience: years spent in company, whether employee has experienced work accident, department, salary
- Response variable: satisfaction level

## Machine Learning Models Used
- Random Forest Regression
- Gradient Boosting Regression

## Conclusion
- Weak linear relationships between predictor variables and response variable.
- Top 2 most important factors in predicting employee satisfaction are number of projects and average monthly hours worked.
- Interestingly, Random Forest Regression performed better than Gradient Boosting Regression in terms of prediction accuracy.

## Contributors
- Clarabelle Chua Jia Yi: Data Preparation & Cleaning, Exploratory Data Analysis, Random Forest Regression
- Siew Jing En: Data Preparation & Cleaning, Exploratory Data Analysis, Gradient Boosting Regression
- Chiang Wen Xi: Data Preparation & Cleaning, Exploratory Data Analysis, Video Presentation

## References
- https://www.kaggle.com/datasets/redpen12/employees-satisfaction-analysis
- https://www.kaggle.com/code/dinasinclair/basic-random-forest-pipeline-housing-prices
- https://www.kaggle.com/code/dennismathewjose/emplolyeesurvey
- https://www.kaggle.com/code/yasinnsariyildiz/gradient-boosting-machines-tutorial
