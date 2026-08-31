# Abraham Sanchez Olea

**Senior Software Engineer** · Distributed systems, .NET, cloud & LLMOps  
Guadalajara, Mexico Metropolitan Area

[LinkedIn](https://www.linkedin.com/in/abraham-sanchez-olea-472b97b) · [GitHub profile](https://github.com/abrsanchezolea) · [abrsanchez@gmail.com](mailto:abrsanchez@gmail.com)

**Public work on GitHub:** [Profile + AMEFA](https://github.com/abrsanchezolea) · [AMEFA architecture (services, clients, flows)](https://github.com/abrsanchezolea/AMEFA-platform)

**[Interactive resume (EN/ES)](https://abraham-sanchez-olea.github.io/resume/)** · **[Versión en español](RESUME.es.md)** · **[JSON Resume](resume.json)**

---

## Summary

Senior Software Engineer with **18+ years** designing, building, and operating enterprise backend systems and distributed architectures. Core strength is taking complex, high-throughput domains—logistics, tax/compliance, GIS, health-tech, and now LLM platforms—from design through production.

The through-line of the career is **resilient .NET systems**: Clean Architecture, microservices, event-driven integration (Kafka, RabbitMQ, Redis Streams), and serious data work (SQL Server as a practitioner/DBA, PostgreSQL, MongoDB, Oracle Spatial). In recent years that foundation extends into **cloud-native multi-cloud** (Azure, GCP, AWS) and **LLMOps**: observability for agents and workflows (Langfuse, distributed tracing, alerting) and RAG systems on Azure OpenAI.

Comfortable as the engineer who owns the backend, the integration contract, and the operational story—APIs, gateways, workers, telemetry, and CI/CD—while pairing with frontend (Angular, React) and mobile (Android/Kotlin) when the product needs it.

---

## Core competencies

| Area | Stack |
| --- | --- |
| **Languages** | C#, SQL (T-SQL, PL/SQL), JavaScript/TypeScript, Kotlin, PHP |
| **Backend** | .NET / .NET Core / .NET 8, ASP.NET Web API, MVC, Clean Architecture, microservices, WCF |
| **Data** | SQL Server, PostgreSQL, MongoDB, Oracle, MySQL, spatial SQL, Entity Framework, ADO.NET |
| **Messaging** | Apache Kafka (Confluent), RabbitMQ, Redis Streams, webhooks |
| **Cloud & DevOps** | Azure (API Management, App Services, Data Factory, Blob Storage), GCP, AWS, Docker, Docker Compose, GitHub Actions, Jenkins, CI/CD |
| **AI / LLMOps** | Azure OpenAI, RAG, vector ingestion, prompt-chaining, Langfuse, LangFlow, Model Context Protocol (MCP) |
| **Observability** | Distributed tracing, structured logging, correlation IDs, health scoring, alerting dashboards |
| **Frontend & mobile** | Angular, React, HTML/CSS, Android (Kotlin / Android Studio) |
| **Payments & identity** | Stripe (PaymentIntents, webhooks), JWT, 2FA |
| **Practices** | Technical leadership, mentoring, unit testing, secure coding, audit-ready reporting |

---

## Experience

### Integration Engineer · [GlobalLogic](https://www.globallogic.com)
**Dec 2025 – Present** · Mexico

Designed and built an enterprise **Monitoring & Observability** platform for LLM applications, LangFlow workflows, and Model Context Protocol (MCP) components—turning agent activity into something operations can actually see, score, and alert on.

- Architected a distributed observability layer for high-throughput agent activity, workflow execution, and operational metrics.
- Integrated **Langfuse** as the primary telemetry source: spans, events, prompts, and error logs feeding real-time health scoring and latency trends.
- Introduced structured logging, distributed tracing, and **correlation IDs** so microservices and AI components share one trace story.
- Built an AI-powered **RAG** path on **Azure OpenAI**: multi-format ingestion (PDF, DOCX, unstructured), chunking, metadata enrichment, vector storage, and prompt-chaining for natural-language search over documents.
- Delivered analytical dashboards and alerting rules to surface error patterns, agent reliability, and downtime risk.

**Stack:** LLMOps, Langfuse, LangFlow, MCP, Azure OpenAI, RAG, vector databases, microservices, distributed tracing.

### Sr Software Engineer · [Charger Logistics Inc.](https://www.chargerlogistics.com)
**Jul 2022 – Oct 2025** · Canada (remote from Mexico; on-site travel to Canada)

Senior engineer on transportation/logistics platforms covering fleet, driver, truck, and load management. Led backend work across multiple services and kept delivery aligned with the frontend team.

- Led design and implementation of a **microservices** architecture for load management across multiple vendor companies.
- Built **LoadPosting**, the service that publishes trips for rating and assignment by driver companies.
- Designed **Platform Science** microservices that consume trailer telemetry (temperature, GPS, fuel) for real-time transport tracking.
- Designed **Nugget** packages for **multi-cloud** operations: unified AppSettings and file storage across **Azure, GCP, and AWS**.
- Mentored and enforced technical consistency and delivery practices across workflow projects.

**Stack:** .NET Core, SQL Server, MongoDB, Kafka (Confluent), Azure, GCP, AWS, microservices, telemetry.

### Sr Fullstack Developer · Freelance (Nautius International)
**Feb 2023 – Nov 2025** · Long Beach, CA · *concurrent with Charger Logistics*

Designed and delivered a **Time Card Management System** (Tides) for HR, operations, and payroll.

- Implemented .NET 8 backend logic for standard hours, overtime, additional hours, and payroll alignment with labor policy.
- Built Angular modules for employees and HR to view, edit, and approve time cards.
- Cut payroll processing time by automating calculations that were previously manual; improved reporting accuracy and auditability.
- Delivered a maintainable, secure architecture with audit-ready reporting.

**Stack:** .NET 8, Angular, payroll/timekeeping domain.

### Senior Staff Software Engineer · [Nagarro](https://www.nagarro.com)
**Sep 2021 – Sep 2022** · Jalisco, Mexico

Senior Staff engineer in a global digital-product engineering organization, contributing to enterprise delivery with the same .NET and distributed-systems backbone used throughout later roles.

### Senior Software Engineer · [Dextra Technologies](https://www.dextratechnologies.com) (J.J. Keller account)
**Mar 2015 – Feb 2021** · Zapopan, Jalisco, Mexico

Six years on J.J. Keller products for logistics, safety, and compliance in the US market—full-stack .NET with production CI.

- Owned and supported **Encompas**, **Keller Mobile Web Services**, **Keller Online**, and related logistics/services applications.
- Delivered **IRS Form 2290** heavy-vehicle tax filing: a client flow that submits to IRS processing plus an admin console to push/revoke filings when users get stuck.
- Practiced unit testing as part of feature work; Jenkins ran the suite on every check-in and blocked the build on failure.
- Trained in native Android (Android Studio / Pluralsight) to contribute to **Keller Mobile**.
- Worked with ELD device integrations, Web API, MVC, and SQL Server.

**Stack:** .NET, ASP.NET MVC, Web API, SQL Server, Jenkins, Android, ELD.

### Software Engineer · SisLogic Sistemas Lógicos
**Jul 2009 – May 2013** · Guadalajara, Jalisco, Mexico

Built **GIS / cadastral** platforms used by Mexican state and municipal governments. Acted as developer and as **project manager / delivery lead** on both major systems.

- **SIC (Sistema de Información Catastral)** for IGECEM (Estado de México): digitization of geographic information, cadastral valuation, and related spatial operations. Rolled out across several Mexican states.
- **APASEO** cadaster (Apaseo, Guanajuato): shape-file import to database, cartography digitization, capture forms, and tying spatial features to tabular records.
- Spatial stack: Oracle Spatial, SQL Server Spatial, Map Suite, PL/SQL, T-SQL, DevExpress, .NET.

### Web Developer · STX
**Jan 2006 – Jul 2009** · Guadalajara, Jalisco, Mexico

Started in product development and moved into the innovation team that built the company’s application kernel.

- E-commerce cart for a networking-equipment business and a conference/course scheduler (PHP, AJAX, jQuery).
- Core framework for **Klaymobile** (formerly Poscel), a business-administration platform, plus a point-of-sale app with Java applets for ticket/invoice printing.
- Joomla-tied CMS used by clients such as PISA to manage their own site.
- XML/XSLT reporting; Linux bash scripts and cron for operational jobs.

---

## Selected projects

### AMEFA — Health-tech membership platform *(personal venture)*

**Public docs:** [AMEFA-platform](https://github.com/abrsanchezolea/AMEFA-platform) · shown on [github.com/abrsanchezolea](https://github.com/abrsanchezolea)

Multi-platform system connecting members with medical memberships, pharmacies, and appointment scheduling. Designed as a production-style distributed system, currently in testing.

- Bounded-context microservices: Auth, Payments, Pharmacy, Appointments, Core API, plus API Gateway (Ocelot).
- Event-driven communication via **Redis Streams**.
- JWT + 2FA; Stripe PaymentIntents and webhooks; AES-GCM payload encryption package.
- Android (Kotlin) + React/Vite web client.
- Docker Compose orchestration, GitHub Actions CI/CD, DigitalOcean VPS, PostgreSQL (Neon).
- Health/readiness endpoints (`/alive`, `/health`, `/ready`) per service.
- Full service catalog, sequence diagrams, and UI illustrations are in the public architecture repo (source remains private).

### TraceSuite — Observability platform
Platform for tracing and operating APIs, workers, and event-driven services: Gateway, Auth, Payments, Events, Workers, Android, and web clients—same operational discipline as the LLM observability work (secrets packages, event bus, orchestration).

### Tides — Time cards
See Nautius International role above. Full-stack timekeeping and payroll calculation for a California operations team.

---

## Education

**Licenciatura en Ingeniería en Sistemas Computacionales**  
Instituto Tecnológico de Tepic (I.T.R.) · Nayarit, Mexico · 2008  
Cédula profesional: 5520682

---

## Certifications & awards

| Year | Credential |
| --- | --- |
| Oct 2017 | **Microsoft Exam 762: Developing SQL Databases** (Credential ID 14881679) |
| Mar 2017 | **Android Expert** — DW Mobile Certified (native Android / Android Studio) |

---

## Languages

- **Spanish** — native
- **English** — professional working proficiency

---

## This repository

| File | Purpose |
| --- | --- |
| [docs/index.html](docs/index.html) | Designed, bilingual, print-to-PDF resume |
| [RESUME.es.md](RESUME.es.md) | Full Spanish résumé (ATS-friendly) |
| [resume.json](resume.json) | [JSON Resume](https://jsonresume.org/) machine-readable source |

Print the web version (`Ctrl+P` / `Cmd+P`) to PDF. Keep this README as the ATS-plain text source for job applications.
