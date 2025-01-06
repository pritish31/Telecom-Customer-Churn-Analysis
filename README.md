
# Telecom Customer Churn Analysis

This repository contains a Jupyter Notebook for performing **customer churn analysis** using a telecommunications dataset. The notebook demonstrates data preprocessing, exploratory data analysis (EDA), and the application of machine learning models to predict customer churn.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Key Steps](#key-steps)
4. [Technologies Used](#technologies-used)
5. [Results](#results)
6. [How to Run](#how-to-run)
7. [Future Enhancements](#future-enhancements)

## Introduction
Customer churn is a critical business problem in the telecommunications sector. This project aims to analyze customer behavior, identify patterns, and build predictive models to reduce churn.

% Senior Citizens - There are only 16% of the customers who are senior citizens. Thus most of our customers in the data are younger people.
Partner and dependent status - About 50% of the customers have a partner, while only 30% of the total customers have dependents.
I also looked at any differences between the % of customers with/without dependents and partners by gender. There is no difference in their distribution by gender. Additionally, there is no difference in senior citizen status by gender.

## Dataset
The dataset used includes customer demographics, account information, and service usage data. The notebook covers:
- Data preprocessing to handle missing values, outliers, and categorical encoding.
- Feature engineering to extract actionable insights.

## Key Steps
Below are the main steps performed in the notebook:
import numpy as np
telecom_cust = pd.read_csv('/Users/pritish/Documents/Project/data/telecom customer churn/custom.csv')
telecom_cust.tail()
telecom_cust.values
telecom_cust.dtypes

## Technologies Used
- **Python**: For data analysis and modeling.
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.
- **Jupyter Notebook**: For interactive code execution.

## Results
- Visualized key factors contributing to churn using heatmaps and bar plots.
- Built predictive models like Logistic Regression, Decision Trees, and Random Forests.
- Evaluated models using accuracy, precision, recall, and F1-score.

## How to Run
1. Clone this repository:  
   ```bash
   git clone <repository-url>
   ```
2. Install required Python libraries:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:  
   ```bash
   jupyter notebook Telecomm.ipynb
   ```

## Future Enhancements
- Incorporate advanced machine learning models like XGBoost or CatBoost.
- Develop a Flask API for deploying the model.
- Integrate real-time data for continuous monitoring.

## Contact
For queries or contributions, feel free to reach out.

---

This README provides a comprehensive overview of the project. Let me know if you'd like further refinements or additional details.
