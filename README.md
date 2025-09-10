# 📈 AI & Finance Trading Agent

This project implements an **LSTM-based volatility prediction model** and a **SARSA reinforcement learning agent** for intraday trading decisions.

---

## 🔍 Project Overview

The project addresses two core challenges in quantitative finance:

1. **Volatility Forecasting** – using deep learning (LSTM)
2. **Trading Strategy Optimization** – using reinforcement learning (SARSA)

These models are trained and tested on minute-level data from the IVV ETF (S&P 500 tracker).

---

## 🚀 Features

### 📊 LSTM Volatility Predictor
- Preprocessing and feature scaling
- Time-series modeling with LSTM layers
- Model training and evaluation (MSE, loss curve)
- Volatility prediction visualization

### 🤖 SARSA Trading Agent
- Tabular Q-learning implementation using SARSA
- Action selection via epsilon-greedy policy
- Reward-based training over market states
- Performance evaluation on test set

---

## 📁 Folder Structure

```
ai-finance-trading-agent/
├── lstm_volatility_prediction.ipynb     # LSTM model for volatility
├── sarsa_trading_agent.py               # SARSA-based trading logic
├── streamlit_app.py                     # (optional) Streamlit demo interface
├── data/
│   ├── IVV_1m_training.csv              # Training data
│   ├── IVV_1m_validation.csv            # Validation data
│   └── README.txt
└── README.md
```

---

## ▶️ How to Run

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run LSTM notebook:
```bash
jupyter notebook lstm_volatility_prediction.ipynb
```

3. Run SARSA agent:
```bash
python sarsa_trading_agent.py
```

4. (Optional) Launch the Streamlit app:
```bash
streamlit run streamlit_app.py
```

---

## 📦 Requirements

```
pandas
numpy
matplotlib
scikit-learn
tensorflow
streamlit
```

---

## 📚 Dataset

The project uses intraday data for the IVV ETF at 1-minute intervals.  
Data is split into:

- `IVV_1m_training.csv`
- `IVV_1m_validation.csv`

> ℹ️ Data files are provided in the `data/` folder.

---

## 👤 Authors

- **Saman Dadkhah**

University of Verona – Master's in Artificial Intelligence  
🔗 [linkedin.com/in/saman-dadkhah](https://www.linkedin.com/in/saman-dadkhah/)
