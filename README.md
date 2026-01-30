# 🛡️ Vicious-RSI-Scanner

A real-time crypto market scanner designed to identify overbought and oversold opportunities using the **Relative Strength Index (RSI)**.

## 🚀 Key Features
* **Multi-Asset Monitoring**: Scans BTC, ETH, SOL, and BNB simultaneously.
* **Live Technical Analysis**: Calculates RSI (14-period) on a 1-minute timeframe.
* **Automated Logging**: Saves every potential trade opportunity to `vicious_journal.txt`.
* **Performance**: Lightweight and fast, powered by `ccxt` and `pandas`.

## 🛠️ Quick Start
### Install dependencies:
```bash
pip install ccxt pandas
