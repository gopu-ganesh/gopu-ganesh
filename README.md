<!-- <div align="center">

```
 ██████╗  █████╗ ███╗   ██╗███████╗███████╗██╗  ██╗
██╔════╝ ██╔══██╗████╗  ██║██╔════╝██╔════╝██║  ██║
██║  ███╗███████║██╔██╗ ██║█████╗  ███████╗███████║
██║   ██║██╔══██║██║╚██╗██║██╔══╝  ╚════██║██╔══██║
╚██████╔╝██║  ██║██║ ╚████║███████╗███████║██║  ██║
 ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═══╝╚══════╝╚══════╝╚═╝  ╚═╝
                                              G O P U
```

### `ML Engineer · AI/LLM Engineer · AI Automation Engineer`

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=00d4ff)](https://ganeshgopu.info)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ganeshgopu)
[![HuggingFace](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/ganeshgopu)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ganeshreddy1811@gmail.com)

</div>

---

## `> whoami`

```python
ganesh = {
    "role"      : "MS Computer Science — University of Bridgeport (May 2026)",
    "focus"     : ["LLM Engineering", "Agentic AI", "AI Automation", "MLOps"],
    "llm_stack" : ["LLaMA 3", "GPT-4o", "Claude 3", "Gemini via Vertex AI"],
    "location"  : "Bridgeport, CT — Open to Relocation",
    "status"    : "🟢 Actively seeking AI Engineer roles",
}
```

I build **production-grade AI systems** — from fine-tuned LLMs and multi-source agentic RAG pipelines to full-stack automation platforms that ship real business impact. My work sits at the intersection of AI engineering, MLOps, and cybersecurity.

---

## `> ls ./skills`

<table>
<tr>
<td valign="top" width="33%">

**🧠 LLM & Generative AI**
```
LLaMA 3 · Phi-3
GPT-4o (OpenAI API)
Claude 3 (Anthropic API)
Gemini (Vertex AI)
PEFT · LoRA · QLoRA
bitsandbytes (4-bit quant)
Prompt Engineering
Few-shot · Zero-shot · CoT
```

</td>
<td valign="top" width="33%">

**🤖 Agentic AI & RAG**
```
LangChain · LangGraph
LlamaIndex · CrewAI
ReAct Agents
Multi-Agent Orchestration
Tool & Function Calling
MCP (Model Context Protocol)
Vertex AI Agent Builder
Hybrid Search (BM25 + vector)
Cross-encoder Reranking
```

</td>
<td valign="top" width="33%">

**⚙️ MLOps & LLMOps**
```
MLflow · Weights & Biases
Docker · GitHub Actions
FastAPI · Gradio
LangSmith (observability)
Guardrails · PII Detection
Hallucination Detection
LLM-as-a-Judge
Eval-gated Deployments
Prompt Versioning
```

</td>
</tr>
<tr>
<td valign="top">

**🗄️ Vector Databases**
```
ChromaDB · FAISS
Pinecone · Qdrant
Embedding Models
```

</td>
<td valign="top">

**☁️ Cloud & Infrastructure**
```
GCP (Vertex AI · GCS)
AWS (S3 · EC2 · SageMaker)
Supabase Cloud
Hugging Face Hub
```

</td>
<td valign="top">

**🔐 AI Safety & Security**
```
LLM Red Teaming
Adversarial ML
Prompt Injection Defense
Network & App Security
Responsible AI
```

</td>
</tr>
</table>

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

---

## `> cat ./projects`

### 🔬 01 — Multi-LLM Agentic RAG System
> **The flagship.** Production-grade agentic RAG system supporting 4 LLM backends with dynamic switching.

- Built with **LangGraph** stateful agents — conditional branching, retry logic, persistent memory across turns
- **Hybrid search** (BM25 + dense vector) + **cross-encoder reranking** for production-grade retrieval precision
- **QLoRA fine-tuning** on Uber & Lyft 2021 financial reports — tracked with **MLflow**, served via **FastAPI + Gradio**
- Layered **guardrail system**: prompt injection detection → PII masking → NLI faithfulness checking → confidence gating
- Deployed to **Hugging Face Hub** · Pipeline observability via **LangSmith** · Outputs validated with **LLM-as-a-Judge**

`LangGraph` `QLoRA` `GPT-4o API` `Claude API` `Vertex AI` `ChromaDB` `FAISS` `MLflow` `FastAPI` `Gradio`

---

### 🏭 02 — SoundCoffees Roasting Automation Platform
> **Real production impact.** Full-stack AI operations platform built during internship.

- Integrated live sales data via **REST API** → ML demand forecasting → auto-generated daily roasting schedules
- **Eliminated 100% of raw material waste** and all stock-out events across the roasting operation
- Real-time **React + Supabase dashboard** replacing manual spreadsheet workflows, used daily by operations staff
- **GitHub Actions CI/CD** for zero-downtime deployments · PostgreSQL ETL pipelines for live data sync

`React` `FastAPI` `Supabase` `PostgreSQL` `Demand Forecasting` `GitHub Actions` `REST API`

---

### 🤖 03 — Intelligent AI Agent — Google Vertex AI
> **Enterprise agent.** Multi-tool orchestration using Gemini + MCP on Google Cloud.

- Built on **Vertex AI Agent Builder** with **Gemini** + custom tool definitions and **function calling**
- **MCP (Model Context Protocol)** for safe, structured external tool integration
- **Qdrant** for self-hosted vector retrieval with metadata filtering · knowledge base in **GCS**
- Eval-gated deployments ensuring zero regression before production promotion

`Vertex AI` `Gemini API` `LangGraph` `MCP` `Qdrant` `GCS` `Function Calling`

---

### ⚡ 04 — Attention-Based Reward Training System
> **Research-grade.** Custom training framework bridging supervised learning and RLHF.

- Applies a **-10 reward gradient** directly through attention blocks on incorrect predictions — reshaping attention patterns
- Differentiable reward shaping in the **backward pass** beyond standard cross-entropy loss
- Tracked with **Weights & Biases** · visualized via **Gradio** UI showing attention weight evolution
- Demonstrates measurable accuracy improvement — validates attention-level reward feedback as a convergence accelerator

`PyTorch` `Transformer Attention` `Custom Loss Functions` `Weights & Biases` `Gradio`

---

### 🎮 05 — Autonomous RL Catch Game Agent
> **96% win rate.** Q-learning agent playing fully autonomously with no human input.

- **Q-learning** with experience replay buffer + custom reward shaping (+1 catch / -1 miss)
- Tuned **epsilon-greedy** exploration decay and replay buffer hyperparameters
- **96/100 games won** in fully autonomous evaluation — all metrics logged in Weights & Biases

`Q-Learning` `Experience Replay` `Epsilon-Greedy` `Reward Shaping` `Weights & Biases`

---

## `> cat ./experience`

```
┌─────────────────────────────────────────────────────────────────┐
│  Automation & Data Systems Intern                               │
│  SoundCoffees · Bridgeport, CT · Jun 2024 – Dec 2024           │
├─────────────────────────────────────────────────────────────────┤
│  → Designed & deployed end-to-end AI roasting automation       │
│    platform replacing all manual tracking workflows             │
│  → ML demand forecasting from live sales API → auto-schedule   │
│  → 100% raw material waste eliminated · Zero stock-out events  │
│  → React + Supabase real-time dashboard · GitHub Actions CI/CD │
└─────────────────────────────────────────────────────────────────┘
```

---

## `> cat ./education`

```
┌─────────────────────────────────────────────────────────────────┐
│  Master of Science in Computer Science                          │
│  University of Bridgeport · May 2026                           │
├─────────────────────────────────────────────────────────────────┤
│  Deep Learning · Advanced Deep Learning · Reinforcement         │
│  Learning · NLP · Cybersecurity · Computer Vision · Data        │
│  Mining · Big Data Systems · Autonomous Vehicles                │
└─────────────────────────────────────────────────────────────────┘
```

---

## `> git log --stats`

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=ganeshgopu&show_icons=true&theme=dark&bg_color=080c10&border_color=1e2d3d&icon_color=00d4ff&title_color=00d4ff&text_color=64748b&hide_border=false)
&nbsp;&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ganeshgopu&layout=compact&theme=dark&bg_color=080c10&border_color=1e2d3d&title_color=00d4ff&text_color=64748b)

</div>

---

## `> ping ganesh`

<div align="center">

**🟢 Actively seeking AI Engineer · ML Engineer · AI Automation roles — May 2026**

I'm always open to interesting conversations, collaborations, and opportunities.<br>
If something on this profile caught your eye — reach out. I respond fast.

<br>

[![Email](https://img.shields.io/badge/ganeshreddy1811@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ganeshreddy1811@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ganeshgopu)
[![Portfolio](https://img.shields.io/badge/View_Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=00d4ff)](https://ganeshgopu.dev)
[![Hugging Face](https://img.shields.io/badge/Models_on_HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/ganeshgopu)

<br>

```
"The goal is not to build AI. The goal is to solve problems — AI is just the best tool we have."
```

</div>

---

<div align="center">
<sub>Built with Python, curiosity, and a lot of GPU hours · © 2026 Ganesh Gopu</sub>
</div>

<!-- # 🌐 Source-Sphere

> *Where ideas converge. Where code evolves.*

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-active-brightgreen.svg)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

---

## About Us

**Source-Sphere** is a technology company dedicated to building innovative software solutions that push the boundaries of what's possible. We believe in the power of open collaboration, clean engineering, and purposeful design.

Our mission is simple: **build tools that matter, ship software that lasts**.

---

## What We Do

- 🔧 **Software Engineering** — Robust, scalable applications from the ground up
- 🤖 **AI & Machine Learning** — Intelligent systems built for real-world impact
- ☁️ **Cloud & Infrastructure** — Resilient, production-ready infrastructure at scale
- 🎨 **Product & Design** — Thoughtful UX backed by engineering excellence

---

## Repository Structure

```
source-sphere/
├── apps/           # Client-facing applications
├── packages/       # Shared libraries and utilities
├── services/       # Backend microservices
├── infrastructure/ # IaC configs (Terraform, Helm, etc.)
├── docs/           # Internal documentation
└── scripts/        # Dev and CI/CD tooling
```

---

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Git](https://git-scm.com/) `>= 2.40`
- [Node.js](https://nodejs.org/) `>= 20.x` *(or relevant runtime for your service)*
- [Docker](https://www.docker.com/) `>= 24.x`

### Installation

```bash
# Clone the repository
git clone https://github.com/source-sphere/<repo-name>.git

# Navigate into the project
cd <repo-name>

# Install dependencies
npm install

# Copy environment variables
cp .env.example .env

# Start development server
npm run dev
```

---

## Contributing

We welcome contributions from everyone — whether you're fixing a typo or shipping a feature.

1. **Fork** the repository
2. **Create** your feature branch: `git checkout -b feat/your-feature`
3. **Commit** your changes: `git commit -m "feat: add your feature"`
4. **Push** to your branch: `git push origin feat/your-feature`
5. **Open** a Pull Request

Please read our [Contributing Guide](CONTRIBUTING.md) and follow the [Code of Conduct](CODE_OF_CONDUCT.md) before submitting.

---

## Commit Convention

We follow [Conventional Commits](https://www.conventionalcommits.org/):

| Prefix | Purpose |
|--------|---------|
| `feat:` | New feature |
| `fix:` | Bug fix |
| `docs:` | Documentation only |
| `chore:` | Maintenance tasks |
| `refactor:` | Code restructure |
| `test:` | Adding or updating tests |

---

## Code of Conduct

Source-Sphere is committed to fostering a welcoming and inclusive environment. All contributors are expected to uphold our [Code of Conduct](CODE_OF_CONDUCT.md).

---

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## Connect With Us

| Channel | Link |
|---------|------|
| 🌐 Website | [source-sphere.io](https://source-sphere.io) |
| 🐦 Twitter / X | [@sourcesphere](https://twitter.com/sourcesphere) |
| 💼 LinkedIn | [Source-Sphere](https://linkedin.com/company/source-sphere) |
| 📬 Email | hello@source-sphere.io |

---

<p align="center">
  Built with ❤️ by the <strong>Source-Sphere</strong> team
</p> -->
# Ganesh Gopu

<div align="center">

# Software Engineer

### AI Platforms • Backend Engineering • Distributed Systems • Cloud-Native Applications

[![Portfolio](https://img.shields.io/badge/Portfolio-ganeshgopu.info-000000?style=for-the-badge&logo=vercel)](https://ganeshgopu.info)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/ganeshgopu)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-Profile-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/ganeshgopu)

</div>

---

## 👋 About Me

I'm a Software Engineer focused on building scalable backend systems, AI-powered platforms, and cloud-native applications.

## 🛠 Tech Stack

- Python • Java • TypeScript • JavaScript
- FastAPI • Spring Boot • Spring Security
- AWS • Docker • Kubernetes • ECS
- PostgreSQL • MySQL • MongoDB
- Kafka • CI/CD
- LangChain • Hugging Face • RAG • Palantir AIP

## 💼 Experience

### Palantir Technologies
- Built backend services with Python and FastAPI.
- Integrated LLM workflows with Palantir AIP.
- Developed applications using Foundry Ontology.

### Accenture
- Built enterprise Java applications.
- Developed Spring Boot microservices.
- Worked with Kafka, REST APIs, and cloud deployments.

## 🚀 Featured Projects

- Financial Intelligence Platform
- Multi-LLM Agentic RAG System
- Intelligent API Gateway
- Coffee Operations Automation

## 📜 Certifications

- AWS Certified Solutions Architect – Associate
- Prompt Engineering for Generative AI
- Google Cloud Generative AI Fundamentals

## 📫 Connect

- Portfolio: https://ganeshgopu.info
- LinkedIn: https://linkedin.com/in/ganeshgopu
- Hugging Face: https://huggingface.co/ganeshgopu

