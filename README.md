# 📊 Demand Forecasting & Inventory Optimization for Construction Machinery

This project was built as part of a Datathon challenge focused on solving a real-world problem in the construction equipment industry. It involved **predicting daily sales (demand)** for various heavy machinery types and **optimizing inventory allocation** under storage constraints using **machine learning** and **linear programming** techniques.

---

## 🧠 Problem Statement

A leading heavy machinery manufacturer is facing issues with demand volatility and inefficient inventory management. The task is to:

1. **Develop a machine learning model** to forecast daily sales for different machinery types.
2. **Optimize the inventory** to fit within a fixed warehouse space (5000 cubic meters), minimizing stockouts and holding costs.

---

## 🎯 Objectives

### 🔹 Objective 1: Demand Forecasting
- Used historical sales data and market-related factors.
- Trained an **XGBoost Regression model** to predict the `Daily Sales Quantity`.
- Achieved an accuracy of approximately **95%** on the validation dataset.

### 🔹 Objective 2: Inventory Optimization
- Used **Linear Programming** (via the `PuLP` library) to determine the best combination of machinery units to store.
- Respected warehouse constraints and prioritized value optimization and space efficiency.

---

## 📁 Project Structure

- `Cleaning dataset.ipynb` – Data preprocessing & exploratory data analysis (EDA).
- `Datathon training.ipynb` – Model building (XGBoost) and optimization logic (PuLP).
---

## 🧰 Tech Stack

- **Languages**: Python
- **Libraries**:
  - `pandas`, `numpy` – Data handling
  - `matplotlib`, `seaborn` – Visualization
  - `xgboost` – Machine learning model
  - `sklearn` – Model evaluation
  - `pulp` – Linear programming for inventory optimization

---

## 📈 Key Insights

- Feature importance was analyzed to understand the impact of political, budget, and marketing columns on demand.
- The optimized inventory strategy was developed by balancing high-value, low-volume machinery units.
- The project simulates a real-world business problem, emphasizing the synergy between **data science** and **operations research**.

