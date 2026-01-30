Vicious- RSI- Scanner
Utilising the Relative Strength Index (RSI), a real-time crypto market scanner designed to spot overbought and oversold conditions.
🚀  characteristics
Multi-Asset Monitoring: Concurrent scans of BTC, ETH, SOL, BNB
Calculates RSI (14-period) on a 1-minute time frame using live technical analysis.
Saves every possible trading chance with price and timestamp in fierce_journal.txt.
Performance: Driven by ccxt and pandas, lightweight and quick.
Rapid Start
Dependencies installation:
Bash
pip install pandas ccxt
Run the scanning:
bash
Python cruel_ trader.py
Strategy Logic:
Asset is overbought (Potential Sell/Short signal); RSI > 70.
RSI < 30: The asset is overbought (Possible Buy/Long signal).
Live Information Samples:
[2026-01-30 13:03:21] POTENTIAL SELL: BTC/USDT (83259.32), RSI: 80.42
[2026-01-30 13:03:22] POTENTIAL SELL: BNB/USDT (843.14) | RSI: 84.53
