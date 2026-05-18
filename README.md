# Bank Term Deposit Subscription Prediction using Machine Learning

## Project Overview

This project predicts whether a customer will subscribe to a bank term deposit based on customer demographics, financial information, and previous marketing campaign interactions. The project applies machine learning techniques, data preprocessing, exploratory data analysis, and ensemble learning models to identify factors affecting customer subscription decisions.

The goal is to improve marketing effectiveness and help financial institutions target potential customers more efficiently.

---

## Features

✔ Data preprocessing and cleaning  
✔ Exploratory Data Analysis (EDA)  
✔ Handling categorical and numerical variables  
✔ Feature engineering  
✔ Multiple machine learning model implementation  
✔ Ensemble learning techniques  
✔ Model evaluation and comparison  
✔ Performance visualization

---

## Dataset Information

Dataset: Bank Marketing Dataset

The dataset contains customer information such as:

- Age
- Job
- Marital Status
- Education
- Default Status
- Housing Loan
- Personal Loan
- Contact Type
- Campaign Information
- Previous Campaign Outcome
- Customer Financial Details

Target Variable:

**Target**

- Yes → Customer subscribed to term deposit
- No → Customer did not subscribe

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Data Preprocessing Steps

### Data Cleaning

- Checked missing values
- Examined data types
- Renamed target variable
- Removed unnecessary attributes

### Feature Engineering

- Converted categorical variables
- Applied encoding techniques
- Prepared features for model training

### Data Splitting

Dataset was divided into:

- Training Data : XX%
- Testing Data : XX%
- Random State : XX

Purpose:
- Training data was used for model learning.
- Testing data was used to evaluate model performance on unseen data.

---

## Machine Learning Models Used

1. Random Forest Classifier
2. Decision Tree Classifier
3. Bagging Classifier
4. AdaBoost Classifier
5. Gradient Boosting Classifier

---

## Workflow

1. Import libraries
2. Load dataset
3. Perform Exploratory Data Analysis
4. Handle preprocessing
5. Split data into training and testing sets
6. Train multiple machine learning models
7. Evaluate models
8. Compare performance scores
9. Identify the best-performing model

---

## Evaluation Metrics

Models were evaluated using:

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Confusion Matrix
- Cross Validation

---

## Results

### Model Performance Comparison

| Model | Accuracy |
|---------|----------|
| Gradient Boosting | 90.35% |
| Random Forest Classifier | 90.10% |
| Ada Boosting | 89.94% |
| Bagging | 89.93% |
| Decision Tree Classifier | 87.11% |

### Best Performing Model

**Gradient Boosting Classifier** achieved the highest accuracy of **90.35%**, making it the most effective model for predicting customer term deposit subscriptions.

---

## Future Enhancements

- Hyperparameter tuning
- Handling class imbalance
- Feature selection optimization
- Model deployment using Flask or Streamlit
- Real-time prediction dashboard implementation

---

## Author

**Vinnakota Nitish Raj**

LinkedIn: https://www.linkedin.com/in/vnr-nitish/
