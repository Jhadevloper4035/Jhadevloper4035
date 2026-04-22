<!-- Header -->
<h1 align="center">👋 Hey, I'm Navroj Jha</h1>

<p align="center">
  <b>🚀 Backend Engineer → DevOps/SRE Engineer | CI/CD | Cloud Infrastructure | Infra as Code</b>
</p>

<p align="center">
  <a href="mailto:your@email.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/Jhadevloper4035"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://medium.com/@navrojjha21"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/your-linkedin"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

---

> *"I don't just write code — I ship it, scale it, and make sure it never goes down."*

---

## ⚡ Quick Profile

| | |
|---|---|
| 📍 **Location** | Delhi, India |
| 💼 **Experience** | 3 Years Backend Engineering |
| 🎯 **Goal** | DevOps / SRE at a Top Product Company |
| 📝 **Writing** | Technical articles on [Medium](https://medium.com/@navrojjha21) |
| ☁️ **AWS** | SAA-C03 (Preparing) |

---

## 🔭 What I'm Working On

- 🔧 Building **[PipeIQ](https://github.com/Jhadevloper4035)** — a CI/CD analytics SaaS (GitHub Actions cost tracker + DORA metrics)
- ☁️ Provisioning production infra with **Terraform + ECS Fargate + RDS + SQS** on AWS
- 📊 Integrating **Prometheus + Grafana** for observability pipelines
- 🐳 Designing multi-container setups with **Docker Compose & Kubernetes**
- 🚀 Building real-world **GitHub Actions CI/CD pipelines** with OIDC federation
- 📖 Preparing for **AWS Certified Solutions Architect – Associate (SAA-C03)**

---

## 🛠️ Tech Stack & Tools

### ☁️ Cloud & DevOps
<p>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
</p>

### 📊 Observability
<p>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/>
</p>

### 💻 Backend & Databases
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
</p>

### 🌐 Frontend & Tools
<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Stripe-008CDD?style=flat-square&logo=stripe&logoColor=white"/>
</p>

---

## 🌟 Featured Projects

### 🔁 PipeIQ — CI/CD Analytics SaaS *(In Progress)*
> Helping engineering teams track GitHub Actions costs, measure DORA metrics, and detect flaky pipelines.

- **Stack:** Node.js/Express · Next.js · RDS PostgreSQL (RLS) · ElastiCache Redis · SQS · ECS Fargate · Terraform
- **Architecture:** GitHub App (org-scoped installs) → HMAC-verified webhooks → SQS → async analytics processor
- **Pricing:** Free / Pro $29 / Team $79 per org · Stripe billing

---

### 🛒 Dockerized E-commerce Platform
> Full-stack e-commerce app with Docker Compose, Redis caching, Razorpay payments, and AWS deployment.

- Multi-tenant frontend (Next.js 15) + Node.js backend + MongoDB
- CI/CD via GitHub Actions → AWS ECR → EC2 with Nginx + SSL
- Cart, wishlist, product compare, OTP auth, JWT refresh rotation

---

### 📋 Lead Management System (Skydecor)
> Enterprise CRM for a B2B interior brand — deployed on AWS EC2 with full RBAC, S3 uploads, and Excel exports.

- Role-based access: Admin / Event / Showroom / Website
- S3 presigned uploads · PM2 · Nginx reverse proxy · Let's Encrypt SSL
- React + Zustand frontend refactored from EJS monolith

---

### 🚀 Cloud Resume / DevOps Projects
> [![AWS Labs](https://img.shields.io/badge/AWS_Labs-GitHub-181717?style=flat-square&logo=github)](https://github.com/Jhadevloper4035)
> [![BulkBuy India](https://img.shields.io/badge/BulkBuy_India_(Spring_Boot_Microservices)-GitHub-181717?style=flat-square&logo=github)](https://github.com/Jhadevloper4035)

---

## 🏗️ Backend Engineering — What I Actually Know

> 3 years of production backend work. Not tutorials — real systems, real bugs, real scale decisions.

<details>
<summary><b>🔐 Auth & Security</b></summary>

- JWT access + refresh token rotation with Redis blacklisting
- Stateless sessions with httpOnly cookies, CSRF mitigation
- Role-based access control (RBAC) with middleware-level guards
- HMAC-SHA256 webhook signature verification (GitHub App pattern)
- Bcrypt password hashing, OTP-based verification flows
- Multi-tenant Row-Level Security (RLS) in PostgreSQL via `SET app.current_org_id`

</details>

<details>
<summary><b>⚡ Performance & Caching</b></summary>

- Redis for session caching, rate limiting, and hot-data lookup (org_id → GitHub install token)
- DB query optimization: indexes, covering indexes, EXPLAIN ANALYZE
- S3 presigned URL pattern for direct client uploads (no server bottleneck)
- Lazy loading, pagination, cursor-based pagination for large datasets
- Background job processing with SQS queues — immediate 200, async processing

</details>

<details>
<summary><b>📨 Async & Event-Driven</b></summary>

- SQS queue consumers with dead-letter queues (DLQ) and retry policies
- RabbitMQ email queues with OTP delivery pipelines
- Webhook receiver pattern: validate → enqueue → respond → process async
- Event-driven architecture: GitHub webhook → resolve org → SQS → analytics processor

</details>

<details>
<summary><b>🗄️ Databases</b></summary>

- **PostgreSQL:** Transactions, joins, RLS policies, Sequelize ORM, schema design for multi-tenancy
- **MongoDB:** Aggregation pipelines, indexing strategies, Mongoose schemas
- **Redis:** TTL management, pub/sub patterns, cache invalidation strategies
- Data modelling for SaaS: org-scoped isolation, Stripe customer mapping, feature flag tables

</details>

<details>
<summary><b>🏛️ API Design</b></summary>

- RESTful API design: resource naming, HTTP verbs, status codes, error envelopes
- Versioned API routes, middleware chains, request validation (Zod/Joi)
- Idempotency keys for payment and webhook endpoints
- API rate limiting with Redis sliding window counters
- OpenAPI/Swagger documentation

</details>

---

## 🧠 System Design — How I Think at Scale

<details>
<summary><b>📐 Patterns I've Applied in Real Projects</b></summary>

| Pattern | Where I Used It |
|---------|----------------|
| **Webhook Fan-out via SQS** | PipeIQ — GitHub events → queue → async analytics |
| **Multi-tenant RLS** | PipeIQ — PostgreSQL per-org data isolation |
| **Presigned URL Upload** | Skydecor LMS — S3 direct uploads without server relay |
| **JWT Refresh Rotation** | E-commerce auth — token theft mitigation |
| **Redis Token Blacklist** | Logout invalidation across distributed sessions |
| **DLQ + Retry Policy** | SQS dead-letter queues for failed webhook processing |
| **OIDC Federation** | GitHub Actions → AWS without long-lived IAM keys |
| **Reverse Proxy + TLS** | Nginx + Let's Encrypt in front of Node.js apps on EC2 |
| **PM2 Cluster Mode** | Zero-downtime restarts, multi-core utilization |
| **Docker Multi-Stage Build** | Slim production images, separate build/runtime layers |

</details>

<details>
<summary><b>🔍 System Design Topics I Can Walk Through</b></summary>

- **Design a URL Shortener** — Hash collisions, base62 encoding, Redis caching, DB write patterns
- **Design a Rate Limiter** — Token bucket vs sliding window, Redis atomic ops, distributed state
- **Design a Notification System** — SQS fanout, retry logic, delivery guarantees, idempotency
- **Design a Multi-Tenant SaaS** — Org isolation strategies (RLS vs schema-per-tenant vs DB-per-tenant)
- **Design a CI/CD Cost Tracker** *(PipeIQ)* — Webhook ingestion, async processing, DORA metric computation
- **Design a File Upload System** — Presigned URLs, multipart upload, virus scanning pipeline
- **Design an Auth System** — OAuth2 flows, JWT vs sessions, refresh token rotation, PKCE
- **Design an API Gateway** — Rate limiting, auth middleware, request routing, observability hooks

</details>

<details>
<summary><b>☁️ AWS Architecture Decisions I Understand</b></summary>

- **ECS Fargate vs EC2:** When to go serverless containers vs managed instances
- **RDS vs DynamoDB:** ACID requirements, query patterns, multi-tenant isolation trade-offs
- **SQS vs SNS vs EventBridge:** Fan-out patterns, ordering guarantees, DLQ strategies
- **ALB vs NLB vs API Gateway:** L7 routing, WebSocket support, cost-per-request models
- **S3 + CloudFront:** Static asset CDN, cache invalidation, presigned URL patterns
- **Secrets Manager vs Parameter Store:** Rotation policies, cost trade-offs, app integration
- **VPC design:** Public/private subnets, NAT gateway, security groups, NACLs

</details>

---

## 📝 Technical Writing on Medium

| Article | Topic |
|---------|-------|
| 🐳 Docker Multi-Stage Builds | Docker · DevOps |
| ⚙️ GitHub Actions Matrix Strategy | CI/CD · Automation |
| 🔐 SELinux Deep Dive | Linux Security |
| ☁️ AWS SAA-C03 Study Notes | Cloud · Certification |

> 👉 [@navrojjha21 on Medium](https://medium.com/@navrojjha21)

---

## 🗺️ DevOps Learning Journey

| Phase | Tools & Concepts | Status |
|-------|-----------------|--------|
| ✅ | Git, GitHub, Linux, Bash | Completed |
| ✅ | Docker, Docker Compose | Completed |
| ✅ | GitHub Actions CI/CD, ECR, EC2 | Completed |
| ✅ | AWS Core (IAM, EC2, S3, VPC, RDS, SQS) | Completed |
| 🔄 | Terraform — Infra as Code | In Progress |
| 🔄 | Prometheus + Grafana (Observability) | In Progress |
| 🔄 | Golang (KodeKloud) | In Progress |
| 🔜 | Kubernetes, Ansible, Jenkins | Coming Soon |

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Jhadevloper4035&show_icons=true&theme=tokyonight&hide_border=true" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jhadevloper4035&layout=compact&theme=tokyonight&hide_border=true" height="160"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Jhadevloper4035&theme=tokyonight&hide_border=true"/>
</p>

---

## 🤝 Let's Connect

<p>
  <a href="https://medium.com/@navrojjha21"><img src="https://img.shields.io/badge/Medium-Read_My_Articles-12100E?style=for-the-badge&logo=medium&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/your-linkedin"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

> *"Infrastructure is the product. Reliability is the feature."* — Navroj Jha

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Jhadevloper4035&color=blueviolet&style=flat-square&label=Profile+Views"/>
</p>
