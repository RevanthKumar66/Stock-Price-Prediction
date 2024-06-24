# Stock-Price-Prediction
Developed a linear regression model for GOOGL stock price prediction and visualized predictions against actual data.

Stock Price Prediction Project:
Objective: The goal of this project is to predict future stock prices for a specific company (e.g., Google/Alphabet) using historical stock price data. We'll build a linear regression model to achieve this.

**Dataset:**
*The dataset contains relevant features such as:*
 * **close:** Closing price of the stock on a given date.
* **high:** Highest price during the trading day.
* **low:** Lowest price during the trading day.
* **open:** Opening price at the beginning of the trading day.
* **volume:** Trading volume (number of shares traded) on that date.
* **adjClose, adjHigh, adjLow, adjOpen, adjVolume:** Adjusted values (accounting for stock splits and dividends).
* **divCash:** Dividends (if any) in cash.
* **splitFactor:** Stock split factor (usually 1.0 unless there was a split).
### Steps Involved:

1. **Data Collection:**
   * Obtain historical stock price data from reliable sources (e.g., Yahoo Finance, Alpha Vantage).
   * Ensure the dataset covers a reasonable time period (several years) for accurate predictions.

2. **Data Preprocessing:**
   * Handle missing values (if any).
   * Convert the date column to datetime format.
   * Remove irrelevant columns (e.g., high, low, adjusted values).

3. **Exploratory Data Analysis (EDA)**:
   * Visualize closing prices over time (line plot).
   * Explore daily returns distribution (histogram).
   * Consider candlestick charts and moving averages.

4. **Splitting the Dataset**:
   > Divide the data into training and testing sets (e.g., 80% training, 20% testing).

5. **Linear Regression Model**:
   * Initialize a linear regression model.
   * Train the model using the training data (features: opening price, volume).
   * Predict closing prices for the testing data.

6. **Model Evaluation**:
   * Calculate performance metrics:
     * **Mean Absolute Error (MAE)**: Measures average absolute differences between actual and predicted prices.
     * **Root Mean Squared Error (RMSE)**: Considers squared differences and penalizes larger errors.
   * Visualize actual vs. predicted closing prices.

### Conclusion:
* The scatter plot shows that most data points align closely with the ideal prediction line, indicating strong predictive performance.
* However, to quantify accuracy, consider additional metrics like R-squared or Adjusted R-squared.
* Remember that stock market prediction is complex due to various factors (market sentiment, news, external events).

This project provides valuable insights into machine learning techniques and their applicability in financial forecasting. Good luck with your stock price predictions! 📈🚀
