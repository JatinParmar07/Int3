# Int3

This project focuses on predicting house prices based on a set of input features using a Linear Regression model.
The goal was to train, test, and evaluate a model that could predict with a high degree of accuracy, using a basic machine learning pipeline.

## Steps Followed
### Data Preparation
1. Loaded the dataset containing house information.

2. Encoded categorical variables (like yes/no fields) into numeric format (0/1).

3. Split the dataset into training and testing sets.

4. To increase the data size:
    - Duplicated the dataset.
    - Shuffled it randomly to prevent any order bias.

### Model Training
1. Used Linear Regression, Random Forest and XGB Regressor.

2. Trained the model on the X_train and y_train datasets.


### Model Evaluation
1. Predicted house prices using the test set.

2. Calculated performance metrics:
    - Mean Squared Error (MSE)
    - Mean Absolute Error (MAE)
    - R² Score (Coefficient of Determination)

### Visualization
Plotted Actual vs Predicted prices to visually inspect the model's performance.




## Learnings and Observations
1. Linear Regression performed decently but did not reach 90% R² (due to data size, noise, or feature quality).

2. Increasing the data size by duplication and shuffling helped stabilize the model a little.

3. Encoding of categorical variables was crucial for model input.

4. Random Forest outperformed Linear Regression and XGB
