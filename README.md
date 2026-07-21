# Sales_Forecasting_Prediction
# 📈 Interactive Sales Forecasting & Demand Prediction App

An end-to-end Machine Learning mini-project designed to predict future product demand using historical time-series data. Built with **Python**, **Scikit-Learn**, and **Streamlit**, this app transforms raw date-based sales data into predictive signals via feature engineering and offers an interactive dashboard for model evaluation and visualization.

---

### ✨ Key Features

* **Temporal Feature Engineering:** Extracts calendar trends (`DayOfWeek`, `Month`, `Year`), lag signals (`Sales_Lag_1`, `Sales_Lag_7`, `Sales_Lag_30`), and moving averages (`Rolling_Mean_7`).
* **Random Forest Regressor:** Uses an ensemble tree model to capture non-linear seasonality and sales trends.
* **Interactive Dashboard:** Built with Streamlit to let users adjust hyperparameter controls (`Number of Trees`, `Train/Test Split Ratio`) on the fly.
* **Dynamic Plotly Visualizations:** Interactive time-series line charts comparing actual sales vs. predictions, along with a feature importance breakdown.
* **Model Evaluation:** Tracks accuracy in real time using **RMSE** (Root Mean Squared Error) and **MAE** (Mean Absolute Error).

---

### 🛠️ Tech Stack

* **Language:** Python 3.x
* **Machine Learning:** `scikit-learn`
* **Data Processing:** `pandas`, `numpy`
* **Visualization:** `plotly`
* **Web Framework:** `streamlit`

---

### 🚀 Quick Start

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Pavan-0612/Sales_Forecasting_Prediction.git](https://github.com/Pavan-0612/Sales_Forecasting_Prediction.git)
   cd sales-forecasting-app

---

### 

1. Install dependencies:
pip install streamlit pandas numpy scikit-learn plotly

2.  Run the Streamlit app:
 streamlit run app.py
