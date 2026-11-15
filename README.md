# GPU Benchmarks

LLM inference benchmarks across GPUs and serving stacks, published at
https://manmohanbrahma.github.io/gpu-benchmark/

| Report | Path |
|---|---|
| Enterprise AI coding on Kimi K3: why the backend network sets the size of the fleet (performance model) | [`kimi-k3-coding-fleet/`](https://manmohanbrahma.github.io/gpu-benchmark/kimi-k3-coding-fleet/) |
| Kimi K3 in FP8 on 16 B300 GPUs: what the network changes as users grow (performance model) | [`kimi-k3-fabric-sweep/`](https://manmohanbrahma.github.io/gpu-benchmark/kimi-k3-fabric-sweep/) |
| Dynamo vs plain vLLM on the Radeon PRO W7900 (same vLLM 0.33.0 ROCm engine) | [`w7900-dynamo-vs-vllm/`](https://manmohanbrahma.github.io/gpu-benchmark/w7900-dynamo-vs-vllm/) |
| AMD GPU fractions in KAI: a hard memory cap at no performance cost (W7900 vs A6000) | [`amd-fraction-dmem-cap/`](https://manmohanbrahma.github.io/gpu-benchmark/amd-fraction-dmem-cap/) |
| Nemotron Nano: NVIDIA RTX A6000 vs AMD Radeon Pro W7900 | [`nemotron-a6000-vs-w7900/`](https://manmohanbrahma.github.io/gpu-benchmark/nemotron-a6000-vs-w7900/) |

To add a benchmark: put its self-contained HTML report in a new folder as `index.html`, then add a card to the root `index.html` and a row here.
