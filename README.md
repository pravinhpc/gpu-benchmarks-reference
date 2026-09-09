# GPU Benchmarks & Model Reference

In-and-out reference docs for the models and diagnostic tests run across GPU fleets — architecture, tuning parameters, real sourced benchmark numbers, and interactive explorers where the data supports it.

[**Open the guide →**](https://pravinhpc.github.io/gpu-benchmarks-reference/)

## Contents

| Page | Covers |
|---|---|
| [Nemotron](https://pravinhpc.github.io/gpu-benchmarks-reference/nemotron.html) | NVIDIA's open LLM family — what/why, training→inference pipeline, evaluation, all model variants, resources |
| [Megatron-LM & Megatron-Core](https://pravinhpc.github.io/gpu-benchmarks-reference/megatron.html) | 5D parallelism (TP/PP/DP/SP/CP/EP), config parameters, real MFU benchmarks + interactive MFU explorer |
| [NCCL & nccl-tests](https://pravinhpc.github.io/gpu-benchmarks-reference/nccl.html) | Collective comms library — ring/tree/NVLS algorithms, env-var tuning, all test types, busbw interpretation, cross-CSP notes, interactive benchmark explorer |
| [HPL / LINPACK](https://pravinhpc.github.io/gpu-benchmarks-reference/hpl.html) | Top500 dense linear algebra benchmark — N/NB/P×Q tuning, HPL vs HPL-AI/MxP vs HPCG, real TOP500 numbers, P×Q grid calculator |
| [gpu-burn & DCGM Diagnostics](https://pravinhpc.github.io/gpu-benchmarks-reference/gpu-burn.html) | GPU stress-test / thermal-throttle & correctness burn-in, plus DCGM diag levels 1-4 + EUD with real timing data |

## Viewing

**Live site:** https://pravinhpc.github.io/gpu-benchmarks-reference/

To view locally, just open `index.html` in a browser — no build step required.

## Sources

Every benchmark number is sourced from public vendor docs, academic papers, GitHub issues, or vendor blogs — cited inline per page. Nothing is simulated; where only a single data point exists, the pages say so explicitly rather than interpolating a false trend.
