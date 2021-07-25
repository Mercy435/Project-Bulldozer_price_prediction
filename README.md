# This project is a regression problem that involves the prediction of sales price of bulldozers.

### It makes use of the `Random Forest Regressor` model to carry out its prediction.

### Hyperparameters were tuned using`RandomizedSearchCV` and the best parameters were used to train the model.

### `RMSLE` (root mean squared log error) between the actual and predicted auction prices was the metric for evaluation:
### the goal is to get a minimal _RMSLE_

## The steps carried out in this project are:

1. The problem is defined
   
2. The data is downloaded from the Kaaggle Bluebook for Bulldozers competition:
   https://www.kaggle.com/c/bluebook-for-bulldozers/data  
   
3. the metric for evaluation is also defined

4. the necessary libraries such as `NUMPy` `Pandas` `matplotlib` `sklearn` are imported

5. _exploratory data analysis_ _EDA_  as wel as _Feature Engineering_ are done on the data: dates are parsed, 
   columns are compared, missing values are filled, data is preprocessed  et.c
   
6. selecting the right model and training it is the next step; data is split into train and validation sets 

7.Model is experimented on to get best results and predictions are made on the test data