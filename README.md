# Rost S. — Quant / Trading Systems R&D

I build **algorithmic trading systems** and **quantitative research infrastructure**, with 12+ years of hands-on experience in trading software (including deep MT4/MT5/MQL5 domain work).

**Focus:** turning trading ideas into testable, reproducible, production-oriented systems.

> **About the name.** *NeoZorK* is my GitHub handle for software engineering work. It is not connected to any video blogger, streamer, gaming channel or game account that uses the same or a similar nickname. This profile contains only professional work: trading systems, research tooling and open-source software.

## Current focus

- Algorithmic trading and market research
- Python / C++ trading infrastructure
- Quantitative validation and backtesting
- AI-assisted R&D (as a development multiplier, not a job title)
- Proprietary market analytics

## Stack hierarchy

| Layer | What |
| --- | --- |
| **Core** | Algorithmic trading · trading systems · Quant R&D |
| **Strong** | Trading architecture · validation · MQL5/C++ domain depth |
| **Applied** | Python · FastAPI · PostgreSQL · Docker |
| **Emerging** | ML / LLM tooling · local AI workflows · MLX |

## Active work

1. **[Monte-Neo](https://github.com/NeoZorK/Monte-Neo)** — an independent verifier for trading strategies written by AI agents and humans. It looks for look-ahead bias, hidden trading costs and overfitting before a backtest reaches real money, and issues reproducible, signable certificates. Adapters for common backtesting frameworks; MCP server for agents.
2. **[ClaimBound Evidence](https://github.com/ClaimBound/claimbound-evidence)** — preregistered evidence discipline (rigor signal; not the hero product)

> Green / `PASSED_UNDER_PROTOCOL` ≠ independently reproduced. Most public cards remain single-operator until a separate rerun.

## Archived prototypes

Kept public for reference, read-only, and described as they are. None of them is a working trading product.

| Repository | What it was | What is actually there |
| --- | --- | --- |
| [trading-data-replay-engine](https://github.com/NeoZorK/trading-data-replay-engine) | A two-hour engineering exercise: replay of historical and live quotes | Latency-aware replay order (`timestamp + latency`), Redis queue, mid-price processor. The arrival-time idea continues in Monte-Neo's verification checks. |
| [DEXArb](https://github.com/NeoZorK/DEXArb) | EVM DEX pool scanner (C++) | Multi-threaded factory and pool scan over public JSON-RPC. No arbitrage detection, execution or wallet logic. |
| [NeoZorK3](https://github.com/NeoZorK/NeoZorK3) | Solana arbitrage-bot skeleton (C++) | CLI, configuration, RPC endpoint discovery. The arbitrage engine and transaction signing are stubs. |
| [neo-slack-bot-production](https://github.com/NeoZorK/neo-slack-bot-production) | Personal Slack Socket Mode client (C++) | Socket Mode connection with native macOS notifications; v0.0.7, not battle-tested. |

## AI-assisted R&D

I use modern AI coding/reasoning systems (Claude, GPT, Gemini, Grok, Cursor, local LLMs) to accelerate research iteration, refactoring, tests, experiment automation, and trading-system prototyping — not as “generic AI development.”

## Contact

Open to **remote Quant Developer / Algorithmic Trading / Trading Systems R&D** roles.  
GitHub: [@NeoZorK](https://github.com/NeoZorK)
