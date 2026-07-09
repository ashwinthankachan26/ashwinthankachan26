<h1 align="center">Ashwin Sunil Thankachan</h1>

<p align="center">
  <b>Backend &amp; AI Systems Engineer</b><br>
  M.S. Software Engineering Systems @ Northeastern · Boston, MA · Graduating Dec 2026
</p>

<p align="center">
  <a href="mailto:thankachan.a@northeastern.edu"><img src="https://img.shields.io/badge/Email-thankachan.a%40northeastern.edu-F0A73E?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://linkedin.com/in/ashwinthankachan"><img src="https://img.shields.io/badge/LinkedIn-ashwinthankachan-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/ashwinthankachan26"><img src="https://img.shields.io/badge/GitHub-ashwinthankachan26-181717?style=flat-square&logo=github&logoColor=white"></a>
</p>

---

### About

I build backend and AI systems that stay correct under load — deterministic where it counts, LLM-assisted where it helps. I like problems where correctness is non-negotiable (grading engines, access control, cloud infrastructure) and reach for deterministic logic first, using models only where ambiguity genuinely calls for it. Java and Python across the stack, AWS and Terraform underneath.

Currently open to **full-time Software Engineer roles** starting after December 2026.

---

### Tech Stack

**Languages**
&nbsp;`Java` &nbsp;`Python` &nbsp;`JavaScript` &nbsp;`TypeScript` &nbsp;`SQL`

**Backend**
&nbsp;`FastAPI` &nbsp;`Spring Boot` &nbsp;`Node.js` &nbsp;`Express.js` &nbsp;`REST APIs` &nbsp;`JWT` &nbsp;`Spring MVC` &nbsp;`Pydantic`

**Databases**
&nbsp;`MongoDB` &nbsp;`PostgreSQL` &nbsp;`SQL Server` &nbsp;`DynamoDB`

**Cloud &amp; DevOps**
&nbsp;`AWS (EC2 · S3 · RDS · IAM · ALB · SNS · Lambda · Auto Scaling · CloudWatch)` &nbsp;`Terraform` &nbsp;`Packer` &nbsp;`Docker` &nbsp;`Jenkins` &nbsp;`GitHub Actions`

**AI / LLM**
&nbsp;`OpenAI API (GPT-4o / GPT-5)` &nbsp;`Function Calling` &nbsp;`Prompt Engineering` &nbsp;`SymPy`

---

### Experience

**Software Development Intern — MyEdMaster** · Jan 2026 – Apr 2026
Built the FastAPI backend for an AI algebra tutoring platform: 15 REST endpoints across grading, hints, step validation, and assessment persistence, backing a React SPA over MongoDB Atlas. Designed a deterministic-first grading engine (exact match → conceptual normalization → SymPy equivalence → OpenAI fallback) covering 20+ answer formats.

**Senior Engineer, Cloud Services — LTIMindtree** · Sep 2022 – Jun 2023
Automated cloud management on AWS EC2 with Python tooling for a BFSI banking client; built CloudWatch monitoring and a Jenkins + GitHub Actions CI/CD pipeline with defined deployment gates and rollbacks.

**Graduate Engineering Trainee — LTIMindtree** · Jul 2022 – Sep 2022
Full-stack government welfare portal: Angular 13 + TypeScript frontend, Java Spring MVC backend (20+ REST routes, JWT), with 3-tier role-based access control.

---

### Featured Project — Intelligent Tutoring System

A full-stack AI algebra tutor built on **React · FastAPI · MongoDB · SymPy · OpenAI**.

- **Deterministic-first grading** — resolves final answers through exact matching, conceptual normalization, and SymPy algebraic equivalence before any LLM fallback, so symbolic math is graded by code and models only handle genuine ambiguity.
- **Real-time reasoning validation** — per-step feedback with deterministic guardrails that reject prose-only "math" steps before an OpenAI function-calling analysis compares student traces against a reference solution.
- **Adaptive hints** — template goal hints handled client-side, deeper step/problem hints from the LLM, with hint-history context and final-answer guardrails.
- **Resumable assessments** — MongoDB-backed drafts with unique `(user, subtopic)` upserts, nested React state serialization, and knowledge-profile recomputation on finalize.
- **Interactive visual math** — number-line and graph-paper tools that convert canvas actions (points, rays, segments, equations) into structured algebra payloads consumed by the grader.

Architecture: a React SPA → FastAPI service layer → domain modules (grading, analysis, adaptivity, hints) → SymPy + a centralized, offline-capable OpenAI client, all persisted to MongoDB Atlas.

---

### Other Projects

**Cloud-Native Web Application** · `Node.js` `PostgreSQL` `AWS` `Terraform` `Packer`
Full AWS infrastructure via Terraform IaC (VPC, EC2 Auto Scaling, RDS, ALB w/ TLS, S3, SNS, KMS, Secrets Manager) with least-privilege IAM and zero-downtime instance refresh; serverless email-verification pipeline on SNS + Lambda + DynamoDB; 46 Jest integration tests in CI.

**F1 Management System** · `SQL Server` `Django REST` `React` `Python`
17-table normalized schema with a 938-line stored-procedure layer (procedures, windowed views, UDFs, triggers), plus Django REST APIs and a React/Vite frontend with Recharts visualizations.

---

### Education

**M.S. Software Engineering Systems** — Northeastern University · GPA 3.83 · Dec 2026
**B.Tech, Computer Science &amp; Engineering** — GRIET, Hyderabad · May 2022

---

<p align="center"><i>Open to full-time SWE roles · Let's build something correct.</i></p>
