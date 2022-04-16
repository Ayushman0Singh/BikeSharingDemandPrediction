# BikeSharingDemandPrediction
Supervised Ml-Regression
Bike-sharing systems are a means of renting bicycles where the process of obtaining rental, and bike return is automated via a network of locations throughout a city. 

We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model could be a good way for management to understand the demand dynamics of a new market.
This looks like a regression problem since we are predicting a continuous variable.

I looked at the individual distributions of all these variables. I proceed to apply certain transformations on these variables in order to make them normally distributed. I also did some hypothesis-driven EDA by verifying certain hypotheses that were important to the business problem at hand. 

After that, I did some data preparation which included steps like Null-value treatment, feature engineering, encoding categorical columns and Standardising the numeric features before applying ML models. I split the data into train and test set for the ml models.

Next, I applied different machine learning models to predict rented_bike_count. I used techniques like Linear Regression, Regularised LR, Decision Tree, Random -forest, Ada-Boost, GBM(Gradient Boosting Machine). Hyperparameter tuning was done for all these algorithms and the best hyper-parameters were considered for training.
Of all the models, GBM performed the best with an r-square value of 0.88, next was RF with an r-square value of 0.84 followed by DT regressor with an r-square of 0.76. Ada-Boost performed the worst among these algorithms with an r-square of 0.58 on only. 
