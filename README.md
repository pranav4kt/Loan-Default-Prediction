# Loan-Default-Prediction


Loan Default Prediction

##Project Overview
This project aims to predict loan defaults using machine learning techniques. The provided dataset includes information about individuals who received loans in 2021.

##Contents

##Data Loading:
- The project utilizes Pandas to load two datasets, train.csv and test.csv.
- Displays information about the datasets.

##Data Exploration and Cleaning :
- Employs data exploration, cleaning, and visualization as needed.
- Visualizes the distribution of the target variable (Default) using seaborn.

##Data Preprocessing:
- Handles missing values:
- Imputes missing numerical values with mean.
- Imputes missing categorical values with mode.

##Encoding Categorical Variables:
- Applies one-hot encoding to categorical variables (Education, EmploymentType, etc.).

##Data Splitting:
- Splits the training dataset into features (X) and target variable (y).
- Divides the data into training and testing sets using train_test_split.

##Model Selection and Training:
- Chooses RandomForestClassifier as the classification algorithm.
- Trains the model on the training set (X_train, y_train).

##Model Evaluation:
- Evaluates the model on the testing set (X_test, y_test) using metrics like accuracy, classification report, and confusion matrix.
- Prediction on Second Dataset:
- Applies the trained model to predict loan defaults in the second dataset (test_df).
- Saves the predictions and probabilities in a DataFrame (prediction_df).

##Final Output:
- Prints test predictions and probabilities.
- Displays the head of the test DataFrame.

##Code Dependencies
- Pandas for data manipulation.
- NumPy for numerical operations.
- Matplotlib and Seaborn for data visualization.
- Scikit-learn for machine learning tools.
