# Regression-Project



**_Summary_**

In this project I took the famous Ames Housing Dataset competition from Kaggle where I tried to predict the price of a house given it's characteristics. After some light feature engineering and a super simple ElasticNet model I was able to achieve a 15% RMSE and get into the top 32% on the leaderboard which unlike my initial result in other Kaggle submissions was pretty high. After this initial submission however, I failed to improve my score for some time through parameter tuning and different approaches to feature engineering. This made me question what other aspects of a dataset influence a model's performance so I looked at distribution of numerical features.


Lessons Learned:

- It is vital to look at the distribution of the numeric features in your dataset. Skewness in data will degrade the model's ability to describe typical cases as there are too many extreme cases for it to deal with. Data points that are closer together will be predicted more accurately than data points that are further from the rest. 

- While parameter tuning and feature engineering are important aspects of a model's performance, they are not the only factors that contribute to it. In future competitions and projects I need to also pay attention to statistical measures like distribution and correlation of features
