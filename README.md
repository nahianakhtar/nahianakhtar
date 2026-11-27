# Nahian Akhtar

AI systems and QA engineer in New York. I build MCP servers, retrieval pipelines and money handling code, and I ship each one with tests that prove it works before anyone else touches it.

Six years of QA on payment and enterprise systems at JetBlue Airways and AAA taught me where production systems break. That is the part I design for first.

**Portfolio and live demos:** [nahianakhtar.github.io](https://nahianakhtar.github.io/)

## Newest work

| Project | What it does | Proof |
| :--- | :--- | :--- |
| [otlp-llm-cost-profiler-rs](https://github.com/nahianakhtar/otlp-llm-cost-profiler-rs) | Reads OpenTelemetry traces from LLM apps and reports exact cost per model, p50/p95/p99 latency, time to first chunk and prompt cache hit ratio. Fails a CI job when spend or latency goes over budget. One Rust binary. | 11 tests, a CI round trip through the official OpenTelemetry Python exporter, prebuilt binaries with SHA256 checksums |
| [mcp-billing-firewall](https://github.com/nahianakhtar/mcp-billing-firewall) | A proxy in front of any MCP server: blocks prompt injection and SSRF, redacts secrets, meters usage with HTTP 402, and keeps a tamper evident audit log. No dependencies. | `mypy --strict`, a 12 thread race test with zero double spend, [live demo](https://nahianakhtar.github.io/demos/mcp-firewall/) |

## MCP servers and automation

| Project | What it does | Proof |
| :--- | :--- | :--- |
| [mcp-moe-hybrid-sdk](https://github.com/nahianakhtar/mcp-moe-hybrid-sdk) | MCP server with OAuth 2.1, hybrid BM25 and vector search with rank fusion, rate limits and PII scrubbing | 42 offline tests, 1.0 Recall@1 on the golden set, [live demo](https://nahianakhtar.github.io/demos/moe-rag/) |
| [invoice-audit-mcp-saas](https://github.com/nahianakhtar/invoice-audit-mcp-saas) | Invoice audit API and MCP server with exact integer money math, Benford checks, Merkle proofs and a GitHub Action | `pytest`, `ruff`, v1.0.0 release |
| [mcp-automation-demo](https://github.com/nahianakhtar/mcp-automation-demo) | CSV and SQLite invoice reconciliation with `Decimal` math, read only database access, write gates and a JSONL audit trail | 77 offline tests |
| [api-glue-mcp](https://github.com/nahianakhtar/api-glue-mcp) | Webhook engine that replaces Zapier style glue: HMAC replay checks, host allowlists, dead letter replay | 8 test suites, `tsc` with zero errors |

## Systems and evaluation

| Project | What it does | Measured |
| :--- | :--- | :--- |
| [polyglot-agent-runtime-rs](https://github.com/nahianakhtar/polyglot-agent-runtime-rs) | Rust and C11 runtime pieces: a cache line aligned CRC32C ring buffer, a DAG scheduler and streaming quantiles | 2.94M ops/s ring buffer, 38M observations/s quantile estimator |
| [fullstack-rag-eval-studio](https://github.com/nahianakhtar/fullstack-rag-eval-studio) | RAG evaluation gateway with guardrails and a 120 case test suite | 100% faithfulness and Recall@2 on the suite |
| [zero-to-code-systems-lab](https://github.com/nahianakhtar/zero-to-code-systems-lab) | Offline course of 100 computer science and systems concepts with CPU and ALU simulators | 407 KB portable build |

## Free browser tools

[GPU VRAM and KV cache cost](https://nahianakhtar.github.io/tools/rag-vram-cost/) · [Freelance net pay and tax reserve](https://nahianakhtar.github.io/tools/freelance-net-tax/) · [Benford invoice audit](https://nahianakhtar.github.io/tools/benford-invoice-audit/) · [Little's Law queue latency](https://nahianakhtar.github.io/tools/littles-law-throughput/) · [Engineering notes](https://nahianakhtar.github.io/articles/)

## How I work

- Read only by default. Writes are explicit and logged.
- Money is integer cents or `Decimal`, never floats.
- Every repo has CI, and claims in a README come from a test or a benchmark you can rerun.
- Python 3.12, TypeScript and Node 22, Rust, C11, SQLite, PostgreSQL, Docker, GitHub Actions, Playwright.

Open to contract work on MCP servers, LLM cost and latency, retrieval quality, and test automation. [Sponsor open source work](https://github.com/sponsors/nahianakhtar)
