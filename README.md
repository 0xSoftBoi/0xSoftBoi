# Tsolmondorj Natsagdorj

Systems & research engineer working on **reliable AI, autonomous systems, and security-critical infrastructure**.

I like problems where the abstraction can lie: model evaluations with leakage, uncertainty estimates that are not calibrated, network diagnostics that need real hardware, and protocols whose correctness has to survive adversarial conditions.

### Selected work

- **[roce-preflight](https://github.com/0xSoftBoi/roce-preflight)** — RDMA/RoCE diagnostics with real-hardware validation; hardware CI found defects that unit tests missed.
- **[BRIDGE-bench](https://github.com/0xSoftBoi/anthropic-fellowship)** — empirical AI-security evaluation work, including contamination controls and evaluator-validity analysis.
- **[active-materials-discovery](https://github.com/0xSoftBoi/active-materials-discovery)** — uncertainty-aware materials ML; optimized MC-dropout inference and measured where its uncertainty signal fails.
- **[aiur](https://github.com/0xSoftBoi/aiur)** — autonomous airborne carrier research prototype: simulation, docking/recovery control, test tooling, and measurable engineering milestones.

### Merged upstream

**ML / scientific computing**

- [materialyzeai/matgl #801](https://github.com/materialyzeai/matgl/pull/801) — MC-dropout uncertainty estimation for pretrained materials models.
- [materialyzeai/matgl #809](https://github.com/materialyzeai/matgl/pull/809) — autograd-correct, numerically safe `SoftExponential` activation.
- [ml-explore/mlx-lm #1372](https://github.com/ml-explore/mlx-lm/pull/1372) — corrected pathological XTC sampling defaults across library, CLI, and server.

**Rust / systems**

- [alloy-rs/core #1105](https://github.com/alloy-rs/core/pull/1105) — EIP-712 self-referential struct canonicalization in `dyn-abi`.
- [uutils/coreutils #12327](https://github.com/uutils/coreutils/pull/12327) — GNU-compatible `date` timezone re-zoning.
- [uutils/parse_datetime #284](https://github.com/uutils/parse_datetime/pull/284), [#285](https://github.com/uutils/parse_datetime/pull/285), [#287](https://github.com/uutils/parse_datetime/pull/287) — date parsing, negative Unix timestamp semantics, and timezone compatibility.

### Building

I build **[Suwappu](https://suwappu.bot)**, where I work on distributed systems, cryptographic protocols, transaction infrastructure, and adversarial reliability. I also maintain smaller experiments in ML inference, scientific computing, networking, and autonomous hardware.

[work & proof](https://github.com/0xSoftBoi/portfolio) · [writing](https://0xsoftboi.github.io) · [X](https://twitter.com/0xSoftBoi) · layerinfinite@gmail.com
