# Tsolmondorj Natsagdorj

Systems & research engineer working on **reliable AI, autonomous systems, and security-critical infrastructure**.

I like problems where the abstraction can lie: model evaluations with leakage, uncertainty estimates that are not calibrated, network diagnostics that need real hardware, and protocols whose correctness has to survive adversarial conditions.

### Start here

- **[197 passing tests, four real-hardware bugs](https://0xsoftboi.github.io/blog/197-tests-four-real-hardware-bugs/)** — why synthetic confidence has to answer to independent device state.
- **[A benchmark can measure its own metadata](https://0xsoftboi.github.io/blog/static-analysis-scores-zero-on-real-exploits/)** — a public correction after a prompt audit found severe leakage in 13/24 benchmark examples.
- **[Upstream is a different kind of test](https://0xsoftboi.github.io/blog/upstream-is-a-different-kind-of-test/)** — what merged third-party patches changed about the unit of correctness.

### Selected work

- **[roce-preflight](https://github.com/0xSoftBoi/roce-preflight)** — RDMA/RoCE diagnostics with real-hardware validation; hardware CI found defects that unit tests missed.
- **[BRIDGE-bench](https://github.com/0xSoftBoi/anthropic-fellowship)** — empirical AI-security evaluation work, including contamination controls and evaluator-validity analysis.
- **[active-materials-discovery](https://github.com/0xSoftBoi/active-materials-discovery)** — materials ML where the mean prediction was useful and the tested MC-dropout uncertainty signal failed calibration.
- **[Aiur](https://github.com/0xSoftBoi/aiur)** — current autonomy/hardware experiment; design, simulation, controller, and acceptance-gate work, with physical recovery performance still explicitly unproven.

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

I build **[Suwappu](https://suwappu.bot)**, where I work on distributed systems, cryptographic protocols, transaction infrastructure, and adversarial reliability. I also maintain experiments in ML inference, scientific computing, networking, and autonomous hardware.

**[Research & work](https://0xsoftboi.github.io/)** · [writing](https://0xsoftboi.github.io/blog/) · [research](https://0xsoftboi.github.io/research/) · [X](https://twitter.com/0xSoftBoi) · layerinfinite@gmail.com
