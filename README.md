### Hi, I'm Avinash: AI/ML engineer and team lead, 15+ years

I build production AI systems: **LLM agents, RAG, tool calling over MCP, and the evaluation that keeps them honest.**
Most recently I was technical lead on an agentic research assistant used by a financial firm: a LangGraph agent with
durable memory, models served as MCP tools and to Excel through a REST gateway, retrieval with citations, and CI-gated
evals, deployed with Docker on GCP. Before that, 15 years of applied ML: forecasting, ensembles and validation.

Everything here runs from a clone and is tested in CI. Client work is rebuilt on synthetic data with every client,
company and person name removed.

---

## Start here

| Project | Why it matters |
|---|---|
| **[ai-chatbot-from-scratch](https://github.com/Avinash186200/ai-chatbot-from-scratch)** | A complete AI assistant, end to end: React chat UI, LangGraph agent with Postgres memory, MCP tools, an Excel gateway, RAG with citations, an intent router, a vendor-neutral LLM adapter, evals, tracing and Docker. Includes a 12-step build guide |
| **[quant-research-agent](https://github.com/Avinash186200/quant-research-agent)** | A Claude agent and MCP server that audits code for look-ahead and selection bias, scored against a planted-bug eval suite |
| **[ai-engineering-from-scratch](https://github.com/Avinash186200/ai-engineering-from-scratch)** | Code for my free 50-episode YouTube course: LLMs, prompting, agents, MCP, RAG, evals, LLMOps, deployment, security and system design |
| **[script-to-video-engine](https://github.com/Avinash186200/script-to-video-engine)** | Generative tooling I built and use: a Python lesson script becomes a narrated video with captions, chapters, Shorts and thumbnails |

## What I work with

| Area | Tools and practice |
|---|---|
| LLM applications | LangGraph, MCP, tool calling, structured output, prompt and context engineering, Anthropic and OpenAI-compatible APIs |
| Retrieval | Chunking, embeddings, hybrid search, pgvector, citations, retrieval evals (recall@k, MRR) |
| Evaluation and safety | Golden sets, LLM-as-judge, CI eval gates, prompt-injection defences, guardrails |
| Production | FastAPI, SSE streaming, Docker, Nginx/TLS, GCP, PostgreSQL, OpenTelemetry, CI/CD |
| Machine learning | scikit-learn, gradient boosting, time-series forecasting, walk-forward and purged validation, multiple-testing control |

---

## Machine learning and research

Rigorous ML on financial data: every repo has an audit table of the biases I found (look-ahead, selection bias,
missing costs) and how I fixed them, and says so plainly when the honest answer was "no edge".

| Repository | What it is |
|---|---|
| [meta-labeling-trade-filter](https://github.com/Avinash186200/meta-labeling-trade-filter) | ML filter that scores each trade at entry; leak-free walk-forward and a FastAPI scoring service |
| [volatility-regime-ml](https://github.com/Avinash186200/volatility-regime-ml) | GARCH, HAR and regime models for volatility forecasting, with rolling QLIKE evaluation |
| [feature-factory](https://github.com/Avinash186200/feature-factory) | Feature generation and screening with a t-1 leakage guard, permutation tests and false-discovery control |
| [vol-etp-hedge-overlay](https://github.com/Avinash186200/vol-etp-hedge-overlay) | ML timing overlay; a look-ahead bug found and fixed, no edge after correction |
| [ecommerce-return-prediction](https://github.com/Avinash186200/ecommerce-return-prediction) | Predicts at order time whether an order line will be returned, using point-in-time features |
| [walk-forward-backtest-pipeline](https://github.com/Avinash186200/walk-forward-backtest-pipeline) | Walk-forward selection with nested threshold choice, a hold-out and selection-decay reporting |
| [emerging-market-feature-library](https://github.com/Avinash186200/emerging-market-feature-library) | Causal feature library for multi-index equity panels, with a timing-leak audit |

<details>
<summary><b>More: allocation, backtesting, data engineering and notebooks (11 repos)</b></summary>

| Repository | What it is |
|---|---|
| [intraday-market-data-pipeline](https://github.com/Avinash186200/intraday-market-data-pipeline) | 5-minute bar pipeline: parallel backfill, split detection, leak-free features, DuckDB/Parquet and QC |
| [drawdown-constrained-allocation](https://github.com/Avinash186200/drawdown-constrained-allocation) | Walk-forward allocator with a hard single-day loss cap |
| [vol-budgeted-model-allocation](https://github.com/Avinash186200/vol-budgeted-model-allocation) | Allocation across models under per-model, group and portfolio volatility budgets |
| [short-interest-gap-strategy](https://github.com/Avinash186200/short-interest-gap-strategy) | Gap strategy on FINRA short-interest data with a random-pick control |
| [fx-strategy-backtester](https://github.com/Avinash186200/fx-strategy-backtester) | FX rule backtester: next-bar fills, bid/ask costs, deflated Sharpe |
| [commodity-strategy-backtester](https://github.com/Avinash186200/commodity-strategy-backtester) | Commodity rule backtester with walk-forward selection |
| [trading-algorithm-backtester](https://github.com/Avinash186200/trading-algorithm-backtester) | RF, SVM, MLP and logistic trade filters on a time split |
| [trailing-stop-loss-study](https://github.com/Avinash186200/trailing-stop-loss-study) | ATR trailing-stop overlay with an out-of-sample check |
| [ml-model-building-workflow](https://github.com/Avinash186200/ml-model-building-workflow) | Feature engineering, point-in-time merge, train-only scaling, clustering |
| [portfolio-metrics-quantstats](https://github.com/Avinash186200/portfolio-metrics-quantstats) | Daily P&L, correlation and QuantStats tear sheets |
| [market-data-and-volatility-notebooks](https://github.com/Avinash186200/market-data-and-volatility-notebooks) | Correlation, implied volatility, resampling and momentum notebooks |

</details>

---

**How these repos are built:** maintained code with tests and CI, a `docs/` folder with the method and a walkthrough,
and where it applies an `original/` folder with the code as I first wrote it, sanitised, so you can compare the two.

**Open to:** AI/ML engineering and AI engineering lead roles, remote or Delhi NCR.

📍 Delhi NCR, India · [LinkedIn](https://www.linkedin.com/in/avinash-mishra-b97b3236) ·
[YouTube: AI Engineering from Scratch](https://www.youtube.com/playlist?list=PLKRdiVI5CiMg)
