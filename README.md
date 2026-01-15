# Hi! I'm NeoZorK 👋

**Quantitative developer & researcher focused on robust, production-grade trading systems.**  
I design and build end-to-end platforms for algorithmic trading, prediction, indicators and data analysis across crypto and traditional markets, from research pipelines and models to execution, monitoring and automation.

## 💼 About Me

I am a Quantitative Developer & Researcher with experience across:

- Systematic and algorithmic trading (discretionary and fully automated workflows)
- Advanced technical indicators and mathematical models for signal extraction
- Design of high-performance components for execution and algorithmic strategies
- Machine learning / deep learning for financial time series and predictive modeling
- Robust validation frameworks to avoid overfitting and improve live performance
- Developer tooling and infrastructure for research productivity and reliability

- LinkedIn: [rostyslav-sh-](https://www.linkedin.com/in/rostyslav-sh-)
- YouTube: [Filo de Ma Analytics](https://www.youtube.com/@filodemaanalytics6342)

## 🛠️ Technologies I Work With

- **Trading Platforms:** MQL5 / MT5 (experts, indicators, trading robots)
- **Languages:** C++, Python, JavaScript 
- **Infrastructure & DevOps:** Docker, Bash / Shell, Linux, automation tooling
- **Data & ML:** modern ML/DL frameworks for time series and tabular data
- **Ecosystem:** crypto, FX, and traditional markets (equities, indices, derivatives)

## 🚀 Public Projects (Selected)

### Core Trading & Prediction Systems

- **[neozork-hld-prediction](https://github.com/NeoZorK/neozork-hld-prediction)**  
  Research and production-ready framework for High/Low prediction on financial time series.  
  Focuses on:
  - Signal generation using modern ML/DL architectures
  - Multi-timeframe processing and feature engineering
  - Integration with MetaTrader 5 via MQL5 for live trading
  - Robust validation to reduce overfitting, including walk-forward analysis

- **[NeoZorK3](https://github.com/NeoZorK/NeoZorK3)**  
  Command-line tool for blockchain data analysis and algorithmic execution with an emphasis on speed and reliability.  
  Includes:
  - High-performance execution components in C++
  - Efficient market data processing and signal detection
  - Focus on robust workflows and stable operation in production

- **[DEXArb](https://github.com/NeoZorK/DEXArb)**  
  Fast algorithmic detection and execution system for decentralized exchanges.  
  Designed to:
  - Scan multiple DEX venues for liquidity and trading signals
  - Evaluate execution feasibility and transaction costs
  - Serve as a foundation for further research into on-chain algorithmic strategies

### MQL5 Trading Indicators and Expert Advisers

- **[Rost_MQL5_Experts](https://github.com/NeoZorK/Rost_MQL5_Experts)**  
  Structured library of expert advisors for MetaTrader 5.  
  Highlights:
  - Modular architecture for building and combining trading logic
  - Ready-to-use strategies and building blocks for automated trading
  - Focus on clarity, extensibility and reuse in real accounts

- **[Rost_MQL5_Include](https://github.com/NeoZorK/Rost_MQL5_Include)**  
  Foundation of reusable components and utilities for MT5/MT4.  
  Provides:
  - Common abstractions for orders, risk, indicators and signals
  - Infrastructure code that simplifies development of new EAs
  - Consistent patterns for error handling and logging

- **[Rost_MQL5_Indicators](https://github.com/NeoZorK/Rost_MQL5_Indicators)**  
  Collection of custom indicators for MetaTrader 5.  
  Focused on:
  - Advanced visualization of market structure and regimes
  - Signal extraction for systematic strategies
  - Compatibility with the expert advisor ecosystem above

### Tooling, Automation & Data

- **[NeoZorK](https://github.com/NeoZorK/NeoZorK)**  
  Main repository aggregating documentation, experiments and higher-level project overview.

- **[neozork-mcp-server](https://github.com/NeoZorK/neozork-mcp-server)**  
  MCP server that enhances development workflow and automation around trading research and coding.

- **[neo-slack-bot-production](https://github.com/NeoZorK/neo-slack-bot-production)**  
  Production-grade Slack bot used for:
  - Delivering trading alerts and monitoring signals
  - Integrating research and execution systems with team communication
  - Automating routine operational tasks via chat interfaces

- **[trading-data-replay-engine](https://github.com/NeoZorK/trading-data-replay-engine)**  
  Engine for replaying and analyzing historical trading data.  
  Enables:
  - Realistic simulation of strategies on tick- or bar-level streams
  - Debugging execution logic and behavior in edge market conditions
  - Building intuition about market microstructure and execution quality

## 🎯 Featured Public Project: neozork-hld-prediction

### Project Overview

The **neozork-hld-prediction** project represents a breakthrough in financial time series prediction, specifically designed to predict High/Low price movements in financial markets. This project emerged from the need to create a robust, profitable trading system that addresses the common pitfalls of overfitted backtest results.

### Key Features

- **Advanced ML/DL Models**: Implementation of state-of-the-art machine learning and deep learning architectures
- **Multi-timeframe Analysis**: Support for various timeframes from minutes to daily charts
- **Real-time Prediction**: Live prediction capabilities with MQL5 integration
- **Risk Management**: Built-in risk management and position sizing algorithms
- **Backtesting Framework**: Comprehensive backtesting with walk-forward analysis
- **Data Preprocessing**: Advanced feature engineering and data normalization

### Technical Stack

- **Python**: Core ML/DL implementation using TensorFlow/PyTorch
- **MQL5**: Real-time trading integration for MetaTrader 5
- **Data Sources**: Multiple financial data providers and APIs
- **Visualization**: Advanced plotting and analysis tools

### Why This Project Exists

The development of this project was motivated by the realization that traditional backtesting approaches often produce **overfitted results** that fail in live trading. This is a critical issue in quantitative finance where models may perform exceptionally well on historical data but fail to generalize to new market conditions.

## 📺 Video Demonstration: The Overfitting Problem

Watch this video from [Filo de Ma Analytics](https://www.youtube.com/@filodemaanalytics6342) that demonstrates the classic overfitted backtest results:

[![Overfitted Backtest Results - Filo de Ma Analytics](https://img.youtube.com/vi/VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=VIDEO_ID)

*This video showcases overfitted backtest results - a common pitfall in algorithmic trading that inspired the creation of a robust ML platform.*

## 🧠 Machine Learning Platform Development

### The Problem with Traditional Approaches

The overfitted backtest results demonstrated in the video above highlight a fundamental issue in quantitative trading: **models that perform well on historical data often fail in live markets**. This occurs due to:

- **Data Snooping**: Over-optimization on historical data
- **Look-ahead Bias**: Using future information in backtesting
- **Survivorship Bias**: Ignoring failed strategies
- **Market Regime Changes**: Models trained on one market condition failing in another

### Solution: Robust ML Platform

To address these challenges, I developed a comprehensive machine learning platform that incorporates:

#### Modern ML/DL Techniques
- **Ensemble Methods**: Combining multiple models for better generalization
- **Deep Learning**: LSTM, GRU, and Transformer architectures for time series
- **Reinforcement Learning**: Adaptive strategies that learn from market feedback
- **Online Learning**: Models that continuously adapt to new market conditions

#### Existing Experience Integration
- **Time Series Analysis**: Deep understanding of financial market behavior
- **Algorithm Development**: Experience in creating efficient, optimized algorithms
- **Risk Management**: Proven methodologies for position sizing and risk control
- **Market Microstructure**: Knowledge of order flow and market dynamics
- **Cross-Asset Analysis**: Experience across crypto, forex, and traditional markets

#### Robust Validation Framework
- **Walk-Forward Analysis**: Testing models on out-of-sample data
- **Cross-Validation**: Proper time series cross-validation techniques
- **Regime Detection**: Identifying different market conditions
- **Stress Testing**: Performance under extreme market conditions

## � Private Research & Production Experience

In addition to the public projects above, I actively develop and maintain proprietary systems (not listed here as repositories), including:

- Production-ready trading systems with live execution and monitoring
- Infrastructure for ingesting, cleaning and storing large volumes of market data
- Risk management and portfolio oversight tools for systematic strategies
- Internal research frameworks for rapid prototyping and evaluation of ideas
- Automation and observability tooling around trading operations and data quality

These projects emphasize:

- Reliability in live trading (graceful degradation, monitoring, alerting)
- Performance and scalability under real market load
- Clean abstractions between research, execution and infrastructure layers
- Reproducible research workflows and auditable decision-making

## 📈 What I Teach and Solve

- Development and optimization of trading strategies (from idea to deployment)
- Design of research pipelines, data handling and feature engineering
- Automation of trading, risk management and operational workflows
- Creation of automated trading and execution algorithms in crypto and traditional markets
- Machine learning applications in finance with a focus on robustness
- Model validation, monitoring and continuous improvement in live environments

## 💰 Support the Project

If you find my work valuable and want to support the development of these open-source tools, you can make a Bitcoin donation:

![Bitcoin Donation QR Code](https://raw.githubusercontent.com/NeoZorK/Rost_MQL5_Experts/main/assets/images/bitcoin_donation_qr.png)

**Bitcoin Address:** `bc1qm0ynz8tk2em3zr8agv5j3550vpm420z3hxd`

*Your support helps maintain and improve these tools for the trading community.*

## 📬 Contact Me

- LinkedIn: [rostyslav-sh-](https://www.linkedin.com/in/rostyslav-sh-)
- YouTube: [Filo de Ma Analytics](https://www.youtube.com/@filodemaanalytics6342)

---

**Open to cooperation and new interesting projects!**

*Building the future of algorithmic trading through robust machine learning and quantitative research.*
