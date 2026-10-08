# ⚙️ AI Systems and Platforms

A free, self-updating hub on **how AI runs in production**: training and inference systems, MLOps platforms, serving, data infrastructure and GPUs. Research, platforms, code and learning material.
Research and code lists refresh every day from arXiv and GitHub. Curated resources are hand-picked and free.

<!-- STAMP:START -->
_Last refreshed: 2026-10-08 15:39 UTC_
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
| 2026-10-07 | [LOCAA: An Agentic System for Automated Lossy Compressor Tuning](https://arxiv.org/abs/2610.10487) | Khondoker Mirazul Mumenin et al. |
| 2026-10-07 | [SUSpMV: A High Frequency Sparse Matrix Vector Multiplier on HBM Enabled FPGA written in SUS](https://arxiv.org/abs/2610.10403) | Lennart Van Hirtum et al. |
| 2026-10-07 | [Fault-tolerant foundation models](https://arxiv.org/abs/2610.10311) | Trevor McCourt et al. |
| 2026-10-07 | [ReSAFT: An Efficient Stuck-at Fault-Tolerant Scheme for ReRAM-based Process-in-Memory Accelerators](https://arxiv.org/abs/2610.09999) | Aniseh Dorostkar et al. |
| 2026-10-07 | [Reproducible LLM Inference Benchmarking: A Sequential Isolation Protocol for Regression Testing](https://arxiv.org/abs/2610.09778) | Arnold Olympio et al. |
| 2026-10-07 | [AeroEval: Staged Program and Execution Validation for AI-Generated Drone Missions](https://arxiv.org/abs/2610.09764) | Kautuk Astu et al. |
| 2026-10-07 | [Fast and Memory Efficient Offload Training Framework with Hybrid XPU Computation](https://arxiv.org/abs/2610.09657) | Zhiyi Yao et al. |
| 2026-10-07 | [Differential Refresh Policies for Models Trained on Lagging Data Snapshots: From a Single-Age Equivalence Limit to an Optimal Per-Segment Allocation](https://arxiv.org/abs/2610.09519) | Amit Rajula |
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
| [vllm-project/vllm](https://github.com/vllm-project/vllm) | A high-throughput and memory-efficient inference and serving engine for LLMs | Python | 93,397 | 2026-10-08 |
| [sgl-project/sglang](https://github.com/sgl-project/sglang) | SGLang is a high-performance serving framework for large language models and multimodal models. | Python | 36,875 | 2026-10-08 |
| [stas00/ml-engineering](https://github.com/stas00/ml-engineering) | Machine Learning Engineering Open Book | Python | 19,410 | 2026-10-08 |
| [mlc-ai/web-llm](https://github.com/mlc-ai/web-llm) | High-performance In-browser LLM Inference Engine | TypeScript | 19,246 | 2026-10-03 |
| [alibaba/MNN](https://github.com/alibaba/MNN) | MNN: A blazing-fast, lightweight inference engine battle-tested by Alibaba, powering high-performance on-device LLMs and Edge AI. | C++ | 16,192 | 2026-10-08 |
| [kvcache-ai/Mooncake](https://github.com/kvcache-ai/Mooncake) | Mooncake is the serving platform for Kimi, a leading LLM service provided by Moonshot AI. | C++ | 6,737 | 2026-10-08 |
<!-- SERVE:END -->

## 🔁 MLOps platforms and pipelines
Most-starred GitHub repositories updated in the last 12 months.

<!-- MLOPS:START -->
| Repository | What it is | Language | Stars | Last update |
|---|---|---|---|---|
| [apache/airflow](https://github.com/apache/airflow) | Apache Airflow - A platform to programmatically author, schedule, and monitor workflows | Python | 47,118 | 2026-10-08 |
| [mlflow/mlflow](https://github.com/mlflow/mlflow) | The open source AI engineering platform for agents, LLMs, and ML models. MLflow enables teams of all sizes to debug, evaluate, monitor, and  | Python | 28,313 | 2026-10-08 |
| [dagster-io/dagster](https://github.com/dagster-io/dagster) | An orchestration platform for the development, production, and observation of data assets. | Python | 16,255 | 2026-10-08 |
| [wandb/wandb](https://github.com/wandb/wandb) | The AI developer platform. Use Weights & Biases to train and fine-tune models, and manage models from experimentation to production. | Python | 11,274 | 2026-10-08 |
| [skypilot-org/skypilot](https://github.com/skypilot-org/skypilot) | The AI Compute Platform for frontier teams. SkyPilot turns fragmented AI compute into one AI supercomputer, so frontier AI teams build custo | Python | 10,685 | 2026-10-08 |
| [pycaret/pycaret](https://github.com/pycaret/pycaret) | Open-source, low-code AutoML platform for Python. PyCaret 4.0: sklearn-native engine + React control plane. | Python | 9,851 | 2026-07-23 |
<!-- MLOPS:END -->

## 🏋️ Distributed training and GPU infrastructure
Most-starred GitHub repositories updated in the last 12 months.

<!-- TRAIN:START -->
| Repository | What it is | Language | Stars | Last update |
|---|---|---|---|---|
| [huggingface/transformers](https://github.com/huggingface/transformers) | 🤗 Transformers: the model-definition framework for state-of-the-art machine learning models in text, vision, audio, and multimodal models, f | Python | 167,059 | 2026-10-08 |
| [deepspeedai/DeepSpeed](https://github.com/deepspeedai/DeepSpeed) | DeepSpeed is a deep learning optimization library that makes distributed training and inference easy, efficient, and effective. | Python | 43,208 | 2026-10-08 |
| [deepseek-ai/3FS](https://github.com/deepseek-ai/3FS) | A high-performance distributed file system designed to address the challenges of AI training and inference workloads. | C++ | 10,271 | 2026-05-07 |
| [NVIDIA/apex](https://github.com/NVIDIA/apex) | A PyTorch Extension: Tools for easy mixed precision and distributed training in Pytorch | Python | 9,005 | 2026-10-05 |
| [THUDM/slime](https://github.com/THUDM/slime) | slime is an LLM post-training framework for RL Scaling. | Python | 8,604 | 2026-10-08 |
| [higgsfield-ai/higgsfield](https://github.com/higgsfield-ai/higgsfield) | Fault-tolerant, highly scalable GPU orchestration, and a machine learning framework designed for training models with billions to trillions  | Jupyter Notebook | 5,902 | 2026-10-07 |
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
