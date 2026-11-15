### Hi, I'm Avinash Mishra: AI & ML engineer and team lead, 15+ years

I build machine learning and AI systems that hold up in production. **On the ML side:** 15 years of forecasting,
classification, ensembles and time-series models, with validation strict enough to catch look-ahead and selection
bias before it reaches a result. **On the AI side:** LLM agents, RAG, tool calling over MCP, and the evals that keep
them honest.

Most recently I was technical lead on an agentic research assistant for a financial firm: our own quantitative models
served as MCP tools and to Excel through a REST gateway, a LangGraph agent with durable memory, retrieval with
citations, and CI-gated evals, deployed with Docker on GCP.

These are projects I have worked on over 15 years, across machine learning, quantitative research and AI.

---

## Start here

**AI engineering**

| Project | What it shows |
|---|---|
| **[ai-chatbot-from-scratch](https://github.com/Avinash186200/ai-chatbot-from-scratch)** | A complete AI assistant, end to end: React chat UI, LangGraph agent with Postgres memory, MCP tools, an Excel gateway, RAG with citations, an intent router, a vendor-neutral LLM adapter, evals, tracing and Docker. Includes a 12-step build guide |
| **[quant-research-agent](https://github.com/Avinash186200/quant-research-agent)** | An LLM agent and MCP server that audits model code for look-ahead and selection bias, scored against a planted-bug eval suite |
| **[ai-engineering-from-scratch](https://github.com/Avinash186200/ai-engineering-from-scratch)** | Code for my free 50-episode YouTube course: LLMs, prompting, agents, MCP, RAG, evals, LLMOps, deployment, security and system design |

**Machine learning**

| Project | What it shows |
|---|---|
| **[meta-labeling-trade-filter](https://github.com/Avinash186200/meta-labeling-trade-filter)** | A second-stage ML model that scores each trade at entry, leak-free walk-forward training, and a FastAPI scoring service |
| **[volatility-regime-ml](https://github.com/Avinash186200/volatility-regime-ml)** | GARCH, HAR and regime-classifier forecasts compared on a rolling, leak-free QLIKE evaluation |
| **[feature-factory](https://github.com/Avinash186200/feature-factory)** | Feature generation and screening with a leakage guard, permutation tests and false-discovery control |
| **[ecommerce-return-prediction](https://github.com/Avinash186200/ecommerce-return-prediction)** | Classic classification end to end: point-in-time features, label lag, calibrated predictions at order time |

## What I work with

| Area | Tools and practice |
|---|---|
| LLM applications | LangGraph, MCP, tool calling, structured output, prompt and context engineering, Anthropic and OpenAI-compatible APIs |
| Retrieval | Chunking, embeddings, hybrid search, pgvector, citations, retrieval evals (recall@k, MRR) |
| Evaluation and safety | Golden sets, LLM-as-judge, CI eval gates, prompt-injection defences, guardrails |
| Production | FastAPI, SSE streaming, Docker, Nginx/TLS, GCP, PostgreSQL, OpenTelemetry, CI/CD |
| Machine learning | scikit-learn, gradient boosting, random forests, neural networks, time-series forecasting (GARCH, HAR), feature engineering, clustering |
| ML validation | Walk-forward and purged cross-validation, hold-outs, deflated Sharpe, permutation tests, false-discovery control, leakage audits |

---

## More machine learning and research

Every repo has an audit table of the biases I found (look-ahead, selection bias, missing costs) and how I fixed them,
and says so plainly when the honest answer was "no signal".

| Repository | What it is |
|---|---|
| [vol-etp-hedge-overlay](https://github.com/Avinash186200/vol-etp-hedge-overlay) | ML timing model; a label-overlap leak found and fixed, no edge after correction |
| [trading-algorithm-backtester](https://github.com/Avinash186200/trading-algorithm-backtester) | Random forest, SVM, MLP and logistic classifiers compared on a strict time split, with costs |
| [ml-model-building-workflow](https://github.com/Avinash186200/ml-model-building-workflow) | Feature engineering, point-in-time merge, train-only scaling, regime clustering and a baseline classifier |
| [walk-forward-backtest-pipeline](https://github.com/Avinash186200/walk-forward-backtest-pipeline) | Model selection with nested walk-forward, a hold-out and selection-decay reporting |
| [emerging-market-feature-library](https://github.com/Avinash186200/emerging-market-feature-library) | Causal feature library for multi-index panels, with a timing-leak audit |
| [intraday-market-data-pipeline](https://github.com/Avinash186200/intraday-market-data-pipeline) | Data pipeline for model inputs: parallel backfill, split detection, leak-free features, DuckDB/Parquet and QC |
| [script-to-video-engine](https://github.com/Avinash186200/script-to-video-engine) | Generative tooling I built for my course: a lesson script becomes a narrated video, Shorts and thumbnails |

<details>
<summary><b>Portfolio allocation, strategy research and notebooks (8 repos)</b></summary>

| Repository | What it is |
|---|---|
| [drawdown-constrained-allocation](https://github.com/Avinash186200/drawdown-constrained-allocation) | Walk-forward allocator with a hard single-day loss cap |
| [vol-budgeted-model-allocation](https://github.com/Avinash186200/vol-budgeted-model-allocation) | Allocation across models under per-model, group and portfolio volatility budgets |
| [short-interest-gap-strategy](https://github.com/Avinash186200/short-interest-gap-strategy) | Gap strategy on FINRA short-interest data with a random-pick control |
| [fx-strategy-backtester](https://github.com/Avinash186200/fx-strategy-backtester) | FX rule backtester: next-bar fills, bid/ask costs, deflated Sharpe |
| [commodity-strategy-backtester](https://github.com/Avinash186200/commodity-strategy-backtester) | Commodity rule backtester with walk-forward selection |
| [trailing-stop-loss-study](https://github.com/Avinash186200/trailing-stop-loss-study) | ATR trailing-stop overlay with an out-of-sample check |
| [portfolio-metrics-quantstats](https://github.com/Avinash186200/portfolio-metrics-quantstats) | Daily P&L, correlation and QuantStats tear sheets |
| [market-data-and-volatility-notebooks](https://github.com/Avinash186200/market-data-and-volatility-notebooks) | Correlation, implied volatility, resampling and momentum notebooks |

</details>

---

**How these repos are organised:** code with tests, a `docs/` folder with the method and a walkthrough, and where it
applies an `original/` folder with the code as I first wrote it, so you can see how it evolved.

**Open to:** AI engineering, ML engineering and AI/ML lead roles, remote or Delhi NCR.

📍 Delhi NCR, India · [LinkedIn](https://www.linkedin.com/in/avinash-mishra-b97b3236) ·
[YouTube: AI Engineering from Scratch](https://www.youtube.com/playlist?list=PLKRdiVI5CiMg)
