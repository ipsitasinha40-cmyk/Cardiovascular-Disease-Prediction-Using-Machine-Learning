# Cardiovascular Disease Prediction Using Machine Learning

## Project Overview

Cardiovascular disease (CVD) is one of the leading causes of death worldwide. Early detection of cardiovascular conditions can significantly improve patient outcomes and support preventive healthcare interventions. This project applies machine learning techniques to predict the presence of cardiovascular disease using patient health and lifestyle indicators.
The project follows a complete data science workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, correlation analysis, machine learning model development, and model evaluation.

## Objectives

* Analyze cardiovascular disease data to identify key risk factors.
* Perform data cleaning and preprocessing to improve data quality.
* Visualize relationships between patient characteristics and disease occurrence.
* Build and compare multiple machine learning classification models.
* Select the best-performing model for cardiovascular disease prediction.

## Dataset

The dataset contains 70,000 patient records and includes demographic, physiological, and lifestyle-related variables such as:

* Age
* Gender
* Height
* Weight
* Systolic Blood Pressure (ap_hi)
* Diastolic Blood Pressure (ap_lo)
* Cholesterol Level
* Glucose Level
* Smoking Status
* Alcohol Consumption
* Physical Activity
* Cardiovascular Disease Status (Target Variable)

## Data Preprocessing

The following preprocessing steps were performed:

* Missing value analysis
* Duplicate record detection
* Age conversion from days to years
* Detection and removal of unrealistic blood pressure values
* Feature selection
* Feature scaling using StandardScaler
After preprocessing, the final dataset contained 68,775 high-quality observations.

## Exploratory Data Analysis

Key insights obtained from EDA include:

* Individuals with cardiovascular disease were generally older.
* Patients with cardiovascular disease tended to have higher body weight.
* Blood pressure variables showed the strongest relationship with cardiovascular disease.
* Cholesterol levels were positively associated with disease occurrence.
* The dataset was balanced between disease and non-disease classes.

## Correlation Analysis

The strongest correlations with cardiovascular disease were:

| Feature                          | Correlation |
| -------------------------------- | ----------- |
| Systolic Blood Pressure (ap_hi)  | 0.43        |
| Diastolic Blood Pressure (ap_lo) | 0.34        |
| Age                              | 0.24        |
| Cholesterol                      | 0.22        |
| Weight                           | 0.18        |

## Machine Learning Models Evaluated

The following classification algorithms were implemented and compared:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Support Vector Machine (SVM)
4. Decision Tree
5. Random Forest

## Model Performance

| Model                        | Accuracy |
| ---------------------------- | -------: |
| Support Vector Machine (SVM) |   73.77% |
| Logistic Regression          |   72.89% |
| Random Forest                |   71.59% |
| K-Nearest Neighbors (KNN)    |   69.55% |
| Decision Tree                |   64.10% |

## Final Model

The Support Vector Machine (SVM) achieved the highest accuracy of **73.77%** and was selected as the final cardiovascular disease prediction model.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## Key Learning Outcomes

* Data preprocessing and cleaning
* Exploratory data analysis
* Feature engineering
* Correlation analysis
* Machine learning model development
* Model evaluation and comparison
* Healthcare data analytics

## Conclusion

This project demonstrates the application of machine learning techniques for cardiovascular disease prediction using real-world healthcare data. Among the evaluated algorithms, Support Vector Machine achieved the best predictive performance with an accuracy of 73.77%, highlighting its effectiveness in identifying patients at risk of cardiovascular disease.
