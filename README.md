# 👋 Hi, I'm Gautier Petit

🎯 Quant-focused MSc Finance (HEC Lausanne) specializing in systematic strategies, event-driven market microstructure, and risk-aware portfolio construction.<br/>
🔬 I build research-grade pipelines that combine finance, machine learning, and performance-aware systems — from event-level data processing to model evaluation under realistic constraints.<br/>
🚀 My goal: contribute to hedge fund–style systematic research and quantitative infrastructure.<br/>

---

## 🧠 Current Focus

- 📊 Event-Driven Market Microstructure Research (C++ + Python)
Designing an event-based limit order book feature engine using NASDAQ ITCH-derived data to explore short-horizon price dynamics under realistic research constraints.
- 📈 Meta-Labeling & Signal Filtering
Improving trade selection and probability calibration for systematic equity strategies.
- 🧮 Tail-Aware Portfolio Optimization
Robust allocation frameworks using CVaR, CDaR, Omega, and semi-parametric risk modeling.
- ⚙️ Performance-Critical Quant Infrastructure
Strengthening C++ for event-driven systems, stateful processing, and research-to-production alignment.

---

## 📌 Featured Project

### [Meta-Labeling Alpha Filter](https://github.com/gautierpetit/meta-labeling-alpha-filter)

>A deployable ML framework that learns when not to trade.
- End-to-end pipeline: point-in-time data → triple-barrier labeling → feature engineering → calibrated ML models (LightGBM, MLP).
- Probability-aware trade gating & sizing with volatility targeting, leverage caps, and turnover controls.
- Results (OOS, net of costs): Sharpe 1.09 in 50/50 blend with SPY; 65.8% win rate across 3,600+ trades.
- 📄 [Full case report included](https://github.com/gautierpetit/meta-labeling-alpha-filter/blob/main/docs/Meta-Labeling%20Alpha%20Filter%20-%20Case%20Report.pdf) | 🐍 Python code | 🔍 Reproducible runs with config snapshots

### [Hedge Fund Portfolio Optimization: A Semi-Parametric Approach](https://github.com/gautierpetit/hedge-fund-portfolio-optimization)

>MSc thesis on hedge fund allocation under tail risk.
- Hybrid framework integrating AR-EGARCH volatility, EVT for tails, and Student-t copulas.
- Objectives: CVaR, CDaR, Omega ratio; non-linear constraints (turnover, correlations).
- Tested on 30+ years of HFR data; improved risk-adjusted performance vs traditional benchmarks.
- 📄 [Thesis PDF included](https://github.com/gautierpetit/hedge-fund-portfolio-optimization/blob/main/thesis.pdf) | 🐍 Python code | 📊 Full documentation & results

---

## ⚙️ Skills

**Programming & Systems**
Python (Advanced), C++ (event-driven systems, developing), Git & GitHub, Linux, SQL, Docker, Bloomberg Terminal

**Quantitative Research**
Market Microstructure (limit order books, OFI, queue and depth imbalance), Portfolio Optimization, Risk Management, Backtesting, Constrained Optimization, Tail Risk Modeling (AR/GARCH, EVT, Copulas)

**Machine Learning**
Supervised Learning (Classification & Regression), LightGBM, MLPs, Probability Calibration, Model Validation, Explainability (SHAP), Time-Series Labeling (triple-barrier, event-horizon)

**Data Engineering**
Event-Based Data Processing, Point-in-Time Construction, Feature Engineering, Time-Series Analysis, Reproducible Research Pipelines

---

## 📫 Contact

📍 Based in Switzerland<br/>
🔗 [LinkedIn – Gautier Petit](https://www.linkedin.com/in/gautierpetitch/)<br/>
💻 [GitHub – gautierpetit](https://github.com/gautierpetit/)<br/>
🤝 Open to quant research, systematic strategy, or quant dev roles<br/>


