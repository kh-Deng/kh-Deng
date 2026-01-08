# AutoQuant: The Auditable Logic Layer for Injective AI Agents

![Status](https://img.shields.io/badge/Status-Hackathon_Build-success)
![Research](https://img.shields.io/badge/Research-ESWA%20(Under_Review)-blue)
![Integration](https://img.shields.io/badge/Integration-ElizaOS_x_Injective-purple)

> **🚀 Injective x ElizaOS Hackathon Entry**
> **"Making AI Agents Auditable Again."**

---

## 💡 Project Concept: The "Cortex" for Trading Agents

Most AI Agents on ElizaOS trade blindly—they hallucinate profits because they ignore **slippage**, **funding rates**, and **look-ahead bias**.

**AutoQuant** acts as the **risk-control layer (The Cortex)** for Injective-based agents. Before an Agent executes a trade on Injective, AutoQuant validates the logic against rigorous historical data and real-time cost models.

* **Problem:** "Garbage In, Garbage Out" strategies in current AI Agents.
* [cite_start]**Solution:** An **Auditable Expert System** [cite: 2, 42] that enforces strict execution semantics and cost accounting.
* **Core Tech:** Based on my research submitted to **Expert Systems with Applications (ESWA)**.

---

## 🔗 Key Resources

* [cite_start]**📄 Core Research (Preprint)**: [**AutoQuant: An Auditable Expert-System Framework** (arXiv:2512.22476)](https://doi.org/10.48550/arXiv.2512.22476) [cite: 4]
    * *Validates the mathematical rigor behind the codebase.*
* **👨‍💻 Developer**: Kaihong Deng (Solo Developer)
* **📧 Contact**: [kh.deng@foxmail.com](mailto:kh.deng@foxmail.com)

---

## 🛠 Hackathon Deliverables

This repository demonstrates how **AutoQuant** integrates with **ElizaOS** to protect Injective users:

### 1. The "Reality Check" Plugin
[cite_start]A plugin for ElizaOS that enforces **Strict T+1 Execution Semantics**[cite: 294].
* **Function:** Prevents Agents from using future data (look-ahead bias).
* **Impact:** Ensures that if an Agent says "I made 50% profit," it is mathematically strictly verified, not hallucinated.

### [cite_start]2. The "Kill-Switch" Guard [cite: 356, 357]
A post-deployment supervisor module.
* **Logic:** Monitors the Agent's live performance on Injective.
* **Action:** Automatically triggers a **"Kill" signal** (halts trading) if live PnL deviates significantly from the backtest baseline or hits a drawdown limit.

### [cite_start]3. Injective Cost-Awareness [cite: 538]
* **Model:** Incorporates Injective-specific **Funding Rates** and **Taker Fees** into the Agent's decision loop.
* **Result:** Filters out high-frequency strategies that only work in zero-fee environments.

---

## 🔬 Research-Driven Engineering

This project is not just a hackathon demo; it is an implementation of academic research on **Backtest-to-Live Consistency**:

| Feature | Scientific Basis (ESWA) |
| :--- | :--- |
| **No Look-Ahead** | [cite_start]Strict separation of Generation ($t$) and Execution ($t+1$)[cite: 296]. |
| **Cost Realism** | [cite_start]Full accounting of fees, slippage, and funding rates[cite: 308]. |
| **Auditability** | [cite_start]Deterministic machine-readable artifacts for every decision[cite: 45]. |

---

## ⚠️ Access & License

* **Open Source Components:** The ElizaOS adapter/plugin and validation logic logic are open for the hackathon judges.
* **Core Engine:** The underlying Bayesian optimization engine is proprietary IP.
* **Verification:** Full reproducibility scripts for the paper's results are available upon request.

**Copyright (c) 2026 Kaihong Deng. All rights reserved.**
