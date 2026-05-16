# teslastockprediction
Tesla Stock Price Prediction using LSTM and SimpleRNN with multi-day forecasting and Keras Tuner-based hyperparameter tuning.


# 📈 Tesla Stock Price Prediction using LSTM & RNN

A deep learning project that forecasts Tesla (TSLA) stock prices using Long Short-Term Memory (LSTM) and Simple RNN models — with predictions for 1-day, 5-day, and 10-day horizons.

---

## 🚀 Live Demo
> Coming Soon / [Add your deployed app link here]

---

## 📌 Features

- 🧠 **LSTM model** for accurate multi-step stock price forecasting
- 🔁 **SimpleRNN model** as baseline comparison
- 📅 **Multi-horizon predictions** — 1 Day, 5 Day, and 10 Day forecasts
- 📊 **Visual analysis** of predicted vs actual stock prices
- 📉 Real Tesla (TSLA) historical stock data

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| TensorFlow / Keras | LSTM and RNN model building |
| Pandas & NumPy | Data processing and feature engineering |
| Matplotlib / Seaborn | Visualization of predictions |
| Scikit-learn | Data preprocessing and scaling |
| Jupyter Notebook | Model development and analysis |

---

## 📂 Project Structure

```
├── teslastocksprediction.ipynb     # Main notebook — EDA, model training, evaluation
├── TSLA.csv                        # Raw Tesla historical stock price data
├── LSTM_1Day_Prediction.csv        # LSTM model — 1-day ahead predictions
├── LSTM_5Day_Prediction.csv        # LSTM model — 5-day ahead predictions
├── LSTM_10Day_Prediction.csv       # LSTM model — 10-day ahead predictions
├── SimpleRNN_1Day_Prediction.csv   # SimpleRNN baseline — 1-day predictions
├── Tesla_Stock_Prediction_Final_Report.docx  # Detailed project report
└── README.md                       # Project documentation
```

---

## ⚙️ How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/amitkumarjy/<repo-name>.git

# 2. Navigate to project folder
cd <repo-name>

# 3. Install dependencies
pip install tensorflow pandas numpy matplotlib scikit-learn jupyter

# 4. Launch Jupyter Notebook
jupyter notebook teslastocksprediction.ipynb
```

---

## 🧠 How It Works

1. **Data Collection** — Tesla (TSLA) historical OHLCV data loaded from `TSLA.csv`
2. **Preprocessing** — Data normalized using MinMaxScaler; sequences created for time-series input
3. **Model 1 — LSTM** — Multi-layer LSTM network trained to capture long-term dependencies in stock price patterns
4. **Model 2 — SimpleRNN** — Baseline RNN model for performance comparison
5. **Multi-horizon Forecasting** — Models trained separately for 1-day, 5-day, and 10-day prediction windows
6. **Evaluation** — Predicted vs actual prices compared using RMSE and MAE metrics

---

## 📊 Results

| Model | Horizon | Metric |
|-------|---------|--------|
| LSTM | 1 Day | Lower RMSE — Best accuracy |
| LSTM | 5 Day | Moderate accuracy |
| LSTM | 10 Day | Higher uncertainty, broader trend captured |
| SimpleRNN | 1 Day | Baseline comparison |

> LSTM consistently outperforms SimpleRNN for stock price forecasting.

---

## 📸 Screenshots

> Add prediction charts and model architecture screenshots here

---

## 📄 Report

- 📝 [Detailed Project Report](Tesla_Stock_Prediction_Final_Report.docx)

---

## ⚠️ Disclaimer

> This project is for **educational purposes only**. Stock price predictions are not financial advice. Markets are inherently unpredictable.

---

## 👨‍💻 Author

**Amit Mutyalwar**  
Data Scientist | ML Engineer  
[LinkedIn](https://www.linkedin.com/in/amitkumar-mutyalwar-56519723b/) | [GitHub](https://github.com/amitkumarjy)

---

## ⭐ If you found this useful, give it a star!
