# Tesla Stock Price Prediction using Simple RNN and LSTM

1. **Open:** The opening price of the stock on a particular trading day. This is the price at which the first trade is executed when the market opens.
2.  **High:** The highest price at which the stock traded during the trading day. It indicates the maximum value that traders were willing to pay for the stock on that day.
3. **Low:** The lowest price at which the stock traded during the trading day. This represents the minimum value for the stock within the trading day.
4. **Close:** The closing price of the stock for the day. It is the last price at which the stock was traded before the market closed. This is one of the most commonly reported and used prices because it reflects the final consensus value of the stock for the day.
5. **Volume:** The total number of shares or contracts traded for the stock during the trading day. It reflects the level of activity or liquidity for the stock. Higher volume indicates more trading activity and, typically, higher investor interest.
6. **Adj Close (Adjusted Close):** This is the closing price adjusted for corporate actions like `stock splits`, `dividends`, and `new stock offerings`. Adjusted close provides a more accurate reflection of a stock’s value and price movements over time because it accounts for events that could affect the stock price directly.

![image](https://github.com/user-attachments/assets/e4e813b3-52b2-4151-8bfe-d3c6cf3b97af)

# RNN model:
- Calculated R-squared (R2) score for Training Dataset : 0.9946221971336522
- Calculated R-squared (R2) score for Testing Dataset: 0.878237575267619
- ![image](https://github.com/user-attachments/assets/261a40f8-bfcb-4c8f-8b89-f3907f8c4acd)
- ![image](https://github.com/user-attachments/assets/5831c746-4d80-4c7e-b369-342371b2b258)
- ![image](https://github.com/user-attachments/assets/c587a82d-470c-46bf-999a-a00d590f333c)


# LSTM model:
- Calculated R-squared (R2) score for Training Dataset: 0.9963969807840648
- Calculated R-squared (R2) score for Testing Dataset: 0.923637988108966
- ![image](https://github.com/user-attachments/assets/b4292e68-c39b-48e1-a3e8-d804b6efca5e)
- ![image](https://github.com/user-attachments/assets/d7e5a357-268c-42ad-bfa9-418a5b155636)
- ![image](https://github.com/user-attachments/assets/14479b50-fd75-40d9-b29a-0a54f38311f5)
