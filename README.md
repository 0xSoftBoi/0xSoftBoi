<img src="profile-banner.png" alt="Tsolmondorj Natsagdorj — ML, systems & security">

systems + ML engineer · evaluations, agent infrastructure & security · Rust, Python, TypeScript

I build systems with AI aggressively, then try to break the assumptions and measurements behind what they produce.

## Upstream proof

- [ml-explore/mlx-lm #1372](https://github.com/ml-explore/mlx-lm/pull/1372) — fixed the XTC sampler threshold default and landed it upstream.
- [materialyzeai/matgl #801](https://github.com/materialyzeai/matgl/pull/801) + [#809](https://github.com/materialyzeai/matgl/pull/809) — added an MC-dropout wrapper and fixed SoftExponential autograd / NaN behavior.
- [alloy-rs/core #1105](https://github.com/alloy-rs/core/pull/1105) — fixed EIP-712 canonicalization for self-referential struct types in `dyn-abi`.
- [uutils/coreutils #12327](https://github.com/uutils/coreutils/pull/12327) + [parse_datetime #284](https://github.com/uutils/parse_datetime/pull/284), [#285](https://github.com/uutils/parse_datetime/pull/285), [#287](https://github.com/uutils/parse_datetime/pull/287) — timezone re-zoning, AM/PM parsing, epoch-floor semantics, and `UT` timezone support in Rust.

## Selected work

- [BRIDGE-bench](https://github.com/0xSoftBoi/anthropic-fellowship) — built an eval on real cross-chain exploits, then found that 13/24 benchmark prompts leaked bug descriptions. I added prompt sanitization, matched controls, dataset-integrity checks, and judge-validity tests instead of preserving the headline score.
- [active-materials-discovery](https://github.com/0xSoftBoi/active-materials-discovery) — uncertainty-aware active learning on MatGL: ~5.15× discovery acceleration on `matbench_perovskites`, with the more important negative result that MC-dropout uncertainty was miscalibrated (Spearman ρ = -0.47 vs. absolute error).
- [sensorforge](https://github.com/0xSoftBoi/sensorforge) — robotics systems work spanning iPhone/ARKit sensor capture, Jetson integration, and a Rust/Metal/CUDA active-inference runtime.
- [suwappubot](https://github.com/0xSoftBoi/suwappubot) — an agent-native cross-chain system spanning provider integrations, SDKs, agent interfaces, and security-critical execution.

## Writing

I wrote [Printing Money](https://tsoma2.gumroad.com/l/printingmoney), a hands-on book about how on-chain systems fail and how to test them; the companion [Foundry labs](https://github.com/0xSoftBoi/printing-money-labs) are public.

[0xsoftboi.github.io](https://0xsoftboi.github.io) · [@0xSoftBoi](https://twitter.com/0xSoftBoi) · layerinfinite@gmail.com
