 Sales Prediction Model

This project uses machine learning to predict future sales for a company based on historical sales data and other relevant factors.

 Data Collection
- Collected previous sales data including sales patterns, monthly revenue, marketing spend, promotional events, holidays, and economic indicators[1].
- Gathered data on identical factors that impact sales such as marketing spend, promotions, holidays, and external economic factors[1].

Data Preprocessing
- Handled missing values by imputing or removing missing data points[1].
- Performed time series decomposition to extract trend, seasonality and residuals from the sales data[1].
- Engineered features like lags, rolling averages and other temporal features[1].
- Split data into training, validation and test sets ensuring no future data leaks into the past[1].

Modeling
- Benchmarked 11 different machine learning models including XGBoost, ARIMA, Holt-Winters, RNNs, LSTMs, and transformers[1][2].
- Ensemble methods like stacking were used to combine models and improve accuracy[1].
- Hyperparameters were tuned using techniques like grid search[2].

Results
- The ensemble DNN model achieved a RMSE of 947.9 on the test set, outperforming the probabilistic BG/NBD and Pareto/NBD models which had RMSEs of 1557 and 1558 respectively[4].
- Adding features like average basket size and returns count to the DNN model further improved results[4].


