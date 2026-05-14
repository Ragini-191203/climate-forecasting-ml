#Advanced Climate Trend Analysis & Forecasting

An end-to-end Machine Learning project for climate trend analysis and temperature forecasting using daily weather data from New Delhi, India (2013–2017).

##Results
| Model | RMSE (°C) | R² |
|-------|-----------|-----|
| Bidirectional LSTM | 1.18 | 0.97 |
| Gradient Boosting | 1.23 | 0.96 |
| Random Forest | 1.45 | 0.94 |
| SARIMA | 2.41 | 0.82 |

## Key Findings
- Statistically significant warming trend of +0.33°C/year detected
- 5 major temperature anomaly events identified
- Bidirectional LSTM achieved R² = 0.97

## Tools & Technologies
Python | scikit-learn | TensorFlow/Keras | pandas | matplotlib | statsmodels

## Features
- Exploratory Data Analysis (12 visualizations)
- Feature Engineering (13 domain-informed features)
- Anomaly Detection using Z-score method
- 4 forecasting models compared using time-series cross-validation
- 90-day daily temperature forecast
