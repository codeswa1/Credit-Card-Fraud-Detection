# Credit Card Fraud Detection

## Overview
This project aims to detect fraudulent credit card transactions using machine learning techniques on the **Credit Card Fraud Detection dataset** from Kaggle. The dataset is highly imbalanced, with fraudulent transactions representing only **0.172%** of all records. 

The project includes **data preprocessing, exploratory data analysis (EDA), model building, and evaluation** with a focus on handling class imbalance.  

## Features
1. **Exploratory Data Analysis (EDA)**
   - Distribution of fraud vs. non-fraud transactions
   - Feature correlation visualization

2. **Data Preprocessing**
   - Scaling transaction amounts
   - Stratified train-test splitting
   - Handling imbalanced classes

3. **Model Building**
   - Random Forest Classifier (chosen for its robustness with imbalanced data)
   - Class weighting applied to improve fraud detection

4. **Model Evaluation**
   - Confusion matrix
   - Precision, Recall, F1-score
   - ROC-AUC score

## Dataset
- **Name:** Credit Card Fraud Detection Dataset  
- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- **Description:** Contains 284,807 transactions over two days in September 2013 by European cardholders. Of these, 492 are fraudulent (0.172%).  
  - Features: `V1`–`V28` (anonymized PCA components), `Time`, `Amount`  
  - Target: `Class` (0 = Legitimate, 1 = Fraudulent)  

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter (for running the notebook)

## Installation & Running the Notebook
1. Clone the repository:
```bash
git clone https://github.com/codeswa1/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection
```
2. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn notebook
```
3. Launch Jupyter Notebook:
```bash
jupyter notebook
```
4. Open credit_card.ipynb and run the cells sequentially.
