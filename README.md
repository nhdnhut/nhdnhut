# Nguyen Huynh Dang Nhut (@nhdnhut)

> **Artificial Intelligence Researcher · Low-Level Systems Architect · Open-Source Contributor**  
> **University of Information Technology (UIT), VNU-HCM**  
> 🌐 Portfolio: [nhdnhut.github.io](https://nhdnhut.github.io) | 💼 LinkedIn: [linkedin.com/in/dangnhutnguyen](https://www.linkedin.com/in/dangnhutnguyen/) | 📧 Email: [dangnhutnguyen.work@gmail.com](mailto:dangnhutnguyen.work@gmail.com)

[![Portfolio](https://img.shields.io/badge/Portfolio-nhdnhut.github.io-0969da?style=flat-square&logo=googlechrome&logoColor=white)](https://nhdnhut.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dangnhutnguyen-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dangnhutnguyen/)
[![GitHub](https://img.shields.io/badge/GitHub-nhdnhut-24292e?style=flat-square&logo=github&logoColor=white)](https://github.com/nhdnhut)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0009--6305--478X-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0009-6305-478X)

---

## 1. Executive Summary

I am an Artificial Intelligence researcher and systems engineer specializing in **Large Language Model (LLM) acceleration, neural compression, hardware-aware execution policies, first-principles deep learning, and secure telecommunication protocol telemetry**.

My research and engineering practice focuses on:
- **LLM Speculative Decoding & Acceleration**: Draft model distillation, parameter-efficient fine-tuning (LoRA), and BitsAndBytes NF4/INT8 quantization schedules on constrained hardware (NVIDIA T4 / CPU).
- **Hardware-Aware Neural Network Compression**: Analytical post-training quantization (INT8 PTQ), structured L1 filter pruning, and low-rank tensor decomposition (SVD).
- **Sequence-to-Sequence & NLP Architecture**: Custom Transformer architectures from scratch with Google SentencePiece subword tokenization and length-penalized beam search.
- **First-Principles Deep Learning**: Analytical backpropagation routines without autograd black-boxes, verified with finite-difference gradient checks ($< 10^{-6}$).
- **High-Performance Distributed Systems & Protocol Telemetry**: Zero-copy I/O, authenticated binary packet framing (AES-256-GCM), anti-replay guards, and asynchronous concurrency invariants.

---

## 2. Flagship Research Initiatives & Open-Source Repositories

| Domain | Repository | Architecture & Technologies | Test Coverage |
| :--- | :--- | :--- | :--- |
| **LLM Acceleration** | [t4-speculative-decoding](https://github.com/nhdnhut/t4-speculative-decoding) | Qwen Speculative Decoding, BitsAndBytes NF4/INT8, LoRA Distillation | GPU Validated |
| **LLM Latency Profiling** | [gemma4-t4-inference-benchmarks](https://github.com/nhdnhut/gemma4-t4-inference-benchmarks) | Gemma Quantization, Random Forest Latency Predictor, Ollama Harness | 15 Tests PASS |
| **Efficient AI / Compression** | [neural-compression-cpu-benchmarks](https://github.com/nhdnhut/neural-compression-cpu-benchmarks) | PyTorch, INT8 PTQ, L1 Structured Pruning, SVD Low-Rank | 32 Tests PASS |
| **Memory Scheduling** | [wari-adaptive-inference](https://github.com/nhdnhut/wari-adaptive-inference) | WARI-L Working-set Layer-Granule Residual CPU Inference Policy | 7 Tests PASS |
| **Neural Machine Translation**| [zh-vi-transformer-nmt](https://github.com/nhdnhut/zh-vi-transformer-nmt) | PyTorch Transformer Seq2Seq, Google SentencePiece, SacreBLEU, Beam Search | 3 Tests PASS |
| **Olympic AI Curriculum** | [voai-olympic-ai-course](https://github.com/nhdnhut/voai-olympic-ai-course) | 38 Jupyter Notebooks, M0-M7 Curriculum, PyTorch, Scikit-Learn | 4 Tests PASS |
| **Active Learning** | [adaptive-sample-selection](https://github.com/nhdnhut/adaptive-sample-selection) | Uncertainty Sampling, SmallCNN Budget Framework, LaTeX Manuscript | 49 Tests PASS |
| **First-Principles AI** | [neural-observatory](https://github.com/nhdnhut/neural-observatory) | From-scratch Neural Network (NumPy / Pure Python), HTML5 Canvas Inspection | 5 Tests PASS |
| **Interpretable Neural Nets** | [neural-network-from-scratch](https://github.com/nhdnhut/neural-network-from-scratch) | Analytical Backpropagation, Finite-Difference Gradient Check ($< 10^{-6}$) | 4 Tests PASS |
| **Autoregressive Generation** | [pixelbudget-autoregressive-generation](https://github.com/nhdnhut/pixelbudget-autoregressive-generation) | CPU-Validated Pixel Budget Allocation, Autoregressive Synthesis | 3 Tests PASS |
| **Applied ML Coursework** | [applied-ml-coursework-labs](https://github.com/nhdnhut/applied-ml-coursework-labs) | Pima Diabetes Classification, Exploratory Data Analysis, ROC-AUC Tuning | 2 Tests PASS |
| **Interactive Pedagogy** | [interactive-ml-learning-platform](https://github.com/nhdnhut/interactive-ml-learning-platform) | Next.js 16 Turbopack, React 19, Tailwind CSS, KaTeX | Production Built |
| **Prompt Engineering** | [promptea-prompt-optimization](https://github.com/nhdnhut/promptea-prompt-optimization) | Language Model Prompt Optimization Framework using NLP & ML | Production |
| **Protocol Telemetry & Security**| [secure-binary-protocol-framework](https://github.com/nhdnhut/secure-binary-protocol-framework) | Authenticated 6-byte Header Framing, AES-256-GCM, Anti-Replay Guard | 3 Tests PASS |
| **Program Analysis & AST** | [pyobfuscate-static-inspector](https://github.com/nhdnhut/pyobfuscate-static-inspector) | AST Control Flow Graph Recovery, Constant Propagation Sandbox | 51 Tests PASS |
| **High-Concurrency Systems** | [boconic-book-sharing-platform](https://github.com/nhdnhut/boconic-book-sharing-platform) | FastAPI 0.110+, SQLAlchemy 2.0 Async, aiogram 3.x, Docker, PostgreSQL | 66 Tests PASS |
| **3D Heritage Engineering** | [sac-viet-heritage-studio](https://github.com/nhdnhut/sac-viet-heritage-studio) | Next.js 15, React 19, Three.js, React Three Fiber, SQLite WAL | 23 Tests PASS |
| **Knowledge Operating System** | [neuralwork-knowledge-os](https://github.com/nhdnhut/neuralwork-knowledge-os) | TypeScript 5 Monorepo, Node.js Native SQLite WAL, FTS5 BM25 | 5 Tests PASS |
| **Scientific Computing** | [conservative-force-simulation](https://github.com/nhdnhut/conservative-force-simulation) | Runge-Kutta RK45 ODE Solver, SymPy, CustomTkinter GUI, MATLAB | 5 Tests PASS |
| **Productivity Systems** | [focumia-productivity-os](https://github.com/nhdnhut/focumia-productivity-os) | Client-side Deep Work Pomodoro & Task Hierarchy Workspace | Production |
| **MIL Learning OS** | [dailynox-learning-os](https://github.com/nhdnhut/dailynox-learning-os) | UNESCO Media & Information Literacy Framework Implementation | Production |
| **Minimalist Workspace** | [writedownia-notes-workspace](https://github.com/nhdnhut/writedownia-notes-workspace) | Distraction-free Browser Journal, Notes & Spaced Repetition Decks | Production |

---

## 3. Academic Manuscripts & Publications

- **LogicPT–GT**: Research on formal logic, problem solving, structured thinking, and automated problem transformation.  
  [Read Manuscript (PDF)](https://drive.google.com/file/d/1NYF5sJFUI2zlBwd7wX-CcVM0hKcQ95es/view)

---

## 4. Engineering & Research Principles

1. **First-Principles Reasoning**: Break down computational bottlenecks to physical machine constraints — CPU execution cycles, memory hierarchy (L1/L2/L3 cache lines `alignas(64)`), and kernel syscall boundaries.
2. **Deterministic Verification**: Every research codebase maintains comprehensive automated test suites with deterministic mathematical validation (finite difference, unit tests, and performance benchmarks).
3. **Open-Source Excellence**: Strict static typing, zero-truncation production code, and clear architectural documentation across every published repository.
