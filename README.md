# 💹 Forex Predictor Application

The **Forex Predictor** is a data-driven web application that forecasts foreign exchange (FX) rates against the USD 
This model deploys ARIMA after a model comparison amongst several model to determine the best model based on RMSE metrics. 
Built with Python and designed for traders, data analysts, and researchers, it offers clear insights into future forex trends.

---

## 🚀 Features

- 🔍 **Forex Pair Selection**: Choose from various currency aginst the USD (e.g., USD/EUR, USD/JPY).
- 📊 **Interactive Visualizations**: Plot historical trends and predicted prices.
- 🤖 Forecasting Models**:
  - ARIMA
- 📈 **Custom Forecast Horizon**: Predict for upto 90 days.
- 🌐 **Web-based Interface**: Simple UI powered by Streamlit.

---

## 🧠 Forecasting Model

| Model     | Strengths                                 |
|-----------|-------------------------------------------|
| ARIMA     | Strong for linear, stationary time series |



## 🧪 How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/Dammyjosh/Foreign-exchange-Predictor.git
cd forex-predictor

2. Install dependencies

pip install -r requirements.txt

Streamlit:

streamlit run app.py

Then go to:
📍 http://localhost:8501



RUN VIA DOCKER
1. Pull image from dockerhub

docker pull damton/forex-predictor

2. Run app on local machine
For a Streamlit app (default port 8501):

docker run -p 8501:8501 your-dockerhub-username/forex-predictor
Access the app at:
➡️ http://localhost:8501



