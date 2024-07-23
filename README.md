# Loan Default Prediction

This project performs traditional Machine Learning model training to a loan default dataset which includes 149,000 customer's loan information from a certain timeline. The aim of this project is to give banks a profile of customers whether to give loan which might get tricky when the customer is not able to pay on due date.  

## Project Overview

The key aspects of this project include:

- Extensive exploratory data analysis on 149,000 customer's bank information to understand factors influencing default of a loan  
- Visualizations for intuitive analysis of general customer profile, their expected income or spendings     
- Feature engineering a crowded dataset with a lot of columns  
- Dimensionality reduction using Random Forest to find most important features  
- Training classification models like SVM, K-Nearest Neighbors, Logistic Regression, Multi-Layer Perceptron, Naive Bayes  
- Comparing model performance when predicting whether the customer will default on the loan    

## Tech Stack

**Language**: Python  
**Technologies**: Pandas, Matplotlib, Seaborn, Numpy, Scikit-Learn  
**Environment**: Jupyter Notebook  

## Getting Started  

### Prerequisites
- Python 3
- Jupyter Notebook

### Installation

- Clone the repository
  ```bash
  git clone https://github.com/meric2/Loan-Default-Prediction.git
  ```

- Start Jupyter notebook
  ```bash
  jupyter notebook
  ```

- Install dependencies
  ```bash
  pip install -r requirements.txt
  ```

- Install [the dataset](https://www.kaggle.com/datasets/yasserh/loan-default-dataset)
- Open `prediction.ipynb` notebook and run all cells  


## Usage

The notebook covers:

- Loading and overview of loan default dataset  
- Extensive EDA with interactive visualizations    
- Data inspection, preprocessing and feature engineering  
- Performance evaluation of models and hyperparameter optimization  

This notebook can also serve as a reference for data analysis and Machine Learning model training pipeline.  
