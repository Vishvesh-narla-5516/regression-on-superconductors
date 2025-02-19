# regression-on-superconductors
# Superconductor Critical Temperature Prediction
This project involves developing a regression model to predict the critical temperature of superconductors based on features extracted from their properties. Using a dataset obtained from the UCI Machine Learning Repository, the model achieves high accuracy through advanced data preprocessing and machine learning techniques.

You can view the project on Google Colab by clicking [here](https://colab.research.google.com/drive/16N-p4xVDmEnED1-Fla72lmvk7wH4POJa?usp=sharing).
# Dataset Overview
### Source: 
UCI Machine Learning Repository
[link](https://archive.ics.uci.edu/dataset/464/superconductivty+data)
### Description: 
The dataset contains 81 features extracted from 21,263 superconductors. The critical temperature is provided as the 82nd column.
### Objective: 
Predict the critical temperature of superconductors based on their extracted features.
# Key Features of the Project
### Outlier Detection:

Implemented the Isolation Forest method to identify and remove outliers from the dataset, improving the quality of the input data.

### Regression Model:

Developed a regression model using XGBoost, a highly efficient and accurate gradient boosting framework.
The model leverages the strengths of XGBoost to handle complex data patterns effectively.
### Model Performance:

Achieved an impressive accuracy of 91.87% on the validation set, demonstrating the model's capability to generalize well.
# Steps Followed
### Data Preprocessing:

Loaded and cleaned the dataset.
Applied outlier detection and removal using Isolation Forest.
### Model Development:

Trained the regression model using XGBoost.
Tuned hyperparameters to achieve the best performance.
### Validation:

Evaluated the model on a validation set, achieving a 91.87% accuracy.
# Technologies Used
Python
Pandas, NumPy (for data preprocessing)
Scikit-learn (for Isolation Forest implementation)
XGBoost (for regression modeling)
# Acknowledgments
The dataset was sourced from the UCI Machine Learning Repository.
Special thanks to the contributors of the XGBoost framework for providing an efficient machine learning toolkit.
