# Titanic Survival Prediction Using Machine Learning

## Project Overview

This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. The study involves data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, and performance evaluation.

Several classification algorithms were developed and compared to determine the most effective model for predicting passenger survival.

## Objectives

The objectives of this project are to:

* Perform data cleaning and preprocessing.
* Conduct exploratory data analysis to identify important patterns and relationships.
* Build multiple machine learning classification models.
* Compare model performance using standard evaluation metrics.
* Identify the most effective model for Titanic survival prediction.

## Dataset

The dataset used for this project is the Titanic dataset, which contains demographic and travel information about passengers aboard the RMS Titanic.

### Features Include

* Passenger Class (Pclass)
* Sex
* Age
* SibSp (Number of siblings/spouses aboard)
* Parch (Number of parents/children aboard)
* Fare
* Embarked
* PassengerID

### Target Variable

* Survived

  * 0 = Did Not Survive
  * 1 = Survived

---

## Exploratory Data Analysis

Several visualizations were created to better understand the dataset, including:

* Age Distribution
* Fare Distribution
* Survival Distribution(class-imbalance)
* Correlation Heatmap
* Feature Importance Analysis
* model comparison plot
* Confusion Matrix
* ROC Curve

The analysis revealed that variables such as passenger class, sex, fare, and age had notable relationships with passenger survival.

## Data Preprocessing

The following preprocessing steps were performed:

* Handling missing values using imputation techniques.
* Feature scaling using StandardScaler where necessary.
* Encoding categorical variables using One-Hot Encoding.
* Building preprocessing pipelines for efficient model training.

  
## Models Implemented

The following machine learning models were trained and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Support Vector Machine (SVM)
5. Multi-Layer Perceptron (MLP)

Additionally, hyperparameter tuning was performed on the Random Forest model using GridSearchCV.

## Model Performance

| Model                        | Accuracy | Precision | Recall | F1 Score |
| ---------------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression          | 0.7877   | 0.7206    | 0.7206 | 0.7206   |
| Random Forest (GridSearchCV) | 0.7877   | 0.7419    | 0.6765 | 0.7077   |
| MLP                          | 0.7821   | 0.7302    | 0.6765 | 0.7023   |
| SVM                          | 0.7821   | 0.7544    | 0.6324 | 0.6880   |
| Random Forest                | 0.7598   | 0.7119    | 0.6176 | 0.6614   |
| Decision Tree                | 0.7095   | 0.6143    | 0.6324 | 0.6232   |

## Key Findings

* Logistic Regression achieved the highest overall performance with an accuracy of 78.77% and the highest F1 Score of 72.06%.
* Hyperparameter tuning using GridSearchCV improved the Random Forest model's performance.
* Sex, fare, age, and Pclass were among the most influential factors affecting survival.
* Simpler linear models performed competitively against more complex machine learning models.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## Repository Structure

```text
Titanic_Project/
│
├── data/
├── models/
├── figures/
├── notebooks/
├── README.md
├── requirements.txt
└── .gitignore
```


## Author

Aniude Paul Ifeanyi

Statistics Student | Data Scientist & Machine Learning Enthusiast
