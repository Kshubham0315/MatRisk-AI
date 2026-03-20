# MatRisk-AI

## 📌 Project Overview

Modern commodity markets are influenced not only by financial trends but also by the **underlying material properties** of industrial resources such as steel, copper, lithium, and rare earth elements.

Traditional financial models ignore this critical connection.

### 🎯 Objective

To build a **cross-domain AI system** that integrates:
- Material Science (physical properties)
- Financial Time-Series Data
- Supply Chain Signals

And improve commodity forecasting using a novel feature:
> **Material Quality Index (MQI)**

---

## 🧠 Key Innovation

### 🔗 Task1 → Task2 Bridge

We introduce a **cross-domain bridge** that transforms:

```text
Material-Level Intelligence → Commodity-Level Features

Predict material properties (Task 1)

Compute MQI

Aggregate MQI at commodity level

Inject into financial forecasting model (Task 2)

👉 This allows combining:

Long-term material behavior

Short-term market dynamics

📊 Datasets Used
Dataset	Description
DS1	Material properties (5,500 materials)
DS2	Commodity prices (10 years daily data)
DS3	Cross-domain features (MQI, supply risk, elasticity)
DS5	Element price data (raw material cost signals)
⚙️ Task 1: Material Property Modelling
Pipeline
Material Composition + Structure
        ↓
Feature Engineering
        ↓
ML Models (LightGBM, XGBoost, RF)
        ↓
Physics Constraints
        ↓
Material Quality Index (MQI)
Predicted Properties

Density

Band Gap

Formation Energy

Bulk Modulus

Shear Modulus

Melting Point

Results
Property	R² Score
Density	0.76
Band Gap	0.67
Formation Energy	0.57
Bulk Modulus	0.51
📈 Task 2: Commodity Forecasting
Pipeline
Financial Features (RSI, MACD, Volatility)
        +
Material Signals (MQI, DS3)
        +
Element Price Signals (DS5)
        +
Task1 Bridge Features
        ↓
Feature Fusion
        ↓
ML Models
        ↓
Prediction
Models Built

Return Prediction (Regression)

Direction Prediction (Classification)

Volatility Prediction

💡 Feature Engineering
Financial Features

RSI, MACD, Momentum

Volatility indicators

Term Spread

Material Features

MQI

MQI trends

Supply disruption probability

Substitution elasticity

Bridge Features

Task1 MQI (commodity-level)

MQI gap & blended MQI

MQI × supply risk interactions

DS5 Features

Element price

Element return

Cost × MQI interactions

🚀 Model Comparison
Model	Performance
Financial Only	Baseline
Material Only	Weak
Fused	Improved
Fused + Bridge	✅ Best

👉 Adding material intelligence improves prediction.

💰 Backtesting Results
Metric	Value
Hit Rate	51.3%
Sharpe Ratio	0.83
Profit Factor	1.16
Max Drawdown	-55%
Insight

Even with noisy predictions, the model generates:

Economically useful trading signals

🔍 Explainability

We used feature importance and SHAP analysis.

Key Drivers

MQI and MQI trends

Supply disruption probability

Momentum indicators

Element price signals


🛠️ Tech Stack

Python

Pandas, NumPy

Scikit-learn

LightGBM, XGBoost

Matplotlib, Seaborn

SHAP

🔮 Future Work

Deep learning models (LSTM, Transformers)

Improved material-to-commodity mapping

Cost-aware inverse material design

Real-time deployment

🏁 Conclusion

Successfully integrated material science and finance

MQI serves as a powerful cross-domain signal

Task1 → Task2 bridge improves forecasting

🚀 This approach opens a new paradigm in commodity prediction.
