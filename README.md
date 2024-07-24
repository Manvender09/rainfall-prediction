# Rainfall Prediction

## Project Overview

This project, "Rainfall Prediction using Machine Learning," aims to predict rainfall using various machine learning models. The models include K-Nearest Neighbors (KNN), Decision Tree, Random Forest, and Logistic Regression. The dataset used contains weather-related features.

## Dataset

The dataset includes various weather-related features such as temperature, humidity, wind speed, and pressure. The target variable is `RainTomorrow`, which indicates whether it will rain the next day.

## Methodology

1. **Data Pre-Processing**: Cleaning the dataset by addressing missing values, removing irrelevant columns, and performing exploratory data analysis (EDA).
2. **Feature Selection**: Using statistical methods such as ANOVA (f_classif) to select the most relevant features for predicting rainfall.
3. **Model Building & Tuning**:
   - **K-Nearest Neighbors (KNN)**: Optimizing the number of neighbors (k) and evaluating model performance.
   - **Decision Tree**: Tuning hyperparameters such as criterion, max depth, and min samples split.
   - **Random Forest**: Performing grid search for hyperparameter tuning and evaluating the best model.
   - **Logistic Regression**: Conducting grid search for the best parameters and evaluating model performance.
4. **Model Evaluation**: Assessing models using metrics such as accuracy, precision, recall, and F1-score. Cross-validation and paired t-tests were performed for robustness.

## Results

- **KNN Model**: Achieved an accuracy of approximately 86.8% with k=5.
- **Decision Tree Model**: Achieved an accuracy of approximately 87.11% with the best parameters (criterion='gini', max depth=3, min samples split=2).
- **Logistic Regression Model**: Achieved an accuracy of 88% with the best parameters (C=0.01, solver='lbfgs').
- **Random Forest Model**: Details provided in the report.

## Conclusion

The machine learning models provide a robust framework for predicting rainfall. The insights from feature selection and model tuning were crucial in improving prediction accuracy. The project highlights the strengths and limitations of each model, with Logistic Regression performing slightly better than the others.

## Files in the Repository

- `Phase_2_Group12.ipynb`: Jupyter notebook containing the code and analysis.

