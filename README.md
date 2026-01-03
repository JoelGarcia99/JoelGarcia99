# impl SeniorEngineer for JoelGarcía

> **High-Performance Systems Architect & Rust Specialist**
> *Bridging the gap between low-level efficiency and cloud-native scalability.*

---

### ⚡ Engineering Philosophy
I specialize in building **fault-tolerant, high-throughput backend systems**. My focus shifts from "making it work" to "making it scale," leveraging **Rust's memory safety** and **Async I/O** to solve expensive infrastructure problems.

- 🦀 **Rust & Systems:** Building zero-cost abstractions for financial engines and real-time gaming logic.
- 🏗️ **Distributed Architecture:** Designing event-driven microservices with **RabbitMQ**, **gRPC**, and **Docker**.
- 🧠 **Applied ML:** Integrating **PyTorch (tch-rs)** models directly into backend pipelines for sub-millisecond inference.
- 📉 **Optimization:** Obsessed with reducing memory footprints and CPU cycles (e.g., migrating from arrays to **Bitboards**).

---

### 🛠 Tech Stack

| Core | Infrastructure | Data & ML |
| :--- | :--- | :--- |
| ![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white) ![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) | ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) | ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |
| ![Actix/Axum](https://img.shields.io/badge/-Axum-orange?style=flat-square) ![Tokio](https://img.shields.io/badge/-Tokio-black?style=flat-square) | ![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white) ![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black) | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) |

---

### 📂 Selected Work

#### 🚀 [Titan Event Gateway](https://github.com/joelgarcia/titan-event-gateway) (Open Source)
> *High-performance WebSocket gateway written in Rust.*
- **Challenge:** Node.js event loop lag during high-concurrency bursts (>10k events/sec).
- **Solution:** Decoupled producers via **RabbitMQ** and implemented a multi-threaded Rust consumer using `lapin` and `tokio`.
- **Outcome:** 90% reduction in memory usage vs previous implementation.

#### 🛡️ **Sigma Financial Core** (Private Commercial)
> *Double-entry ledger system for multi-tenant SaaS.*
- Designed a custom **`i64` monetary type** to eliminate floating-point errors in tax calculations.
- Implemented **optimistic concurrency control** for high-volume invoicing.

#### 🎲 **McKakos Real-Time Engine** (Private Commercial)
> *Low-latency game logic server.*
- **Optimization:** Replaced array-based state checks with **Bitboards (u64)** and bitwise operations.
- **Result:** Reduced winner detection time from **1s to 500ms** while handling 10x concurrent sessions.

---

### 📡 Network
- 🌐 **Portfolio:** [joelgarcia.dev](https://joelgarcia.dev)
- 💼 **LinkedIn:** [linkedin.com/in/joel-garciart](https://www.linkedin.com/in/joel-garciart)
- 📧 **Contact:** [garciajunior796@gmail.com](mailto:garciajunior796@gmail.com)
