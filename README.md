# apple_stock_market_forecasting
# Apple Stock Market Forecasting (1980–2024)

## Overview
This project explores time series forecasting for Apple stock prices using data from 1980 to 2024. It implements multiple methods, including ARIMA, Prophet, and LSTM, to predict stock prices based on features such as Open, High, Low, and Close prices.

## Features
- **Exploratory Data Analysis (EDA):** Visualizing trends and patterns in stock price data.
- **Single-Step Forecasting:** Predicting stock prices for a single day ahead.
- **Multi-Step Forecasting:** Extending predictions to multiple days into the future.
- **Model Comparison:** Evaluating ARIMA, Prophet, and LSTM models for their predictive performance.

## Dataset
- **Source:** Apple Stock Market Dataset (1980–2024)
- **Features:**
  - `Date`: Trading date.
  - `Open`: Opening price.
  - `High`: Highest price of the day.
  - `Low`: Lowest price of the day.
  - `Close`: Closing price.
  - `Volume`: Number of shares traded.

## Tools and Technologies
- **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow, Statsmodels, fbprophet.
- **Models Used:**
  - ARIMA: For univariate and seasonal data forecasting.
  - Prophet: Robust to missing data and holidays.
  - LSTM: A deep learning approach for capturing sequential dependencies.

## Key Steps
1. **Data Preprocessing:**
   - Handling missing values.
   - Converting dates into datetime format.
   - Scaling numerical features for LSTM.
2. **Exploratory Data Analysis:**
   - Visualizing trends, seasonality, and volatility.
   - Checking correlations between features.
3. **Model Implementation:**
   - Fitting ARIMA for univariate time series.
   - Applying Prophet for trend and seasonality adjustments.
   - Training LSTM with sequential input-output pairs.

## Results
- Comparative analysis of ARIMA, Prophet, and LSTM models.
- Insights into the strengths and limitations of each forecasting method.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/apple-stock-forecasting.git
   ```
2. Navigate to the project directory:
   ```bash
   cd apple-stock-forecasting
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Explore the scripts and visualizations.

## Future Improvements
   - Evaluating residuals to ensure model assumptions are satisfied
   - Extending forecasts beyond single-time steps using recursive or direct approaches.
   - Using metrics such as RMSE, MAE, and MAPE to compare models.
   - Visualizing actual vs predicted values.
- Incorporating additional features (e.g., macroeconomic indicators, news sentiment).
- Exploring other advanced models like GRU and Transformers.
- Automating hyperparameter tuning for better model optimization.

## Acknowledgments
- **Data Source:** Kaggle
- **References:**
  - [ARIMA Documentation](https://www.statsmodels.org/stable/generated/statsmodels.tsa.arima.model.ARIMA.html)
  - [Prophet Documentation](https://facebook.github.io/prophet/)
  - [TensorFlow LSTM Guide](https://www.tensorflow.org/guide/keras/rnn)

## Contributing
Feel free to fork this repository and contribute! Suggestions and improvements are welcome.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
Happy Forecasting! 🚀
