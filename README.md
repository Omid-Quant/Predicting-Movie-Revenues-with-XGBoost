# Predicting-Movie-Revenues-with-XGBoost
The movie business has always been a highly risky and unpredictable industry. To help address this challenge, I am working on a project aimed at improving the accuracy of movie revenue forecasts by incorporating machine learning techniques. Enhancing the precision of these predictions could provide a competitive edge over other production companies.

In response to this need, I have been tasked with tuning, testing, and comparing various regression models as part of the data & analytics team. My goal is to identify and deliver the best-performing model with the highest prediction accuracy.

For this project, I am using a dataset (movies.csv) that includes box office revenue (the target variable) for over 3,500 movies released since 1998, along with several factors that influence revenue, such as movie budget (features). I am specifically focusing on developing and evaluating an XGBoost Regression model using the gbtree booster.

I am implementing the project in Python, utilizing libraries such as pandas, numpy, seaborn, xgboost, and scikit-learn. My workflow includes setting up pipelines, using column transformers, handling missing data with imputers, applying feature scaling/standardization, and performing hyperparameter tuning through randomized search cross-validation.

Before model training, I conduct an exploratory data analysis (EDA) to understand the data and uncover patterns or anomalies. To assess the performance of the models, I rely on two evaluation metrics: Root Mean Squared Error (RMSE) and the Coefficient of Determination (R-squared).

Ultimately, my objective is to identify and present the best model, along with its tuned hyperparameters, that achieves the lowest RMSE and delivers the most reliable revenue forecasts.
