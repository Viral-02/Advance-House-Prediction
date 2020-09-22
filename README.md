# Advance-House-Prediction

Kaggle Competition - Advanced House Prices Prediction.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

### Rank : 2092/4688

Please follow House_Predictions.ipynb and House_pricing_test_evaluation.ipynb

## House_Predictions.ipynb : Main file used for modelling and Prediction
## House_pricing_test_evaluation.ipynb : Handling Missing values in Test Data

# Steps:

# 1.  Understanding the dataset.

# 2.  Data Collection:

      a. Data fetched from House Prices prediction dataset from Kaggle website https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data
  
# 3.  Data Preprocessing:
		
	  a. Exploratory Data Analysis Numerical values, temproal values(date,time,year) and categorical values.

      b. Handling Missing Values(Train and Test data separately)
      
      c. Encoding of categorical columns (Combined encoding of Train and Test Data)
      
      d. Normalization ( log transformation for Numeric value)
      
      e. Feature Selection.
 
# 4.  Modelling:

      a. Machine learning model used XGBoost Regressor
  
# 5.  Evaluation:

      a. Model evaluation metrics used Mean Absolute error.
	  
	    b. R2 Square
  
# 6.  Hyper-Parameter tuning:

      a. RandomizedSearchCV 
 
# 7.  Prediction file generated for submission.

