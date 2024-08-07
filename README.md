# 🫀 Heart Disease Prediction Project

## 🔍 Overview

This project aims to predict the presence of heart disease in patients using machine learning techniques. We use a dataset containing various medical attributes of patients to build and evaluate predictive models.

## 📊 Dataset

The original data came from the [Cleveland database](https://archive.ics.uci.edu/ml/datasets/heart+Disease) from UCI Machine Learning Repository.

Howevever, we've downloaded it in a formatted way from [Kaggle](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset).

The dataset includes features such as:
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol levels
- Maximum heart rate
- And more...

The target variable is whether the patient has heart disease (1) or not (0).

## 🚀 Project Steps

1. 📈 Data Exploration and Visualization
   - Examined the distribution of heart disease across different factors
   - Created visualizations to understand relationships between variables

2. 🧹 Data Preprocessing
   - Split the data into features (X) and target variable (y)
   - Further split into training and testing sets

3. 🤖 Model Selection and Training
   - Implemented three models: K-Nearest Neighbors, Logistic Regression, and Random Forest
   - Compared their performances

4. ⚙️ Model Optimization
   - Performed hyperparameter tuning for Logistic Regression and Random Forest using RandomizedSearchCV and GridSearchCV

5. 📏 Model Evaluation
   - Used various metrics including accuracy, precision, recall, and F1-score
   - Plotted ROC curve and confusion matrix

6. 🔬 Feature Importance Analysis
   - Examined which factors were most influential in predicting heart disease

## 🎯 Key Findings

- Logistic Regression performed best among the tested models
- The optimized model achieved an accuracy of about 89% on the test set
- Chest pain type, sex, and maximum heart rate were among the most important predictors
- The model showed slightly better performance in identifying patients with heart disease (91% recall) compared to those without (86% recall)

## 🛠️ Tools Used

- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Scikit-learn for machine learning models and evaluation

## 📝 How to Use

1. Ensure you have Python and the required libraries installed (pandas, numpy, scikit-learn, matplotlib, seaborn)
2. Clone this repository
3. Run the Jupyter notebook or Python script to see the analysis and results

## 🔮 Future Work

- Collect more data to potentially improve model performance
- Try other machine learning algorithms or ensemble methods

## 👥 Contributors
Julio Chavez
Jchav77@gmail.com
