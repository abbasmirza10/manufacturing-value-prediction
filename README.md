# Predicting Future Value Added in Manufacturing Industries

This repository contains a Jupyter Notebook that demonstrates the use of machine learning techniques to predict the future value added by manufacturing industries. The project focuses on analyzing economic, labor, and operational indicators to uncover patterns that can improve forecasting capabilities in economic modeling.

## Project Overview
Manufacturing industries play a vital role in economic growth. By leveraging a dataset spanning 61 years, this project explores how key indicators such as employment, payroll, shipments, and capital expenditures influence the value added by manufacturing industries over time and across regions.

### Research Question
How do economic, labor, and operational indicators (e.g., total employment, payroll, shipments, and capital expenditures) contribute to predicting the future value added by manufacturing industries?

### Dataset
- **Source**: NBER-CES Manufacturing Industry Database  
- **Scope**: Includes data from 1958 to 2018, spanning over 22,204 observations across multiple manufacturing sub-sectors.  
- **Response Variable**: Total Value Added (VADD)  
- **Predictors**: Economic, labor, and operational indicators  

## Methodology
The project employs the following machine learning techniques:  
- Linear Regression  
- Lasso Regularization  
- Support Vector Machines  
- Neural Networks  

Key evaluation metrics include:  
- Root Mean Squared Error (RMSE)  
- Training and testing error rates  
- Precision and recall values  

## Tools Used
- **Python** (via Jupyter Notebook)  
- Libraries: `pandas`, `scikit-learn`, `matplotlib`, `seaborn`  

## How to Use
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/manufacturing-value-added-prediction.git
