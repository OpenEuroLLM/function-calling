# OpenEuroLLM Function Calling

This repository is the public index for OpenEuroLLM function-calling post-training, evaluation, and release artifacts. Each software component remains in its own repository so it can preserve its upstream history and development workflow.

## Available components

| Component | Purpose | Release state |
| --- | --- | --- |
| [function-calling-post-training](https://github.com/OpenEuroLLM/function-calling-post-training) | Data preparation, supervised post-training, checkpoint conversion, and active Qwen3.5 experiment code | Public |
| [Qwen3.5 active branch](https://github.com/OpenEuroLLM/function-calling-post-training/tree/codex/qwen35-causal-suite) | Current hardware qualification and controlled experiment implementation | Active work in progress |
| [OLMo 3 historical branch](https://github.com/OpenEuroLLM/function-calling-post-training/tree/olmo3-phase2) | Leonardo-based source snapshot for the five-source OLMo 3 result | Public historical snapshot |
| [OLMo 3 result tag](https://github.com/OpenEuroLLM/function-calling-post-training/tree/olmo3-five-source-result-v1) | Immutable source revision associated with the five-source result | Tagged |
| [tmax-reproduction](https://github.com/OpenEuroLLM/tmax-reproduction) | Code-only work-in-progress snapshot for the TMAX reproduction and transfer study | Public work in progress |
| [bfcl](https://github.com/OpenEuroLLM/bfcl) | OpenEuroLLM fork of the Berkeley Function Calling Leaderboard evaluator | Public |
| [tau2-bench](https://github.com/OpenEuroLLM/tau2-bench) | OpenEuroLLM fork of the tau2-bench evaluator | Public |

## Planned releases

- The OLMo 3 function-calling checkpoint in the [OpenEuroLLM Hugging Face organization](https://huggingface.co/OpenEuroLLM)
- The processed five-source training dataset in the OpenEuroLLM Hugging Face organization

Machine-local evaluation harnesses, operational records, and private research material are outside the scope of this public index.

See [components.yaml](components.yaml) for a machine-readable component list.
