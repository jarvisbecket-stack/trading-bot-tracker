# Trading Bot Dashboard

Live dashboard for the AI-powered trading bot using Trend Momentum Strategy.

## 🎯 Strategy: TrendMomentum_EMA_RSI

Combines trend following (EMA crossover) with momentum indicators (RSI) for stock trading.

**Parameters:**
- EMA Fast: 9 periods
- EMA Slow: 21 periods
- RSI Period: 14
- Stop Loss: 2%
- Take Profit: 6%

## 📊 Dashboard

**Live Dashboard:** https://jarvisbecket-stack.github.io/trading-bot-tracker/

## 🔌 API Integrations

| API | Status | Purpose |
|-----|--------|---------|
| Tradier | ✅ Connected | Stock/options trading execution |
| Finnhub | ✅ Connected | Real-time market data |
| Claude | ✅ Connected | Strategy analysis |

## 📈 Performance Tracking

| Metric | Value |
|--------|-------|
| Win Rate | -- |
| Profit Factor | -- |
| Max Drawdown | -- |
| Total Trades | 0 |

## 📝 Trade Log

| Date | Symbol | Action | Entry | Exit | P&L | Status |
|------|--------|--------|-------|------|-----|--------|
| -- | -- | -- | -- | -- | -- | Awaiting signals |

## 🚀 Getting Started

### Run Bot Locally
```bash
cd trading-bot
python3 trading_bot.py
```

### Test APIs
```bash
python3 test_bot_simple.py
```

## 📚 Documentation

- [API Inventory](API_INVENTORY.md) - All API keys and endpoints
- [Video Analysis](VIDEO_ANALYSIS.md) - Strategy insights from tutorial
- [Source Code](trading_bot.py) - Full trading bot implementation

## ⚠️ Important

This bot is currently running in **PAPER TRADING MODE**. No real money is at risk.

---

**Built for:** Ricardo Davila  
**Last Updated:** 2026-02-26

[View Source on GitHub](https://github.com/jarvisbecket-stack/trading-bot-tracker)
