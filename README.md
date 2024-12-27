# ML Project

## Loading and Preprocessing
### Objective

Load the dataset.

Handle any missing values.

Preprocess data, including encoding categorical variables, feature scaling, and splitting the dataset into training and testing sets.

## Model Implementation
### Objective
Implement five regression algorithms:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Support Vector Regressor (SVR)

*Each algorithm will be evaluated based on how well it predicts the car price.*

#### Explanation:
We initialize and train five regression models.

The evaluation metrics are R-squared, Mean Squared Error (MSE), and Mean Absolute Error (MAE).

We display these metrics for each model.

## Model Evaluation
### Objective
Compare the performance of all the models using R-squared, MSE, and MAE.

Identify the best-performing model.

***The key is to compare R-squared, MSE, and MAE values. The model with the highest R-squared and lowest MSE/MAE will be considered the best.***
**Here the Random Forest Regressor is the best performing model.**

## Feature Importance Analysis
### Objective
Identify the significant variables affecting the car prices.

Use feature importance techniques for tree-based models like Random Forest Regressor and Gradient Boosting Regressor.

#### Explanation
For tree-based models like Random Forest, we can use the feature_importances_ attribute to evaluate which features are more important in predicting the target variable.

This will help identify the most important variables affecting car prices.

**The most important variables affecting car prices are-**

***Engine size,Curb weight, Highway mpg, Horse power, car_ID***

## Hyperparameter Tuning
### Objective
Perform hyperparameter tuning to check whether it improves the model’s performance

#### Explanation
GridSearchCV helps in finding the best combination of hyperparameters for models, and we evaluate the performance using cross-validation.

This step can improve the model’s generalization ability.

**The Performance of the model has increased**

