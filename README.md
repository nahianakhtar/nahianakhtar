# Nahian Akhtar

**Systems & Protocol Engineer** | New York, NY | [Portfolio & Interactive Lab](https://nahianakhtar.github.io/)

I build Model Context Protocol (MCP) servers, CLI reconciliation pipelines, webhook automation bridges, and low-level Rust/C11 runtimes verified with offline test suites before delivery.

## Open-Source Client Proof Repositories (MIT License)

| Repository | Stack | Core Scope | Offline Verification |
| :--- | :--- | :--- | :--- |
| [mcp-moe-hybrid-sdk](https://github.com/nahianakhtar/mcp-moe-hybrid-sdk) | Python 3.10+, SQLite FTS5, OAuth 2.1 | MCP 2025-11-25 Streamable HTTP server, hybrid BM25 + cosine search, token rate limits, PII scrubbing | `42` offline `pytest` tests, `1.0000` Recall@1 (`v1.9.0`, CI green) |
| [mcp-automation-demo](https://github.com/nahianakhtar/mcp-automation-demo) | Python 3.12, `uv`, `mcp==2.3.0`, SQLite | CSV and SQLite invoice reconciliation CLI (`Decimal` math, read-only database open, write gates, JSONL audit) | `77` offline `pytest` tests + stdio smoke checks (CI green) |
| [api-glue-mcp](https://github.com/nahianakhtar/api-glue-mcp) | TypeScript, Node 22 `node:sqlite`, MCP v2 | Idempotent webhook and Zapier replacement engine (HMAC replay check, HTTPS host allowlists, dead-letter replay) | `8` offline `node --test` suites + `tsc` `0` errors (CI green) |
| [`invoice-audit-mcp-saas`](https://github.com/nahianakhtar/invoice-audit-mcp-saas) | Python 3.12, MCP `2025-11-25`, SQLite WAL | Metered 128-bit micro-dollar invoice REST API & Streamable HTTP MCP server (`HTTP 402`, Stripe HMAC, Merkle proofs, GitHub Action) | Offline `pytest` + `ruff` + `v1.0.0` release (CI green) |
| [`mcp-billing-firewall`](https://github.com/nahianakhtar/mcp-billing-firewall) | Python 3.12, MCP `2025-11-25`, SQLite WAL | Zero-dependency MCP security firewall, prompt-injection & SSRF blocker, atomic micro-credit `HTTP 402` / `x402` proxy, Polar/Stripe webhooks & SHA-256 hash chain | `mypy --strict`, `ruff`, 12-thread race `pytest` + `v1.0.0` (CI green) |
| [`accounting-tax-doc-verifier`](https://github.com/nahianakhtar/accounting-tax-doc-verifier) | Python 3.12, MCP `2025-11-25`, Vercel | 2026 IRS Form 1099-NEC (`$2,000` OBBBA / `$600` state & legal) verifier, 128-bit micro-dollar math, `24%` missing W-9 backup WH, split-bill detection & SHA-256 Merkle proofs | `mypy --strict`, `ruff`, `pytest` + `v1.0.0` (CI green) |

## Systems Runtimes & Verification Lab

| Repository | Stack | Measured Results |
| :--- | :--- | :--- |
| [polyglot-agent-runtime-rs](https://github.com/nahianakhtar/polyglot-agent-runtime-rs) | Rust 2021, ISO C11 FFI (`-Werror`) | `2.94M ops/s` CRC32C ring buffer (`0.3819 µs` p95), `38.01M obs/s` Jain-Chlamtac `P²` quantiles |
| [fullstack-rag-eval-studio](https://github.com/nahianakhtar/fullstack-rag-eval-studio) | TypeScript, Node 22 HTTP/SSE | `100%` faithfulness and Recall@2, `7,623.5 cases/s` offline evaluation gateway |
| [zero-to-code-systems-lab](https://github.com/nahianakhtar/zero-to-code-systems-lab) | ES5/SVG Web + C# x64 WebView2 | `100` CS and systems concepts offline with hardware CPU/ALU simulators (`407 KB` portable zip) |

## Live In-Browser Workbenches, Free Tools & Technical Notes

Test live Sparse Top-2 MoE routing, OAuth 2.1 RFC 9728 metadata, PKCE S256 token checks, 128-bit micro-dollar Merkle proofs, and compiled `wasm32` telemetry tables directly in the browser with zero external API keys:

- **Portfolio & Protocol Studio**: [nahianakhtar.github.io](https://nahianakhtar.github.io/)
- **8 Interactive Engineering Workbenches**: [MoE + Hybrid RRF](https://nahianakhtar.github.io/demos/moe-rag/) | [128-Bit Ledger Merkle](https://nahianakhtar.github.io/demos/ledger-audit/) | [64B Rust Ring + DAG](https://nahianakhtar.github.io/demos/rust-ring-dag/) | [120-Case Guardrail Eval](https://nahianakhtar.github.io/demos/guardrail-automaton/) | [Per-Monitor V2 UIA DPI](https://nahianakhtar.github.io/demos/uia-metrology/) | [MCP Billing Firewall](https://nahianakhtar.github.io/demos/mcp-firewall/) | [LLM Cost & Latency Profiler](https://nahianakhtar.github.io/demos/llm-cost-profiler/) | [2026 Tax & 1099 Verifier](https://nahianakhtar.github.io/demos/tax-doc-verifier/)
- **4 Free Local Browser Calculators**: [GPU VRAM / KV Cost](https://nahianakhtar.github.io/tools/rag-vram-cost/) | [Freelance Net Tax & ACH](https://nahianakhtar.github.io/tools/freelance-net-tax/) | [Benford Invoice Auditor](https://nahianakhtar.github.io/tools/benford-invoice-audit/) | [Little's Law p95 Queue](https://nahianakhtar.github.io/tools/littles-law-throughput/)
- **4 Engineering Notes**: [Read all architecture briefs](https://nahianakhtar.github.io/articles/)
- **Support Open Source**: [GitHub Sponsors](https://github.com/sponsors/nahianakhtar)

## Core Tooling
- **Protocols & Automation**: MCP (`stdio` and Streamable HTTP), JSON-RPC 2.0, OAuth 2.1, HMAC webhooks, dead-letter replay queues
- **Languages & Data**: Python 3.12 (`uv`, `pytest`, `ruff`), TypeScript, Node.js 22 (`node:sqlite`), Rust, ISO C11, SQLite WAL/FTS5
- **Delivery Standards**: Read-only defaults, explicit write gating, exact `Decimal` math for money, JSONL audit logs, Docker, GitHub Actions CI
