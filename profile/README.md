# Astral Research Labs 🌌
**Architecting the Future of Sparse and Efficient Intelligence.**

Astral Research Labs is an independent R&D initiative dedicated to the development of modular **Mixture of Experts (MoE)** architectures. Our mission is to bridge the gap between high-level neural research and execution on resource-constrained hardware.

---

## 🔬 Research Focus
We focus on the intersection of sparsity, dynamic routing, and edge-computing optimization. By moving away from monolithic dense models, we aim to democratize AI through:

* **Modular Sparsity:** Developing MoE layers that activate only relevant neurons, drastically reducing FLOPs.
* **JIT (Just-In-Time) Highways:** Optimizing token routing paths for real-time inference.
* **Neurogenesis Logic:** Experimenting with dynamic parameter expansion during the training phase.
* **Edge Inference:** Compiling complex architectures for ARM-based systems (Raspberry Pi/Jetson).

---

## 🛠 Active Projects

### 1. [ASTRAL-MoE](https://github.com/black-swas/astral-moe-v2)
Our flagship modular Mixture of Experts architecture. It has plug and play capability with various families of models through ffn injection in such as qwen gemma llama and even unrecognised models being as a external filter with custom router with load balancing and custom design to create experts on demand while preventing expert collapse. Designed for high-throughput and hardware-agnostic scalability.
* **Current Benchmark:** 22.14 tokens/sec (Modular V3.2.1) vs 28.8 on qwen baseline while being 60% better in performance 
* **Key Tech:** PyTorch, Custom Routing Kernels , CUDA, neurogeneis


### 2. [TonyMoE](https://github.com/black-swas/tonymoe)
A  implementation of sparse expert layers specifically optimized for edge devices and headless Linux environments.
* **Target Hardware:** Raspberry Pi Zero 2 W / Pi 4 & 5.
* **Status:** Stable / Optimization Phase.

### 3. [Research to analayse of connection between hallucination and entropy](https://github.com/black-swas/Entropy-As-Hallucinogen)

<p>A work in progress research trying to establish connection between shannon entropy as the reason behind hallucination in models , currently working on a modular tool to run the experiments on as various model families as baseline. Using TruthfulQA as dataset</p>
---

## 📊 Technical Stack
* **Frameworks:** `PyTorch`,`triton`, `FAISS`, `Three.js` (for visualization).
* **Languages:** `Python`, `C++`, `JavaScript (Node.js)`.
* **Environments:** `Ubuntu`, `Kali Linux (Headless)`, `DietPi`, `raspberry pi os `.
* **Hardware:** `Cloud-based t4 Dual GPU`, `Raspberry Pi Ecosystem`.

---

## 📖 Documentation & Benchmarks
We believe in rigorous validation. Every project in this lab includes:
1.  **Slightweightystem Benchmarks:** Real-world performance data across various hardware tiers.
2.  **Architecture Diagrams:** Detailed wandb or SVG visualizations of model logic.
3.  **Deployment Guides:** Full documentation for setup and inference.

---

## 🤝 Collaboration & Inquiries
Astral Research Labs is currently led by RISHIT BHAT. We are open to academic collaborations regarding efficient AI and sparse model research.

* **LinkedIn:** [Your LinkedIn Profile Link]
* **Location:** Srinagar, Jammu & Kashmir
* **Status:** Researching toward Fall 2027 Academic Intake.

---
> *"Efficiency is the highest form of innovation."*
