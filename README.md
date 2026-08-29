# Hi, I'm Rost

**Quantitative developer and R&D engineer building reproducible benchmark tooling, trading research platforms, and production-oriented market infrastructure.**

I work at the intersection of financial time series, algorithmic trading, public benchmarking, high-performance C++/Python systems, MetaTrader/MQL5 integration, and operational automation. My focus is not only to find signals, but to build systems that can be tested, reproduced, monitored, and challenged honestly.

## Current R&D Highlight: ClaimBound Public Benchmarks

**[claimbound-public-benchmarks](https://github.com/NeoZorK/claimbound-public-benchmarks)** is my newest public R&D result: an open-source foreground for pre-registered public time-series evaluation.

The repository is designed around reproducibility discipline:

- source eligibility is checked before a real run;
- targets, scorers, controls, and acceptance gates are fixed before execution;
- raw public-source payloads stay outside the repository;
- committed artifacts contain commands, hashes, summaries, and claim boundaries;
- negative and blocked outcomes are treated as valid evidence, not hidden failures.

Current public evidence is intentionally narrow and honest:

> NASA POWER D-103 passed the pre-registered gate under protocol `1.0.143` and was independently reproduced at outcome/gate level on `2026-04-29`.

That does **not** claim universal forecasting edge, deployment readiness, or superiority over all statistical methods. The value of the project is the public evaluation workflow itself: pre-registration, source-lineage discipline, baseline comparison, reproducible summaries, and explicit limits on what the result is allowed to mean.

## What I Build

- **Research-to-production trading systems**: from idea, data ingestion, features, and validation to APIs, dashboards, execution adapters, monitoring, and operations.
- **Robust validation frameworks**: walk-forward testing, Monte Carlo stress checks, out-of-sample discipline, benchmark gates, and evidence summaries.
- **High-performance market infrastructure**: C++ engines, Python orchestration, GPU/Apple Silicon acceleration experiments, async services, and cross-platform build/test flows.
- **MetaTrader and MQL5 tooling**: indicators, expert-advisor architecture, thin clients, WebRequest/API bridges, and parity checks against external services.
- **Risk-first automation**: shadow/simulation modes, certification gates, API-key handling, operational smoke checks, and fail-fast safety controls.
- **Developer productivity tooling**: CLI/TUI tools, Docker workflows, CI-ready test suites, documentation systems, and operator guides.

## Public Projects

### [claimbound-public-benchmarks](https://github.com/NeoZorK/claimbound-public-benchmarks)

Open benchmark foreground for public time-series evaluation. The project demonstrates how I structure public R&D claims: pre-register the task, freeze the evaluation path, keep payload boundaries clean, publish hashes and summaries, and state residual risks clearly.

### [Monte-Neo](https://github.com/NeoZorK/Monte-Neo)

Python framework for Monte Carlo-based indicator research. It combines target-based generation, stress testing, walk-forward validation, Binance OHLCV ingestion, visualization, Docker support, and an interactive CLI. The strongest part of this project is the research loop: generate, test, perturb, reject weak candidates, and keep robustness visible.

### [DEXArb](https://github.com/NeoZorK/DEXArb)

C++23 DEX arbitrage scanner focused on multi-chain discovery, pool scanning, public RPC usage, JSON configuration, performance metrics, and cross-platform builds. It shows my low-level systems side: CMake, C++ utilities, build automation, test coverage, and practical market-data scanning.

### [NeoZorK3](https://github.com/NeoZorK/NeoZorK3)

C++20 Solana arbitrage research bot with modular components for market data, strategy logic, order management, configuration, logging, and risk limits. It is useful as a systems architecture example: separate the data layer, opportunity engine, execution layer, and risk layer instead of mixing them into one script.

### [trading-data-replay-engine](https://github.com/NeoZorK/trading-data-replay-engine)

Python replay engine for historical trading data and mid-price processing. This project reflects a core theme in my work: before trusting a strategy, replay the data path and inspect how the system behaves under realistic event ordering.

### [neo-slack-bot-production](https://github.com/NeoZorK/neo-slack-bot-production)

C++17 Slack bot using Socket Mode, HTTP API calls, native macOS notifications, logging, reconnection logic, Docker builds, and cross-platform documentation. It demonstrates production-style integration work outside trading: event processing, API auth, operational reliability, and maintainable C++ structure.

## Private R&D and Production Work

Some of my most complete systems are private, so I describe them by capability rather than repository name.

### Proprietary trading research platform

I maintain a private multi-module trading platform that combines CEX/DEX connectors, event-driven orchestration, risk controls, simulation/shadow/live mode separation, terminal dashboards, and a backtesting/certification layer. The system includes Python 3.13 orchestration, C++/pybind acceleration, Apple Silicon/MLX experiments, Monte Carlo and walk-forward tooling, and a large automated test surface.

Strengths demonstrated there:

- modular separation of connectors, decision logic, risk, execution, storage, and UI;
- certification gates before higher-risk modes;
- multi-venue market data and strategy orchestration;
- extensive documentation for architecture, operations, testing, and deployment;
- strong bias toward shadow validation before live exposure.

### Closed-source quantitative analytics API

I also maintain a private API server around a proprietary mathematical analytics core. It includes a Python/FastAPI service, PostgreSQL-backed API-key management, documented HTTP contracts, C++ client/server components, MQL5 bridge compatibility, parity/golden-vector workflows, load and black-box benchmark scripts, and operator quick-start guides.

Strengths demonstrated there:

- turning research math into a versioned API product;
- cross-language implementation and compatibility work across Python, C++, MQL5, and Swift/Metal experiments;
- auth, database, deployment, and local production-style runbooks;
- validation reports covering health checks, version endpoints, OpenAPI, authenticated calls, client checks, and load profiles;
- clear separation between closed proprietary logic and public benchmark foregrounds.

### Private prediction and MQL5 libraries

I also work with private high/low direction prediction research and MetaTrader libraries for experts, indicators, reusable include files, risk helpers, and strategy building blocks. These projects are useful because they connect research outputs to the environment where many traders actually test and operate strategies.

## Technical Stack

- **Languages:** Python, C++, MQL5, JavaScript, Bash
- **Trading and market systems:** MetaTrader 5, CEX/DEX data, crypto, FX, equities, indices, derivatives
- **Research and validation:** walk-forward analysis, Monte Carlo, stress testing, benchmark gates, reproducibility workflows
- **Backend and infrastructure:** FastAPI, PostgreSQL, Docker, Linux/macOS automation, CLI/TUI tools
- **Performance:** C++20/23, pybind11, SIMD-oriented design, MLX/Apple Silicon experiments, Metal experiments
- **Quality:** pytest, pytest-xdist, mypy, ruff, CMake, GoogleTest/Catch2-style workflows, operator documentation

## Engineering Principles

- **Evidence before claims.** A result is only useful if its data source, protocol, controls, hashes, and limits can be inspected.
- **Validation before automation.** I prefer shadow modes, certification gates, stress tests, and out-of-sample checks before live operation.
- **Architecture over scripts.** Data, signal logic, execution, risk, UI, and operations should have clear boundaries.
- **Performance where it matters.** I use C++/GPU/native components when they reduce real bottlenecks, not just for aesthetics.
- **Honest public/private boundary.** Public repositories should be independently useful; private systems should not leak proprietary internals.

## Contact

- LinkedIn: [rostyslav-sh-](https://www.linkedin.com/in/rostyslav-sh-)

---

Open to cooperation on quantitative research, trading infrastructure, benchmark design, and production-grade market systems.
