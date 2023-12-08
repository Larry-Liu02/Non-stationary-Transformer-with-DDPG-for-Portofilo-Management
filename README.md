# S&P 500 Financial Data Datasets

This repository contains three CSV datasets representing financial data from the S&P 500 index, aimed at facilitating the development and validation of portfolio management models through Deep Reinforcement Learning (DRL). Each dataset is tailored to a specific phase in the machine learning model lifecycle: training, validation, and testing.

## Dataset Descriptions

- `dataset_train_2012-2014.csv`: This is the training dataset containing data from the years 2012 to 2014. It is used for initially training the DRL models.

- `dataset_validate_2015.csv`: This dataset includes data from the year 2015 and serves as the validation set. It is employed to evaluate the performance of the models and fine-tune hyperparameters based on the validation outcomes.

- `dataset_test_2016.csv`: Comprising data from the year 2016, this testing dataset is used for assessing the final performance of the models, ensuring they can generalize and perform well on unseen data.

## Feature Dimensions

Each dataset is structured with the following features, offering a comprehensive view of market conditions and stock performance:

- `time`: Timestamp of the data entry.
- `CPI`: Consumer Price Index, reflecting inflation.
- `GDP using BBKI`: Gross Domestic Product using the BBKI method, indicating economic growth.
- `Unemp_rate`: Unemployment rate, a macroeconomic indicator.
- `score`: Sentiment score derived from related news articles.
- `open`: Opening price of the S&P 500 index.
- `high`: Highest price of the index within the entry's timeframe.
- `low`: Lowest price of the index within the entry's timeframe.
- `close`: Closing price of the S&P 500 index.
- `adjcp`: Adjusted closing price post trading hours.
- `volume`: Trading volume, reflecting the total number of shares traded.
- `tic`: Ticker symbol representing each constituent company in the S&P 500 index.

Utilize these datasets to train, validate, and test your financial models, aiming to predict market movements and optimize portfolio management strategies.
