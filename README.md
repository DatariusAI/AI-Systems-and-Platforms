# ⚙️ AI Systems and Platforms

A free, self-updating hub on **how AI runs in production**: training and inference systems, MLOps platforms, serving, data infrastructure and GPUs. Research, platforms, code and learning material.
Research and code lists refresh every day from arXiv and GitHub. Curated resources are hand-picked and free.

<!-- STAMP:START -->
_Last refreshed: 2026-11-19 04:29 UTC_
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
| 2026-11-18 | [Mechanistic Critics for Sample-Efficient NPU Design-Space Exploration](https://arxiv.org/abs/2611.24733) | Yicheng He et al. |
| 2026-11-18 | [Hypnos: A Dual-Phase End-to-End Platform for Scalable Continual Learning at the Edge](https://arxiv.org/abs/2611.24637) | Guilherme Guedes et al. |
| 2026-11-18 | [Harvesting Expert-Parallel Bubbles for Fine-Tuning](https://arxiv.org/abs/2611.24496) | Oana Balmau et al. |
| 2026-11-18 | [Dissecting an Unexplored SASS Control-Code Field: Barrier Exemption and Programmable Warp Priority](https://arxiv.org/abs/2611.24437) | Ziwen Wang et al. |
| 2026-11-18 | [How to Turn an Attention Neural Network into an Interpretable Hard-Logic Predicate Circuit: Truth-Table Predicate Extraction and State-Machine Merging under Ship-of-Theseus Replacement](https://arxiv.org/abs/2611.24381) | Yuchen Li et al. |
| 2026-11-18 | [OpenGNS: An Open Dataset of the Gradient Noise Scale across Vision, Language, and Diffusion Models](https://arxiv.org/abs/2611.24331) | Marcel Aach et al. |
| 2026-11-18 | [Hardware Acceleration of Vision-Language-Action Models with Weight Precision Rising over the Flow Steps](https://arxiv.org/abs/2611.24234) | Robin Geens et al. |
| 2026-11-18 | [LEDGE: An Efficient Simulator for Distributed LLM Serving on Heterogeneous Edge Devices](https://arxiv.org/abs/2611.24085) | Zihao Wang et al. |
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
| [vllm-project/vllm](https://github.com/vllm-project/vllm) | A high-throughput and memory-efficient inference and serving engine for LLMs | Python | 97,192 | 2026-11-19 |
| [sgl-project/sglang](https://github.com/sgl-project/sglang) | SGLang is a high-performance serving framework for large language models and multimodal models. | Python | 39,044 | 2026-11-19 |
| [stas00/ml-engineering](https://github.com/stas00/ml-engineering) | Machine Learning Engineering Open Book | Python | 19,732 | 2026-11-18 |
| [mlc-ai/web-llm](https://github.com/mlc-ai/web-llm) | High-performance In-browser LLM Inference Engine | TypeScript | 19,390 | 2026-11-18 |
| [alibaba/MNN](https://github.com/alibaba/MNN) | MNN: A blazing-fast, lightweight inference engine battle-tested by Alibaba, powering high-performance on-device LLMs and Edge AI. | C++ | 16,574 | 2026-11-18 |
| [xorbitsai/inference](https://github.com/xorbitsai/inference) | Open-source inference platform for language, vision, embedding, reranking, image, audio, and video models. Deploy with multiple engines acro | Python | 9,665 | 2026-11-18 |
<!-- SERVE:END -->

## 🔁 MLOps platforms and pipelines
Most-starred GitHub repositories updated in the last 12 months.

<!-- MLOPS:START -->
| Repository | What it is | Language | Stars | Last update |
|---|---|---|---|---|
| [apache/airflow](https://github.com/apache/airflow) | Apache Airflow - A platform to programmatically author, schedule, and monitor workflows | Python | 47,536 | 2026-11-19 |
| [mlflow/mlflow](https://github.com/mlflow/mlflow) | The open source AI engineering platform for agents, LLMs, and ML models. MLflow enables teams of all sizes to debug, evaluate, monitor, and  | Python | 28,876 | 2026-11-19 |
| [dagster-io/dagster](https://github.com/dagster-io/dagster) | An orchestration platform for the development, production, and observation of data assets. | Python | 16,444 | 2026-11-18 |
| [wandb/wandb](https://github.com/wandb/wandb) | The AI developer platform. Use Weights & Biases to train and fine-tune models, and manage models from experimentation to production. | Python | 11,328 | 2026-11-19 |
| [skypilot-org/skypilot](https://github.com/skypilot-org/skypilot) | The AI Compute Platform for frontier teams. SkyPilot turns fragmented AI compute into one AI supercomputer, so frontier AI teams build custo | Python | 10,855 | 2026-11-19 |
| [pycaret/pycaret](https://github.com/pycaret/pycaret) | Open-source, low-code AutoML platform for Python. PyCaret 4.0: sklearn-native engine + React control plane. | Python | 9,864 | 2026-07-23 |
<!-- MLOPS:END -->

## 🏋️ Distributed training and GPU infrastructure
Most-starred GitHub repositories updated in the last 12 months.

<!-- TRAIN:START -->
| Repository | What it is | Language | Stars | Last update |
|---|---|---|---|---|
| [huggingface/transformers](https://github.com/huggingface/transformers) | 🤗 Transformers: the model-definition framework for state-of-the-art machine learning models in text, vision, audio, and multimodal models, f | Python | 169,198 | 2026-11-19 |
| [deepspeedai/DeepSpeed](https://github.com/deepspeedai/DeepSpeed) | DeepSpeed is a deep learning optimization library that makes distributed training and inference easy, efficient, and effective. | Python | 43,339 | 2026-11-19 |
| [pingcap/talent-plan](https://github.com/pingcap/talent-plan) | open source training courses about distributed database and distributed systems | Rust | 11,053 | 2026-11-02 |
| [deepseek-ai/3FS](https://github.com/deepseek-ai/3FS) | A high-performance distributed file system designed to address the challenges of AI training and inference workloads. | C++ | 10,484 | 2026-11-17 |
| [NVIDIA/apex](https://github.com/NVIDIA/apex) | A PyTorch Extension: Tools for easy mixed precision and distributed training in Pytorch | Python | 9,008 | 2026-11-17 |
| [THUDM/slime](https://github.com/THUDM/slime) | slime is an LLM training framework for RL Scaling. | Python | 8,845 | 2026-11-05 |
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
