# Stock_Price_Predictor
A model that predicts stock prices based on historical data. Use linear regression or more advanced techniques if desired.
# 📈 Stock Price Predictor (ML Project)

This project predicts the next day's closing stock price using historical data.  
It uses **Linear Regression** and data fetched from **Yahoo Finance** via the `yfinance` API.

Built and tested on **Google Colab**.

---

## 🚀 Features

- Downloads real-time stock data using `yfinance`
- Trains a Linear Regression model to predict next-day closing price
- Calculates model accuracy (MAE, MSE, R² score)
- Saves the trained model as `.pkl` using `joblib`
- Loads the saved model for predictions without retraining
- Visualizes actual vs predicted prices with **dates on the X-axis**

---

## 🛠️ Requirements

- Python 3.x
- See `requirements.txt` for all packages

---

## 📂 How to Use

### On Google Colab:

1. Upload `stock_predictor.ipynb` to Colab.
2. Run all cells to:
   - Download stock data
   - Train model
   - Save model as `stock_price_model.pkl`
3. To download the model:
   - Click the 📂 sidebar → Right-click `stock_price_model.pkl` → Download

### Alternatively (Local):

```bash
git clone <your-repo-link>
cd stock-price-predictor
pip install -r requirements.txt
jupyter notebook stock_predictor.ipynb


📊 Data Source
Stock data is downloaded from Yahoo Finance using yfinance.



📌 Notes
This is a basic ML project using Linear Regression.

Can be extended to deep learning (LSTM, etc.) for better performance.


🧑‍💻 Author
Aakash Pal
palaakaah148@gmail.com
