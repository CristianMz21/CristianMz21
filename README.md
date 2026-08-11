<div align="center">

# Cristian Arellano Muñoz

### Fullstack Engineer · Python & .NET

[![Portfolio](https://img.shields.io/badge/Portfolio-cristianarellano.com-f97316?style=for-the-badge)](https://cristianarellano.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-czaidarellanomunoz-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/czaidarellanomunoz)
[![Email](https://img.shields.io/badge/Email-hi%40cristianarellano.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hi@cristianarellano.com)
[![CV](https://img.shields.io/badge/Download_CV-blue?style=for-the-badge&logo=googledocs&logoColor=white)](https://cristianarellano.com/cv.pdf)

</div>

---

I don't collect technologies — I solve problems and ship the fix to production. Everything below is real and running in production. Where a repository is private it is commercial code, and the live product or a written case study is linked in its place.

<div align="center">

![Tests](https://img.shields.io/badge/16,432_automated_tests-90.1%25_coverage-2ea44f?style=flat-square)
![Fuzzing](https://img.shields.io/badge/93,952_fuzz_runs-0_vulnerabilities-blue?style=flat-square)
![Quality](https://img.shields.io/badge/SonarQube-Reliability_A_·_Security_A-orange?style=flat-square)
![Certs](https://img.shields.io/badge/55%2B_certifications-Meta_·_Microsoft_·_IBM_·_Google-8A2BE2?style=flat-square)

</div>

🟢 **Open to:** backend / full-stack roles · full-time · remote or Cali, Colombia
📍 **Based in:** Cali, Colombia (UTC-5) · 🌐 Remote-first · ⚡ Reply in under 24h

---

### 🔧 Real problems → shipped solutions

**💳 "A payment can never be lost, even if the server dies mid-checkout."**
Built a checkout **Saga orchestrator with the Outbox pattern** over Stripe Connect and Wompi: every step is recoverable, every event is delivered. No lost orders, no double charges. → [case study](https://cristianarellano.com/shoppipai/)

**🧾 "Selling online in Colombia requires legal e-invoicing."**
Integrated **DIAN electronic invoicing** through the Factus API — invoices generated and reported automatically on every sale. A legal requirement most portfolio projects ignore, solved end-to-end.

**🐢 "The product listing took too long under real data."**
Profiled the ORM, added composite indexes and query projections: **90% fewer database hits** on complex lookups. Verified with performance tests, not vibes.

**🛡️ "How do you trust a codebase?"**
You test it like an attacker: **16,432 automated tests (90.1% coverage)** plus **93,952 API fuzzing tests → 0 vulnerabilities across 169 endpoints**. SonarQube rates it Reliability A / Security A. Quality is not a promise here — it's a number.

**🔌 "Frontend and backend always drift apart."**
Killed the drift: the React storefront consumes a **typed SDK auto-generated from the OpenAPI spec** — if the API changes, the build breaks before the user notices. A **pre-push gate** (lint → typecheck → tests → build → bundle budget → e2e smoke) mirrors CI locally: red gate, no push. → [shop.cristianarellano.com](https://shop.cristianarellano.com/)

**📦 "Inventory lived in spreadsheets and memory."** *(Tigo Colombia)*
Built Python apps and **ETL pipelines from CRM and POS platforms** to digitalize inventory control; the rotation reports they produced drove real logistics decisions.

**🖥️ "One person keeping a whole site running."** *(CDA La Luna)*
Automated monitoring, alerts and backup validation with **Python + Bash**, hardened servers and managed access control — operational continuity without a night shift.

**🤖 "ATS scores are a black box."**
Built the opposite: a **deterministic, explainable CV-scoring engine** — six weighted sections, a whole-string match first and a curated alias lexicon only when that misses, and no language model anywhere in the score. Every suggestion re-runs the formula with one gap closed and reports the measured delta. 1,418 test methods across four per-layer test projects, 0 skipped, 0 TODOs in 334 source files. → [buildcv-v2](https://github.com/CristianMz21/buildcv-v2) · [live](https://buildcv.cristianarellano.com)

---

### 🛠️ Stack I ship to production

```text
Python  ·  Django  ·  DRF  ·  FastAPI  ·  Celery  ·  GraphQL
PostgreSQL  ·  Redis  ·  SQLite
TypeScript  ·  React 19  ·  Next.js  ·  Node.js (NestJS · Express)
C#  ·  .NET 10  ·  ASP.NET Core
Docker  ·  Linux  ·  GitHub Actions CI/CD  ·  AWS S3/CloudFront
DDD  ·  Hexagonal  ·  Clean Architecture
pytest  ·  Playwright  ·  mypy (strict)  ·  SonarQube  ·  Sentry
```

---

### 🚀 Projects

**The Shoppipai ecosystem** — one product, three codebases, built end-to-end. It is a commercial product, so the
repositories are private; each row links to the thing you can actually open.

| Component | What it solves | Stack |
|---|---|---|
| **Backend** — [case study](https://cristianarellano.com/shoppipai/) | Payments, e-invoicing, RAG search, 27 DDD bounded contexts | Django 5.2 · PostgreSQL · Redis |
| **Storefront** — [shop.cristianarellano.com](https://shop.cristianarellano.com/) | Typed SDK generated from the OpenAPI spec, plus a pre-push quality gate | React 19 · Vite · TS strict |
| **Ops dashboard** — client access only | 18+ admin modules, RBAC, Kanban orders | Next.js 16 · NextAuth v5 |

**More:**

| Project | What it solves | Stack |
|---|---|---|
| [**Prescription Management**](https://github.com/CristianMz21/prescriptions-app-backend) | Paper prescriptions → digital flow with doctor/patient roles and PDF output | NestJS · Prisma · PostgreSQL |
| [**ecommerce-api**](https://github.com/CristianMz21/ecommerce-api) | REST API with smart Redis cache invalidation — mypy strict, 0 errors, 28/28 tests | Django · DRF · Redis |
| [**Sistema de Reservas**](https://github.com/CristianMz21/Sistema-de-Reservas-de-Eventos-Masivos) | Mass-event ticketing with multi-role JWT auth | Django · DRF · PostgreSQL |
| [**JobsColombia**](https://github.com/CristianMz21/JobsColombia) | Classifies and scores tech job postings for the Colombian market | Python · pandas |

---

### 📚 Currently

- **Microsoft Full-Stack Developer Professional Certificate** — in progress (6/12 done, incl. *Back-End Development with .NET* and *Database Integration and Management*)
- **Tecnólogo en Análisis y Desarrollo de Software (ADSO)** — SENA
- Certified: **Meta Back-End Developer** · Microsoft (C# / .NET / Web / Blazor) · IBM (Django, Docker, Linux, DevOps)

---

<div align="center">

**Have a problem like these?** [Let's talk →](https://cristianarellano.com/#contact)

<sub>Designed and shipped by hand. No templates.</sub>

</div>
