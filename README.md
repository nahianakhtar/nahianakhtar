# Nahian Akhtar

**Systems & Protocol Engineer** | New York, NY | [Portfolio & 5 Live Workbenches](https://nahianakhtar.github.io/) | [Engineering Notes](https://nahianakhtar.github.io/articles/)

I build Model Context Protocol (`MCP 2025-11-25`) servers, exact-decimal CSV and SQLite reconciliation CLIs, idempotent webhook automation bridges, and low-level Rust/C11 runtimes verified with offline test suites before delivery.

---

## Verified MIT Proof Repositories & Live Workbenches

| Repository | Stack | Live Interactive Workbench | Offline CI Verification |
| :--- | :--- | :--- | :--- |
| [mcp-moe-hybrid-sdk](https://github.com/nahianakhtar/mcp-moe-hybrid-sdk) | Python 3.12 · SQLite `WAL + FTS5` · OAuth 2.1 | [MoE + Bitset RRF](https://nahianakhtar.github.io/demos/moe-rag/) | `42` `pytest` tests + `mypy --strict`, `100%` Recall@1 (`0.27 ms` p95) |
| [mcp-automation-demo](https://github.com/nahianakhtar/mcp-automation-demo) | Python 3.12 · `uv` · `mcp==2.3.0` stdio | [128-Bit Ledger & Merkle](https://nahianakhtar.github.io/demos/ledger-audit/) | `77` `pytest` tests, `ROUND_HALF_EVEN`, `mode=ro` + `--apply` |
| [api-glue-mcp](https://github.com/nahianakhtar/api-glue-mcp) | TypeScript · Node 22 `node:sqlite` · MCP v2 | [Portfolio Proof Spec](https://nahianakhtar.github.io/#repositories) | `8` `node --test` suites, `tsc` `0` errors, HMAC-SHA256 + DLQ |
| [polyglot-agent-runtime-rs](https://github.com/nahianakhtar/polyglot-agent-runtime-rs) | Rust 2021 · ISO C11 FFI (`-Werror`) · `wasm32` | [64B Ring & Kahn DAG](https://nahianakhtar.github.io/demos/rust-ring-dag/) | `3.13M ops/s` CRC32C ring (`0.36 µs` p95), `37.3M obs/s` `P2` quantiles |
| [fullstack-rag-eval-studio](https://github.com/nahianakhtar/fullstack-rag-eval-studio) | TypeScript · Node 22 HTTP/SSE · OTLP | [Guardrail & 120-Case Eval](https://nahianakhtar.github.io/demos/guardrail-automaton/) | `12/12` `node --test` suites, pairwise A/B diff + SSE streaming |
| [zero-to-code-systems-lab](https://github.com/nahianakhtar/zero-to-code-systems-lab) | Air-Gapped ES5/SVG · Win x64 WebView2 | [Live CS Lab](https://nahianakhtar.github.io/zero-to-code-systems-lab/) · [UIA DPI](https://nahianakhtar.github.io/demos/uia-metrology/) | `0` network calls CSP, `100` CS concepts, Win x64 release CI |
| [nahianakhtar.github.io](https://github.com/nahianakhtar/nahianakhtar.github.io) | Pure ES2022 + TypedArrays + Rust `wasm32` | [5-Workbench Directory](https://nahianakhtar.github.io/demos/) | `6/6` `node:test` property suites + live Edge CDP verified |

---

## Published Engineering Briefs

1. [MCP 2025-11-25 Without Infrastructure Sprawl: OAuth 2.1 PKCE, Session Replay, and SQLite FTS5 RRF](https://nahianakhtar.github.io/articles/mcp-oauth-pkce-sqlite-rrf/)
2. [Zero-Allocation Telemetry Rings Across Rust 2021, ISO C11 FFI, and WebAssembly](https://nahianakhtar.github.io/articles/cache-line-64b-c11-crc32c-rust-ffi/)
3. [Why Invoice Reconciliation Pipelines Leak Cents (and How Fixed-Point BigInt + SHA-256 Merkle Trees Fix It)](https://nahianakhtar.github.io/articles/microdollar-reconciliation-merkle-audit/)
4. [Per-Monitor V2 DPI Coordinate Metrology for Reliable Windows UIA Automation](https://nahianakhtar.github.io/articles/per-monitor-v2-uia-dpi-metrology/)

---

## Consulting & Fixed-Scope Delivery Scope

- **Prepaid Fixed Deliverables (PPD)**: `$175` CI/Test Diagnostic | `$450` Standard Python/TypeScript MCP Server or Reconciliation CLI | `$950` Full Multi-Source Pipeline / Evaluation Gateway (with itemized NY written statement of work for `>= $800`).
- **Pilot-to-Production Retainer (PPP)**: `$1,000` staged MVP + `$350/mo` schema monitoring and maintenance, plus US Form W-9 contractor availability.
- **Verification Floor**: Read-only defaults, input/output JSON-Schema contracts, zero-leak secret/PII scrubbing, and automated `pytest` / `node --test` / `cargo test` CI gates on every handoff.
