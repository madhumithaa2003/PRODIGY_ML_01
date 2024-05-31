# PRODIGY_ML_01
Implement a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms.

The intership program have mentioned the following link for accessing the datasets. In which, various datasets are given for further processing. 

https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

train.csv - the training set.

test.csv - the test set.

data_description.txt - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here.

sample_submission.csv - a benchmark submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms.

WORK FLOW:
1. Import all the necessary packages, read 'train.csv' file from drive.
2. Selection of required columns from the dataframe.
3. The obtained dependent and independent features are used to train the model.
4. Further, 'test.csv' file is read and stored as dataframe to predict the trained model using the same features that are used during training.
5. The final results: 'Id', "Est_SalePrice' are stored in a file.
6. The Predicted output is checked with the given output in the 'sample_submission.csv' file.

