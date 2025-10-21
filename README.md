# 🧮 Workforce & Capacity Planning Dashboard

### 📌 Overview
This project simulates and analyzes customer support operations data (across Email, Chat, and Phone channels) to support workforce and capacity planning. The goal is to drive efficiency in staffing, forecast volume, and improve SLA adherence.

---

### 📊 Key Features
- Synthetic dataset creation (180 days of data across 3 support channels)
- Forecasting daily support case volumes using **seasonality + noise**
- Operational metrics calculated:  
  `Cases`, `Avg Handling Time`, `SLA %`, `Headcount`, `Resolved Cases`, `Backlog`
- Time series trend visualizations using **rolling averages** and **FacetGrids**
- Anomaly detection using:
  - Z-Score thresholding
  - Isolation Forest
  - Local Outlier Factor (LOF)

---

### 📈 Tools Used
- Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
- Jupyter Notebook

---

### 🎯 Business Value
This type of operational insight helps:
- Prevent SLA breaches
- Optimize BPO headcount
- Improve customer experience through timely case handling

---

### ✅ Future Improvements
- Add LSTM forecasting for case volume and backlog
- Build a real-time dashboard (e.g., in Power BI or Streamlit)
