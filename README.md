# Awesome-Quantum-Computing-Cloud-Service

## Top Quantum Computing Cloud Service Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Quantum Cloud Access, Hybrid Algorithms & Open-Source Quantum SDKs*  

**Last updated: October 2026**



This repository tracks notable **commercial quantum computing cloud services** and **open-source projects** that provide access to quantum processors, simulators, and development frameworks. These platforms enable researchers and developers to run quantum circuits, optimize hybrid algorithms, and explore quantum advantage.



**Examples** include Amazon Braket, IBM Quantum Platform, Microsoft Azure Quantum, Rigetti Computing, D-Wave Leap, IonQ Quantum Cloud, QuEra Computing, Strangeworks, Xanadu PennyLane Cloud, and QC Ware Forge (the category leaders).



**Open-source emphasis**: Quantum computing is a domain where open-source software leads. **Qiskit** (IBM), **Cirq** (Google), **PennyLane** (Xanadu), and **ProjectQ** provide the foundational frameworks that power most quantum development. **Catalyst** brings JIT compilation, **CUDA-Q** extends quantum programming to GPU-accelerated systems, and **OpenFermion** handles quantum chemistry. **QuTiP** simulates open quantum systems. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

> **Sector Overview:** The global quantum computing cloud service market is estimated at **$1.1B–$1.6B in 2026** (projected to reach **$6.2B+ by 2030** at ~35% CAGR). The sector is **highly fragmented** due to competing qubit hardware modalities (superconducting, trapped-ion, neutral-atom, photonic, annealing) and a dual model where hyperscale aggregators (AWS, Azure) distribute specialized pure-play quantum hardware backends.

| Platform | Company Size (Valuation/Revenue) | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Azure Quantum](https://azure.microsoft.com/en-us/products/quantum)** | Market Cap: ~$3.10 Trillion (Rev: ~$245B) | Microsoft's cloud quantum service — access to IonQ, Quantinuum, Rigetti, Pasqal. Q# programming language, Resource Estimator & Copilot integration. | $0.30/task + $0.00035–$0.01/shot (QPU); $10.00/hour (quantum simulator execution) | $500 free credit per provider for new users; unlimited free cloud simulator & Quantinuum Emulator without Azure account |
| **[Amazon Braket](https://aws.amazon.com/braket/)** | Market Cap: ~$2.10 Trillion (AWS Rev: ~$90B) | AWS fully managed quantum service — access to IonQ, Rigetti, QuEra, and D-Wave. Unified Python SDK, 11 pre-built algorithms & Braket Direct. | $0.30/task + $0.00035–$0.01/shot (QPU); $0.075/min (SV1 simulator execution) | 1 hour per month of managed simulator execution (SV1/TN1/DM1) free for first 12 months |
| **[IBM Quantum Platform](https://quantum.ibm.com/)** | Market Cap: ~$200.00 Billion (Rev: ~$62B) | Longest-running quantum cloud service (since 2016) with Heron QPU access. Data locality options, SSO integration, and native Qiskit SDK support. | $1.60 per QPU second (Pay-as-you-go Plan); $800/month minimum for Premium tier | 10 minutes of QPU time per month free forever on 127-qubit / Heron quantum processors (Open Plan) |
| **[IonQ Quantum Cloud](https://ionq.com/)** | Market Cap: ~$2.20 Billion (Rev: ~$35M) | Trapped-ion quantum computers with industry-leading gate fidelity. Quantum Cloud Console for job management, API access & multi-cloud SDK integration. | $0.30/task + $0.01/shot (Aria/Forte QPU); $100.00/hour reserved QPU access | $500 free Azure/AWS partner credit allocation; 100 free simulator credits on account signup |
| **[Xanadu PennyLane Cloud](https://www.xanadu.ai/)** | Valuation: ~$1.00 Billion (Private Unicorn) | Photonic quantum computing cloud access featuring Aurora scalable hardware with real-time error correction and PennyLane QML framework. | $0.0005 per shot (X-series photonic QPU); $10.00/hour cloud simulator execution | Free access to PennyLane ecosystem with 2 hours/month cloud simulator time & 10 free photonic QPU jobs on signup |
| **[Rigetti Computing](https://www.rigetti.com/)** | Market Cap: ~$350.00 Million (Rev: ~$13M) | Cloud access to Rigetti superconducting quantum processors with hybrid classical-quantum co-processing using Quil language & Forest SDK. | $0.30/task + $0.00035/shot (QPU via Braket/Azure); $900.00/hour dedicated QPU reservation | 10 minutes free QPU testing on Rigetti Novera QPU via partner trial; $500 AWS/Azure partner credits |
| **[QuEra Computing](https://www.quera.com/)** | Valuation: ~$300.00 Million (Private VC) | Neutral-atom quantum computers featuring Aquila (256 qubits with analog control) available via Amazon Braket and Azure Quantum. | $0.30/task + $0.01/shot (QPU execution via Braket/Azure); $2,250.00/hour reserved QPU time | $500 AWS Braket credit allocation for research users; 1 hour free analog simulation trial |
| **[D-Wave Leap](https://www.dwavequantum.com/solutions-and-products/cloud-platform/)** | Market Cap: ~$250.00 Million (Rev: ~$10M) | Commercial quantum annealing cloud service with 99.9% uptime. Access to Advantage2 annealing systems & hybrid solvers for up to 2M variables. | $0.35 per QPU second (Pay-as-you-go); $2,000/month Developer subscription (15 QPU sec/month) | 1 minute (60 seconds) of QPU time per month free on sign-up (up to 20 minutes if GitHub account linked) |
| **[Strangeworks](https://strangeworks.com/)** | Valuation: ~$120.00 Million (Private VC) | Unified compute platform aggregating quantum, quantum-inspired, HPC, and classical backends with one-click setup and zero markup. | $0.001 per shot (zero markup on cloud QPU execution); $500.00/month enterprise workspace subscription | Free Community tier with unlimited public workspace access & 100 free simulator jobs/month |
| **[QC Ware Forge](https://qcware.com/)** | Valuation: ~$100.00 Million (Private VC) | Enterprise quantum computing platform featuring specialized turnkey algorithms for quantum chemistry, optimization, and machine learning. | $50.00/hour hybrid algorithm solver usage; $2,500.00/month Starter subscription | 30-day free trial with 1,000 Forge credit units for chemistry & optimization solver testing |





## Open-Source GitHub Projects



### Quantum SDKs & Frameworks



- **[Qiskit](https://github.com/Qiskit/qiskit)**  

  **The most widely adopted open-source quantum SDK**, Apache-2.0 licensed . **IBM's quantum computing framework** for building, simulating, and running quantum circuits on IBM hardware and simulators . Features **Terra (circuit construction), Aer (high-performance simulators), and Ignis (noise characterization)** . **The de facto standard for quantum programming** . **Best for general-purpose quantum development and IBM hardware access** .



- **[Cirq](https://github.com/quantumlib/Cirq)**  

  **Google's open-source quantum computing framework**, Apache-2.0 licensed . **Designed for NISQ-era algorithms** — precise control over quantum circuits and gates . **Native support for Google's Sycamore and Willow processors** . **Best for Google hardware and NISQ algorithm development** .



- **[PennyLane](https://github.com/PennyLaneAI/pennylane)**  

  **The leading open-source quantum machine learning framework**, Apache-2.0 licensed with **2,000+ GitHub stars** . **Differentiable quantum programming** — integrates with PyTorch, TensorFlow, and JAX . **Hardware-agnostic** — runs on IBM, Google, Rigetti, IonQ, Xanadu, and simulators . **Best for quantum ML and hybrid quantum-classical optimization** .



- **[ProjectQ](https://github.com/ProjectQ-Framework/ProjectQ)**  

  **Open-source quantum computing framework from ETH Zurich**, Apache-2.0 licensed . **Compiler-focused architecture** — separates high-level algorithm description from hardware execution . **Best for compiler research and resource estimation** .



- **[Q# (Microsoft Quantum Development Kit)](https://github.com/microsoft/qsharp)**  

  **Microsoft's open-source quantum programming language and QDK**, MIT licensed . **Hardware-agnostic language** . **Rust-based core for speed and portability** . **Azure Quantum Resource Estimator** for scalability measurement . **Best for Microsoft ecosystem and hybrid quantum-classical programming** .



- **[CUDA-Q](https://github.com/NVIDIA/cuda-quantum)**  

  **NVIDIA's open-source quantum programming platform**, Apache-2.0 licensed . **CUDA-Q Logical** expands to **fault-tolerant quantum computing** . **GPU-accelerated quantum simulation** — the fastest way to simulate quantum circuits . **Best for GPU-accelerated quantum development and error correction research** .



- **[Catalyst](https://github.com/PennyLaneAI/catalyst)**  

  **JIT compiler for hybrid quantum programs in PennyLane**, Apache-2.0 licensed . **MLIR-based compilation stack** — the industry's most downloaded quantum MLIR compiler . **Best for optimizing hybrid quantum-classical workflows** .



### Quantum Simulation & Algorithms



- **[QuTiP](https://github.com/qutip/qutip)**  

  **Quantum Toolbox in Python** — open-source framework for simulating quantum systems, Apache-2.0 licensed . **The standard for quantum physics simulation** — open quantum systems, master equations, and quantum optics . **Best for physics research and quantum dynamics simulation** .



- **[OpenFermion](https://github.com/quantumlib/OpenFermion)**  

  **Google's open-source library for quantum chemistry**, Apache-2.0 licensed . **The standard for electronic structure calculations** — molecular Hamiltonians, fermionic operators, and qubit mappings . **Best for quantum chemistry and materials science** .



- **[Yao.jl](https://github.com/QuantumBFS/Yao.jl)**  

  **Julia-based quantum algorithm framework**, Apache-2.0 licensed . **Extensible design** — build custom quantum algorithms . **QuAlgorithmZoo.jl** provides curated algorithm implementations . **Best for Julia users and algorithm research** .



- **[Tweedledum](https://github.com/boschmitt/tweedledum)**  

  **C++17 library for quantum circuit analysis, compilation, and optimization**, MIT licensed with **92 GitHub stars** . **The reference for quantum circuit optimization** . **Best for quantum compiler development** .



- **[Strawberry Fields](https://github.com/XanaduAI/strawberryfields)**  

  **Xanadu's open-source photonic quantum computing library**, Apache-2.0 licensed . **Continuous-variable (CV) quantum computing** . **Blackbird** is the quantum programming language for CV systems . **Best for photonic quantum computing research** .



### Additional Strong Open-Source Options



- **Cirq-Google** — Native Cirq support for Google hardware .

- **Qiskit-Braket-Provider** — Qiskit integration for Amazon Braket .

- **PennyLane-Cirq** — PennyLane plugin for Cirq integration .

- **PyQtorch** — PyTorch-based quantum simulator .

- **sQUlearn** — scikit-learn interface for quantum algorithms .

- **TensorFlow Quantum** — Google's quantum ML library (archived) .

- **Quantum++** — C++ quantum computing library .

- **QuTiP** — Quantum Toolbox in Python .

- **ProjectQ** — Compiler-focused quantum framework .

- **UniversalQCompiler** — Synthesizing arbitrary quantum computations .



**Frameworks for building custom quantum computing solutions**: Choose based on hardware target and use case. **Qiskit** for IBM hardware and general-purpose development . **Cirq** for Google hardware and NISQ algorithms . **PennyLane** for quantum ML and hybrid optimization with hardware-agnostic execution . **ProjectQ** for compiler research and resource estimation . **Q#** for Microsoft ecosystem and hardware-agnostic programming . **CUDA-Q** for GPU-accelerated simulation and error correction . Note that true quantum advantage with fault-tolerant systems remains years away; current NISQ-era platforms provide value in hybrid optimization (D-Wave Leap), quantum chemistry (OpenFermion), and algorithm research.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Quantum computing services provide access to experimental hardware with limited qubit counts and error rates. **Results are not guaranteed** — quantum advantage demonstrations are specific to particular problems and implementations.

- **Costs vary significantly** — Amazon Braket provides near-real-time cost estimates via Tracker context manager . D-Wave Leap is SOC 2 Type 2 compliant with enterprise pricing . Review pricing before committing to large workloads.

- **Open-source frameworks are vendor-neutral but hardware-specific** — Qiskit targets IBM, Cirq targets Google, PennyLane is hardware-agnostic . Choose based on your hardware access.

- **The quantum ecosystem is rapidly evolving** — verify current platform status and hardware availability before committing to a provider.

- The open-source ecosystem provides strong quantum SDKs, simulators, and algorithms, but **fault-tolerant quantum computing with verifiable advantage** remains primarily a research milestone achieved on specific hardware.



---



**Made for quantum researchers, algorithm developers, and enterprises exploring quantum computing.**  

Let's make quantum computing cloud services more open, transparent, and accessible.
