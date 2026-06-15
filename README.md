# Hey, I'm Wisdom Ojochegbe Shaibu 👋

I started out in cloud infrastructure — provisioning Kubernetes clusters, hardening CI/CD pipelines, writing Terraform for reproducible environments. Then AI agents arrived and changed what backend engineering means. Now I sit at the intersection of both: building agent-native systems and the production infrastructure that makes them reliable.

That dual background isn't accidental. The discipline of DevOps — observability, guardrails, deployment safety — turns out to be exactly what AI-assisted development needs most.

> *I build backends that hold up, and agents that don't go rogue.*

🌐 **Portfolio:** [wisdom-portfolio-rho.vercel.app](https://wisdom-portfolio-rho.vercel.app)

---

## 🧭 What I'm Working On

**AI Engineer (Agent-Native) · VettedAI** *(Jan 2026 – Present)*  
Working inside an agent-first engineering culture where AI agents generate and review most of the code. My job is to make that safe and sustainable — reviewing agent output for logic correctness and security impact, designing guardrails to prevent regressions, and shipping backend improvements through structured agent workflows.

**Backend Engineer · ArchSaint Nexus** *(Jan 2026 – Present)*  
Built the production backend for a pickup logistics platform: full shipment lifecycle management, real-time tracking via WebSockets, JWT + RBAC auth, OTP verification backed by Redis, and an async email queue with BullMQ. TypeScript strict mode throughout, Jest + MongoDB Memory Server for business logic coverage, GitHub Actions for CI.

---

## 🚀 Featured Projects

### ArchSaint Nexus — Logistics API
*The backend that actually ships (pun intended)*

A production-ready logistics API built for real operational load.

**Stack:** Node.js · TypeScript · MongoDB · Redis · BullMQ · WebSockets · JWT · GitHub Actions

- Shipment lifecycle management with event-driven architecture (Node EventEmitter)
- Real-time driver/order tracking via WebSocket
- Role-based access control across four actor types: customer, business, admin, driver
- Async email notifications decoupled from the request path via BullMQ workers
- OTP verification flow backed by Redis with TTL-controlled expiry
- Full CI pipeline with Jest + MongoDB Memory Server

🔗 [github.com/wizzfi1/archsaint-nexus](https://github.com/wizzfi1/archsaint-nexus)

---

### WizFi Microservices Platform
*8+ services, one coherent platform*

End-to-end ownership: from AWS infrastructure to Kubernetes deployments to production monitoring.

**Stack:** K3s · Terraform · Helm · AWS EC2 · PostgreSQL · Prometheus · Grafana · NGINX

- Provisioned AWS infrastructure from scratch with Terraform
- Deployed 8+ independently deployable Node.js and Python services on K3s
- Automated HTTPS with NGINX Ingress + Let's Encrypt
- Prometheus + Grafana for live infrastructure and application metrics
- Helm charts for version-controlled, repeatable releases

🔗 [github.com/wizzfi1/Wizfi-Microservices](https://github.com/wizzfi1/Wizfi-Microservices)

---

### FullStack DevSecOps Demo
*Security is not a final step*

A pipeline built around the idea that security belongs in the commit, not the postmortem.

**Stack:** GitHub Actions · Docker · Helm · K3s · Prometheus · Grafana · Sentry

- SAST scanning, secrets detection, and IaC validation gated into every pipeline run
- Hardened container images: non-root execution, minimal base layers, vulnerability scanning
- Metrics-based observability with alert thresholds and Sentry release tracking
- Zero manual releases — every deployment is policy-driven and auditable

🔗 [github.com/wizzfi1/FullStack_DevSec](https://github.com/wizzfi1/FullStack_DevSec)

---

### Wisdom's Order Fellow
*Order lifecycle management with integrity*

Production backend for real-time order tracking with a full onboarding and approval workflow.

**Stack:** Node.js · PostgreSQL · WebSockets · JWT

- Secure webhook-driven architecture with shared-secret authentication
- Registration → OTP → KYC → admin approval gating
- Strict relational order lifecycle transitions enforced at the data layer

---

## 🛠️ Core Stack

**Backend:** Node.js (Express, NestJS) · TypeScript · Python (Flask) · C# (.NET) · REST APIs · WebSockets · Event-Driven Architecture

**Databases:** PostgreSQL · MongoDB · Redis · Sequelize ORM · BullMQ

**DevOps & Cloud:** Docker · Kubernetes (K3s, AKS) · Helm · Terraform · Ansible · AWS · Azure · GitHub Actions · Azure DevOps

**Observability:** Prometheus · Grafana · Sentry · Structured Logging · Health Endpoints

**Security:** JWT · RBAC · SAST · Secrets Scanning · Non-Root Containers · IaC Policy Enforcement

**AI & Agents:** Agent-native development · Agent workflow design · Guardrail architecture · Code review for AI-generated output · Azure AI Services · Azure OpenAI

---

## 🎓 Certifications

- Microsoft Certified: **Azure AI Engineer Associate** (2026)
- Microsoft Certified: **Identity and Access Administrator Associate** (2026)
- Microsoft Certified: **Azure Developer Associate** (2025)
- **Kubernetes and Cloud Native Associate** — KCNA (2025)
- Microsoft Certified: Azure AI Fundamentals (2025)
- Microsoft Certified: Azure Fundamentals (2025)
- GitHub Foundations (2025)
- Foundational C# with Microsoft (2025)

---

## 📚 Background

**B.Eng. Computer Engineering** · Federal University of Technology, Minna

Before engineering full-time, I spent two years at Sterling Bank processing high-volume transactions inside core banking systems — which gave me an unusually grounded appreciation for data integrity, auditability, and what "production" actually means under financial-grade load.

---

## 🌍 Let's connect

- 🌐 [wisdom-portfolio-rho.vercel.app](https://wisdom-portfolio-rho.vercel.app)
- 💼 [linkedin.com/in/wisdom-shaibu-tech](https://linkedin.com/in/wisdom-shaibu-tech)
- 📧 shaibuwisdom@gmail.com
- 🐙 [github.com/wizzfi1](https://github.com/wizzfi1)
