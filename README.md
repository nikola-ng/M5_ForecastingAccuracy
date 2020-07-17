# M5_ForecastingAccuracy

This is a Kaggle competition hosted by Walmart, with challenge that can you estimate, as precisely as possible, the point forecasts of the unit sales of various products sold in the USA by Walmart?
You can check it out by this link below:

https://www.kaggle.com/c/m5-forecasting-accuracy

## Description of my work
In this repository, I deployed a framework for this competition such as fetching data, eda, feature engineering, preparing model and prediction. With just LightGBM model, it would help you to jump on private leader board ranked 12 (private score 0.54928).

## Data of this competition
You can download data from this site https://www.kaggle.com/c/m5-forecasting-accuracy/data.

In the challenge, you are predicting item sales at stores in various locations for two 28-day time periods. Information about the data is found in the M5 Participants Guide.

**Files**

- calendar.csv - Contains information about the dates on which the products are sold.
- sales_train_validation.csv - Contains the historical daily unit sales data per product and store [d_1 - d_1913]
- sample_submission.csv - The correct format for submissions. Reference the Evaluation tab for more info.
- sell_prices.csv - Contains information about the price of the products sold per store and date.
- sales_train_evaluation.csv - Includes sales [d_1 - d_1941] (labels used for the Public leaderboard)

## Future Work

- Focus more in feature engineering part
- Hyperparameter tunning
- Ensembling models Lasso, Ridge and LightGBM (certainly better score)
- Deploying Entity embedding
- Deploying LSTM model

## Reference

https://www.kaggle.com/anshuls235/time-series-forecasting-eda-fe-modelling
