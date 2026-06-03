# Bijan Pourriahi

**Senior Backend / Platform Engineer**  
Rust · Python · Rails · Kubernetes · Trading Infrastructure · Data Systems · Automation

I build backend and systems software for data-heavy, automation-heavy domains: trading infrastructure, market-data pipelines, simulation engines, research platforms, internal tools, and real-time execution systems.

My work focuses on systems that need to be reproducible, inspectable, replayable, and operationally useful: ingestion pipelines, strategy runtimes, backtesting engines, event matching, execution tooling, evidence capture, and infrastructure for turning raw data into decisions.

Previously built automated trading infrastructure for a hedge fund, including large-scale strategy backtesting, analytics, automated strategy selection, dashboards, and cloud operations. Current work is focused on QuantBox: Rust/Python infrastructure for systematic trading research, prediction-market analytics, market ingestion, simulation, and runtime systems.

## Trading Platform Work

I built an internal futures trading workstation for managing multiple funded-style accounts from one operator surface. The system combined execution, copy trading, risk controls, account fan-out, strategy dispatch, live state monitoring, and research workflows.

Key capabilities:

- Managed 10 accounts simultaneously from a single execution and monitoring UI
- Copy-traded orders across account groups with per-account position, balance, drawdown, and guardrail visibility
- Ran hundreds of strategy variants across live and replay workflows
- Backtested thousands of strategy/day/configuration combinations with sortable strategy comparison views
- Supported real-time backtesting, live dispatch review, account health checks, kill switches, flatten/cancel controls, and operator explanations for each action

![Trading fleet dashboard](./assets/trading-fleet-dashboard.png)

![Strategy explorer](./assets/strategy-explorer.png)

![Live execution dashboard](./assets/live-execution-dashboard.png)

![Mobile control surface](./assets/mobile-control-surface.png)

## Featured Engineering Work

### [QuantBox / Aikido Systematic Trading](https://github.com/bijmaxx/aikido-systematic-trading)

Rust-first research, simulation, runtime, and evidence platform for systematic trading.

**Focus areas:**

- Strategy simulation and evaluation
- Reproducible research pipelines
- Runtime architecture
- Evidence capture
- Risk and drawdown logic
- Market-data infrastructure

### [Polymarket Weather Research](https://github.com/bijmaxx/polymarket-weather-research)

Paper-trading research engine for prediction markets with market ingestion, signal evaluation, and experiment tracking.

**Focus areas:**

- Market ingestion
- Signal evaluation
- Paper-trading research
- Experiment tracking
- Replayable analysis

### [Polymarket Trader Intelligence](https://github.com/bijmaxx/polymarket-trader-intelligence)

CLI toolkit for wallet alerts, replayable market analysis, SQLite storage, and trader profile intelligence.

**Focus areas:**

- Wallet intelligence
- Trader behavior analysis
- Replayable event storage
- CLI tooling
- SQLite-backed local research workflows

### [Matching System](https://github.com/bijmaxx/matching-system)

Explainable event-matching system for cross-platform prediction-market analysis.

**Focus areas:**

- Event matching
- Cross-platform market analysis
- Explainable matching logic
- Data normalization
- Research tooling

### [Vector Backtester](https://github.com/bijmaxx/vector-backtester)

ClickHouse-backed cryptocurrency strategy backtester using SQL-native vectorized execution.

**Focus areas:**

- Vectorized backtesting
- ClickHouse analytics
- SQL-native strategy research
- Market-data storage
- High-volume strategy evaluation

### [Prediction Market Oracle Timing Research](https://github.com/bijmaxx/polymarket-oracle-bot)

Prototype for studying oracle-lag timing, market behavior, and automated execution workflows.

## Core Engineering Areas

- Backend architecture
- Rust/Python systems engineering
- Trading infrastructure
- Market-data ingestion and normalization
- Simulation and backtesting engines
- Data pipelines and replayable workflows
- PostgreSQL, ClickHouse, SQLite
- Kubernetes, Docker, Linux, AWS
- CLI tools and internal platforms
- Automation and AI-assisted workflows

## Stack

**Languages:** Rust, Python, Ruby, Go, TypeScript, SQL  
**Backend:** Rails, FastAPI, APIs, WebSockets, background jobs, CLI systems  
**Data:** PostgreSQL, ClickHouse, SQLite, ETL, event logs, market-data pipelines  
**Infrastructure:** Kubernetes, Docker, AWS, Linux, Ansible, CI/CD, Grafana  
**Domains:** Trading systems, prediction markets, research infrastructure, automation, analytics

## Contact

- Email: bijan.pourriahi@gmail.com
