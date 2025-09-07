# 🌍 OpenDefiBot — Free & Open Source Crypto Trading Framework

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg) ![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-blue.svg)

---
## Why it exists

Most trading bots you find online are either scams, hidden behind paywalls, or so complex that beginners give up.  
This project is different: **it’s free, open, and simple enough to start learning right away.**

The goal is to give you a real framework you can play with.  
It’s not magic. It won’t make you rich overnight. But it will help you **learn by doing** — and maybe find your own trading edge.

---
## ✨ Features

- **Easy to extend** → plug in your own strategies.  
- **Examples included** → EMA crossover, simple arbitrage check.  
- **Multi-exchange support** → Binance, Coinbase, Uniswap.  
- **Basic risk tools** → position sizing, stop-loss.  
- **Backtester** → try your ideas on past data before going live.

---
## 🔧 Requirements

- Python 3.10+  
- Dependencies (installed with `requirements.txt`):  
  - `ccxt` (exchange connections)  
  - `web3` (Ethereum/DeFi interactions)  

---
## 🚀 Quickstart

1. **Get the code**

    ```bash
    git clone https://github.com/MattFox613/opendifibot.git
    cd opendifibot
    ```

2. **Install requirements**

    ```bash
    pip install -r requirements.txt
    ```

3. **Run an example**

    ```bash
    python run.py --exchange binance --strategy ema_crossover
    ```

---
## 📸 Example Run

```
[2025-09-06 12:42:01] Connected to Binance  
[2025-09-06 12:42:03] Running EMA crossover on BTC/USDT...  
[2025-09-06 12:43:15] Trade executed: BUY 0.01 BTC at 99,250  
```

---
## 📂 Project Structure

```
opendifibot/  
├── strategies/       # Example trading strategies  
├── exchanges/        # Exchange API connectors  
├── backtester/       # Historical data simulator  
├── utils/            # Helpers & risk management tools  
├── tests/            # Unit tests for strategies & components  
├── run.py            # Main entry point  
└── requirements.txt  
```

---
## ⚠️ Disclaimer

This bot is for **learning and experimenting only**.  
Trading is risky — never use money you can’t afford to lose.

---
## 🤝 Contributing

Pull requests are welcome!  
Add your strategy under `strategies/`, update the docs, and open a PR.

---
## 📜 License

MIT — free to use, modify, and share.

---
## 🌱 Vision

I want to empower people by giving away something real, useful, and free.  
If this project helps you learn, trade smarter, or even just get inspired — then it’s already a success.
