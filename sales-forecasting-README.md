# Retail Sales Forecasting

A time series forecasting project to predict future retail sales using historical transaction data, built with Python and evaluated using industry-standard regression metrics.

---

## Problem Statement

Accurate sales forecasting is critical for inventory management, staffing, and revenue planning. This project builds and evaluates time series models to predict weekly/monthly retail sales, enabling data-driven business decisions.

---

## Models Used

| Model | Description |
|---|---|
| ARIMA | Classical statistical model capturing autocorrelation and seasonality |
| LSTM *(if applicable)* | Deep learning model for long-range temporal dependencies |
| Prophet *(if applicable)* | Facebook's forecasting library optimised for business time series |

> ⚑ Keep only the models you actually used and remove the rest.

---

## Results

| Metric | Value |
|---|---|
| MAE | *(add your score)* |
| RMSE | *(add your score)* |
| Forecast Horizon | *(e.g. 4 weeks / 3 months ahead)* |

> ⚑ These are the most important numbers in this README — pull them from your notebook output. Even a rough figure like "RMSE of 312 units on a weekly forecast" tells a hiring manager you actually ran and evaluated the model.

---

## Key Steps

1. **Data Loading & EDA** — explored sales trends, seasonality, and holiday effects
2. **Preprocessing** — handled missing dates, resampled to weekly frequency, applied log transformation to stabilise variance
3. **Feature Engineering** — created lag features, rolling averages, and time-based features (day of week, month, quarter)
4. **Stationarity Testing** — applied ADF test; differenced series where required
5. **Model Training** — trained and tuned forecasting models on training split
6. **Evaluation** — assessed on held-out test set using MAE and RMSE

---

## Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy, Statsmodels, Scikit-learn, Matplotlib, Seaborn
- **Deep Learning (if used):** TensorFlow / Keras
- **Environment:** Jupyter Notebook

---

## Dataset

- **Source:** [Kaggle — Store Sales Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting) *(or your actual source)*
- **Size:** *(e.g. 3 years of daily sales data across 50 stores)*
- **Features:** Date, store ID, product category, sales volume, promotions, holidays

> ⚑ Update with your actual dataset source and description.

---

## How to Run

```bash
# Clone the repo
git clone https://github.com/omanshisharma/sales-forecasting
cd sales-forecasting

# Install dependencies
pip install -r requirements.txt

# Launch notebook
jupyter notebook notebooks/sales_forecasting.ipynb
```

---

## Project Structure

```
sales-forecasting/
│
├── data/
│   └── sales_data.csv
├── notebooks/
│   └── sales_forecasting.ipynb
├── models/                    # Saved model files
├── results/
│   └── forecast_plot.png      # Add a chart of actual vs predicted
├── requirements.txt
└── README.md
```

---

## Visual Output

> ⚑ Add a chart image here showing **Actual vs Predicted sales** over the test period. This is the single most persuasive thing you can add to a forecasting project README.

---

## Author

**Omanshi Sharma** — [LinkedIn](https://linkedin.com/in/omanshi-sharma) · [GitHub](https://github.com/omanshisharma)
