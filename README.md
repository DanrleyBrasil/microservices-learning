# Microservices Learning — Organização e Documentação Inicial

Este repositório é dedicado ao **aprendizado e prática de arquitetura de microserviços**.  
Nosso objetivo é construir uma base sólida de backend, evoluindo depois para o frontend, sempre documentando cada etapa.

---

## 🎯 Propósito do Projeto
- Explorar conceitos de **arquitetura de microserviços**.
- Documentar **decisões, boas práticas e aprendizados** ao longo do processo.
- Construir uma base reutilizável para projetos futuros (portfólio).
- Demonstrar a evolução: **do zero → backend → frontend → deploy**.

---

## 🏗️ Estratégia de Construção

1. **Backend primeiro (foco inicial)**
   - Criar microserviços independentes (ex.: autenticação, produtos, pedidos).
   - Cada serviço terá sua documentação local (`README.md` dentro da pasta).
   - Testar e validar via **Swagger** ou **Postman**.

2. **Infraestrutura**
   - Uso de **Docker** e **Docker Compose** para ambiente local.
   - Preparação para **Kubernetes** em fases futuras.
   - Configurações e manifests organizados em `/infrastructure`.

3. **Frontend (etapa posterior)**
   - Implementação em **Angular**.
   - Consumo das APIs através do **API Gateway**.
   - Documentação de integração no próprio frontend.

---

## 📂 Estrutura de Pastas (inicial)

- / (raiz do repositório)
- ├─ docs/ → Documentação global (arquitetura, setup, convenções, decisões)
- ├─ infrastructure/ → Arquivos de infraestrutura (docker, k8s, ci/cd)
- ├─ scripts/ → Scripts auxiliares para desenvolvimento
- └─ (futuro) microserviços/ → auth-service, product-service, etc.


- `docs/` conterá guias gerais, convenções e decisões arquiteturais.
- Cada microserviço terá seu próprio `README.md` **local**.

---

## 📘 Documentação Global
- **Visão Geral:** este `README.md`.
- **Arquitetura:** visão macro do sistema, diagramas e decisões.
- **Setup:** instruções para iniciar o ambiente do zero.
- **Convenções:** padrões de branches, commits, nomenclatura e organização.
- **ADRs:** registros de decisões arquiteturais (em `docs/adr/`).

---

## 🛣️ Roadmap Macro

### Fase 1 — Backend
- Definição e criação dos primeiros microserviços.
- Documentação de endpoints com Swagger.
- Validação via Postman.

### Fase 2 — Infraestrutura
- Contêineres com Docker.
- Orquestração local com Docker Compose.
- Preparação de pipeline CI/CD.

### Fase 3 — Frontend
- Implementação em Angular.
- Consumo das APIs via API Gateway.
- Integração documentada.

### Fase 4 — Deploy
- Configuração em Kubernetes.
- Monitoramento, observabilidade e escalabilidade.

---

## 📜 Licença
Projeto de estudo/portfólio. Licença a definir.