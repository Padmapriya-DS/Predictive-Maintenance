# 🚀 Predictive Maintenance for Manufacturing Equipment

## 💡 Project Overview
This project presents a predictive maintenance pipeline for industrial manufacturing equipment, leveraging deep learning to forecast Remaining Useful Life (RUL). The solution shifts operations from reactive to proactive maintenance minimizing downtime, reducing repair costs and enhancing safety and efficiency.

## 🔧 Problem Statement
Unplanned equipment failure in manufacturing leads to:
- 🔴 Unscheduled downtime and halted production
- 💸 Emergency repair costs
- ⚠️ Safety risks for workers
- 📉 Reduced efficiency and output

## 🧠 Our Solution: LSTM-Based Predictive Maintenance
We use an **LSTM (Long Short-Term Memory)** neural network; a deep learning model tailored for time-series data to predict engine degradation and estimate when maintenance is needed, **before failure occurs**.

---

## 📊 Methodology

1. **📥 Data Acquisition**  
   NASA C-MAPSS dataset (`train_FD001.txt`) containing operational settings and 21 sensor signals from multiple engines.

2. **🧹 Data Preprocessing & Feature Engineering**  
   - Engine cycles labeled with RUL (Remaining Useful Life)
   - Scaled features using MinMaxScaler  
   - Rolling statistics (mean & std) to capture trends

3. **🧠 Model Development**  
   - Built a 2-layer **LSTM** model with Dropout regularization using TensorFlow/Keras
   - Trained to map sensor patterns to RUL

4. **📈 Evaluation**  
   - **MAE**: 16.55  
   - **MSE**: 608.62  
   - **RMSE**: 24.67  

5. **📊 Visualization**  
   - Power BI Dashboard for real-time exploration of predictions

---

## 🧾 Key Files

| File | Description |
|------|-------------|
| `Predictive Maintenance for Manufacturing Equipment.ipynb` | Jupyter Notebook with full E2E pipeline |
| `Predictive_Maintenance_Dashboard.pbix` | Power BI Dashboard with model results |
| `Predictive Maintenance Report.pptx` | Executive summary presentation for stakeholders |

---

## 🧰 Tools & Tech Stack
- **Python** (Jupyter Notebook)
- `Pandas`, `NumPy`, `Scikit-learn`
- **TensorFlow / Keras** for LSTM modeling
- **Power BI** for dashboard visualization

---

## 🎯 Business Impact
- ⏱️ Anticipates failures before they happen
- 💰 Reduces repair & downtime costs
- 📊 Provides insights for engineers via visual dashboards

---

## ✅ Final Thoughts
This project simulates a real-world predictive maintenance use case, delivering value across analytics, engineering and business intelligence. It’s tailored for MNCs embracing Industry 4.0 and predictive systems for smarter asset management.

---

### 📂 Dataset Source  
This project uses the **CMAPSS dataset** from NASA, accessed via Kaggle.

- **Kaggle Link**: [Predictive Maintenance Dataset - CMAPSS](https://www.kaggle.com/datasets/behrad3d/nasa-cmaps)  
- **Original Source**: NASA's Prognostics Center of Excellence  
- **Citation**:  
  Saxena, A., Goebel, K., Simon, D., & Eklund, N. (2008). *Damage Propagation Modeling for Aircraft Engine Run-to-Failure Simulation*.  
- **Usage**: For academic and non-commercial research purposes.
