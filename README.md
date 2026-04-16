# Gautier Petit

Quant-focused MSc Finance graduate from HEC Lausanne with a strong interest in systematic strategies, market microstructure, and research engineering.

I build research-grade quantitative projects at the intersection of finance, machine learning, and reproducible infrastructure, with a focus on realistic evaluation, robust experimental design, and public documentation.

My goal is to contribute to hedge fund-style systematic research and quantitative infrastructure.

---

## Current Focus

**Event-Driven Market Microstructure Research**  
Designing event-based limit order book research pipelines in C++ and Python to study short-horizon price dynamics from order flow and book state.

**Meta-Labeling and Signal Filtering**  
Building machine learning frameworks to improve trade selection, probability calibration, and portfolio-level robustness in systematic equity strategies.

**Tail-Aware Portfolio Optimization**  
Developing allocation frameworks using CVaR, CDaR, Omega ratio, and semi-parametric risk modeling under realistic constraints.

**Research Engineering**  
Strengthening the engineering side of quant research through modular pipelines, reproducibility, testing, and performance-aware implementation.

---

## Featured Projects

### [MicroAlpha Engine](https://github.com/gautierpetit/microalpha-engine)

A C++/Python market microstructure research engine for event-driven limit order book prediction.

- Reproducible pipeline for short-horizon midprice prediction using LOBSTER data across multiple NASDAQ tickers
- Event-level feature engineering in C++ with Python bindings via pybind11
- Config-driven experiments, pooled cross-sectional evaluation, diagnostics, permutation importance, and saved run artifacts
- Public repository with documentation, tests, Docker support, and preserved example outputs

### [Meta-Labeling Alpha Filter](https://github.com/gautierpetit/meta-labeling-alpha-filter)

A machine learning framework designed to refine a baseline cross-sectional momentum strategy through probability-based filtering and sizing.

- Point-in-time S&P 500 dataset construction, triple-barrier labeling, and engineered predictive features
- Calibrated LightGBM and MLP models combined through chronology-respecting validation and blending
- Portfolio construction with volatility targeting, leverage caps, turnover constraints, and asymmetric transaction costs
- Public repository with full case report, reproducible workflows, and documented evaluation

### [Hedge Fund Portfolio Optimization: A Semi-Parametric Approach](https://github.com/gautierpetit/hedge-fund-portfolio-optimization)

MSc thesis on hedge fund allocation under tail risk and non-Gaussian dependence.

- Semi-parametric framework combining AR-EGARCH volatility, EVT tail modeling, and Student's t copulas
- Allocation objectives including CVaR, CDaR, and Omega ratio under practical portfolio constraints
- Tested on 30+ years of hedge fund data with full thesis report publicly available
- Repository kept primarily for research transparency; newer projects better reflect my current engineering standards

---

## Skills

**Programming and Infrastructure**  
Python, C++, scikit-learn, Git, GitHub, Linux, SQL, Docker, CMake, pybind11, pytest

**Quantitative Research**  
Market microstructure, event-driven feature engineering, portfolio optimization, risk management, backtesting, performance evaluation, tail risk modeling

**Machine Learning**  
Supervised learning, ensemble methods, probability calibration, model validation, time-series cross-validation, explainability

**Data and Research Workflows**  
Point-in-time data construction, limit order book data handling, feature engineering, reproducible research pipelines, diagnostics, artifact-driven experimentation

---

## Contact

Based in Switzerland

[LinkedIn](https://www.linkedin.com/in/gautierpetitch/)  
[GitHub](https://github.com/gautierpetit/)
