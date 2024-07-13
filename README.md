# Titanic-Survival-Prediction
This repo consists of datasets and code related to the Titanic survival prediction.

**Dataset:** I used Kaggle Dataset for predicting the Survivals of Titanic incident.

**About the Project:**
  1. Importing Libraries:
     
     a. Imported pandas for reading the datasets.
     
     b. Imported numpy to manipulate arrays.
     
     c. Imported seaborn to visualize the data.
     
     d. Imported scikit-learn to perform encoding and train the model.
     
  3. Loading datasets
  4. Visualising the data using seaborn
  5. Data preprocessing:
     
     a. Concatenate the train data and test data to preprocess data at one go.
     
     b. Drop unnecessary columns
     
     c. Fill null values of numerical data using mean.
     
     d. Fill null values of categorical data using mode.
     
     e. Apply log transformation for attributes that lack uniform distribution.
     
7. Correlation Matrix
8. Model training with Decision Tree
9. Model training with Logistic Regression
10. Model training with Random Forest
11. Comparing the Cross validation scores of each model
12. Complete model training with Random Forest
