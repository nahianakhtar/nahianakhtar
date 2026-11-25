# Nahian Akhtar — Custom MCP Servers, CLI Pipelines & Systems Automation

Engineering deterministic AI protocols, guardrailed automation CLIs, memory-safe Rust/C11 runtimes, and hybrid SQLite/Vector retrieval engines in New York, NY.

- **Live Editorial Studio & Interactive Lab**: [nahianakhtar.github.io](https://nahianakhtar.github.io) *(Light-mode `#FAF9F6` showcase + live WASM/MCP protocol lab)*
- **LinkedIn**: [nahian-akhtar-b42086443](https://www.linkedin.com/in/nahian-akhtar-b42086443)
- **GitHub**: [@nahianakhtar](https://github.com/nahianakhtar)
- **Core Stack**: `Python 3.12` · `TypeScript / Node.js 22` · `MCP (stdio & Streamable HTTP)` · `SQLite WAL FTS5` · `Rust 2021` · `ISO C11 FFI` · `Docker & GitHub Actions CI`

---

## Featured Automation & Systems Repositories (MIT Licensed · CI Verified)

| Repository | Stack | Verified Capabilities & Benchmarks | CI Gate |
| :--- | :--- | :--- | :--- |
| [**`mcp-moe-hybrid-sdk`**](https://github.com/nahianakhtar/mcp-moe-hybrid-sdk) | Python 3.10+, SQLite WAL `FTS5`, MCP `2025-11-25`, OAuth 2.1, Docker | **`42` offline tests** · **`1.00` Recall@1** · Sparse Top-2 MoE routing · `Mcp-Session-Id` SSE replay · RFC 9728 / PKCE S256 | ![CI](https://github.com/nahianakhtar/mcp-moe-hybrid-sdk/actions/workflows/ci.yml/badge.svg) |
| [**`mcp-automation-demo`**](https://github.com/nahianakhtar/mcp-automation-demo) | Python 3.12, `uv`, official `mcp==2.3.0` stdio + `recon` CLI | **`77` offline tests** · `Decimal` (`ROUND_HALF_EVEN`) CSV/SQLite reconciliation · `mode=ro` + write-root confinement · JSONL audit log | ![CI](https://github.com/nahianakhtar/mcp-automation-demo/actions/workflows/ci.yml/badge.svg) |
| [**`api-glue-mcp`**](https://github.com/nahianakhtar/api-glue-mcp) | TypeScript `7.0.2`, Node 22 `node:sqlite`, `@modelcontextprotocol/server@2.4.0` | **`8` offline tests** · HMAC-SHA256 replay guard · SSRF allowlist · SQLite WAL idempotency · `Retry-After` backoff + DLQ replay | ![CI](https://github.com/nahianakhtar/api-glue-mcp/actions/workflows/ci.yml/badge.svg) |
| [**`polyglot-agent-runtime-rs`**](https://github.com/nahianakhtar/polyglot-agent-runtime-rs) | Rust 2021 + C11 FFI (`-O3 -Wall -Wextra -Werror`), `wasm32` | **`2.93M+ ops/sec`** 64B CRC32C ring vault · capability-fenced DAG scheduler · `O(1)` Jain-Chlamtac `P²` quantiles | ![CI](https://github.com/nahianakhtar/polyglot-agent-runtime-rs/actions/workflows/ci.yml/badge.svg) |
| [**`fullstack-rag-eval-studio`**](https://github.com/nahianakhtar/fullstack-rag-eval-studio) | TypeScript `.d.ts`, Zero-Dep Node.js 22 ESM, HTTP + SSE, Docker | **`100%` Faithfulness** · **`97.5%` AP@2** · OAuth 2.1 RFC 9728 + `Mcp-Session-Id` SSE replay (`35` suites) | ![CI](https://github.com/nahianakhtar/fullstack-rag-eval-studio/actions/workflows/ci.yml/badge.svg) |
| [**`zero-to-code-systems-lab`**](https://github.com/nahianakhtar/zero-to-code-systems-lab) | Zero-Dep ES5/HTML5/SVG, Native C# x64 WebView2, Inno Setup | **100% Air-Gapped (`0` Net Calls)** · `100` CS Concepts (`300+` variants) · [Live Lab](https://nahianakhtar.github.io/zero-to-code-systems-lab/) & [Win x64 Release](https://github.com/nahianakhtar/zero-to-code-systems-lab/releases/latest) | ![CI](https://github.com/nahianakhtar/zero-to-code-systems-lab/actions/workflows/ci.yml/badge.svg) |
| [**`nahianakhtar.github.io`**](https://github.com/nahianakhtar/nahianakhtar.github.io) | Editorial Light Studio (`#FAF9F6` / `#141413`), ES2022 + Rust `wasm32` | **10 Interactive MCP/WASM Lab Modes** · `12`-Dimension Competency Matrix · `0` External Runtime Deps | ![CI](https://github.com/nahianakhtar/nahianakhtar.github.io/actions/workflows/ci.yml/badge.svg) |

---

## Engineering Principles

- **Deterministic Pre-Action Guardrails**: Enforce read-only defaults, SSRF/path confinement, `Decimal` precision, and append-only JSONL audit logs in code—never via prompt-only instructions.
- **Offline Verification First**: Every Python, TypeScript, and Rust repository ships socket-guarded or mocked offline test suites and reproducible builds verified in GitHub Actions CI.
- **Verified Credentials**: B.S. in Computer Science & Engineering · Phitron *CS Fundamentals (C/C++)* · Simplilearn *Prompt Engineering* (`11042519`).
