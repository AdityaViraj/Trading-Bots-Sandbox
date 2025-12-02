# 📈 Trading-Bots-Sandbox

Experimental sandbox for **algorithmic trading strategies** – backtests, ideas, and prototypes.

> ⚠️ **Disclaimer**: This repository is for **educational purposes only**.  
> Not financial advice. Do NOT risk real money based solely on this code.

## 🧠 What’s inside?

- `strategies/`
  - `mean_reversion/` – simple mean reversion ideas  
  - `breakout/` – breakout / momentum style entries  

- `data/` – sample OHLCV data (CSV / Parquet)  
- `backtests/` – evaluation scripts + results  
- `utils/` – loaders, common functions  
- `config/` – strategy parameters & paths

## ▶️ Example usage

```bash
git clone https://github.com/AdityaViraj/Trading-Bots-Sandbox.git
cd Trading-Bots-Sandbox
pip install -r requirements.txt

python backtests/run_backtest.py --config config/example.yaml
