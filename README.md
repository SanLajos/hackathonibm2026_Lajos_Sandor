# hackathonibm2026_Lajos_Sandor

# Autonomous Storage Fabric: IBM Automation Shield for Huawei Cloud

![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)
![Platform](https://img.shields.io/badge/Cloud-Huawei%20Cloud-red.svg)
![AI-Powered](https://img.shields.io/badge/AI-Agentic%20Orchestration-orange.svg)

An AI-native automation framework designed to manage **T Public Cloud EVS (Block)** and **OBS (Object)** storage across 4 regions and 9 Availability Zones. This project leverages the **IBM Automation Shield** (Instana, Turbonomic, Concert, and watsonx) to provide a self-healing, cost-optimized, and compliant storage utility.

## 🚀 Project Overview

As cloud environments scale, manual storage management becomes a bottleneck. This repository provides the logic, governance policies, and orchestration skills to transform reactive storage tasks into a **Closed-Loop Automation** workflow.

- **Production (3 AZs):** High-performance, auto-scaling focus.
- **Amsterdam (2 AZs):** Efficiency and load-balancing focus.
- **Preprod (2 AZs):** Aggressive waste reclamation and cost recovery.
- **Hybrid (2 AZs):** Strict sovereignty and compliance-gated expansion.

---

## 🏗️ Architecture & Technology Stack

The solution follows the **Observe-Decide-Govern-Act** loop:

1.  **Observe (IBM Instana):** 1-second telemetry ingestion from Huawei Cloud Eye.
2.  **Decide (IBM Turbonomic):** Economic engine for right-sizing and placement.
3.  **Govern (IBM Concert):** Compliance "Circuit Breaker" for data sovereignty.
4.  **Act (IBM watsonx):** Agentic orchestration of Huawei Cloud APIs.

---