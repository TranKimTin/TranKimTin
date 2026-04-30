<!-- https://github.com/anuraghazra/github-readme-stats -->
<p align="center">
  <a href="https://github.com/TranKimTin" rel="noopener noreferrer">
    <img src="https://github-readme-stats.vercel.app/api?username=TranKimTin&show_icons=true&show=reviews,discussions_started,discussions_answered,prs_merged&rank_icon=percentile&text_bold=false&include_all_commits=false&count_private=true" width="49%" />
  </a>
  <a href="https://github.com/TranKimTin" rel="noopener noreferrer">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TranKimTin&layout=compact&card_height=200&langs_count=8" width="49%" />
  </a>
</p>

---

## 🚀 Personal Projects

### 📈 [MyBotMaker](https://mybotmaker.com/)

> **A high-performance crypto trading bot framework — connect, automate, and manage trading strategies across multiple exchanges.**

**MyBotMaker** ([mybotmaker.com](https://mybotmaker.com/)) is a personal SaaS product I designed and built from scratch. It provides a full-stack platform for running automated crypto trading bots across exchanges like Binance Futures, Bybit, and OKX, combining a C++ execution core with a modern web UI and Telegram integration.

**✨ Key Features:**
- 🔄 **Multi-exchange Support** — Connect to Binance Futures, Bybit, OKX Spot and more via WebSocket for real-time market data
- 🎨 **Visual Strategy Builder** — Design trading strategies as a DAG (directed acyclic graph) using a drag-and-drop node editor (Cytoscape); no code required
- 🤖 **Automated Trading Strategies** — Define and run strategies using an expression DSL supporting arithmetic, comparison, and logical operators (`&&`, `||`)
- 📊 **Order Chart & Backtest Viewer** — Visualize historical trades with entry/TP/SL/close markers and indicator overlays (EMA, etc.)
- ⏪ **Backtesting Engine** — Replay historical candle data to simulate strategies with full PnL, drawdown, and win-rate reporting
- 🔔 **Telegram Notifications** — Receive real-time trade alerts and control bots via Telegram bot with button support
- 🧠 **AI Bot Config Generator** — Describe your strategy in natural language and get a bot config preview powered by an LLM (OpenAI-compatible, Premium feature)
- 🔐 **Account & Subscription System** — Free and Premium tiers with configurable bot-count limits, symbol access, and daily AI usage quotas
- 👥 **Shared Bot History** — Share bot trade history publicly or with specific accounts; browse bots shared with you via a sidebar
- 🧮 **Calculator API** — Evaluate indicator expressions at any timestamp via a C++ runtime (e.g. `close(0) > ema(20,0)`)
- 💰 **Deposit & Balance Accounting** — USDT-native balance tracking with deposit submission and TX hash verification
- ⚡ **Rate Server** — Dedicated OHLCV cache service (Redis-backed) that can run on a separate machine to avoid exchange rate limits

**🔧 Tech Stack:** C++ (core engine) · Node.js · TypeScript · MySQL · Redis · WebSocket · Telegram Bot API · OpenAI API · Nginx

**🌐 Live:** [https://mybotmaker.com](https://mybotmaker.com/)
