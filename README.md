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
| **[llm-serving-patterns](https://github.com/Avinash186200/llm-serving-patterns)** | Semantic cache, model router, conversation memory and a resilience layer, each benchmarked: hit rate vs wrong answers, cost vs task success, tokens vs recall |
| **[rag-evaluation-benchmark](https://github.com/Avinash186200/rag-evaluation-benchmark)** | Chunking, BM25 vs dense vs hybrid retrieval, cross-encoder reranking and abstention, measured on a labelled question set with hard cases |
| **[llm-release-playbook](https://github.com/Avinash186200/llm-release-playbook)** | How I release LLM apps safely: release standard, go/no-go and rollout checklists, eval and incident playbooks, metrics spec, and a release-gate tool |
| **[llm-finetuning-lora](https://github.com/Avinash186200/llm-finetuning-lora)** | LoRA fine-tuning compared with zero-shot and few-shot prompting on a strict-JSON extraction task: validity, exact match, latency, rank ablation, seeds, and where fine-tuning stops generalising |
| **[speech-to-signal](https://github.com/Avinash186200/speech-to-signal)** | Central-bank speech to a hawkish/dovish signal: Whisper transcription, four stance classifiers (lexicon, TF-IDF, fine-tuned FinBERT, LLM adapter) on a leak-free test set, and a backtest showing how latency eats the edge |
| **[ai-engineering-from-scratch](https://github.com/Avinash186200/ai-engineering-from-scratch)** | Code for my free 50-episode YouTube course: LLMs, prompting, agents, MCP, RAG, evals, LLMOps, deployment, security and system design |
| | New in the course: [system designs](https://github.com/Avinash186200/ai-engineering-from-scratch/tree/main/system_design) (8, four of them ML), [lessons learned](https://github.com/Avinash186200/ai-engineering-from-scratch/tree/main/lessons_learned) (10), an [interview bank](https://github.com/Avinash186200/ai-engineering-from-scratch/tree/main/interview_bank) with 371 flashcards, an [agent testing day](https://github.com/Avinash186200/ai-engineering-from-scratch/tree/main/day18_agent_testing), a [deployment skills day](https://github.com/Avinash186200/ai-engineering-from-scratch/tree/main/day19_deploy_skill), and [how architecture evolves](https://github.com/Avinash186200/ai-engineering-from-scratch/tree/main/arch_evolution) |

**Machine learning**

| Project | What it shows |
|---|---|
| **[mlops-model-lifecycle](https://github.com/Avinash186200/mlops-model-lifecycle)** | A churn model through its whole life: data checks, model cards, a registry with promotion gates and rollback, a scoring API, drift monitoring and an 18-month test of retraining policies |
| **[meta-labeling-trade-filter](https://github.com/Avinash186200/meta-labeling-trade-filter)** | A second-stage ML model that scores each trade at entry, leak-free walk-forward training, and a FastAPI scoring service |
| **[volatility-regime-ml](https://github.com/Avinash186200/volatility-regime-ml)** | GARCH, HAR and regime-conditional HAR forecasts compared on a rolling, leak-free QLIKE evaluation |
| **[feature-factory](https://github.com/Avinash186200/feature-factory)** | Feature generation and screening with a leakage guard, permutation tests and false-discovery control |
| **[ecommerce-return-prediction](https://github.com/Avinash186200/ecommerce-return-prediction)** | Classic classification end to end: point-in-time features, label lag, calibrated predictions at order time |
| **[clustered-feature-importance](https://github.com/Avinash186200/clustered-feature-importance)** | MDI, permutation, SHAP, drop-column and clustered importance scored against known ground truth under correlated features, with parallel permutation and a downstream selection test |
| **[well-log-production-ml](https://github.com/Avinash186200/well-log-production-ml)** | Ranking planned wells by early production from well logs: a data-readiness audit, LightGBM Tweedie, and how much random CV overstates results compared with spatial and leave-one-field-out CV |

## What I work with

| Area | Tools and practice |
|---|---|
| LLM applications | LoRA/PEFT fine-tuning, LangGraph, MCP, tool calling, structured output, prompt and context engineering, Anthropic and OpenAI-compatible APIs |
| Retrieval | Chunking, embeddings, hybrid search, pgvector, citations, retrieval evals (recall@k, MRR) |
| Evaluation and safety | Golden sets, LLM-as-judge, CI eval gates, prompt-injection defences, guardrails |
| Production | MLOps (model registry, promotion gates, drift monitoring, retraining), FastAPI, SSE streaming, Docker, Nginx/TLS, GCP, PostgreSQL, OpenTelemetry, CI/CD |
| Machine learning | scikit-learn, gradient boosting, random forests, neural networks, time-series forecasting (GARCH, HAR), feature engineering, clustering |
| ML validation | Walk-forward and purged cross-validation, hold-outs, deflated Sharpe, permutation tests, false-discovery control, leakage audits |

---

## More ML and AI

| Repository | What it is |
|---|---|
| [ml-model-building-workflow](https://github.com/Avinash186200/ml-model-building-workflow) | Feature engineering, point-in-time merge, train-only scaling, clustering and a baseline classifier |
| [trading-algorithm-backtester](https://github.com/Avinash186200/trading-algorithm-backtester) | Random forest, SVM, MLP and logistic classifiers compared on a strict time split |
| [intraday-market-data-pipeline](https://github.com/Avinash186200/intraday-market-data-pipeline) | Data pipeline for model inputs: parallel backfill, quality checks, leak-free features, DuckDB/Parquet |
| [security-master-resolver](https://github.com/Avinash186200/security-master-resolver) | Entity resolution for a point-in-time security master: IDs, names and price continuity linked with union-find across renames, mergers, spin-offs and relistings |
| [realtime-signal-broker](https://github.com/Avinash186200/realtime-signal-broker) | WebSocket broker with JWT auth, per-topic sequence numbers and replay from Redis Streams or SQLite; fault-injection tests prove gap-free, duplicate-free delivery |
| [job-application-tracker](https://github.com/Avinash186200/job-application-tracker) | A small CLI to track job applications: SQLite store, de-duplication, status pipeline, follow-ups and a weekly response-rate report |
| [script-to-video-engine](https://github.com/Avinash186200/script-to-video-engine) | Generative tooling I built for my course: a lesson script becomes a narrated video, Shorts and thumbnails |
| [docker-from-scratch](https://github.com/Avinash186200/docker-from-scratch) | Docker end to end: 18 chapters from basics to internals, 8 labs, 78 interview questions, a real disk-full incident, and a tested Dockerfile linter |

## Earlier ML work (2020 to 2021)

The first versions of my ML work, with their original commit history. Each README says what I would do differently
today and links to the maintained version.

| Repository | Year | What it is |
|---|---|---|
| [ml-trading-classifiers-2020](https://github.com/Avinash186200/ml-trading-classifiers-2020) | 2020 | Random forest, SVM and neural-network classifiers scoring signals, with feature importance |
| [ml-feature-engineering-pipeline-2020](https://github.com/Avinash186200/ml-feature-engineering-pipeline-2020) | 2020 | Feature pipeline: indicators, label merge, standardisation, K-means clustering, feature importance |
| [ecommerce-returns-ml-2021](https://github.com/Avinash186200/ecommerce-returns-ml-2021) | 2021 | Predicting online order returns with a random forest and a small neural network |

<details>
<summary><b>Quantitative research (15 repos)</b></summary>

Each has an audit table of the biases I found (look-ahead, selection bias, missing costs) and how I fixed them.

| Repository | What it is |
|---|---|
| [vol-etp-hedge-overlay](https://github.com/Avinash186200/vol-etp-hedge-overlay) | ML timing model; a label-overlap leak found and fixed, no edge after correction |
| [walk-forward-backtest-pipeline](https://github.com/Avinash186200/walk-forward-backtest-pipeline) | Model selection with nested walk-forward, a hold-out and selection-decay reporting |
| [emerging-market-feature-library](https://github.com/Avinash186200/emerging-market-feature-library) | Causal feature library for multi-index panels, with a timing-leak audit |
| [drawdown-constrained-allocation](https://github.com/Avinash186200/drawdown-constrained-allocation) | Walk-forward allocator with a hard single-day loss cap |
| [vol-budgeted-model-allocation](https://github.com/Avinash186200/vol-budgeted-model-allocation) | Allocation across models under per-model, group and portfolio volatility budgets, plus a non-ML minimum-variance follow-up that shows the caps remove its edge, and an ML method selector tested on 10 untouched seeds with a no-regime control |
| [batch-copula-fitting-jax](https://github.com/Avinash186200/batch-copula-fitting-jax) | Thousands of bivariate copulas fitted at once with JAX: parameter recovery, AIC family selection, tail dependence, and a stress test where a Gaussian fit understates joint crashes |
| [target-to-book-simulator](https://github.com/Avinash186200/target-to-book-simulator) | How much of a model's paper return survives into a real book after mandate limits, vol cap, costs, carry and rebalance timing, attributed step by step over 10 held-out seeds |
| [trade-signing-and-vpin-lab](https://github.com/Avinash186200/trade-signing-and-vpin-lab) | Trade-signing rules scored against known ground truth, and whether VPIN warns of informed trading (it lags rather than leads), with a no-signal control |
| [lob-tick-model-lowlatency](https://github.com/Avinash186200/lob-tick-model-lowlatency) | Order-book move model with microsecond compiled inference, and a fill-aware backtest showing the mid-price edge disappears after queue position and fees |
| [short-interest-gap-strategy](https://github.com/Avinash186200/short-interest-gap-strategy) | Gap strategy on short-interest data with a random-pick control |
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
