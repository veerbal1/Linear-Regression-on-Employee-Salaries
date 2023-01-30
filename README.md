# Salary Prediction Experiment
In this experiment, we build a linear regression model to predict the salary of employees based on their years of experience.

## Data
The data consists of 30 observations, each representing an employee with a certain number of years of experience and a corresponding salary. The data was loaded into a pandas dataframe and used to train and evaluate the model.

## Model
The linear regression model was implemented using the LinearRegression class from the sklearn.linear_model module. The model was fit on 80% of the data (training set) and evaluated on 20% of the data (test set) using the score method, which returns the R-squared score. The R-squared score is a measure of how well the model fits the data, with a score of 1 indicating a perfect fit and a score close to 0 indicating a poor fit.

## Result
The R-squared score on the test data was approximately 0.97, indicating a good fit of the model to the data. The model was also able to predict the salary for an employee with 12 years of experience with a reasonable accuracy.

## Conclusion
The linear regression model was able to fit the data well and accurately predict the salary of employees based on their years of experience. This experiment demonstrates the use of linear regression for solving a real-world problem and highlights the importance of evaluating the model on a separate test set to ensure its generalization ability.
