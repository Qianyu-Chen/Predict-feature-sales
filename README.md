# Predict-feature-sales

The dateset I used is from Kaggle 'Predict feature sales'.

This repo use the ensemble architecture to predict the amount of sale of different shops and items. For the first level, it uses some regression methods(catboost, XGBboost, random forest) and linear regressor to predict the sale and analyse the features. Then the second level of this system uses a linear regressor to make an overall better prediction.
In the end the RMSE = 1.13816 according to Kaggle.
