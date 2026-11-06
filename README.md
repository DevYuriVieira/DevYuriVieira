<div align="center">

# Yuri Vieira Teixeira
### Software Engineer | Distributed Systems • Java (Spring Boot & Virtual Threads) • .NET / C# • TypeScript (React & Angular) • React Native

<p align="center">
  <a href="https://devyurivieira.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://linkedin.com/in/yuri-vieira-teixeira" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:yurivieirateixeira98@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

</div>

---

## ⚡ Engineering Benchmarks & Impact

<div align="center">

| 🚀 Peak Throughput | 🧪 Automated Tests | 🛡️ Web Reliability | 🔄 Messaging Resilience |
| :---: | :---: | :---: | :---: |
| **2,450 req/s**<br><sub>Zero 5xx under k6 stress (Java Virtual Threads)</sub> | **1,000+ Tests**<br><sub>Unit, integration, E2E & concurrency suites</sub> | **100/100 Lighthouse**<br><sub>Max score in all 4 categories (Work-Fitness & Portfolio)</sub> | **Zero Dual-Write**<br><sub>Transactional Outbox + RabbitMQ DLQ/TTL</sub> |

</div>

---

## 🚀 About Me

Full-Stack Software Engineer with deep focus on **Java (Spring Boot, Virtual Threads)**, **.NET / C# (ASP.NET Core)**, and modern frontend/mobile engineering with **TypeScript (React, Angular, React Native Offline-First)**.

- 👨‍🏫 **Former Programming Instructor at SENAI / FAETEC:** Taught programming logic, relational databases (PostgreSQL), OOP in Java, and RESTful API architecture.
- 🏢 **Zeiss AI Platform Delivery:** Engineered an enterprise-grade MVP in partnership with **Carl Zeiss Vision** during the 790-hour Serratec Residency (OCR + RAG AI pipeline via n8n, 3-tier JWT/RBAC, and real-time sales analytics).
- ⚙️ **Distributed Systems & Event-Driven Architecture:** Proven track record implementing the Transactional Outbox pattern, RabbitMQ message brokers, Keycloak OIDC, PostgreSQL concurrency (`FOR UPDATE SKIP LOCKED`, RLS), and distributed tracing via OpenTelemetry/Jaeger.
- 🎯 **Production Excellence:** Commercial software active in production scoring a verified **100/100 in Google Lighthouse**, backed by rigorous test automation (Vitest, Playwright, Cypress, xUnit, JUnit, k6).
- 🎓 **Education:** Postgraduate degree in Software Engineering and Bachelor's in Industrial Engineering. Advanced English (B2+).

---

## 🏛️ Architectural Principles in Practice

- **Event-Driven Resilience & At-Least-Once Delivery:** Decoupling microservices and modules using the **Transactional Outbox** pattern inside database transactions to eliminate dual-write hazards, backed by idempotent consumers keyed by `MessageId` and RabbitMQ retry queues with dead-letter routing (DLQ).
- **Offline-First Field Architecture:** Client-side deterministic FIFO mutation queues persisted locally (AsyncStorage) with background synchronization and server-side conflict resolution when connectivity restores.
- **Defensive Concurrency & Security:** Database row-level locking via `FOR UPDATE SKIP LOCKED` for lock-free parallel workers, optimistic locking via PostgreSQL `xmin`, fail-closed Row Level Security (RLS), and OAuth 2.0 / OIDC resource server authentication with Keycloak (RS256/JWKS).
- **Comprehensive Quality Assurance:** Multi-layered test suites spanning unit tests, database rollback integration tests, fault-injection resilience tests, load tests with k6, and automated WCAG 2.1 AA/AAA accessibility audits.

---

## 🌟 Featured Projects

| Project | Highlights & Architecture | Links |
| :--- | :--- | :---: |
| 🕶️ **Zeiss - AI Recommendation Assistant** | Enterprise MVP built with an 11-person team for Carl Zeiss Vision. Features assisted prescription OCR validation (Human-in-the-Loop), an AI lens recommendation engine (n8n/RAG), stateless JWT RBAC, and real-time ApexCharts dashboards. | *Corporate NDA* |
| 🚜 **FarmFlow (Mobile & Distributed Engine)** | End-to-end agri-tech system for mid-field operations: **React Native (Expo)** app with a transactional FIFO offline-first queue and MAPA regulatory compliance, consuming a **Java (Virtual Threads & Spring Boot)** distributed backend sustaining **2,450 req/s** with zero 5xx errors. **549 automated tests**. | [Mobile](https://github.com/DevYuriVieira/farmflow-mobile) • [Backend](https://github.com/DevYuriVieira/farmflow-backend) |
| 🚛 **FleetOps API** | Event-driven fleet and logistics engine built with **.NET 10 (C# 14)** and Clean Architecture across 5 DDD Bounded Contexts. Implements Transactional Outbox on **RabbitMQ** (Publisher Confirms, DLQ), idempotent consumers, Keycloak OIDC, and OpenTelemetry/Jaeger tracing. Sustains **278 RPS** in ACID writes with **300 automated tests**. | [Repository](https://github.com/DevYuriVieira/fleetops-api) |
| 🏋️ **Work-Fitness Platform** | Production commercial web platform delivered end-to-end for a fitness coach. Clean Architecture core without DOM dependencies, qualified WhatsApp lead capture, WCAG 2.1 AA accessibility, and a perfect **100/100 score in all 4 Google Lighthouse categories**. | [Live Demo](https://viniciusantos.vercel.app/) |
| 🌐 **Interactive Portfolio** | Production portfolio built with **Angular** standalone components, native Signals, and `OnPush` change detection, featuring a GPU-accelerated **WebGL/Three.js** particle system. Tested across 3 layers (**195 automated tests** with Vitest, Playwright, Axe-Core WCAG, and Cypress). | [Repository](https://github.com/DevYuriVieira/portfolio) • [Live](https://devyurivieira.vercel.app) |
| 🛒 **Spring Boot E-Commerce API** | Layered e-commerce REST API in **Java & Spring Boot** managing order lifecycles, N:N relationships, concurrent stock management, Spring Security (JWT), ViaCEP integration, and Swagger/OpenAPI documentation. | [Repository](https://github.com/DevYuriVieira/ecommerce-serratec-api) |
| 💰 **Payroll System Java** | Batch payroll tax calculation engine (**INSS/IRRF**) built with **raw JDBC on PostgreSQL** in MVC + DAO architecture without ORM. Implements exact monetary precision with `BigDecimal`, Singleton connection pooling, and CSV export. | [Repository](https://github.com/DevYuriVieira/payroll-system-java) |
| 🎮 **PlayStation Evolution Timeline** | 30-year interactive hardware evolution timeline built with **React, TypeScript, CSS Modules**, and **Framer Motion** declarative 60 FPS transitions driven by the Intersection Observer API. | [Repository](https://github.com/DevYuriVieira/playstation-evolution-timeline) • [Live](https://playstation-evolution-timeline.vercel.app) |

---

## 📊 GitHub Analytics

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DevYuriVieira&layout=compact&theme=dark&hide_border=true&langs_count=8&exclude_repo=DevYuriVieira" alt="Top Languages" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=DevYuriVieira&show_icons=true&theme=dark&include_all_commits=true&count_private=true" alt="GitHub Stats" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=DevYuriVieira&theme=dark&hide_border=true" alt="GitHub Streak" />
</p>

---

## 🛠️ Technologies & Tools

### ⚙️ Backend & Distributed Systems
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-%236DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=microsoft&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/Django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-009688?style=for-the-badge&logo=keycloak&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)

### 💻 Frontend & Mobile
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![React](https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Angular](https://img.shields.io/badge/Angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Expo](https://img.shields.io/badge/Expo-1C2024?style=for-the-badge&logo=expo&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)

### 🗄️ Database
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![DBeaver](https://img.shields.io/badge/DBeaver-382923?style=for-the-badge&logo=dbeaver&logoColor=white)

### 🤖 AI & Automation
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

### 🧪 Testing
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![xUnit](https://img.shields.io/badge/xUnit-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Cypress](https://img.shields.io/badge/Cypress-69D3A7?style=for-the-badge&logo=cypress&logoColor=white)
![k6](https://img.shields.io/badge/k6-7D64FF?style=for-the-badge&logo=k6&logoColor=white)

### 📋 Methodologies & Agile
![Scrum](https://img.shields.io/badge/Scrum-20232A?style=for-the-badge&logo=scrumalliance&logoColor=white)
![Kanban](https://img.shields.io/badge/Kanban-0052CC?style=for-the-badge)
![Trello](https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white)

### 🔧 Tools & IDEs
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
![VS Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## 📬 Connect With Me

<p align="center">
  <a href="https://linkedin.com/in/yuri-vieira-teixeira" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://devyurivieira.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="mailto:yurivieirateixeira98@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>
