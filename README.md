
---

# Field_Study

## Problem Statement

Accurate forecasting and analysis of vegetable and fruit prices are crucial for effective decision-making and resource management in agriculture. Traditional methods struggle to capture the complex, dynamic nature of price changes influenced by factors like climate and market demand. To address this, an AI-driven approach is proposed, utilizing advanced time series forecasting techniques to predict future prices and identify trends.

## Objectives

- **Forecast Future Prices**: Predict future vegetable and fruit prices to help stakeholders anticipate market trends and adjust strategies.
- **Analyze Price Trends and Seasonality**: Discover patterns and seasonal variations in price data to inform strategic planning.
- **Develop Pricing Strategies**: Create models to suggest optimal pricing strategies for maximizing profitability and competitiveness.

## Methodology

1. **Data Import and Preprocessing**: Load and clean the dataset using Pandas.
2. **Data Exploration and Visualization**: Visualize the data with Matplotlib to understand trends and patterns.
3. **Feature Preparation**: Generate windowed datasets for machine learning models.
4. **Model Building**: Implement forecasting models (Dense, SimpleRNN, Bi-directional LSTM, Conv1D + LSTM) using TensorFlow's Keras API.
5. **Model Training and Evaluation**: Train models and evaluate performance with metrics like MAE, MSE, RMSE, and R2.
6. **Forecasting and Visualization**: Generate and compare forecasts against actual prices.
7. **Model Comparison**: Compare different models to select the best-performing one.

## Conclusion

The Simple RNN model proved most accurate, capturing price patterns effectively. The Dense model and Bi-LSTM also performed well, while Conv1D models were less effective. Recurrent deep learning models are suitable for time series forecasting, with further fine-tuning potentially improving results.

---

# Vegetable_Price_Forecasting

Vegetable price forecasting is a machine learning project designed to predict vegetable prices based on historical time series data. The focus is on predicting the price for the next day using previous price data. We tested two algorithms: Linear Regression and Random Forest. The Random Forest algorithm achieved an accuracy of 87%, making it a robust choice for price prediction. The model allows users to input parameters such as state, district, month, date, and vegetable variety to obtain accurate price predictions.

---

# Fair_Price_Detector

The Fair Price Detector predicts the price of vegetables based on selected criteria including seasonal crop, variety, and quality. This feature ensures that the prices align with current market conditions and the specific attributes of the vegetables, facilitating fair and transparent pricing.

---

# Selling

## Network 1

We developed a robust transportation network using a custom Dijkstra algorithm to optimize vehicle routes based on supply and demand in each district. This approach resulted in a 28% improvement in delivery efficiency by effectively planning routes and vehicle allocation.

## Network 2

We optimized supply routes using a customized Dijkstra algorithm combined with the Knapsack Problem. This optimization involved assigning quantities and storage units to be delivered via the most efficient routes, achieving a 36% improvement in on-time delivery. The system accounts for demand and availability of vegetables, determining the number of vehicles required to distribute excess vegetables and collect surplus from other states efficiently.

---

