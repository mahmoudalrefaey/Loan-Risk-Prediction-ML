# Loan-Risk-Prediction-ML
This ML project predicts loan risk using Decision Tree, Random Forest, and Linear Regression models. The code, implemented in Python, includes data preprocessing, model training, and user-friendly predictions. Evaluate and compare model performances for effective loan risk assessment.

Overview:
This repository contains a Python project for predicting loan risk using machine learning. The code utilizes three models: Decision Tree, Random Forest, and Linear Regression. The implementation includes data preprocessing, model training, and user-friendly predictions.

What does this model perform?

1. Data Loading and Exploration:
   - Reads a CSV file ("Training Data.csv") into a Pandas DataFrame (`df`).
   - Displays the first few rows of the DataFrame, its shape, and some basic statistics.
   - Checks for and prints the count of null values and data types of each column.
2. Data Preprocessing:
   - Encodes categorical variables using Label Encoding.
   - Displays the updated data types and the first few rows of the DataFrame after encoding.
3. Data Visualization:
   - Prints the count of unique values in the "Risk_Flag" column.
   - Plots a countplot for the "Risk_Flag" column using Seaborn.
4. Data Splitting:
   - Separates the target variable ("Risk_Flag") from the features ("X").
   - Scales the features using StandardScaler.
   - Splits the data into training and testing sets.
5. Model Training:
   - Uses a Decision Tree Regressor to train a predictive model on the training data.
6. Model Evaluation:
   - Predicts the target variable on the test set.
   - Calculates and prints Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) for model evaluation.
   - Converts the predicted values to binary and calculates the accuracy.
7. Prediction on New Data:
   - Loads a new dataset ("Test Data.csv") into a DataFrame (`new_dataDf`).
   - Preprocesses the new data by encoding categorical variables.
   - Asks the user to input an index corresponding to a person in the new data for prediction.
   - Uses the trained model to predict the risk for the chosen person.
   - Displays details of the chosen person and the model's prediction result.

Getting Started:
Add Datasets: Download and place Training & Testing datasets.
Run the jupyter notebook: ML project.ipynb

Usage:
Follow the prompts to input applicant details for personalized predictions.
Explore model evaluation metrics for Decision Tree, Random Forest, and Linear Regression.

Contributors:
Mahmoud Al Refaey

Acknowledgments:
Special thanks to Data Source for providing the loan datasets.
Feel free to contribute, open issues, or provide feedback!
