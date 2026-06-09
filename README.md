# Hi, I'm Daniel Nogueras 👋

I am a software engineer and graduate of **42**, specializing in **Backend, DevOps, and Site Reliability Engineering (SRE)**. 

Before diving into infrastructure, I **spent years competing at the highest levels as a professional League of Legends & poker player**. This background directly translates to SRE and DevOps: it forged my ability to manage real-time crises under extreme pressure, execute probability-driven risk assessments during critical system incidents, and maintain a sharp, data-driven mindset when service-level objectives are on the line.

---

### 🚀 Featured Projects

#### 🛡️ [Sentinel — Secure Go AI Terminal Agent](https://github.com/danoguer/sentinel) *(In Progress)*
A decoupled CLI utility and system daemon built in Go that acts as a secure, context-aware AI companion inside your shell using the Gemini API.
- **Core:** Real-time regex engine sanitizes passwords, IPs, and JWTs before storing data securely, ensuring zero sensitive data exposure to third-party LLMs.
- **DevOps:** Implements on-demand Function Calling, Linux/WSL background daemons (`wsl.conf`), and automated retry layers for transient 502 errors.

#### 🐳 [Inception — Production-Grade Infrastructure](https://github.com/danoguer/Inception)
A highly secure, multi-tier containerized infrastructure built from scratch using Docker and Docker Compose.
- **Orchestration:** Engineered an isolated network running **8 distinct services**: NGINX (Reverse Proxy, TLS 1.3, path-based & multi-root routing), WordPress (PHP-FPM 8.2 hardened workers), and an internally isolated MariaDB instance.
- **SRE & Operations:** Integrated Redis for object caching, vsftpd (FTPS data mapping), Adminer (secure UI), and **cAdvisor** to aggregate real-time container metrics (CPU, memory, and network I/O) directly from cgroups.

#### 💬 [Ft_irc — High-Concurrency IRC Server](https://github.com/danoguer/ft_irc)
An authentic Internet Relay Chat (IRC) server built in C++ conforming to the RFC standards.
- **Architecture:** Engineered with non-blocking I/O multiplexing (`poll`/`select`) to handle massive concurrent client connections efficiently over TCP sockets without thread exhaustion.
- **Features:** Implements channel/user management, network protocols, and an automated bot interfacing with external APIs for real-time channel metrics and environment alerts.

---

### 🛠️ Tech Stack & Core Competencies

- **Languages:** C (Expert), Go (Current Focus), C++ (Intermediate), Bash/Shell scripting
- **Tools & Infrastructure:** Docker, Containerization, Linux Systems, Nginx, Systems Administration, Git
- **Systems Concepts:** Concurrency, Network Programming (Sockets), Linux/POSIX API, System Daemons, Memory Management, Automation
- **Currently Exploring:** Kubernetes, Terraform, Prometheus / Grafana, CI/CD Pipelines

---

### 📫 Connect with me

- 💼 **LinkedIn:** [linkedin.com/in/daniel-nogueras-22054a387](https://www.linkedin.com/in/daniel-nogueras/)
- ✉️ **Email:** [danoguer.dev@gmail.com](mailto:danoguer.dev@gmail.com)
