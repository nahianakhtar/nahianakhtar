# Nahian Akhtar — Systems, Polyglot AI SDK & Verification Engineer

Engineering deterministic AI protocols, memory-safe Rust/C11 runtimes, hybrid SQLite/Vector retrieval engines, and zero-flake verification pipelines in New York, NY.

- **Live Interactive Showcase**: [nahianakhtar.github.io](https://nahianakhtar.github.io) *(Try the live client-side Sparse Top-2 MoE + BM25/Vector RRF Simulator)*
- **LinkedIn**: [nahian-akhtar-b42086443](https://www.linkedin.com/in/nahian-akhtar-b42086443)
- **GitHub**: [@nahianakhtar](https://github.com/nahianakhtar)
- **Core Stack**: `Rust 2021` · `ISO C11 FFI` · `Python 3.12` · `TypeScript / Node.js 22` · `SQLite WAL FTS5` · `MCP 2025-11-25` · `PyTorch (QLoRA/DoRA)` · `Docker & GitHub Actions CI`

---

## Flagship Public Repositories (100% MIT Licensed & GitHub Actions Verified)

| Repository | Stack | Measured Engineering Benchmarks | CI Gate |
| :--- | :--- | :--- | :--- |
| [**`mcp-moe-hybrid-sdk`**](https://github.com/nahianakhtar/mcp-moe-hybrid-sdk) | Python 3.12, SQLite WAL `FTS5`, Vector RRF, MCP `2025-11-25`, Docker | **`1.00` Recall@1** (`0.466 ms` p95) · **`1.00` Top-2 MoE Router Acc** (`0.012 ms` p95) · Secret redaction guard | ![CI](https://github.com/nahianakhtar/mcp-moe-hybrid-sdk/actions/workflows/ci.yml/badge.svg) |
| [**`polyglot-agent-runtime-rs`**](https://github.com/nahianakhtar/polyglot-agent-runtime-rs) | Rust 2021 + C11 FFI (`-O3 -Wall -Wextra -Werror`), Docker | **`2.93M ops/sec`** 64B CRC32C ring vault (`0.406 µs` p95) · **`392k DAGs/sec`** scheduler · **`35.48M obs/sec`** P² `O(1)` quantiles | ![CI](https://github.com/nahianakhtar/polyglot-agent-runtime-rs/actions/workflows/ci.yml/badge.svg) |
| [**`fullstack-rag-eval-studio`**](https://github.com/nahianakhtar/fullstack-rag-eval-studio) | TypeScript `.d.ts`, Zero-Dep Node.js 22 ESM, HTTP + SSE, Docker | **`1.00` Faithfulness** · **`0.975` Precision** · **`96.67%` Semantic Cache Hit Rate** · **`0.417 ms` p95** (`120` golden cases) | ![CI](https://github.com/nahianakhtar/fullstack-rag-eval-studio/actions/workflows/ci.yml/badge.svg) |
| [**`nahianakhtar.github.io`**](https://github.com/nahianakhtar/nahianakhtar.github.io) | Semantic HTML5, Bento Grid CSS, ES2022 Client Simulator | **`12/12` FAANG Competency Matrix** · Live browser MoE + RRF simulator (`0.099 ms` p50) | ![CI](https://github.com/nahianakhtar/nahianakhtar.github.io/actions/workflows/ci.yml/badge.svg) |

---

## Engineering Principles

- **Polyglot Systems Depth**: Cache-line-aligned C11 FFI (`_Alignas(64)`) paired with zero-`unsafe` high-level orchestration, strict type contracts, and zero third-party bloat where stdlib primitives excel.
- **Deterministic AI Verification**: Every retrieval pipeline, MoE router, and tool-call guardrail ships with reproducible golden datasets, tail-latency ($p_{50}/p_{95}/p_{99}$) gates, and automated CI checks.
- **Verified Credentials**: B.S. in Computer Science & Engineering · Phitron *CS Fundamentals (C/C++)* · Simplilearn *Prompt Engineering* (`11042519`) · Google *Generative AI with Gemini*.
