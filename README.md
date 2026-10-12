# ⚙️ AI Systems and Platforms

A free, self-updating hub on **how AI runs in production**: training and inference systems, MLOps platforms, serving, data infrastructure and GPUs. Research, platforms, code and learning material.
Research and code lists refresh every day from arXiv and GitHub. Curated resources are hand-picked and free.

<!-- STAMP:START -->
_Last refreshed: 2026-10-12 04:50 UTC_
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
| 2026-10-09 | [Scheduling in Cloud,Fog, and Edge Computing: A Comparative Analysis and Decision Framework for Technique Selection](https://arxiv.org/abs/2610.13830) | Rana Ghazali et al. |
| 2026-10-09 | [GPU-resident Execution for Timing-predictable Sensor Processing Systems](https://arxiv.org/abs/2610.13809) | Soham Sinha et al. |
| 2026-10-09 | [Stacked Intelligent Metasurface-Based MultiModal Feature Fusion for Collaborative Inference in Edge Networks](https://arxiv.org/abs/2610.13364) | Yushi Wang et al. |
| 2026-10-09 | [Multi-Source and Multi-Dimensional Information Fusion in Resource-Constrained Edge Networks](https://arxiv.org/abs/2610.13298) | Yushi Wang et al. |
| 2026-10-09 | [Capturing Electrical Windows Through Reconfigurable Optical Networks: Transfer-aware Scheduling of Multi-Region AI Data Centers](https://arxiv.org/abs/2610.13061) | Xi Tong et al. |
| 2026-10-09 | [Execution-Feasible Dispatch of LLM Pre-training Loads for Renewable-Dominant AI Data Centers](https://arxiv.org/abs/2610.13047) | Xi Tong et al. |
| 2026-10-09 | [SlackSwap: Bandwidth-Aware Activation Swapping and Recomputation for Memory-Efficient DNN Training](https://arxiv.org/abs/2610.13003) | Hui Feng et al. |
| 2026-10-09 | [Minions: A Dynamic and Distributed Virtual GPU Cloud Built on Idle Apple Silicon Devices](https://arxiv.org/abs/2610.12970) | Jianhua Li et al. |
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
| [vllm-project/vllm](https://github.com/vllm-project/vllm) | A high-throughput and memory-efficient inference and serving engine for LLMs | Python | 93,601 | 2026-10-12 |
| [sgl-project/sglang](https://github.com/sgl-project/sglang) | SGLang is a high-performance serving framework for large language models and multimodal models. | Python | 37,012 | 2026-10-12 |
| [stas00/ml-engineering](https://github.com/stas00/ml-engineering) | Machine Learning Engineering Open Book | Python | 19,472 | 2026-10-11 |
| [mlc-ai/web-llm](https://github.com/mlc-ai/web-llm) | High-performance In-browser LLM Inference Engine | TypeScript | 19,255 | 2026-10-11 |
| [alibaba/MNN](https://github.com/alibaba/MNN) | MNN: A blazing-fast, lightweight inference engine battle-tested by Alibaba, powering high-performance on-device LLMs and Edge AI. | C++ | 16,208 | 2026-10-10 |
| [kvcache-ai/Mooncake](https://github.com/kvcache-ai/Mooncake) | Mooncake is the serving platform for Kimi, a leading LLM service provided by Moonshot AI. | C++ | 6,767 | 2026-10-12 |
<!-- SERVE:END -->

## 🔁 MLOps platforms and pipelines
Most-starred GitHub repositories updated in the last 12 months.

<!-- MLOPS:START -->
| Repository | What it is | Language | Stars | Last update |
|---|---|---|---|---|
| [apache/airflow](https://github.com/apache/airflow) | Apache Airflow - A platform to programmatically author, schedule, and monitor workflows | Python | 47,147 | 2026-10-12 |
| [mlflow/mlflow](https://github.com/mlflow/mlflow) | The open source AI engineering platform for agents, LLMs, and ML models. MLflow enables teams of all sizes to debug, evaluate, monitor, and  | Python | 28,347 | 2026-10-12 |
| [dagster-io/dagster](https://github.com/dagster-io/dagster) | An orchestration platform for the development, production, and observation of data assets. | Python | 16,268 | 2026-10-09 |
| [wandb/wandb](https://github.com/wandb/wandb) | The AI developer platform. Use Weights & Biases to train and fine-tune models, and manage models from experimentation to production. | Python | 11,275 | 2026-10-11 |
| [skypilot-org/skypilot](https://github.com/skypilot-org/skypilot) | The AI Compute Platform for frontier teams. SkyPilot turns fragmented AI compute into one AI supercomputer, so frontier AI teams build custo | Python | 10,696 | 2026-10-12 |
| [pycaret/pycaret](https://github.com/pycaret/pycaret) | Open-source, low-code AutoML platform for Python. PyCaret 4.0: sklearn-native engine + React control plane. | Python | 9,851 | 2026-07-23 |
<!-- MLOPS:END -->

## 🏋️ Distributed training and GPU infrastructure
Most-starred GitHub repositories updated in the last 12 months.

<!-- TRAIN:START -->
| Repository | What it is | Language | Stars | Last update |
|---|---|---|---|---|
| [huggingface/transformers](https://github.com/huggingface/transformers) | 🤗 Transformers: the model-definition framework for state-of-the-art machine learning models in text, vision, audio, and multimodal models, f | Python | 167,529 | 2026-10-12 |
| [deepspeedai/DeepSpeed](https://github.com/deepspeedai/DeepSpeed) | DeepSpeed is a deep learning optimization library that makes distributed training and inference easy, efficient, and effective. | Python | 43,216 | 2026-10-12 |
| [deepseek-ai/3FS](https://github.com/deepseek-ai/3FS) | A high-performance distributed file system designed to address the challenges of AI training and inference workloads. | C++ | 10,277 | 2026-05-07 |
| [NVIDIA/apex](https://github.com/NVIDIA/apex) | A PyTorch Extension: Tools for easy mixed precision and distributed training in Pytorch | Python | 9,004 | 2026-10-05 |
| [THUDM/slime](https://github.com/THUDM/slime) | slime is an LLM post-training framework for RL Scaling. | Python | 8,633 | 2026-10-10 |
| [higgsfield-ai/higgsfield](https://github.com/higgsfield-ai/higgsfield) | Fault-tolerant, highly scalable GPU orchestration, and a machine learning framework designed for training models with billions to trillions  | Jupyter Notebook | 5,956 | 2026-10-07 |
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
