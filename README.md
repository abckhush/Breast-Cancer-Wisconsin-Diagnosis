# Breast Cancer Wisconsin Diagnosis

## Overview
This project focuses on using logistic regression to predict breast cancer diagnosis based on various features extracted from digitized images of breast mass. The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Data Set (https://www.kaggle.com/uciml/breast-cancer-wisconsin-data) from Kaggle.

## Data Description
- The dataset contains 569 instances and 30 features.
- Features include mean, standard error, and worst values for various attributes such as radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension.
- The target variable is the diagnosis, which is classified as malignant (M) or benign (B).

## Tools and Technologies
- Python: Data preprocessing, model training, and evaluation
- pandas, NumPy: Data manipulation and numerical operations
- scikit-learn: Implementation of logistic regression model
- Matplotlib, Seaborn: Data visualization

## Workflow
1. Data Preprocessing: The dataset is loaded and preprocessed to handle missing values and encode categorical variables if any.
2. Data Exploration: Exploratory Data Analysis (EDA) is performed to understand the distribution of features and their relationships with the target variable.
3. Model Training: A logistic regression model is trained on the preprocessed data to predict the diagnosis.
4. Model Evaluation: The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score.
5. Results: The results of the model are presented, including any insights gained from the analysis.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/abckhush/breast-cancer-diagnosis.git
   cd breast-cancer-diagnosis
2. Install the required dependencies
   ```bash
   pip install -r requirements.txt
3. Run the Jupyter notebook
   ```bash
   jupyter notebook breast_cancer_diagnosis.ipynb

##Conclusion
The logistic regression model achieved an accuracy of 95% on the test set, demonstrating its effectiveness in predicting breast cancer diagnosis based on the given features.
