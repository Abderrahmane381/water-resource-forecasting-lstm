# 💧 Water Resource Forecasting and Management — Tangier Region

> Multivariate LSTM forecasting framework for water demand, supply, 
> and storage prediction with policy scenario simulation and MPC allocation.

---

## 📌 Project Overview

This project presents a data-driven framework for forecasting and managing 
water resources in the Tangier region. It combines:

- Multivariate LSTM forecasting
- Sectoral demand analysis (domestic, agricultural, industrial)
- Water stress evaluation
- Policy scenario simulation
- Model Predictive Control (MPC) for water allocation

---

## 🏗️ Architecture

**Pipeline :**
1. Data cleaning & storage reconstruction
2. Scaling & sequence creation
3. Multivariate LSTM training
4. Forecasting (5 variables)
5. Policy scenario simulation
6. MPC water allocation

---

## 📂 Project Structure

```
├── data/
│   ├── tangier_synthetic_water_model_with_supply_2000_2035.csv
│   ├── tangier_synthetic_water_model_with_supply_FIXED_STORAGE_2000_2035.csv
│   ├── tangier_synthetic_water_virtual_water_2000_2035.csv
│   └── tangier_synthetic_water_food_self_sufficiency_2000_2035.csv
│
├── src/
│   ├── fixed_dataset.ipynb
│   ├── final_lstm_forecasting.ipynb
│   └── lstm_policy_scenarios.ipynb
│
└── README.md
```
---

## 📓 Recommended Reading Order

1. `fixed_dataset.ipynb` — Dataset cleaning & storage reconstruction
2. `final_lstm_forecasting.ipynb` — Main LSTM forecasting pipeline
3. `lstm_policy_scenarios.ipynb` — Policy scenario analysis

---

## 🗂️ Dataset

- Synthetic dataset designed to reflect realistic temporal behavior
- Period : 2000–2035
- Region : Tangier, Morocco
- 3 policy scenarios : Baseline, Virtual Water, Food Self-Sufficiency

---

## 📊 Main Outputs

- Forecasts of domestic, agricultural, and industrial demand
- Total supply forecasting
- Storage forecasting
- Water stress analysis
- Scenario comparison
- Water allocation analysis using MPC

---

## 🛠️ Tech Stack

Python · TensorFlow · Keras · LSTM · Scikit-learn · 
Pandas · NumPy · Matplotlib · Google Colab

---

