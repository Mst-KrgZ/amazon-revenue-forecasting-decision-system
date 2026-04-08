# 📈 Amazon Revenue & Profitability Forecasting Decision System

Weekly revenue and profit forecasting using SARIMA, Prophet, XGBoost and LSTM on Amazon e-commerce data.

## 🚀 Live Demo

[![Hugging Face Spaces](https://img.shields.io/badge/🤗%20Hugging%20Face-Spaces-blue)](https://huggingface.co/spaces/mesut-karagoz/amazon-revenue-forecasting)

👉 **[Click here to open the app](https://huggingface.co/spaces/mesut-karagoz/amazon-revenue-forecasting)**

## 📌 Project Overview

End-to-end revenue forecasting project for Amazon marketplace data, combining time series analysis, feature engineering, and business-driven insights to support data-informed decision making.

## 🤖 Models Used

| Model | Description |
|-------|-------------|
| **SARIMA** | Seasonal ARIMA for trend and seasonality |
| **Prophet** | Facebook Prophet with holiday effects |
| **XGBoost** | Gradient boosting with lag/rolling features |
| **LSTM** | Deep learning with long-term memory |
| **Ensemble** | Weighted combination of all models |

## 📊 Features

- Upload your own Amazon order CSV files or use built-in demo data
- Forecast revenue and/or profit for up to 26 weeks ahead
- Compare model performances (MAE, RMSE, MAPE)
- Confidence interval bands for uncertainty estimation
- Interactive Plotly charts

## 🗂️ Project Structure

```
amazon-revenue-forecasting-decision-system/
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
├── runtime.txt         # Python version (3.11)
└── README.md
```

## ⚙️ Installation & Local Run

```bash
git clone https://github.com/Mst-KrgZ/amazon-revenue-forecasting-decision-system.git
cd amazon-revenue-forecasting-decision-system
pip install -r requirements.txt
streamlit run app.py
```

## 📦 Requirements

- Python 3.11
- streamlit, pandas, numpy, plotly
- scikit-learn, statsmodels
- prophet, xgboost, tensorflow

## 📁 Data Format

The app accepts two CSV files from Amazon Seller Central:
- `amazon_orders_2023_time_series.csv`
- `df_time_series.csv`

Or use the built-in **Demo Data** option from the sidebar.

## 👨‍💻 Author

**Mesut Karagöz**  
Data Scientist  
[GitHub](https://github.com/Mst-KrgZ) · [Live Demo](https://huggingface.co/spaces/mesut-karagoz/amazon-revenue-forecasting)
