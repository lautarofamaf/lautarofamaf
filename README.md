<div align="center">

# Lautaro Deco

**Full-Spectrum Backend & Systems Engineer**  
*Computer Science @ FaMAF — Universidad Nacional de Córdoba*

```
[ Microarchitecture ]  ───>  [ Kernel & OS ]  ───>  [ Network Protocols ]  ───>  [ Distributed Backends ]
   LEGv8 CPU Core             xv6 Scheduler            Reliable Transport           FastAPI & Spark
```

Bridging the gap between silicon-level hardware logic, kernel-level synchronization, and high-concurrency cloud backends.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/lautaro-deco)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:portadeco@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/lautarofamaf)

</div>

---

## 🧭 Engineering Index

| Domain | Core Focus | Featured Projects |
| :--- | :--- | :--- |
| **Distributed Backends & Real-Time** | Concurrency, WebSockets, Event-Driven APIs | [`dotc-backend`](#death-on-the-cards--real-time-multiplayer-backend), [`diagnovet-challenge`](#diagnovet--automated-clinical-report-service), [`Coding-Challenge-APM`](#apm-dynamic-segment-tree-engine) |
| **Operating Systems & Hardware** | CPU Pipelining, Scheduling, Kernel Synchronization | [`pipelined-legv8-processor`](#5-stage-pipelined-legv8-processor-core), [`xv6-kernel-scheduler-mlfq`](#xv6-kernel-scheduler-mlfq), [`xv6-kernel-semaphores-sync`](#xv6-kernel-synchronization--semaphores) |
| **Networks & Distributed Data** | Flow/Congestion Control, RDD Transformations | [`reliable-transport-protocol-cpp`](#reliable-transport-protocol--congestion-control), [`spark-distributed-data-pipeline`](#distributed-big-data-pipeline) |

---

## ⚡ Architectural Case Studies

### 🌐 High-Concurrency & Real-Time Systems

#### 🎮 [Death on the Cards — Real-Time Multiplayer Backend](https://github.com/lautarofamaf/dotc-backend)
> **Stack:** `Python` `FastAPI` `WebSockets` `SQLAlchemy` `Pytest` `Docker`

* **State Synchronization:** Full-duplex WebSocket architecture managing synchronized multi-client state transitions, action broadcasting, and reconnect resilience with low end-to-end latency.
* **Domain Decoupling:** Strictly layered design isolating transport endpoints, dependency injection wiring, database persistence, and card-effect state machines.
* **Test Automation:** Comprehensive Pytest coverage verifying concurrent game rooms, turn timeouts, and complex edge-case game resolution.

#### 🐾 [DiagnoVET — Automated Clinical Report Service](https://github.com/lautarofamaf/diagnovet-challenge)
> **Stack:** `Python` `FastAPI` `PyMuPDF` `Google Cloud Firestore` `Docker` `Render`

* **Asynchronous Ingestion Pipeline:** Streamlined document parsing service extracting structured entities and embedded clinical imagery from arbitrary PDF reports.
* **Cloud Persistence:** Integrated with Firestore for document indexing and metadata querying, containerized with Docker, and deployed on Render with secure credential rotation.

#### 📈 [APM Dynamic Segment Tree Engine](https://github.com/lautarofamaf/Coding-Challenge-APM)
> **Stack:** `Python` `Algorithms & Data Structures` `Stress Testing`

* **Logarithmic Complexity:** Implemented an implicit dynamic segment tree supporting range average queries and point updates in `O(log U)` time.
* **Memory Pacing:** Dynamic node allocation keeping memory strictly proportional to distinct accessed coordinates rather than the total coordinate span.
* **Oracle Verification:** Validated correctness through randomized stress testing against brute-force reference oracles across high-variance workloads.

---

### ⚙️ Operating Systems & Microarchitecture

#### 🖥️ [5-Stage Pipelined LEGv8 Processor Core](https://github.com/lautarofamaf/pipelined-legv8-processor)
> **Stack:** `SystemVerilog` `ARMv8 / LEGv8 ISA` `Computer Architecture`

* **Pipelined Datapath:** Implemented an active 5-stage instruction pipeline (`IF`, `ID`, `EX`, `MEM`, `WB`) in SystemVerilog.
* **Hazard Management:** Designed dedicated hardware hazard detection and forwarding units to resolve data dependencies (RAW) without stalling, alongside branch penalty mitigation.
* **ALU Extensions:** Extended decoder logic and arithmetic-logic unit to natively execute logical shift operations (`LSL`, `LSR`).

#### 🐧 [xv6 Kernel Scheduler (MLFQ)](https://github.com/lautarofamaf/xv6-kernel-scheduler-mlfq)
> **Stack:** `C` `xv6-riscv` `RISC-V` `Operating Systems`

* **Adaptive Scheduling:** Re-engineered the xv6 RISC-V kernel from Round Robin to a **Multi-Level Feedback Queue (MLFQ)** scheduler.
* **Prioritization & Aging:** Shorter quantum for interactive tasks, longer quantum for compute-bound tasks; dynamic priority demotion upon slice exhaustion and automatic priority aging to eliminate process starvation.
* **Context-Switch Profiling:** Analyzed turnaround and response time trade-offs using kernel-level instrumentation and timeline visualizers.

#### 🔒 [xv6 Kernel Synchronization & Semaphores](https://github.com/lautarofamaf/xv6-kernel-semaphores-sync)
> **Stack:** `C` `xv6-riscv` `Concurrency` `Kernel Locks`

* **Counting Semaphores:** Built atomic kernel synchronization channels with `sem_open`, `sem_close`, `sem_up`, and `sem_down` primitives.
* **Race Condition Elimination:** Utilized kernel sleep locks and channel queue management to ensure safe inter-process communication (IPC), verified via concurrent ping-pong stress tests.

---

### 📡 Network Protocols & Distributed Computing

#### 🛰️ [Reliable Transport Protocol & Congestion Control](https://github.com/lautarofamaf/reliable-transport-protocol-cpp)
> **Stack:** `C++17` `OMNeT++` `Discrete-Event Simulation` `Transport Layer`

* **End-to-End Reliability:** Designed and evaluated sender/receiver transport state machines over lossy, delay-prone synthetic networks.
* **Flow & Congestion Avoidance:** Engineered adaptive windowing and receiver buffer feedback to prevent receiver overrun (flow bottleneck) and intermediate router packet drop (congestion bottleneck).

#### 📊 [Distributed Big Data Pipeline](https://github.com/lautarofamaf/spark-distributed-data-pipeline)
> **Stack:** `Apache Spark` `Java 11` `Maven` `Distributed Computing`

* **Resilient Data Processing:** Scalable batch aggregation pipeline extracting entities from RSS feeds and Reddit data sources using Spark RDDs.
* **Parallel Transformations:** Leveraged distributed partitioning and `reduceByKey` operations to aggregate keyword frequencies and categories with high throughput.

---

## 🛠️ Technology Landscape

```
Languages           Python  ·  C  ·  C++  ·  Java  ·  Haskell  ·  SystemVerilog  ·  SQL  ·  Assembly
Backend & APIs      FastAPI  ·  WebSockets  ·  REST  ·  SQLAlchemy  ·  PostgreSQL  ·  MongoDB  ·  Firestore
Systems & Runtime   Linux (Arch)  ·  xv6 Kernel  ·  gem5  ·  OMNeT++  ·  Docker  ·  Git  ·  Apache Spark
Methodologies       Clean Architecture  ·  TDD / Automated Testing  ·  Concurrency  ·  Algorithmic Optimization
```

---

## 🧠 Engineering Philosophy

* **Mechanical Sympathy:** Software performs best when written with respect for the underlying machine—cache hierarchies, context-switch overheads, and kernel boundaries.
* **Deterministic Verification:** Systems code must be defended by automated tests, stress simulations, and boundary analysis before touching production.
* **Strict Layering:** Keep transport protocols, business rules, and persistence primitives decoupled so architectures remain extensible and testable.

---

## 🐧 Workstation & Personal Systems
Beyond application code, I maintain a tailored Unix workflow and system environment:
* [Hyprland Dotfiles](https://github.com/lautarofamaf/dots-hyprland) — Custom Wayland/Hyprland environment optimized for keyboard-driven development.
* [System Configuration](https://github.com/lautarofamaf/config) — Shell configurations, developer utilities, and environment automation.
* [Competitive Programming](https://github.com/lautarofamaf/cpc) — Algorithmic problem solving in C++.

---

## 🎯 Looking For
Open to opportunities as a **Junior Backend Engineer** or **Systems / Software Engineer**. Interested in backend architectures, distributed services, concurrency challenges, and infrastructure engineering.
