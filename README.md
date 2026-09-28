# Daniel Nogueras 

### Cloud & DevOps Engineer | Systems & Infrastructure

Former professional League of Legends player and poker player, with a decade of competitive experience in decision-making, risk assessment, and analytical problem-solving. Now a 42 Systems Graduate focused on building reliable, automated, and cloud-native infrastructure.

Focused on DevOps, Site Reliability Engineering (SRE), and Cloud Infrastructure, combining low-level systems programming (C/C++, Go) with Infrastructure as Code and container automation.

---

###  Tech Stack & Core Competencies

| Domain                    | Technologies & Skills                                                                           |
| :------------------------ | :---------------------------------------------------------------------------------------------- |
| **Cloud & IaC**           | AWS (EC2, VPC, Security Groups), Terraform, Ansible                                             |
| **Containers & Systems**  | Docker, Docker Compose, Linux, Linux administration, cgroups                                    |
| **Languages**             | Go, C, C++, Bash/Shell Scripting                                                                |
| **Networking & Security** | TCP/IP, POSIX sockets, I/O multiplexing (`poll`), NGINX, TLS, reverse proxy, input sanitization |
| **Observability & CI/CD** | Prometheus, Grafana, cAdvisor, GitHub Actions, Git, Linux CLI                                   |
| **Expanding Knowledge**   | AWS Solutions Architect – Associate (In preparation), Kubernetes                                |

---

###  Featured Projects

####  [CloudForge](https://github.com/danoguer/cloudforge) — Automated AWS Infrastructure Pipeline

*Automated AWS deployment pipeline using Infrastructure as Code and configuration management.*

- **IaC & Automation:** Provisioned multi-tier AWS EC2 infrastructure using **Terraform** paired with **Ansible** for automated server configuration.
- **Architecture & Proxy:** Containerized web application stack managed via **Docker Compose** behind an automated **NGINX** reverse proxy with SSL/TLS termination.
- **CI/CD:** Automated validation and deployment workflows using **GitHub Actions**.
- **Reproducibility:** Single-command deployment and teardown through Terraform, Ansible, and Docker Compose.

####  [Sentinel](https://github.com/danoguer/sentinel) — AI-Assisted SRE Context Engine & System Daemon

*A Go-based SRE agent combining host telemetry, logs, workspace context, and AI-assisted diagnostics.*

- **Go Systems Architecture:** CLI and background daemon collecting host telemetry, logs, and workspace context for AI-assisted diagnostics.
- **Security & Resilience:** Built automated regex sanitization to strip secrets, credentials, and tokens before API transmission; implemented exponential backoff retries for transient HTTP errors.
- **Observability:** Integrates system metrics, process information, logs, and workspace context to provide actionable diagnostic recommendations.

####  [IRC Server](https://github.com/danoguer/irc-server) — Non-Blocking C++ Network Service

*Custom C++98 Internet Relay Chat server designed for low-level resource management and socket I/O multiplexing.*

- **Event-Driven Architecture:** Single-threaded event loop utilizing non-blocking `poll()` over TCP sockets to handle thousands of concurrent clients without thread overhead.
- **Benchmarking:** Built a custom stress tester in **Go** (utilizing 5,000 Goroutines), sustaining **4,090 simultaneous connections with 0.00% packet loss** up to OS kernel file descriptor limits (`ulimit`).

####  [Inception](https://github.com/danoguer/inception) — Multi-Tier Containerized Infrastructure

*Multi-service containerized infrastructure built from scratch under strict architectural constraints.*

- **Network Architecture:** Docker environment orchestrating 7 isolated services: NGINX, PHP-FPM, MariaDB, Redis, vsftpd, Adminer, and cAdvisor.
- **Observability:** Integrated cAdvisor to aggregate real-time container metrics (CPU, Memory, Disk I/O) directly from Linux cgroups.

---

###  Background

- **42 Systems Core:** C/C++, Unix, networking, memory management, and systems programming.
- **Competitive Background:** 5 years professional League of Legends + 5 years professional poker.
- **Current Focus:** AWS, Infrastructure as Code, DevOps, and SRE.

---

###  Connect

-  [LinkedIn](https://linkedin.com/in/daniel-nogueras)
-  [danoguer.dev@gmail.com](mailto:danoguer.dev@gmail.com)
-  [danoguer.dev](https://danoguer.dev)
