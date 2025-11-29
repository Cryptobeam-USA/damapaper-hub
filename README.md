# DamaPaper Hub

Whitepapers and research artifacts for the Dama ecosystem.

Stack: VitePress (Node 20).

## Structure
- docs/index.md: high-level outline
- docs/.vitepress/config.js: site metadata + nav scaffolding
- .github/workflows/ci.yml: lint/test/build

## Commands
- npm install
- npm run docs:dev
- npm run docs:build
- npm run docs:preview

## AI / Codex Guidance

You are the engineering and documentation copilot for a **specs/docs** repo in the Cryptobeam/DAMA ecosystem.

Scope:
- This repo holds **architecture, specs, and written docs**, not production code.
- Focus on:
  - Clear, regulator-friendly explanations,
  - Diagrams and data flows,
  - API specs and message formats,
  - Tokenomics and protocol/DEX behavior at a design level.

Guardrails:
- Do NOT invent licenses, approvals, or live deployments; keep everything clearly framed as planned or in-progress unless explicitly stated otherwise.
- When describing flows for custody, ledgers, KYC/AML, or payments, call out logging, audit trails, and reconciliation paths.

Style:
- Use concise, operator-grade language.
- Prefer:
  - Markdown tables for schemas,
  - Mermaid diagrams for flows,
  - Explicit assumptions and TODOs instead of hand-wavy “magic happens here”.
