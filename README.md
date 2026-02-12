# Sales Forecasting: Prophet vs ARIMA 🏆

Prophet **crushed** ARIMA on synthetic sales data!

## Results
| Model  | Test MAE | Status |
|--------|----------|--------|
| Prophet| **3.71** | 🥇 WINNER |
| ARIMA  | 14.96    | 🥈     |

## 🎯 Key Skills Demonstrated
- Synthetic time series generation (trend + weekly/yearly seasonality)
- Prophet forecasting (auto seasonality detection)
- SARIMA modeling (pmdarima auto_arima)
- Model comparison (MAE metrics + visualizations)
- Professional plotting & evaluation

## 📊 Live Results
![Forecast Comparison](https://via.placeholder.com/800x400/007bff/ffffff?text=Prophet+vs+ARIMA+Forecast)

## 🚀 Quick Start
```bash
# Clone repo
git clone https://github.com/YOUR_USERNAME/sales-forecasting-prophet-arima.git
cd sales-forecasting-prophet-arima

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook sales_forecasting_prophet_arima.ipynb
