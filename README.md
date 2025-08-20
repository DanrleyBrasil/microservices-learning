# Microservices Learning — Initial Organization and Documentation

This repository is dedicated to the **study and practice of microservices architecture**.  
Our goal is to build a solid backend foundation, and later evolve into the frontend, while documenting each step of the journey.

---

## 🎯 Project Purpose
- Explore core concepts of **microservices architecture**.
- Document **decisions, best practices, and lessons learned** along the way.
- Build a reusable foundation for future projects (portfolio).
- Show the evolution path: **from scratch → backend → frontend → deployment**.

---

## 🏗️ Development Strategy

1. **Backend first (initial focus)**
   - Create independent microservices (e.g., authentication, products, orders).
   - Each service will include its own local documentation (`README.md` inside the folder).
   - Validate and test endpoints through **Swagger** or **Postman**.

2. **Infrastructure**
   - Use **Docker** and **Docker Compose** for the local environment.
   - Prepare for **Kubernetes** in later phases.
   - Store infrastructure configs and manifests under `/infrastructure`.

3. **Frontend (later stage)**
   - Implementation in **Angular**.
   - Consume APIs via the **API Gateway**.
   - Provide integration documentation within the frontend itself.

---

## 📂 Repository Structure (initial)

- / (repository root)
- ├─ docs/ → Global documentation (architecture, setup, co1nventions, decisions)
- ├─ infrastructure/ → Infrastructure files (docker, k8s, ci/cd)
- ├─ scripts/ → Development helper scripts
- └─ (future) services/ → auth-service, product-service, etc.


- `docs/` will contain global guides, conventions, and architectural decisions.
- Each microservice will include its own **local `README.md`**.

---

## 📘 Global Documentation
- **Overview:** this `README.md`.
- **Architecture:** macro view of the system, diagrams, and design decisions.
- **Setup:** instructions to bootstrap the environment from scratch.
- **Conventions:** branch, commit, and naming standards.
- **ADRs:** architecture decision records (in `docs/adr/`).

---

## 🛣️ High-Level Roadmap

### Phase 1 — Backend
- Define and create the first microservices.
- Document endpoints with Swagger.
- Validate through Postman.

### Phase 2 — Infrastructure
- Containerization with Docker.
- Local orchestration with Docker Compose.
- CI/CD pipeline preparation.

### Phase 3 — Frontend
- Implementation with Angular.
- API consumption via API Gateway.
- Integration documentation.

### Phase 4 — Deployment
- Kubernetes configuration.
- Monitoring, observability, and scalability.

---

## 📜 License
Study/portfolio project. License to be defined.