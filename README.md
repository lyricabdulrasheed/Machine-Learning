# Machine-Learning
Summary of the Machine Learning Project
This project explores building a machine learning model to predict the Material Safety Data Sheet (MSDS) Pressure (MSP) of a substance based on various properties. Here's a breakdown of the key steps involved:

Data Acquisition and Cleaning:

Loaded data from an Excel file named "SAF Dataset.xlsx".
Checked for missing values and duplicates. Removed duplicates to avoid data inconsistencies.
Performed exploratory data analysis to understand the relationships between features and the target variable (MSP).
Feature Engineering:

Separated numerical and categorical features.
Handled potential skewness in the data using techniques like log transformation (if necessary).
Model Building and Evaluation:

Built and evaluated several machine learning models, including:
Linear Regression (Univariate and Multivariate)
LASSO Regression (for feature selection and regularization)
Other Ensemble methods like Random Forest, Gradient Boosting, AdaBoost, etc.
Split the data into training and testing sets for model evaluation.
Used metrics like R-squared and Root Mean Squared Error (RMSE) to assess model performance.
Analyzed the coefficients of the models to understand the importance of different features in predicting MSP.
Compared the performance of various models to identify the best fit for this specific task.
Key Findings:

The project explored the effectiveness of different machine learning models in predicting MSP.
Feature selection techniques like LASSO regression might be beneficial to identify the most important features for prediction.
The report suggests that models like Random Forest or Extra Trees might outperform simpler models like Linear Regression for this dataset.
