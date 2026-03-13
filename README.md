# 🌌 Zenith-Agent-Mesh

[![AI Engineering](https://img.shields.io/badge/Focus-Multi--Agent%20Systems-blueviolet.svg)]()
[![Azure AI](https://img.shields.io/badge/Tech-Azure%20AI%20Foundry-blue.svg)]()
[![Semantic Kernel](https://img.shields.io/badge/Framework-Semantic%20Kernel-orange.svg)]()
[![Python](https://img.shields.io/badge/Language-Python%203.10+-yellow.svg)]()

**Zenith** is a production-grade **Multi-Agent Orchestration Framework** designed for enterprise-level autonomous workflows. It leverages **Azure AI Foundry**, **Semantic Kernel**, and **MCP (Model Context Protocol)** to enable complex reasoning, long-term memory, and self-correcting agent collaboration.

## 🌟 Key Features

- **🧠 Dynamic Orchestration:** A central 'Brain' module that decomposes high-level goals into actionable sub-tasks for specialized agents.
- **🔄 Semantic Kernel Integration:** Built-in support for native functions, plugins, and advanced planners for tool-augmented reasoning.
- **🛡️ Autonomous Self-Reflection:** A built-in feedback loop where a 'Critic' agent reviews and validates outputs before final delivery.
- **📚 Contextual Memory Fabric:** Persistent vector-based memory allowing agents to retain context across long-running sessions.
- **📊 Enterprise Observability:** Detailed execution traces and telemetry, optimized for Azure AI Foundry monitoring.

## 🛠️ System Architecture

1.  **Mesh Orchestrator:** The core controller that manages state and agent communication.
2.  **Specialist Agents:** (Researcher, Coder, Architect) - Task-specific units with unique system prompts and tools.
3.  **Validation Layer:** Self-reflection module ensuring accuracy, security, and compliance.
4.  **Semantic Bridge:** Connects LLMs to enterprise data and external APIs via Semantic Kernel.

## 🚀 Quick Start

### Installation
`ash
git clone https://github.com/UtsunomiyaTomohiro/Zenith-Agent-Mesh.git
cd Zenith-Agent-Mesh
pip install -r requirements.txt
`

### Run Demo
`ash
python main.py --goal "Design a multi-cloud disaster recovery strategy"
`

---
Developed with 🚀 by [Utsunomiya Tomohiro](https://www.linkedin.com/in/utsunomiya-tomohiro-892254190/)