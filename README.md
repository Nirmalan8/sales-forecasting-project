#  Sales Forecasting Using Linear Regression

This project uses past weekly sales data to predict future sales using a simple machine learning model. It’s a beginner-friendly regression project that walks through data cleaning, feature engineering, visualization, model training, and evaluation.

---

##  Dataset

- The dataset includes weekly sales values along with:
  - Date
  - Holiday flag (whether the week had a holiday)
- It helps forecast how much a store might sell in the future.

---

##  Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn (Linear Regression, train-test split, metrics)

---

##  Workflow

1. **Data Loading & Exploration**
   - Load CSV using Pandas
   - Explore structure using `.info()` and `.describe()`

2. **Feature Engineering**
   - Convert `Date` column into:
     - Day of week
     - Month
     - Year
   - Use `Holiday_Flag` to capture special weeks

3. **Visualization**
   - Line plot of weekly sales over time

4. **Modeling**
   - Train a `LinearRegression` model
   - Features used: `day_of_week`, `month`, `year`, `Holiday_Flag`

5. **Evaluation**
   - Metrics:
     - Mean Absolute Error (MAE)
     - Root Mean Squared Error (RMSE)

6. **Prediction**
7. ---

##  What I Learned

- How to prepare date features for time-based predictions
- Building a basic regression model in scikit-learn
- Evaluating model performance with error metrics
- Visualizing time series data

---

##  Future Ideas

- Add moving averages or lag-based features
- Compare models: Random Forest, XGBoost
- Deploy the model with Streamlit for real-time predictions

---
   - Forecast sales for a custom date (like June 2025)

---


