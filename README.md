# Gold Price Prediction using Machine Learning

This project predicts gold prices using the Random Forest Regressor algorithm.

## 📌 Project Overview

The model is trained using historical gold price data and related financial indicators such as:

- SPX
- USO
- SLV
- EUR/USD

The project performs:
- Data preprocessing
- Correlation analysis
- Data visualization
- Model training
- Prediction
- Accuracy evaluation

---

# 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

# 📂 Dataset Features

| Feature | Description |
|---|---|
| Date | Date of record |
| SPX | S&P 500 Index |
| GLD | Gold Price |
| USO | United States Oil Fund Price |
| SLV | Silver Price |
| EUR/USD | Euro to USD exchange rate |

---

# 🤖 Machine Learning Algorithm Used

## Random Forest Regressor

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

```python
regressor = RandomForestRegressor(n_estimators=100)
