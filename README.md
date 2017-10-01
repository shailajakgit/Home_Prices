# Home_Prices

This project describes my approach to predicting home prices from home features. This house prices dataset is from [this] (https://www.kaggle.com/c/house-prices-advanced-regression-techniques) Kaggle competition. 

This dataset contains 1460 rows, with values in 1/3 of rows missing. Another challenge with the dataset is that it has too many predictors, most of them are categorical and insignificant. The focus of this analysis is to systematically reduce the number of insignificant parameters with keeping as many observations as possible within the dataset.

The analysis has the following steps:
1. Determine the distribution of the dependent variable with and without transformations.
2. Cleaning the missing data as appropriate.
3. Trying out multiple predictive models, comparing them and choosing the final model.
