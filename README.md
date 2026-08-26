# Aircraft Engine RUL Prediction

**Predictive maintenance project using Python, Machine Learning, SQL Server, and Power BI.**

## 📌 Project Overview

Built an end-to-end machine learning pipeline to predict the **Remaining Useful Life (RUL)** of aircraft engines from historical sensor data.

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

![Aircraft Engine RUL Dashboard](Images/Aircraft_Project_Dashboard.png)

## 🛠️ Tech Stack

**Python:** Pandas, NumPy, Scikit-learn, Matplotlib  
**SQL:** SQL Server, SSMS, Views, Window Functions  
**Visualization:** Power BI  
**Development:** VS Code, GitHub

## 📁 Project Structure

```text
Aircraft-Engine-RUL-Prediction/
│
├── notebooks/
│   └── 01_data_exploration.ipynb
│
├── powerbi/
│   └── README.md
│
├── images/
│   └── aircraft_engine_rul_dashboard.png
│
├── requirements.txt
└── README.md
