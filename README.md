:

🛡️ Vicious-RSI-Scanner
A real-time crypto market scanner designed to identify overbought and oversold opportunities using the Relative Strength Index (RSI).

🚀 Key Features
Multi-Asset Monitoring: Scans BTC, ETH, SOL, and BNB simultaneously.

Live Technical Analysis: Calculates RSI (14-period) on a 1-minute timeframe.

Automated Logging: Saves every potential trade opportunity, including price and timestamp, to vicious_journal.txt.

Performance: Lightweight and fast, powered by ccxt and pandas.

🛠️ Quick Start
Install dependencies:

Bash
pip install ccxt pandas
Run the scanner:

Bash
python vicious_trader.py
📈 Strategy Logic
RSI > 70: Asset is overbought (Potential Sell/Short signal).

RSI < 30: Asset is oversold (Potential Buy/Long signal).

📊 Live Data Samples
[2026-01-30 13:03:21] POTENTIAL SELL: BTC/USDT (83259.32) | RSI: 80.42

[2026-01-30 13:03:22] POTENTIAL SELL: BNB/USDT (843.14) | RSI: 84.53
