# NASA GISS Surface Temperature Analysis (GISTEMP v4) 
# Combined Land-Surface Air and Sea-Surface Water Temperature Anomalies Prediction

Classical methods for time series forecasting, including AR, MA, ARMA, and ARIMA, focus on capturing the linear relationships between data and time. In this study, we analyzed NASA’s GISS Surface Temperature Anomalies and showed that neural networks can outperform traditional statistical modeling methods on forecasting non-stationary and non-linear data with trend and seasonality. We tested three kinds of neural networks in this report, and all models were able to capture the non-linear trend of data at each time point with significantly less computation cost. This demonstrated the capability of neural networks as compared to statistical time series forecasting methods on univariate time series forecasting problems. Long short-term memory neural networks (LSTM), in particular, outperforms the other models on both precision and computational cost.

### Data

The data for this study can be downloaded from [NASA’s GISS Website](https://data.giss.nasa.gov/gistemp/)

## Deployment

NASA_GISS.ipynb - Global-mean monthly, seasonal, and annual means, 1880-present
NASA_NHT.ipynb - Northern Hemisphere-mean monthly, seasonal, and annual means, 1880-present
NASA_SHT.ipynb - Southern Hemisphere-mean monthly, seasonal, and annual means, 1880-present

## Documentation

The full report of this project can be accessed [here](https://drive.google.com/file/d/1q_flBa3yUagoTgCBYFARxMe1k1lCNWXP/view?usp=sharing)
