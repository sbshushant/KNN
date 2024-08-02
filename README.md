# KNN
Introduction
This project focuses on applying the K-Nearest Neighbors (KNN) algorithm to classify data. The dataset used is the Titanic dataset, which contains information about passengers on the Titanic and their survival status.

Table of Contents
Introduction About the Dataset Data Preprocessing Exploratory Data Analysis Feature Engineering Implementing KNN Model Performance Evaluation Conclusion

About the Dataset
The Titanic dataset includes the following features:

Survived: Survival status (0 = No, 1 = Yes) Pclass: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd) Sex: Gender of the passenger Age: Age of the passenger SibSp: Number of siblings/spouses aboard the Titanic Parch: Number of parents/children aboard the Titanic Fare: Fare paid for the ticket Embarked: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

Data Preprocessing
Loading Data:
The dataset was loaded into a pandas DataFrame for inspection.

Handling Missing Values:
Replaced missing values in numerical columns with the mean and in categorical columns with the mode.

Encoding Categorical Variables:
Categorical variables (Sex and Embarked) were converted into numerical format using label encoding. Exploratory Data Analysis

Descriptive Statistics:
Reviewed the basic statistics and structure of the dataset.

Box Plots:
Created box plots for numerical features to check for outliers. Feature Engineering

Variance Inflation Factor (VIF):
Calculated VIF to check for multicollinearity among features and dropped features with VIF > 6.

Feature Selection:
Selected relevant features for the KNN model. Implementing KNN

Data Splitting:
Split the dataset into training and testing sets using an 80-20 split.

Training the KNN Model:
Trained the KNN classifier using the training data. Predicted the survival status for the testing data. Model Performance Evaluation

Accuracy Score:
Calculated the accuracy score of the model.

Confusion Matrix:
Generated the confusion matrix to evaluate the performance of the classification.

Classification Report:
Created a classification report to provide precision, recall, and F1-score for the model.

Conclusion
The analysis demonstrated the application of the K-Nearest Neighbors (KNN) algorithm to classify data in the Titanic dataset. Key findings include:

The KNN classifier provided a reasonable accuracy for predicting the survival status of passengers. The model performance was evaluated using accuracy score, confusion matrix, and classification report. These insights highlight the utility of the KNN algorithm in classification tasks, particularly when dealing with datasets where the relationships between features are non-linear and complex.
