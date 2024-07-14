# Boston House Price Predictor Project Summary
# Objective
The project aimed to predict house prices in Boston based on various input features using different regression algorithms.

# Dataset
The dataset used is the Boston Housing Dataset, which contains features such as the number of rooms, crime rate, property tax rate, and more, influencing house prices.

# Methodology
# Data Preprocessing:

 Data cleaning : Handling missing values and outliers.
 
 Feature selection: Identifying relevant features for the model.
 
 Feature scaling: Normalizing or standardizing features to improve model performance.
 
# Model Implementation:

Linear Regression: A basic approach that assumes a linear relationship between the input features and the target variable.

DecisionTree Regression: A tree-based model that splits the data into subsets based on feature values.

Bagging Regressor: An ensemble method that uses multiple base regressors (e.g., Decision Trees) to improve prediction accuracy.

RandomForest Regressor: An advanced ensemble method that builds multiple decision trees and merges their results for better accuracy and robustness.

# Model Evaluation:
Split the dataset into training and testing sets.

Train each regression model on the training set.

Evaluate model performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²) on the testing set.

# Results
RandomForest Regressor outperformed other models, providing the best predictions with the lowest error rates and highest R-squared value, indicating its 
effectiveness in capturing complex patterns in the data.

# Conclusion
The RandomForest Regressor was identified as the most suitable model for predicting house prices in Boston, thanks to its ability to handle non-linear relationships and interactions between features effectively.
