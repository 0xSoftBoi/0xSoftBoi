# Tsolmondorj Natsagdorj

Systems engineer working on transaction infrastructure, Rust protocols, cryptographic software, and scientific ML.

## Merged upstream

- [alloy-rs/core #1105](https://github.com/alloy-rs/core/pull/1105) — EIP-712 canonicalization for recursive struct types.
- [uutils/parse_datetime #320](https://github.com/uutils/parse_datetime/pull/320) — GNU-compatible military timezone `J` handling.
- [uutils/coreutils #12327](https://github.com/uutils/coreutils/pull/12327) — fixed `date` timezone re-zoning semantics.
- [uutils/parse_datetime #284](https://github.com/uutils/parse_datetime/pull/284) — `HH:MM am/pm` parsing.
- [uutils/parse_datetime #285](https://github.com/uutils/parse_datetime/pull/285) — correct negative Unix timestamp floor semantics.
- [uutils/parse_datetime #287](https://github.com/uutils/parse_datetime/pull/287) — bare `UT` timezone support.
- [ml-explore/mlx-lm #1372](https://github.com/ml-explore/mlx-lm/pull/1372) — fixed pathological XTC sampling defaults.
- [materialyzeai/matgl #809](https://github.com/materialyzeai/matgl/pull/809) — autograd-correct, numerically safe `SoftExponential`.
- [materialyzeai/matgl #801](https://github.com/materialyzeai/matgl/pull/801) — MC-dropout uncertainty estimation for pretrained models.
- [BankrBot/skills #491](https://github.com/BankrBot/skills/pull/491) — Suwappu cross-chain MCP skill.

## Research & publications

### Suwappu Research — working papers

- **[A 10-for-1 stock split can leave your ERC-20 balance unchanged](https://suwappu.bot/research/replication/papers/erc8056-stock-token-interface-risk.md)** — tokenized assets / ERC-8056, 2026.
- **[USDT0 backing reconciliation: separating protocol coverage from issuer risk](https://suwappu.bot/research/replication/papers/usdt0-collateral-reconciliation.md)** — reserve and settlement risk, 2026.
- **[What is a minute of cross-chain execution worth? Pricing latency without confusing ETA for finality](https://suwappu.bot/research/replication/papers/settlement-latency-value.md)** — execution governance, 2026.
- **[Incentive budgets as market design: what survives after the model fails](https://suwappu.bot/research/replication/papers/points-tullock-contests.md)** — mechanism design and model risk, 2026.
- **[When a mathematically correct model is wrong: an allocation-model validation case study](https://suwappu.bot/research/replication/papers/airdrop-concentration.md)** — model validation, 2026.

### Report

- **[Accounting for an Omnichain Dollar](https://suwappu.bot/research/reports/accounting-for-an-omnichain-dollar.pdf)** — Suwappu Research Report 01, 2026. Institutional report edition of the USDT0 study.

### Scientific ML

- **[Pre-trained Surrogates Suffice: Active Learning for Crystal Stability on the WBM Benchmark](https://github.com/0xSoftBoi/active-materials-discovery/blob/master/paper/paper_final.pdf)** — research manuscript. [Source](https://github.com/0xSoftBoi/active-materials-discovery/blob/master/paper/materials_discovery_paper.tex) · [Erratum](https://github.com/0xSoftBoi/active-materials-discovery/blob/master/paper/ERRATA.md).

### Research release

- **[BRIDGE-bench: Measuring LLM Reasoning on Compositional Cross-Chain Bridge Exploits](https://doi.org/10.5281/zenodo.20604295)** — citable research/software release, 2026. DOI: `10.5281/zenodo.20604295`.

## Building

### [Suwappu](https://github.com/0xSoftBoi/suwappubot)

Execution infrastructure for onchain applications and agents.

Recent work includes:
- transaction routing and settlement reconciliation
- wallet policy and smart-account authentication
- cross-chain execution and simulation
- WebMCP / agent transaction controls
- production reliability across Postgres, RPC infrastructure, Railway, and nginx

### [LCA-1](https://github.com/0xSoftBoi/LCA-1)

Pre-silicon post-quantum cryptography accelerator work.

### [active-materials-discovery](https://github.com/0xSoftBoi/active-materials-discovery)

Constrained active learning for materials discovery using graph models and uncertainty estimation.

### [MERIDIAN](https://github.com/0xSoftBoi/meridian)

Rust implementation of post-quantum finality certificates and validator accountability.

[Website](https://0xsoftboi.github.io/) · [Research](https://0xsoftboi.github.io/research/) · [ORCID](https://orcid.org/0009-0009-6010-6273) · [Writing](https://0xsoftboi.github.io/blog/) · [X](https://twitter.com/0xSoftBoi)
