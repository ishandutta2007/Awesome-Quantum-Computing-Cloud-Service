# Awesome-Quantum-Computing-Cloud-Service

# Top Quantum Computing Cloud Service Ecosystem

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

- **[Amazon Braket](https://aws.amazon.com/braket/)**  
  **AWS's fully managed quantum computing service** — access to **IonQ, Rigetti, IQM, QuEra, and D-Wave** hardware . **Unified Python SDK** for building, testing, and running quantum circuits . **11 pre-built algorithm library**, **Program Sets** for bundling circuits, and **Braket Direct** for exclusive hardware reservations . **Tracker context manager** provides near-real-time cost estimates before submission . **Best for AWS-native quantum computing** .

- **[IBM Quantum Platform](https://quantum.ibm.com/)**  
  **The longest-running quantum cloud service** (since 2016) with **Heron QPU access for Open Plan users** . **Data locality** (choose EU datacenter), **enhanced security with SSO and Service IDs**, and **seamless integration with Cloud Object Storage and VPC** . **Qiskit** is the primary SDK . **Best for IBM hardware access** .

- **[Microsoft Azure Quantum](https://azure.microsoft.com/en-us/products/quantum)**  
  **Microsoft's cloud quantum service** — access to multiple hardware providers (IonQ, Quantinuum, Rigetti, Pasqal) . **Q# programming language with hardware-agnostic execution** . **Resource Estimator** for measuring scalability, **Copilot** guidance for quantum coding . **Free to use without Azure account** for code samples and Quantinuum Emulator . **Best for Microsoft ecosystem and hybrid quantum-classical programming** .

- **[Rigetti Computing](https://www.rigetti.com/)**  
  Cloud access to Rigetti's superconducting quantum processors . **Pioneered quantum co-processing** — hybrid classical-quantum architecture . **Quil** programming language and **Forest** SDK for development . **Best for superconducting quantum computing** .

- **[D-Wave Leap](https://www.dwavequantum.com/solutions-and-products/cloud-platform/)**  
  **The most commercially mature quantum cloud service** with 99.9% uptime and subsecond QPU response times . Access to **Advantage2 annealing quantum systems** and **hybrid solvers handling up to 2 million variables** . **SOC 2 Type 2 compliant** . **The best platform for optimization problems** — scheduling, routing, resource allocation .

- **[IonQ Quantum Cloud](https://ionq.com/)**  
  Access to IonQ's **trapped-ion quantum computers** with industry-leading gate fidelities . **Quantum Cloud Console** at cloud.ionq.com for managing API credentials and inspecting jobs . **Supports the most SDKs, languages, and cloud integrations** of any quantum hardware provider . **Best for high-fidelity quantum computing** .

- **[QuEra Computing](https://www.quera.com/)**  
  **Neutral-atom quantum computers** with **Aquila** — 256 qubits with analog control . **Available via Amazon Braket and Azure Quantum** . **Best for analog quantum simulation** .

- **[Strangeworks](https://strangeworks.com/)**  
  **Unified platform for quantum, quantum-inspired, HPC, and classical compute** — one interface, any backend . **One-click activation and zero markup on compute** . **Best for comparing across providers** .

- **[Xanadu PennyLane Cloud](https://www.xanadu.ai/)**  
  Access to Xanadu's **photonic quantum computers** via cloud . **Aurora** is the first networked, modular, scalable quantum computer with **real-time error-correction decoding** . **PennyLane** — the leading open-source quantum ML framework — powers Xanadu's software ecosystem . **Best for photonic quantum computing** .

- **[QC Ware Forge](https://qcware.com/)**  
  **Enterprise quantum computing platform** — algorithms and applications for chemistry, optimization, and machine learning . **Best for enterprise quantum applications** .

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
