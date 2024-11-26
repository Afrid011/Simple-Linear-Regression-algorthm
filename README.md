
# Linear Regression Model for Predicting Weight from Height

Purpose:

This Python script implements a linear regression model to predict a person's weight based on their height. It leverages the scikit-learn library for efficient model training and evaluation.

Data:

The model is trained and tested on a dataset containing height and weight measurements. The dataset is assumed to be in a CSV file named data.csv. Ensure that the dataset has two columns: Height and Weight.

# Code Structure:

1. Import Libraries:
 
- numpy: For numerical computations.
- pandas: For data manipulation and analysis.
- matplotlib.pyplot: For data visualization.
- sklearn.model_selection: For splitting data into training and testing sets.
- sklearn.linear_model: For implementing linear regression.
- sklearn.metrics: For evaluating model performance

2. Data Loading and Preprocessing:

- Read the CSV file into a pandas DataFrame.
- Split the data into features (X, height) and target variable (y, weight).

3. Data Splitting:

- Divide the data into training and testing sets using train_test_split.

4. Model Training:

- Create a LinearRegression object.
- Train the model on the training data.

5. Model Evaluation:

- Make predictions on the training and testing sets.

6. Calculate performance metrics:

- Mean Squared Error (MSE)
- R-squared score

7. Visualization:

- Visualize the training and testing data along with the predicted regression line.




## Acknowledgements

- [Regression](https://www.geeksforgeeks.org/machine-learning/?ref=ghm#supervised-learning) 
 - [Simple Linear Regression](https://www.geeksforgeeks.org/ml-linear-regression/)



## 🚀 About Me
Data Analyst

## Github : https://github.com/Afrid011




