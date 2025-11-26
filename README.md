# TSA-PROJECT-Forecasting
## 📁 Project Overview

This project performs a full Time Series Analysis (TSA) workflow using Python. It includes exploratory analysis, model building, forecasting, and evaluation. The goal is to identify patterns in historical data and generate reliable future predictions.

The main script/notebook used in this project is:

```
Final Script TSA 02.ipynb
```

---

## ✅ Key Features

* ✅ Data loading 
* ✅ Exploratory time series visualization
* ✅ Trend & seasonality analysis
* ✅ Stationarity testing (ADF / KPSS)
* ✅ Differencing & transformations
* ✅ ARIMA / SARIMA model building
* ✅ Model selection using AIC / BIC
* ✅ Forecasting future values
* ✅ Confidence interval visualization

---

## 🛠️ Technologies Used

* **Python 3**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Statsmodels**
* **pmdarima (auto_arima)**

---

## 📂 Project Structure

```
📦 Time Series Analysis Project
 ┣ 📓 Final Script TSA 02.ipynb
 ┣ 📁 data/ INVEST.csv       # (Raw dataset)
 ┣ 📁 Project Presentation/      # (Contains Forecasts, plots, saved models)
 ┗ README.md
```

---

## 🚀 How to Run the Project

1. Clone or download the repository
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:

   ```bash
   jupyter notebook "Final Script TSA 02.ipynb"
   ```
4. Run all cells in sequence

> ✅ Make sure your dataset path matches the code in the notebook.

---

## 📈 Results

* Visualized historical patterns
* Identified trend/seasonality
* Built a forecasting model
* Generated future predictions with confidence intervals

(You can attach sample plots here.)

---

## 🔮 Future Improvements

* Add model comparison (Prophet, LSTM, VAR, etc.)
* Automate hyperparameter tuning
* Deploy forecasting API or dashboard
* Save model as a pickle file for reuse
