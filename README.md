# GPU Benchmarks & Model Reference

In-and-out reference docs for the models and diagnostic tests run across GPU fleets — architecture, tuning parameters, real sourced benchmark numbers, and interactive explorers where the data supports it.

[**Open the guide →**](https://pravinhpc.github.io/gpu-benchmarks-reference/)

## Contents

### Model training benchmarks

| Page | Covers |
|---|---|
| [Nemotron](https://pravinhpc.github.io/gpu-benchmarks-reference/#nemotron) | NVIDIA's open LLM family — what/why, training→inference pipeline, evaluation, all model variants, resources |
| [Megatron-LM & Megatron-Core](https://pravinhpc.github.io/gpu-benchmarks-reference/#megatron) | 5D parallelism (TP/PP/DP/SP/CP/EP), config parameters, real MFU benchmarks + interactive MFU explorer |

### Communication / fabric

| Page | Covers |
|---|---|
| [NCCL & nccl-tests](https://pravinhpc.github.io/gpu-benchmarks-reference/#nccl) | Collective comms library — ring/tree/NVLS algorithms, env-var tuning, all test types, busbw interpretation, nvbandwidth vs. collective bandwidth, cross-CSP notes, interactive benchmark explorer |

### Compute benchmarks

| Page | Covers |
|---|---|
| [HPL / LINPACK](https://pravinhpc.github.io/gpu-benchmarks-reference/#hpl) | Top500 dense linear algebra benchmark — N/NB/P×Q tuning, HPL vs HPL-AI/MxP vs HPCG, real TOP500 numbers, P×Q grid calculator |
| [MLPerf Training & Inference](https://pravinhpc.github.io/gpu-benchmarks-reference/#mlperf) | Real end-to-end AI workload benchmark — Closed/Open divisions, GB300 vs GB200 results, cross-vendor comparison vs AMD Instinct |

### Stress / burn-in

| Page | Covers |
|---|---|
| [gpu-burn & DCGM Diagnostics](https://pravinhpc.github.io/gpu-benchmarks-reference/#gpu-burn) | GPU stress-test / thermal-throttle & correctness burn-in, plus DCGM diag levels 1-4 + EUD with real timing data |

### GPU vendors

| Page | Covers |
|---|---|
| [AMD Instinct & ROCm](https://pravinhpc.github.io/gpu-benchmarks-reference/#amd) | MI300X→MI400 hardware, Infinity Fabric mesh topology, ROCm/RCCL/AMD-SMI/RVS tooling, AMD's Megatron fork, Instella open models, real cluster acceptance thresholds |

### Real HPC application benchmarks

| Page | Covers |
|---|---|
| [LAMMPS / GROMACS / NAMD](https://pravinhpc.github.io/gpu-benchmarks-reference/#md-benchmarks) | Real molecular-dynamics application benchmarks — GPU acceleration approach per tool, real GROMACS/NAMD ns/day numbers across H100/GH200/A100 |
| [GPUDirect Storage / gdsio](https://pravinhpc.github.io/gpu-benchmarks-reference/#gpudirect-storage) | Direct DMA storage-to-GPU I/O — architecture, cufile.json config, silent fallback trap, gdsio benchmark tool, real checkpoint/model-load speedups |

### Model landscape

| Page | Covers |
|---|---|
| [Open Model Landscape](https://pravinhpc.github.io/gpu-benchmarks-reference/#open-model-landscape) | Cross-vendor comparison — Llama 4/Qwen3/DeepSeek/GLM/Gemma/Mistral/Grok/Phi-4/OLMo — licenses, dense vs. MoE, leaderboard caveats, how to choose |

## Viewing

**Live site:** https://pravinhpc.github.io/gpu-benchmarks-reference/

## Sources

Every benchmark number is sourced from public vendor docs, academic papers, GitHub issues, or vendor blogs — cited inline per page. Nothing is simulated; where only a single data point exists, the pages say so explicitly rather than interpolating a false trend.
