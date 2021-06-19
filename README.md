# ARCHIVED

# Kaggle_Housing_Prices
A Kaggle submission for the Housing Prices competition. The dataset contains 79 variables describing residential homes in Ames, Iowa, such as overall quality, number of fireplaces, and garage surface area. The goal of the competition is to predict the sales price of the homes in the test set. After cleaning and processing the data, Random Forest and Gradient Boosting regression models are trained on the training data set. These model types are chosen because the dataset is a mix of categorical and continuous variables, the dimensionality is not that small, and because these models generally perform well. The Gradient Boosting model slightly outperforms the Random Forest model, and so the former is used to make a prediction for the test set. The important variables for predicting sales price are overall quality, total basement square feet, and living area square feet. Kaggle scores submissions based on the Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. The model receives a score of 0.14 (the 10th place score is 0.11).
