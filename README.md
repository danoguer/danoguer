# Daniel Nogueras

### Cloud & DevOps Engineer | Systems & Infrastructure

[danoguer.me](https://danoguer.me) · [LinkedIn](https://linkedin.com/in/daniel-nogueras) · [danoguer.dev@gmail.com](mailto:danoguer.dev@gmail.com)

Former professional League of Legends player and poker player with a decade of competitive experience in decision-making under uncertainty, risk assessment, and data-driven analysis. Now a systems-focused software engineer combining low-level Linux/Unix fundamentals with cloud infrastructure, automation, and Site Reliability Engineering principles.

---

### Tech Stack & Core Competencies

| Domain | Technologies & Skills |
| :--- | :--- |
| **Cloud** | AWS (VPC, EC2, S3, IAM, CloudFront, Lambda@Edge, Route 53, ACM) |
| **IaC & Automation** | Terraform, Ansible, GitHub Actions (OIDC) |
| **Containers & Observability** | Docker, Docker Compose, Prometheus, Grafana, cAdvisor |
| **Systems & Networking** | Linux internals, Bash, Go, C, C++, POSIX sockets, TCP/IP, NGINX |
| **Certifications** | AWS Certified Solutions Architect – Associate (SAA-C03) |

---

### Featured Projects

#### [Sentinel](https://github.com/danoguer/sentinel) — AI-Assisted SRE Context Engine & System Daemon
*Go, Linux Telemetry, Prometheus, Grafana, Gemini API, Docker*

Native Go daemon and CLI that collects live Linux telemetry (Prometheus metrics, journald logs, kernel/process states) and transforms it into structured evidence for AI-assisted incident diagnostics.

- **Systems Architecture:** CLI and daemon communicate over an authenticated UNIX domain socket to query host states with minimal footprint.
- **Security & Privacy:** Automated sanitization pipeline that strips secrets, keys, and credentials from logs and metrics before model ingestion.
- **Resilience:** Exponential backoff and bounded payload memory buffers designed for production-like reliability.

#### [CloudForge](https://github.com/danoguer/cloudforge) — Automated AWS Infrastructure Pipeline
*AWS, Terraform, Ansible, Docker, GitHub Actions, NGINX*

Production-style AWS environment with strict architectural layer separation and automated configuration management.

- **Infrastructure as Code:** Provisions modular VPC, public/private subnets, least-privilege IAM roles, security groups, and EC2 instances via Terraform with remote S3 state and DynamoDB locking.
- **Configuration Management:** Ansible playbooks automate host provisioning, package installations, and Docker daemon lifecycle.
- **Edge & Networking:** Web application stack containerized with Docker Compose, routed privately behind an automated NGINX reverse proxy with TLS termination.

#### [danoguer.me](https://github.com/danoguer/danoguer.dev) — Serverless Portfolio on AWS
*CloudFront, S3, Lambda@Edge, Route 53, ACM, Terraform, GitHub Actions*

Zero-maintenance, secure static web architecture hosted natively on AWS serverless services.

- **Secure CI/CD Deployment:** Deployed via GitHub Actions authenticated through federated OpenID Connect (OIDC) roles, eliminating static, long-lived AWS credentials.
- **Edge Security & Performance:** Private S3 bucket accessible exclusively through CloudFront Origin Access Control (OAC); strict CSP and security response headers enforced at the edge via Lambda@Edge.

---

### Background

- **42 School Common Core:** Low-level work on POSIX sockets, memory management, signals, concurrency, and Unix internals.
- **Competitive Esports & Poker:** 10 years competing professionally in high-stakes environments, shaping real-time decision-making, probability modeling, and mental resilience under pressure.
- **Spoken Languages:** Spanish (Native) · English (C1 Advanced, EF SET Certified).

---

### Connect

- **Portfolio:** [danoguer.me](https://danoguer.me)
- **LinkedIn:** [linkedin.com/in/daniel-nogueras](https://linkedin.com/in/daniel-nogueras)
- **Email:** [danoguer.dev@gmail.com](mailto:danoguer.dev@gmail.com)
