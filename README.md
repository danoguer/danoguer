# Daniel Nogueras 👋
### Backend & Infrastructure Engineer
**Go • C • C++ • Linux • Docker • Networking • Systems Programming**

42 graduate focused on Backend Development and Systems Infrastructure. Former professional League of Legends and poker player—a background that trained my decision-making under pressure, analytical risk assessment, and data-driven approach to complex troubleshooting. 

**Seeking Backend, Infrastructure, or DevOps-oriented roles** where I can apply systems programming, Linux administration, and automation skills while continuing to grow in cloud-native technologies.

---

## 🚀 Featured Projects

### 💬 IRC Server — Non-Blocking C++ Network Service
An Internet Relay Chat (IRC) server written in C++98 to demonstrate manual resource management and low-level network programming without modern language abstractions.

*   **Architecture:** Designed around a single-threaded event loop utilizing non-blocking I/O multiplexing via `poll()` over TCP sockets, avoiding thread-per-connection scaling limitations.
*   **High-Concurrency Benchmarking:** Audited via a custom concurrent stress tester written in Go (utilizing 5,000 Goroutines), sustaining **4,090 simultaneous client connections** with 0.00% packet loss up to the OS kernel file descriptor limits (`ulimits`).
*   **Features:** Implements dynamic channel/operator management, standard protocols (PRIVMSG), and a containerized bot service interfacing with external APIs for diagnostics.

### 🛡️ Sentinel — Go CLI Utility & System Daemon (In Progress)
A decoupled CLI utility and background system daemon built in Go that interfaces with the Gemini API to act as a secure, context-aware shell companion.

*   **Core Logic:** Reduces the risk of sensitive data exposure (passwords, IPs, JWTs) through automated regex sanitization before external API transmission.
*   **Systems & Automation:** Leverages Linux/WSL background daemons (`wsl.conf`), on-demand Function Calling, and automated retry layers designed to handle transient 502 network errors.

### 🐳 Inception — Multi-Tier Containerized Network
A multi-tier containerized infrastructure environment built from scratch using Docker and Docker Compose under strict academic architectural constraints.

*   **Networking & Services:** Engineered an isolated virtual network running 8 distinct services, including NGINX (configured as a reverse proxy with TLS 1.3, path-based, and multi-root routing), WordPress (PHP-FPM 8.2 workers), and a MariaDB instance running on a private Docker network.
*   **Monitoring & Storage:** Integrated Redis for object caching, vsftpd for FTPS data mapping, Adminer for database management, and cAdvisor to aggregate real-time container metrics (CPU, memory, and network I/O) directly from Linux cgroups.

---

## 🛠️ Tech Stack & Core Competencies

*   **Languages:** C, Go, C++, Bash/Shell scripting
*   **Tools & Infrastructure:** Docker, Docker Compose, Linux Systems, Nginx, Systems Administration, Git
*   **Systems Concepts:** Concurrency, Network Programming (Sockets), Linux/POSIX API, System Daemons, Memory Management, Automation
*   **Expanding Knowledge:** Kubernetes, Terraform, Prometheus / Grafana, CI/CD Pipelines

---

## 📫 Connect with me

*   💼 LinkedIn: linkedin.com/in/daniel-nogueras-22054a387
*   ✉️ Email: danoguer.dev@gmail.com
