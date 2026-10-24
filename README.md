# Nguyen Huynh Dang Nhut (@nhutnhd)

> Artificial Intelligence Researcher · Low-Level Systems Architect · Open-Source Contributor
> University of Information Technology (UIT), VNU-HCM
> Official Portfolio: [nhutnhd.github.io](https://nhutnhd.github.io) | LinkedIn: [linkedin.com/in/dangnhutnguyen](https://www.linkedin.com/in/dangnhutnguyen/) | Email: [dangnhutnguyen.work@gmail.com](mailto:dangnhutnguyen.work@gmail.com)

[![Portfolio](https://img.shields.io/badge/Portfolio-nhutnhd.github.io-0969da?style=flat-square&logo=googlechrome&logoColor=white)](https://nhutnhd.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dangnhutnguyen-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dangnhutnguyen/)
[![GitHub](https://img.shields.io/badge/GitHub-nhutnhd-24292e?style=flat-square&logo=github&logoColor=white)](https://github.com/nhutnhd)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0009--6305--478X-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0009-6305-478X)

---

## 1. Executive Summary

I am an AI researcher and software systems architect specializing in efficient deep learning, neural network compression, low-level execution policies, and mathematically rigorous machine learning from first principles.

My research and engineering practice focuses on:
- Hardware-aware neural network compression (INT8 post-training quantization, structured pruning, and low-rank tensor decomposition).
- Neural Machine Translation (NMT), sequence-to-sequence Transformer architectures, and subword tokenization models.
- Speculative decoding acceleration, draft model distillation, and parameter-efficient fine-tuning on resource-constrained hardware.
- First-principles mathematical implementation of deep learning algorithms without opaque autograd abstractions.
- Local-first, high-concurrency software architectures with strict memory safety and deterministic invariants.
- Defensive security telemetry, binary protocol framing, and operating system internals research (strictly archived reference models).

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
| Scientific Computing | [conservative-force-simulation](https://github.com/nhutnhd/conservative-force-simulation) | Runge-Kutta RK45 ODE Solver, SymPy, CustomTkinter GUI, MATLAB | Production · 5 Tests |
| Interactive Pedagogy | [interactive-ml-learning-platform](https://github.com/nhutnhd/interactive-ml-learning-platform) | Next.js 16 Turbopack, React 19, Tailwind CSS, KaTeX | Production · Built |
| Olympic AI Curriculum | [voai-olympic-ai-course](https://github.com/nhutnhd/voai-olympic-ai-course) | 38 Jupyter Notebooks, M0-M7 Curriculum, PyTorch, Scikit-Learn | Production · 4 Tests |
| Neural Machine Translation | [zh-vi-transformer-nmt](https://github.com/nhutnhd/zh-vi-transformer-nmt) | PyTorch Transformer Seq2Seq, Google SentencePiece, SacreBLEU, Beam Search | Production · 3 Tests |
| Applied ML Coursework | [applied-ml-coursework-labs](https://github.com/nhutnhd/applied-ml-coursework-labs) | Pima Diabetes Classification, Exploratory Data Analysis, ROC-AUC Tuning | Production · 2 Tests |
| Autoregressive Generation | [pixelbudget-autoregressive-generation](https://github.com/nhutnhd/pixelbudget-autoregressive-generation) | CPU-Validated Pixel Budget Allocation, Autoregressive Synthesis | Production · 3 Tests |
| Algorithmic Problem Solving | [apcs-algorithm-problem-solving](https://github.com/nhutnhd/apcs-algorithm-problem-solving) | Prime Sieve, Number Theory, Twin Primes, Taylor Series, Dynamic Programming | Production · 4 Tests |
| Prompt Engineering | [PrompTEA](https://github.com/nhutnhd/PrompTEA) | Language Model Prompt Optimization Framework using NLP & ML | Production |
| Productivity Systems | [Focumia](https://github.com/nhutnhd/Focumia) | Client-side Deep Work Pomodoro & Task Hierarchy Workspace | Production |
| MIL Learning OS | [dailynox](https://github.com/nhutnhd/dailynox) | UNESCO Media & Information Literacy Framework Implementation | Production |
| Minimalist Workspace | [writedownia](https://github.com/nhutnhd/writedownia) | Distraction-free Browser Journal, Notes & Spaced Repetition Decks | Production |
| Security Telemetry Workstation | [security-research-telemetry-workstation](https://github.com/nhutnhd/security-research-telemetry-workstation) | 29 Core Tools, Payment Telemetry, C2 Framing, WinAPI PEB Traversal | Archived Reference · 24 Tests |
| Distributed C2 Architecture | [modular-c2-distributed-framework](https://github.com/nhutnhd/modular-c2-distributed-framework) | Modular C2, AES-256-GCM Framing, Multi-Session Manager, Web UI Dashboard | Archived Reference · 18 Tests |
| Credential Forensics & DPAPI | [infostealer-mechanics-defense-lab](https://github.com/nhutnhd/infostealer-mechanics-defense-lab) | Chromium DPAPI v10/v20, AES-GCM Key Derivation, SQLite Vault Triage, EDR | Archived Reference · 3 Tests |
| Activity Telemetry & Binary PE | [system-activity-telemetry-auditor](https://github.com/nhutnhd/system-activity-telemetry-auditor) | Clean Re-implementation, KLG1 Binary Overlay Protocol, PE Header Inspection | Archived Reference · 5 Tests |
| Web Target Recon & Simulation | [web-recon-simulation-framework](https://github.com/nhutnhd/web-recon-simulation-framework) | 147 API Endpoints Catalog, Fastify Local Sandbox Simulator, DOM Modeling | Archived Reference · 4 Tests |
| Web Pentest Intelligence Suite | [web-pentest-intelligence-suite](https://github.com/nhutnhd/web-pentest-intelligence-suite) | 14 Autonomous Defensive Agent Skills, MITRE ATT&CK & CAPEC Alignment | Archived Reference · 2 Tests |
| Security Audit Assessment Reports| [penetration-testing-audit-reports](https://github.com/nhutnhd/penetration-testing-audit-reports) | Sanitized Forensic Pentest Reports, RealIELTS Assessment, Turnstile DOM Triage| Archived Reference · 3 Tests |
| Checkout Testing & Automation | [automation-and-checking-tools](https://github.com/nhutnhd/automation-and-checking-tools) | Luhn Checksum Verification, Headless Browser Checkout Telemetry | Archived Reference · 2 Tests |
| Defensive Code Analysis | [pyobfuscate-static-inspector](https://github.com/nhutnhd/pyobfuscate-static-inspector) | AST Control Flow Graph Recovery, Constant Propagation Sandbox | Archived Reference · 51 Tests |
| Telemetry & Network Framing | [c2-protocol-simulation-framework](https://github.com/nhutnhd/c2-protocol-simulation-framework) | Authenticated 6-byte Header Framing, AES-256-GCM, Anti-Replay Guard | Archived Reference · 3 Tests |

---

## 3. Academic Papers & Research Manuscripts

- **LogicPT–GT**: Research on formal logic, problem solving, structured thinking, and automated problem transformation.  
  [Read Manuscript (PDF)](https://drive.google.com/file/d/1NYF5sJFUI2zlBwd7wX-CcVM0hKcQ95es/view)

---

## 4. Engineering & Research Principles

1. **First-Principles Derivation**: Never rely on opaque black-box abstractions when understanding the physical limits of hardware (CPU cycle boundaries, L1/L2/L3 cache line alignment `alignas(64)`, and kernel syscall transitions).
2. **Deterministic Reproducibility**: Every research repository features end-to-end automated unit, integration, and stress tests to guarantee zero regressions.
3. **Responsible Open-Source Governance**: All offensive security, binary exploitation, and credential telemetry research modules are strictly maintained as public read-only educational archives with comprehensive synthetic data quarantine and formal responsible disclosure policies.
