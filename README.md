# GPU Benchmarks

LLM inference benchmarks across GPUs and serving stacks, published at
https://manmohanbrahma.github.io/gpu-benchmark/

| Report | Path |
|---|---|
| Dynamo vs plain vLLM on the Radeon PRO W7900 (same vLLM 0.33.0 ROCm engine) | [`w7900-dynamo-vs-vllm/`](https://openinferencefabric.us.ci/benchmarks/w7900-dynamo-vs-vllm/) (moved; the old path redirects) |
| AMD GPU fractions in KAI: a hard memory cap at no performance cost (W7900 vs A6000) | [`amd-fraction-dmem-cap/`](https://openinferencefabric.us.ci/benchmarks/amd-fraction-dmem-cap/) (moved; the old path redirects) |
| Nemotron Nano: NVIDIA RTX A6000 vs AMD Radeon Pro W7900 | [`nemotron-a6000-vs-w7900/`](https://manmohanbrahma.github.io/gpu-benchmark/nemotron-a6000-vs-w7900/) |

Open Inference Fabric benchmarks now live at https://openinferencefabric.us.ci/benchmarks/ (repo openinferencefabric/openinferencefabric.github.io).

To add a benchmark here: put its self-contained HTML report in a new folder as `index.html`, then add a card to the root `index.html` and a row here.
