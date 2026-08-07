<img src="profile-banner.png" alt="Tsolmondorj Natsagdorj — security, systems & evaluation">

security + systems engineer · agent evaluation, adversarial reliability & tooling · Rust, Python, TypeScript

I build security-critical systems and evaluations, then attack the assumptions and measurements behind them before I trust the result.

## Selected evidence

- [BRIDGE-bench](https://github.com/0xSoftBoi/anthropic-fellowship) — an evaluation of model vulnerability detection on real contracts that became a measurement-validity project. I found **13/24 prompts leaked bug descriptions**, showed the score moves **14.5 points from the grader alone**, added prompt sanitization, matched buggy/fixed controls, negative controls, and dataset/judge-validity tests. The contaminated headline result is explicitly retired.
- [evmsec](https://github.com/0xSoftBoi/evmsec) — defensive EVM tooling with offline replay fixtures captured from real mainnet contracts, deterministic verdict tests, strict TypeScript gates, JSON/SARIF output, and Node 20/22 CI.
- [suwappubot](https://github.com/0xSoftBoi/suwappubot) — production cross-chain/agent infrastructure: provider integrations, SDK/MCP surfaces, transaction execution, reconciliation, and security-critical state transitions.
- [lock-mint-bridge-lab](https://github.com/0xSoftBoi/lock-mint-bridge-lab) — stateful Foundry invariants and exploit reproductions around lock/mint solvency, double-spend, and attestation boundaries.

## Merged upstream

| Project | Contribution | Proof |
|---|---|---|
| MLX-LM | Corrected the XTC sampler threshold default | [ml-explore/mlx-lm #1372](https://github.com/ml-explore/mlx-lm/pull/1372) |
| MatGL | MC-dropout wrapper; SoftExponential autograd / NaN fix | [#801](https://github.com/materialyzeai/matgl/pull/801) · [#809](https://github.com/materialyzeai/matgl/pull/809) |
| Alloy | EIP-712 canonicalization for self-referential struct types | [alloy-rs/core #1105](https://github.com/alloy-rs/core/pull/1105) |
| uutils | `date` timezone re-zoning + parser fixes | [coreutils #12327](https://github.com/uutils/coreutils/pull/12327) · [parse_datetime #284](https://github.com/uutils/parse_datetime/pull/284) · [#285](https://github.com/uutils/parse_datetime/pull/285) · [#287](https://github.com/uutils/parse_datetime/pull/287) |

## Research / systems breadth

- [active-materials-discovery](https://github.com/0xSoftBoi/active-materials-discovery) — uncertainty-aware active learning with a useful negative result: MC-dropout uncertainty was miscalibrated (Spearman ρ = -0.47 vs. absolute error), so the measured discovery gain could not honestly be attributed to the uncertainty bonus.
- [sensorforge](https://github.com/0xSoftBoi/sensorforge) — iPhone/ARKit sensor capture, Jetson integration, and a Rust/Metal/CUDA runtime for embodied experiments.

## Writing

I wrote [Printing Money](https://tsoma2.gumroad.com/l/printingmoney), a hands-on book on how on-chain systems fail and how to test them; the companion [Foundry labs](https://github.com/0xSoftBoi/printing-money-labs) are public.

[0xsoftboi.github.io](https://0xsoftboi.github.io) · [@0xSoftBoi](https://twitter.com/0xSoftBoi) · layerinfinite@gmail.com
