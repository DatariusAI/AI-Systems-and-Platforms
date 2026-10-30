# ⚙️ AI Systems and Platforms

A free, self-updating hub on **how AI runs in production**: training and inference systems, MLOps platforms, serving, data infrastructure and GPUs. Research, platforms, code and learning material.
Research and code lists refresh every day from arXiv and GitHub. Curated resources are hand-picked and free.

<!-- STAMP:START -->
_Last refreshed: 2026-10-30 04:31 UTC_
<!-- STAMP:END -->

## Contents
- [Latest research](#-latest-research)
- [Core open-source platforms](#-core-open-source-platforms)
- [Papers that shaped the field](#-papers-that-shaped-the-field)
- [LLM inference and serving](#-llm-inference-and-serving)
- [MLOps platforms and pipelines](#-mlops-platforms-and-pipelines)
- [Distributed training and GPU infrastructure](#-distributed-training-and-gpu-infrastructure)
- [Free learning resources](#-free-learning-resources)
- [How this repo stays fresh](#-how-this-repo-stays-fresh)

## 📄 Latest research
Newest papers on arXiv for this topic, newest first.

<!-- ARXIV:START -->
| Date | Paper | Authors |
|---|---|---|
| 2026-10-27 | [SLICE-CiM: Selective Layer-wise Inference Control Engine with Confidence-Based Early Exit for SRAM based Digital Compute-in-Memory](https://arxiv.org/abs/2610.37601) | Pratham Sharma et al. |
| 2026-10-27 | [Keeping Inference in the Radio: Design and Measurement of a Spiking Accelerator for mmWave ISAC Activity Recognition](https://arxiv.org/abs/2610.37480) | Anthony Sánchez et al. |
| 2026-10-27 | [Request-Adaptive Execution for Efficient Hybrid LLM Inference](https://arxiv.org/abs/2610.37432) | Fahao Chen et al. |
| 2026-10-27 | [AnalogScout: Simulation-Efficient PVT-Aware Analog Sizing with LLM Agents](https://arxiv.org/abs/2610.37319) | Yichen Long et al. |
| 2026-10-27 | [EdgePace: Deadline- and Freshness-Aware LLM Scheduling on Unified-Memory Platforms](https://arxiv.org/abs/2610.37307) | Teng Mei et al. |
| 2026-10-27 | [TAO: Tool-Aware Joint Scheduling for LLM-Based Agentic Serving](https://arxiv.org/abs/2610.37230) | Shuhuai Li et al. |
| 2026-10-27 | [PipeLink: Contract-Guided Linking of GPU Kernel Components](https://arxiv.org/abs/2610.37200) | Jize Guo et al. |
| 2026-10-27 | [Hardware-Matched Spiking Neural Networks for Real-Time Purkinje Cell Spike Classification](https://arxiv.org/abs/2610.37104) | Arooba Farhan et al. |
<!-- ARXIV:END -->

## 🧰 Core open-source platforms

| Platform | Role |
|---|---|
| [vLLM](https://github.com/vllm-project/vllm) | High-throughput LLM inference |
| [Ray](https://github.com/ray-project/ray) | Distributed compute for training, tuning and serving |
| [KServe](https://github.com/kserve/kserve) | Model serving on Kubernetes |
| [Kubeflow](https://github.com/kubeflow/kubeflow) | ML platform on Kubernetes |
| [MLflow](https://github.com/mlflow/mlflow) | Experiment tracking, registry and deployment |
| [Feast](https://github.com/feast-dev/feast) | Feature store |

## 📄 Papers that shaped the field

- [Megatron-LM: Training Multi-Billion Parameter Language Models](https://arxiv.org/abs/1909.08053) (2019)
- [ZeRO: Memory Optimizations Toward Training Trillion Parameter Models](https://arxiv.org/abs/1910.02054) (2019)
- [Challenges in Deploying Machine Learning: a Survey of Case Studies](https://arxiv.org/abs/2011.09926) (2020)
- [FlashAttention: Fast and Memory-Efficient Exact Attention](https://arxiv.org/abs/2205.14135) (2022)
- [Efficient Memory Management for LLM Serving with PagedAttention (vLLM)](https://arxiv.org/abs/2309.06180) (2023)

## 🚀 LLM inference and serving
Most-starred GitHub repositories updated in the last 12 months.

<!-- SERVE:START -->
| Repository | What it is | Language | Stars | Last update |
|---|---|---|---|---|
| [vllm-project/vllm](https://github.com/vllm-project/vllm) | A high-throughput and memory-efficient inference and serving engine for LLMs | Python | 95,878 | 2026-10-30 |
| [sgl-project/sglang](https://github.com/sgl-project/sglang) | SGLang is a high-performance serving framework for large language models and multimodal models. | Python | 38,371 | 2026-10-30 |
| [stas00/ml-engineering](https://github.com/stas00/ml-engineering) | Machine Learning Engineering Open Book | Python | 19,631 | 2026-10-27 |
| [mlc-ai/web-llm](https://github.com/mlc-ai/web-llm) | High-performance In-browser LLM Inference Engine | TypeScript | 19,330 | 2026-10-11 |
| [alibaba/MNN](https://github.com/alibaba/MNN) | MNN: A blazing-fast, lightweight inference engine battle-tested by Alibaba, powering high-performance on-device LLMs and Edge AI. | C++ | 16,310 | 2026-10-30 |
| [kvcache-ai/Mooncake](https://github.com/kvcache-ai/Mooncake) | Mooncake is the serving platform for Kimi, a leading LLM service provided by Moonshot AI. | C++ | 6,923 | 2026-10-30 |
<!-- SERVE:END -->

## 🔁 MLOps platforms and pipelines
Most-starred GitHub repositories updated in the last 12 months.

<!-- MLOPS:START -->
| Repository | What it is | Language | Stars | Last update |
|---|---|---|---|---|
| [apache/airflow](https://github.com/apache/airflow) | Apache Airflow - A platform to programmatically author, schedule, and monitor workflows | Python | 47,315 | 2026-10-30 |
| [mlflow/mlflow](https://github.com/mlflow/mlflow) | The open source AI engineering platform for agents, LLMs, and ML models. MLflow enables teams of all sizes to debug, evaluate, monitor, and  | Python | 28,590 | 2026-10-30 |
| [dagster-io/dagster](https://github.com/dagster-io/dagster) | An orchestration platform for the development, production, and observation of data assets. | Python | 16,351 | 2026-10-30 |
| [wandb/wandb](https://github.com/wandb/wandb) | The AI developer platform. Use Weights & Biases to train and fine-tune models, and manage models from experimentation to production. | Python | 11,310 | 2026-10-29 |
| [skypilot-org/skypilot](https://github.com/skypilot-org/skypilot) | The AI Compute Platform for frontier teams. SkyPilot turns fragmented AI compute into one AI supercomputer, so frontier AI teams build custo | Python | 10,767 | 2026-10-30 |
| [pycaret/pycaret](https://github.com/pycaret/pycaret) | Open-source, low-code AutoML platform for Python. PyCaret 4.0: sklearn-native engine + React control plane. | Python | 9,858 | 2026-07-23 |
<!-- MLOPS:END -->

## 🏋️ Distributed training and GPU infrastructure
Most-starred GitHub repositories updated in the last 12 months.

<!-- TRAIN:START -->
| Repository | What it is | Language | Stars | Last update |
|---|---|---|---|---|
| [huggingface/transformers](https://github.com/huggingface/transformers) | 🤗 Transformers: the model-definition framework for state-of-the-art machine learning models in text, vision, audio, and multimodal models, f | Python | 168,337 | 2026-10-30 |
| [deepspeedai/DeepSpeed](https://github.com/deepspeedai/DeepSpeed) | DeepSpeed is a deep learning optimization library that makes distributed training and inference easy, efficient, and effective. | Python | 43,270 | 2026-10-30 |
| [deepseek-ai/3FS](https://github.com/deepseek-ai/3FS) | A high-performance distributed file system designed to address the challenges of AI training and inference workloads. | C++ | 10,398 | 2026-05-07 |
| [NVIDIA/apex](https://github.com/NVIDIA/apex) | A PyTorch Extension: Tools for easy mixed precision and distributed training in Pytorch | Python | 9,001 | 2026-10-26 |
| [THUDM/slime](https://github.com/THUDM/slime) | slime is an LLM training framework for RL Scaling. | Python | 8,762 | 2026-10-27 |
| [PeterGriffinJin/Search-R1](https://github.com/PeterGriffinJin/Search-R1) | Search-R1: An Efficient, Scalable RL Training Framework for Reasoning & Search Engine Calling interleaved LLM based on veRL | Python | 5,551 | 2025-11-13 |
<!-- TRAIN:END -->

## 📚 Free learning resources

| Resource | Why it's useful |
|---|---|
| [Machine Learning Systems (free book)](https://mlsysbook.ai/) | Harvard's open textbook on ML systems |
| [Deep Learning Systems course (CMU)](https://dlsyscourse.org/) | Build a deep learning framework from scratch |
| [Made With ML](https://madewithml.com/) | MLOps end to end, free |
| [Full Stack Deep Learning](https://fullstackdeeplearning.com/) | Shipping ML products |
| [Introduction to ML Interviews Book](https://huyenchip.com/ml-interviews-book/) | Free book by Chip Huyen, strong on ML systems |

## 🔄 How this repo stays fresh
A GitHub Action runs every day. It queries the public arXiv API for new papers and the GitHub search API for active, popular repositories, then rewrites the lists above. The code is in [`scripts/hub_refresh.py`](scripts/hub_refresh.py) and the search terms are in [`hub.json`](hub.json).

Inclusion in a list is automatic and is not an endorsement. Check each project's license before reuse.

---
Curated by [Mohammad Alrashed](https://github.com/DatariusAI). Part of a series of free AI hubs: see the [profile page](https://github.com/DatariusAI) for industry, cloud and mathematics hubs. Contributions welcome by pull request.
