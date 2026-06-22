<!-- https://github.com/anuraghazra/github-readme-stats -->
<p align="center">
  <a href="https://github.com/TranKimTin" rel="noopener noreferrer">
    <img src="https://github-readme-stats-js4w.vercel.app/api?username=TranKimTin&show_icons=true&show=reviews,discussions_started,discussions_answered,prs_merged&rank_icon=percentile&text_bold=false&include_all_commits=true&count_private=true&hide=html,css" width="49%" />
  </a>
  <a href="https://github.com/TranKimTin" rel="noopener noreferrer">
    <img src="https://github-readme-stats-js4w.vercel.app/api/top-langs/?username=TranKimTin&layout=compact&card_height=200&langs_count=8&count_private=true&hide=html,css" width="49%" />
  </a>
</p>

---

## Featured Personal Project: MyBotMaker

[![Live Website](https://img.shields.io/badge/Live_Website-mybotmaker.com-2563eb?style=flat-square)](https://mybotmaker.com)
[![GitHub](https://img.shields.io/badge/GitHub-MyBotMaker-181717?style=flat-square&logo=github)](https://github.com/TranKimTin/MyBotMaker)
![C++17](https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=cplusplus)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vue 3](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white)
![ANTLR4](https://img.shields.io/badge/ANTLR4-EA2C2C?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

MyBotMaker is my personal full-stack crypto trading bot platform for building,
backtesting, replaying, and running automated trading strategies — no coding required.

**Live:** [mybotmaker.com](https://mybotmaker.com) · **Code:** [github.com/TranKimTin/MyBotMaker](https://github.com/TranKimTin/MyBotMaker)

| Area | What I built |
|------|--------------|
| **Trading engine** | High-performance C++17 engine for strategy evaluation, indicator computation, multi-timeframe aggregation (1m→1w), and real order execution, optimized with a thread pool, memory pools and lock-minimized snapshots |
| **Strategy system** | Visual strategy-graph editor plus a custom expression DSL built on a single ANTLR4 grammar shared (codegen) across the C++ engine, Node backend and the browser — compiled to bytecode and run on a stack machine |
| **Backtesting & replay** | Deterministic historical backtesting on both server and in-browser **WebAssembly**, with PnL, drawdown, win-rate and blow-up detection; an order-replay/playback mode renders entries/TP/SL with live indicators recomputed via a WASM worker |
| **Charting** | Lightweight charts with indicator overlays, order markers, and TradingView-style drawing tools |
| **AI assistant** | Generates a bot config preview from a natural-language strategy description (LLM-backed, with heuristic fallback and per-account daily quota) |
| **Backend** | Node.js/Express + TypeScript + Socket.IO API: auth (JWT + Google OAuth + Turnstile), bot management, premium billing, support tickets, admin tools |
| **Market data** | A live recorder persists Binance spot/futures OHLCV into compact `.bin` files so the engine warm-starts from disk instead of hammering REST APIs; self-healing gap repair |
| **Frontend** | Vue 3 dashboard (PrimeVue + TailwindCSS + Cytoscape) for bot config, backtesting, charts, order history and account management, fully bilingual-ready with light/dark themes |

### Highlights

- Visual strategy-graph editor to build bot logic without writing code
- Generate a starter bot from plain language with an AI assistant
- Deterministic backtesting + order replay, in the browser via WebAssembly
- TradingView-style chart drawing tools and technical-indicator overlays
- Binance Futures, Bybit, OKX live WebSocket market data and Telegram notifications
- Google sign-in, Cloudflare Turnstile, scrypt password hashing, refresh-token sessions
- Bot sharing (public or per-email), bot templates and in-app guided tours
- Premium tiers (USDT-native), tier-based limits, support tickets, and admin tooling

