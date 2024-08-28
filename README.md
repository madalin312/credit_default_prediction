# Fraud Prediction Based on Customer Behavior

## Overview
This project focuses on predicting fraud based on customer behavior using machine learning techniques. It was developed as a diploma thesis at the Faculty of Automatic Control and Computer Science, Polytechnic University of Bucharest.

## Project Structure

### 1. Introduction
The project aims to create a Python program that trains various machine learning models to predict whether an individual will commit fraud. The program was trained using data from individuals applying for loans, but it can be adapted for broader purposes.

### 2. Technology and Tools
- **Python**: The primary programming language used for model development.
- **Jupyter Notebook**: The platform used for organizing and presenting the code and results.

### 3. Data Analysis and Preprocessing
The dataset, obtained from [Kaggle](https://www.kaggle.com/datasets/subhamjain/loan-prediction-based-on-customer-behavior), contains information from loan applicants. The target variable is `Risk_flag`, indicating whether an individual has committed fraud in the past. The data was preprocessed to handle null values, encode categorical variables, and address data imbalance.

### 4. Machine Learning Models Implemented
The following models were implemented and tested:
- **Logistic Regression**: A statistical model used for binary classification.
- **Decision Trees**: A model that makes decisions based on a tree-like graph of decisions.
- **Random Forest**: An ensemble method that builds multiple decision trees and merges them to get a more accurate and stable prediction.
- **Extra Trees**: Similar to Random Forest but with more randomization, leading to a diverse set of decision trees.
- **AdaBoost**: An ensemble method that combines multiple weak classifiers to create a strong classifier.

### 5. Hyperparameter Tuning
Hyperparameters for each model were optimized using `GridSearchCV` from the Scikit-learn library to improve model performance.

### 6. Results and Validation
The models were evaluated using accuracy, recall, precision, and confusion matrix metrics. The Random Forest model provided the best performance with an accuracy of approximately 90.8%.

### 7. Conclusion
The project successfully developed a model that predicts fraud with high accuracy, achieving the set objective of at least 90% accuracy. The results indicate that decision tree-based models, particularly Random Forest, are well-suited for this classification task.

## How to Run
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/madalin312/credit_default_prediction
    ```
2. **Install Dependencies**:
    - Ensure you have Python and the necessary libraries installed
	
3. **Run the Project**:
    - Open the Jupyter Notebook provided and run the cells to train and evaluate the models.

4. **Evaluate the Results**:
    - The notebook includes sections for data preprocessing, model training, hyperparameter tuning, and evaluation.

## Bibliography
- [Kaggle Dataset: Loan Prediction Based on Customer Behavior](https://www.kaggle.com/datasets/subhamjain/loan-prediction-based-on-customer-behavior)
- Various online resources on machine learning, Python programming, and data analysis.

## Author
- **Radu Mădălin-Cristian**
- **Scientific Coordinator**: Prof. Bogdan Dumitrescu
