<p align="center">
  <img src="https://docs.kliver.ai/images/Logo-h.png" alt="Kliver Logo" width="220"/>
</p>

<h1 align="center">🌍 Kliver — Intelligent Simulation Platform</h1>

<p align="center">
  <em>Empowering learning through AI-driven role-play, behavioral analytics, and adaptive feedback.</em>
</p>

---

<p align="center">
  🎬 <a href="https://www.kliver.ai/klivi/home/Klivi.webm" target="_blank">Watch the demo video</a>
</p>

---

Kliver is an **AI-powered simulation platform** that enables organizations to train and evaluate **soft skills, communication, and decision-making** through dynamic, realistic role-playing scenarios.  
Built with a **modern microservices architecture**, Kliver integrates **AI agents, real-time analytics, and skill evaluation engines** to deliver measurable, scalable learning experiences.

---

## 🧠 Core Vision

Kliver transforms traditional training into **interactive simulations** where users engage with AI-driven characters that adapt emotionally, strategically, and linguistically.  
Each interaction is analyzed in real time to assess competencies such as communication, empathy, adaptability, and critical thinking.

---

## ⚙️ Technology Stack

| Layer | Technology | Description |
|-------|-------------|-------------|
| **Backend** | .NET 8 (C#), MediatR, CQRS | High-performance API with domain-driven microservices |
| **AI Engine** | OpenAI Realtime, Gemini, LangChain, ElevenLabs | Multi-provider AI orchestration for dialogue and evaluation |
| **Frontend** | React + TypeScript + Vite | Interactive dashboards and real-time simulation interface |
| **Data Layer** | PostgreSQL, Redis, EF Core | Reliable storage, caching, and message bus |
| **Observability** | OpenTelemetry, Application Insights, Grafana Alloy | Full-stack tracing, logs, and metrics |
| **Infra & DevOps** | Docker, Kubernetes (Scaleway), GitHub Actions | CI/CD pipelines and scalable multi-environment deployment |

---

## 🧩 Platform Components

| Project | Description |
|----------|--------------|
| **Kliver API** | Core backend that manages users, workspaces, simulations, and AI sessions |
| **Kliver AI** | Graph-based workflow engine for contextual reasoning and adaptive conversations |
| **Kliver Workers** | Microservices for email, analytics, and session processing |
| **Kliver Front** | Web application for users and administrators |
| **Kliver Docs** | Centralized documentation, guides, and API reference |

---

## 🎮 Key Capabilities

- **AI-Driven Role-Play:** Simulated dialogues that adapt to tone, intent, and skill level  
- **Soft-Skill Evaluation:** Automated scoring for communication, empathy, adaptability, etc.  
- **Dynamic Storylines:** Multi-step scenarios with success/failure logic  
- **Multi-Tenant System:** Workspaces, clients, and roles for enterprise scalability  
- **Realtime Feedback:** Streaming responses via OpenAI Realtime & SignalR  
- **Observability-Ready:** Complete tracing, structured logs, and business KPIs  

---

## 🧱 Architecture Snapshot
```
Client ↔ Kliver Front ↔ Kliver API ↔ Redis ↔ Workers ↔ PostgreSQL
                                 ↳ OpenAI / Gemini / Azure Speech / ElevenLabs
```

---

## 🚀 Deployment Environments

- **Development** — Local docker-compose stack  
- **QA / Stage** — Isolated cluster with automated test runs  
- **Production** — Scaleway Kapsule Kubernetes with Grafana Alloy monitoring  

Continuous delivery via **GitHub Actions** with environment-specific secrets and versioned Docker images.

---

## 🤝 Collaboration

We welcome contributors, researchers, and organizations interested in:
- Behavioral analytics  
- Educational AI  
- Soft-skill assessment  
- AI simulation design  

👉 Check out our repositories below or contact us at **[www.kliver.ai](https://www.kliver.ai)**

---

<p align="center">
  <strong>Built with ❤️ by the Kliver Team</strong><br/>
  <em>AI that listens, reacts, and helps humans grow.</em>
</p>
