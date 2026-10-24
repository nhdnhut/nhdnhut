# Nguyen Huynh Dang Nhut (@nhutnhd)

> Artificial Intelligence Researcher · Low-Level Systems Architect · Open-Source Contributor
> University of Information Technology (UIT), VNU-HCM
> Official Portfolio: [nhutnhd.github.io](https://nhutnhd.github.io) | LinkedIn: [linkedin.com/in/dangnhutnguyen](https://www.linkedin.com/in/dangnhutnguyen/) | Email: [penciltalk0910@gmail.com](mailto:penciltalk0910@gmail.com)

[![Portfolio](https://img.shields.io/badge/Portfolio-nhutnhd.github.io-0969da?style=flat-square&logo=googlechrome&logoColor=white)](https://nhutnhd.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dangnhutnguyen-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dangnhutnguyen/)
[![GitHub](https://img.shields.io/badge/GitHub-nhutnhd-24292e?style=flat-square&logo=github&logoColor=white)](https://github.com/nhutnhd)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0009--6305--478X-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0009-6305-478X)

---

## 1. Executive Summary

I am an AI researcher and software systems architect specializing in efficient deep learning, neural network compression, low-level execution policies, and mathematically rigorous machine learning from first principles.

My research and engineering practice focuses on:
- Hardware-aware neural network compression (INT8 post-training quantization, structured pruning, and low-rank tensor decomposition).
- Speculative decoding acceleration, draft model distillation, and parameter-efficient fine-tuning on resource-constrained hardware.
- First-principles mathematical implementation of deep learning algorithms without opaque autograd abstractions.
- Local-first, high-concurrency software architectures with strict memory safety and deterministic invariants.

---

## 2. Flagship Research Initiatives & Open-Source Repositories

| Domain | Repository | Architecture & Technologies | Status |
| :--- | :--- | :--- | :--- |
| Efficient AI / Compression | [neural-compression-cpu-benchmarks](https://github.com/nhutnhd/neural-compression-cpu-benchmarks) | PyTorch, INT8 PTQ, L1 Structured Pruning, SVD Low-Rank | Production · 32 Tests |
| LLM Acceleration | [t4-speculative-decoding](https://github.com/nhutnhd/t4-speculative-decoding) | Qwen Speculative Decoding, BitsAndBytes NF4/INT8, LoRA Distillation | Production · GPU Validated |
| LLM Latency Profiling | [gemma4-t4-inference-benchmarks](https://github.com/nhutnhd/gemma4-t4-inference-benchmarks) | Gemma Quantization, Random Forest Latency Predictor, Ollama Harness | Production · 15 Tests |
| First-Principles AI | [neural-observatory](https://github.com/nhutnhd/neural-observatory) | From-scratch Neural Network (NumPy / Pure Python), HTML5 Canvas Inspection | Production · 5 Tests |
| Interpretable Neural Nets | [neural-network-from-scratch](https://github.com/nhutnhd/neural-network-from-scratch) | Analytical Backpropagation, Finite-Difference Gradient Check ($< 10^{-6}$), MNIST | Production · 4 Tests |
| Active Learning | [adaptive-sample-selection](https://github.com/nhutnhd/adaptive-sample-selection) | Uncertainty Sampling, SmallCNN Budget Framework, LaTeX Manuscript | Production · 49 Tests |
| Memory Scheduling | [wari-adaptive-inference](https://github.com/nhutnhd/wari-adaptive-inference) | WARI-L Working-set Layer-Granule Residual CPU Inference Policy | Production · 7 Tests |
| High-Concurrency Systems | [boconic-book-sharing-platform](https://github.com/nhutnhd/boconic-book-sharing-platform) | FastAPI 0.110+, SQLAlchemy 2.0 Async, aiogram 3.x, Docker, PostgreSQL | Production · 66 Tests |
| 3D Heritage Engineering | [sac-viet-heritage-studio](https://github.com/nhutnhd/sac-viet-heritage-studio) | Next.js 15, React 19, Three.js, React Three Fiber, SQLite WAL | Production · 23 Tests |
| Knowledge Operating System | [neuralwork-knowledge-os](https://github.com/nhutnhd/neuralwork-knowledge-os) | TypeScript 5 Monorepo, Node.js Native SQLite WAL, FTS5 BM25 | Production · 5 Tests |
| Defensive Code Analysis | [pyobfuscate-static-inspector](https://github.com/nhutnhd/pyobfuscate-static-inspector) | AST Control Flow Graph Recovery, Constant Propagation Sandbox | Archived Reference · 51 Tests |
| Telemetry & Network Framing | [c2-protocol-simulation-framework](https://github.com/nhutnhd/c2-protocol-simulation-framework) | Authenticated 6-byte Header Framing, AES-256-GCM, Anti-Replay Guard | Archived Reference · 3 Tests |
| Scientific Computing | [conservative-force-simulation](https://github.com/nhutnhd/conservative-force-simulation) | Runge-Kutta RK45 ODE Solver, SymPy, CustomTkinter GUI, MATLAB | Production · 5 Tests |
| Interactive Pedagogy | [interactive-ml-learning-platform](https://github.com/nhutnhd/interactive-ml-learning-platform) | Next.js 16 Turbopack, React 19, Tailwind CSS, KaTeX | Production · Built |
| Prompt Engineering | [PrompTEA](https://github.com/nhutnhd/PrompTEA) | Language Model Prompt Optimization Framework using NLP & ML | Production |
| Productivity Systems | [Focumia](https://github.com/nhutnhd/Focumia) | Client-side Deep Work Pomodoro & Task Hierarchy Workspace | Production |
| MIL Learning OS | [dailynox](https://github.com/nhutnhd/dailynox) | UNESCO Media & Information Literacy Framework Implementation | Production |
| Minimalist Workspace | [writedownia](https://github.com/nhutnhd/writedownia) | Distraction-free Browser Journal, Notes & Spaced Repetition Decks | Production |

---

## 3. Academic Papers & Research Manuscripts

- **LogicPT–GT**: Research on formal logic, problem solving, structured thinking, and automated problem transformation.  
  [Read Manuscript (PDF)](https://drive.google.com/file/d/1NYF5sJFUI2zlBwd7wX-CcVM0hKcQ95es/view)

- **AIAPE–Education**: Framework investigating artificial intelligence, computer science education, and pedagogical feedback loops.  
  [Access Research Assets & Documentation](https://drive.google.com/drive/folders/1sKKR-0nAkkW8pxi9hwmYsg33vJEzTD71)

- **Concentrated Solar Thermal Modeling & Tracking System**: Dual-axis solar tracking concentrator coupling geometric optics, differential calculus, and empirical thermodynamic flux validation.  
  [Access Dataset & Field Measurements](https://drive.google.com/drive/folders/1g0kjru5iUEEIMqUf0hc3hUX7bRBMZUkr)

---

## 4. Technical Arsenal

- **Languages**: Python (3.11+, 3.12+), Modern C++ (C++20, C++23), TypeScript, JavaScript (ES6+), SQL, LaTeX.
- **Machine Learning & AI**: PyTorch, Hugging Face Transformers, BitsAndBytes, Active Learning, Model Quantization (INT8 PTQ, NF4), LoRA, Scikit-learn, NumPy, SymPy.
- **Backend & Systems**: FastAPI, SQLAlchemy Async, Node.js, SQLite (WAL Mode, FTS5), Docker, PostgreSQL, Linux, Git.
- **Frontend & Visualization**: Next.js (App Router, Turbopack), React 19, Three.js, React Three Fiber, Tailwind CSS, KaTeX, Chart.js.
- **Testing & Quality Assurance**: Pytest, Vitest, TypeScript Strict Mode, Static AST Analysis, Benchmarking & Profiling.

---

## 5. Contact & Professional Inquiries

- **LinkedIn**: [linkedin.com/in/dangnhutnguyen](https://www.linkedin.com/in/dangnhutnguyen/)
- **GitHub**: [github.com/nhutnhd](https://github.com/nhutnhd)
- **Portfolio**: [nhutnhd.github.io](https://nhutnhd.github.io)
- **Email**: [penciltalk0910@gmail.com](mailto:penciltalk0910@gmail.com)
