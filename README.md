# Hi, I'm Jêfferson Maxwell 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/j%C3%AAfferson-maxwell-01201a219/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jefferson.maxwell1603@gmail.com)
[![Location](https://img.shields.io/badge/Location-São%20Luís%2C%20Brazil-informational?style=flat-square&logo=google-maps&logoColor=white)](https://www.google.com/maps)

**Systems & Data Infrastructure Engineer @ Vale S.A.** | **Computer Science @ UFMA 🎓**  
Specialized in high-concurrency systems, low-level Linux driver debugging, distributed runtimes, and scalable data infrastructure.

---

## 🌍 Open Source & Systems Engineering

### 🐧 Linux Kernel & Hardware Drivers
* **[`Q300Z/rtl8821ce`](https://github.com/Q300Z/rtl8821ce)** — Realtek RTL8821CE PCIe Wi-Fi Driver
  * **Role:** Official Co-author ([Commit `4a8414a`](https://github.com/Q300Z/rtl8821ce/commit/4a8414af7e5b83959350969e73f9cb6b708ff568))
  * Diagnosed and patched hardware DMA desyncs and AMD-Vi IOMMU `IO_PAGE_FAULT` memory crashes on modern AMD Ryzen APUs.
  * Resolved PCIe bus-master DMA sleep state drops on Linux `s2idle` suspend/resume transitions.
  * Integrated memory read barriers (`rmb()`), TX/RX descriptor polling, and H2C queue flushing for Kernel 6.x & 7.x.

### 🦀 High-Concurrency & Distributed Systems
* **[`rustdesk/rustdesk-server`](https://github.com/rustdesk/rustdesk-server)** — High-Performance Remote Management Infrastructure (Rust)
  * **Role:** Contributor ([PR #735](https://github.com/rustdesk/rustdesk-server/pull/735))
  * Implemented an embedded, low-overhead OpenMetrics / Prometheus exporter with **zero-lock atomic counters** (`Ordering::Relaxed`) and RAII resource guards (`ActivePeerGuard`).
  * Validated through distributed load testing on Apache Spark cluster handling **50,000 concurrent peers** and 150+ MB/s relay throughput with 0 packet drops.
* **[`MaxwellAt/UnifiedCompiler`](https://github.com/MaxwellAt/UnifiedCompiler)** — Universal Distributed Remote Execution Engine
  * **Role:** Creator & Lead Architect
  * Distributed engine in Rust featuring Content-Addressable Storage (CAS), zero-delta Merkle tree synchronization, and transparent process I/O streaming.

### ⚡ Developer Tooling & Compilers
* **[`hey-api/openapi-ts`](https://github.com/hey-api/openapi-ts)** — OpenAPI to TypeScript Code Generator
  * **Role:** Merged Contributor ([PR #2287](https://github.com/hey-api/openapi-ts/pull/2287))
  * Fixed type generation collision when handling `allOf` combined with `additionalProperties: false` (11 merged commits).

---

## 🛠️ Tech Stack & Skills

### Data & Cloud Engineering
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/azure/azure-original.svg" width="40" height="40" title="Azure" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" height="40" title="Python" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/apachespark/apachespark-original.svg" width="40" height="40" title="Apache Spark" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" width="40" height="40" title="Pandas" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" width="40" height="40" title="PostgreSQL" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" width="40" height="40" title="MySQL" />
</p>

* High-volume ETL and automated data pipeline development (Python, PySpark, SQL).
* Relational data modeling, index optimization, and analytical querying.
* Cloud data solutions and automation on Microsoft Azure.

### Backend, Systems & Infrastructure
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-original.svg" width="40" height="40" title="Rust" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" width="40" height="40" title="C" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="40" height="40" title="Linux" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="40" height="40" title="Docker" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="40" height="40" title="Node.js" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="40" height="40" title="Git" />
</p>

* High-concurrency Rust and low-level C programming, Linux kernel driver tracing, and hardware DMA/IOMMU debugging.
* Containerized deployments, microservices, and reproducible environments using Docker.
* RESTful API architecture, automation scripting, and rigorous Git workflows.

---

## 📊 GitHub Analytics

<div align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=MaxwellAt&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true" />
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MaxwellAt&layout=compact&langs_count=8&theme=github_dark&hide_border=true" />
</div>

<br/>

<div align="center">
  <img alt="ko4la" src="https://media.tenor.com/FTZx57BugI4AAAAC/koala-sleeping.gif" width="55">
</div>
