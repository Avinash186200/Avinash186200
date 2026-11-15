### Hi, I'm Avinash: AI/ML engineering leader, 15+ years

I build production AI systems: LLM agents, RAG pipelines, tool-calling architectures, and the machine learning
underneath them. Recently I've moved deep into **GenAI and agentic AI** (LangGraph, MCP, retrieval, evals), on top of
15 years of applied ML and quantitative research (forecasting, ensembles, statistical validation).

Everything below is public, runs from a clone, and is tested in CI. Client work has been rebuilt on synthetic data
with every client, company and person name removed.

---

## AI engineering

| Repository | What it is |
|---|---|
| [ai-engineering-from-scratch](https://github.com/Avinash186200/ai-engineering-from-scratch) | Code for my free YouTube course: LLMs, prompting, LangGraph agents, MCP, RAG, evals, production, system design, plus a 10-question interview special |
| [ai-chatbot-from-scratch](https://github.com/Avinash186200/ai-chatbot-from-scratch) | Build an AI analytics chatbot from scratch: React chat UI, LangGraph agent, MCP tools, Excel gateway, RAG with citations, evals and Docker, with a 12-step build guide |
| [quant-research-agent](https://github.com/Avinash186200/quant-research-agent) | A Claude agent and MCP server that audits trading strategies for look-ahead and selection bias, with a planted-bug eval suite |
| [script-to-video-engine](https://github.com/Avinash186200/script-to-video-engine) | Turns a Python lesson script into a narrated video with captions and chapters, a vertical Short and thumbnails. It produced every video in my course |

## Quantitative research and backtesting

| Repository | What it is |
|---|---|
| [meta-labeling-trade-filter](https://github.com/Avinash186200/meta-labeling-trade-filter) | Meta-labeling filter that scores each trade at entry and skips the weakest; leak-free walk-forward, FastAPI scoring |
| [vol-etp-hedge-overlay](https://github.com/Avinash186200/vol-etp-hedge-overlay) | ML timing overlay on an equity / volatility-ETP book; look-ahead bias found and fixed, no edge after correction |
| [drawdown-constrained-allocation](https://github.com/Avinash186200/drawdown-constrained-allocation) | Walk-forward allocator across a book of strategies with a hard single-day loss cap |
| [vol-budgeted-model-allocation](https://github.com/Avinash186200/vol-budgeted-model-allocation) | Allocation across trading models under per-model, group and portfolio volatility budgets |
| [walk-forward-backtest-pipeline](https://github.com/Avinash186200/walk-forward-backtest-pipeline) | Five-step walk-forward selection with a nested threshold choice, a hold-out and selection-decay reporting |
| [short-interest-gap-strategy](https://github.com/Avinash186200/short-interest-gap-strategy) | Intraday gap strategy on FINRA short-interest data with a random-pick control and an honest no-edge verdict |
| [fx-strategy-backtester](https://github.com/Avinash186200/fx-strategy-backtester) | Daily FX rule backtester: next-bar fills, bid/ask costs, walk-forward selection, deflated Sharpe |
| [commodity-strategy-backtester](https://github.com/Avinash186200/commodity-strategy-backtester) | Daily rule-strategy backtester for commodities with walk-forward selection and a leakage audit |
| [trading-algorithm-backtester](https://github.com/Avinash186200/trading-algorithm-backtester) | Time-split backtest of RF, SVM, MLP and logistic classifiers that filter base-strategy trades |
| [trailing-stop-loss-study](https://github.com/Avinash186200/trailing-stop-loss-study) | ATR trailing stop overlay with gap-through fills and a grid search checked once out of sample |
| [volatility-regime-ml](https://github.com/Avinash186200/volatility-regime-ml) | Volatility forecasting and regime classification with leak-free, rolling evaluation |
| [feature-factory](https://github.com/Avinash186200/feature-factory) | Feature generation and screening with a t-1 leakage guard, permutation tests and false-discovery control |
| [emerging-market-feature-library](https://github.com/Avinash186200/emerging-market-feature-library) | Causal feature library for multi-index equity panels, with a timing-leak audit |

## Data engineering

| Repository | What it is |
|---|---|
| [intraday-market-data-pipeline](https://github.com/Avinash186200/intraday-market-data-pipeline) | 5-minute bar pipeline: parallel backfill, weekly refresh with split detection, leak-free features, DuckDB/Parquet and QC |

## Machine learning and research notebooks

| Repository | What it is |
|---|---|
| [ecommerce-return-prediction](https://github.com/Avinash186200/ecommerce-return-prediction) | Predicts at order time whether an order line will be returned, using point-in-time features |
| [ml-model-building-workflow](https://github.com/Avinash186200/ml-model-building-workflow) | Feature engineering, point-in-time merge, train-only scaling, regime clusters and a baseline classifier |
| [portfolio-metrics-quantstats](https://github.com/Avinash186200/portfolio-metrics-quantstats) | Trade-level P&L to daily returns, pairwise correlation and QuantStats tear sheets |
| [market-data-and-volatility-notebooks](https://github.com/Avinash186200/market-data-and-volatility-notebooks) | Cross-asset correlation, implied volatility, bar resampling and momentum notebooks |

---

**How these repos are built.** Each one has the maintained code, tests and CI, a `docs/` folder with the method, and
an audit table of every bias I found (look-ahead, selection bias, missing costs) with its fix. Where it applies,
`original/` holds the code as I first wrote it, sanitised, so you can compare the two. Results come from synthetic
data unless clearly labelled otherwise; when the honest answer was "no edge", the README says so.

**What I work with:** Python · LangGraph / LangChain · MCP · RAG and vector search · FastAPI · Docker · GCP ·
PostgreSQL · scikit-learn · walk-forward validation · CI-gated evals.

**Open to:** AI/ML engineering roles, remote or Delhi NCR.

📍 Delhi NCR, India · [LinkedIn](https://www.linkedin.com/in/avinash-mishra-b97b3236) ·
[YouTube course](https://www.youtube.com/playlist?list=PLKRdiVI5CiMg)
