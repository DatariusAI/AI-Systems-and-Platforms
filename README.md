# ⚙️ AI Systems and Platforms

A free, self-updating hub on **how AI runs in production**: training and inference systems, MLOps platforms, serving, data infrastructure and GPUs. Research, platforms, code and learning material.
Research and code lists refresh every day from arXiv and GitHub. Curated resources are hand-picked and free.

<!-- STAMP:START -->
_Lists fill in after the first daily refresh._
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
_Loading on first refresh._
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
_Loading on first refresh._
<!-- SERVE:END -->

## 🔁 MLOps platforms and pipelines
Most-starred GitHub repositories updated in the last 12 months.

<!-- MLOPS:START -->
_Loading on first refresh._
<!-- MLOPS:END -->

## 🏋️ Distributed training and GPU infrastructure
Most-starred GitHub repositories updated in the last 12 months.

<!-- TRAIN:START -->
_Loading on first refresh._
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
