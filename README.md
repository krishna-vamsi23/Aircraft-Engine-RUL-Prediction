# Aircraft Engine RUL Prediction

**Predictive maintenance project using Python, Machine Learning, SQL Server, and Power BI.**

## 📌 Project Overview

Using the NASA C-MAPSS aircraft engine degradation dataset, this project addresses the challenge of predicting when an aircraft engine may require maintenance before failure occurs. By analyzing historical engine operating conditions and sensor behavior over time, the solution provides an early indication of remaining useful life, supporting proactive maintenance planning and reducing the risk of unexpected downtime.

The project covers:

- 📊 Data exploration and preprocessing
- ⚙️ Sensor feature engineering and rolling averages
- 🤖 Machine learning for RUL prediction
- 🗄️ SQL Server analysis using views and window functions
- 📈 Interactive Power BI dashboard for engine health and model analysis

## 📊 Dataset

- **100 aircraft engines**
- **20,631 engine-cycle records**
- **21 sensor measurements**
- Target: **Remaining Useful Life (RUL)**

## 🤖 Model Performance

| Metric | Test Result |
|---|---:|
| **MAE** | **24.16 cycles** |
| **RMSE** | **32.28 cycles** |
| **R²** | **0.396** |

**MAE** — Mean Absolute Error<br>
**RMSE** — Root Mean Squared Error<br>
**R²** — Coefficient of Determination

The final model was evaluated on **unseen test-engine data**.

## 📈 Power BI Dashboard

The dashboard provides an interactive view of:

- Engine fleet KPIs
- Engine lifetime comparison
- Sensor degradation trends
- 5-cycle rolling-average analysis
- RUL degradation
- Actual vs. predicted RUL
- Prediction error analysis

## Power BI Dashboard

The dashboard uses **Engine 69 as an example case** to demonstrate sensor degradation and RUL trends. Engine 69 was selected because it has one of the longest operating lifetimes in the training dataset (**362 cycles**), making its degradation trend easy to visualize.

![Aircraft Engine RUL Dashboard](Images/Aircraft_Project_Dashboard.png)



## 🛠️ Tech Stack

**Python:** Pandas, NumPy, Scikit-learn, Matplotlib  
**SQL:** SQL Server, SSMS, Views, Window Functions  
**Visualization:** Power BI  
**Development:** VS Code, GitHub

## Conclusion

This case study helped me understand how an aircraft engine’s condition changes throughout its operating life and how this information can be used to estimate when maintenance may be needed. The results show that monitoring sensor patterns over time can help identify signs of degradation earlier and support better maintenance planning.

**Outcome:** The final model achieved a **MAE of 24.16 cycles** and **RMSE of 32.28 cycles** on 100 unseen test engines, while the Power BI dashboard provides an interactive view of engine health, degradation trends, RUL, and prediction errors.

