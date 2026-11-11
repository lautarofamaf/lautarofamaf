<div align="center">

# Hi there! 👋 I'm Lautaro Deco

### Software Engineer | Backend, Distributed Systems & Low-Level Architecture
**Computer Science (FaMAF, UNC) | Linux & Systems Enthusiast**

Building reliable backend services, real-time architectures, and performance-critical software.  
Bridging the gap between low-level hardware/kernel mechanics and scalable cloud backends.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/lautaro-deco)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:portadeco@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/lautarofamaf)

</div>

---

## 🚀 Featured Engineering Projects

### 🎮 [Death on the Cards — Real-Time Multiplayer Backend](https://github.com/lautarofamaf/dotc-backend)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white) ![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
* **Real-Time Architecture:** Full-duplex WebSocket communication managing concurrent player sessions, real-time events, and synchronized game states with low latency.
* **Modular Domain Design:** Layered architecture strictly decoupling API transport, domain rules, card effect engines, and persistence with dependency injection.
* **Reliability:** Automated test suite with Pytest simulating complex multi-client game workflows, state transitions, and edge-case turns.

### 🐾 [DiagnoVET — Automated Medical Report Extraction Service](https://github.com/lautarofamaf/diagnovet-challenge)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Firestore](https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)
* **Data Processing Pipeline:** Asynchronous parsing pipeline extracting unstructured clinical text, patient metadata, and embedded medical images from veterinary PDFs using PyMuPDF.
* **Cloud & Containerization:** Fully containerized with Docker and deployed to production on Render, utilizing Google Cloud Firestore for persistence and secure credential rotation.

### ⚡ [Dynamic Segment Tree Engine — Range Queries](https://github.com/lautarofamaf/Coding-Challenge-APM)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Algorithms](https://img.shields.io/badge/Complexity-O(log%20U)-blue?style=flat-square) ![Testing](https://img.shields.io/badge/Testing-Oracles%20%26%20Stress-success?style=flat-square)
* **High-Performance Core:** Implemented dynamic segment tree with lazy node allocation, enabling `O(log U)` interval updates and point queries while keeping memory proportional to accessed positions.
* **Verification:** Stress-tested using randomized oracle test suites and large workloads to validate boundary behavior and numerical precision under high variance.

---

## ⚙️ Systems & Core Engineering
*Deep-tech implementations involving Operating System Kernels, Computer Architecture, Networks, and Distributed Computing.*

### 🖥️ [Pipelined LEGv8 Processor Core](https://github.com/lautarofamaf/pipelined-legv8-processor)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-1A365D?style=flat-square&logo=verilog&logoColor=white) ![Hardware](https://img.shields.io/badge/Hardware-CPU_Pipelining-green?style=flat-square)
* **CPU Design:** Extended a 5-stage RISC processor (Fetch, Decode, Execute, Memory, Writeback) in SystemVerilog.
* **Hazard Resolution:** Implemented data forwarding logic, hazard detection units, and hardware pipeline stalls to prevent data and control hazards.
* **Instruction Set:** Extended the control unit, datapath registers, and ALU to support logical shift instructions (`LSL`, `LSR`).

### 🐧 [xv6 Kernel Scheduler (MLFQ)](https://github.com/lautarofamaf/xv6-kernel-scheduler-mlfq)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![xv6](https://img.shields.io/badge/OS-xv6--riscv-orange?style=flat-square)
* Modified the xv6 RISC-V kernel to replace the default Round Robin scheduler with a **Multi-Level Feedback Queue (MLFQ)**.
* Implemented priority queues, quantum tracking, dynamic priority demotion, and starvation prevention via periodic aging.
* Measured context-switch latency and process turnaround time improvements for mixed CPU/IO-bound workloads.

### 📡 [Reliable Transport Protocol & Congestion Control](https://github.com/lautarofamaf/reliable-transport-protocol-cpp)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![OMNeT++](https://img.shields.io/badge/Sim-OMNeT%2B%2B-blue?style=flat-square)
* Engineered an end-to-end reliable transport layer simulation in C++ over an unreliable network medium.
* Implemented **Flow Control** (sliding window) and **Congestion Control** mechanisms to prevent network saturation and packet drop.
* Evaluated throughput and queue utilization under severe synthetic latency and high packet loss scenarios.

### 🔒 [xv6 Kernel Synchronization & Semaphores](https://github.com/lautarofamaf/xv6-kernel-semaphores-sync)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![Concurrency](https://img.shields.io/badge/Concurrency-Kernel_Locks-red?style=flat-square)
* Engineered kernel-level semaphore synchronization primitives (`sem_open`, `sem_close`, `sem_up`, `sem_down`) in xv6.
* Integrated system calls managing sleep locks, atomic state transitions, and coordination queues to eliminate race conditions.

### 📊 [Distributed Big Data Pipeline](https://github.com/lautarofamaf/spark-distributed-data-pipeline)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
* Distributed batch processing pipeline leveraging Spark RDD transformations and `reduceByKey` to ingest and process large XML/JSON news feeds.
* Scaled named-entity extraction and topic aggregation with resilient distributed datasets and partition optimizations.

### 🔬 [gem5 Processor Architecture Simulation](https://github.com/lautarofamaf/gem5-processor-architecture-sim)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![gem5](https://img.shields.io/badge/Simulator-gem5-purple?style=flat-square)
* Configured and simulated In-Order and Out-of-Order CPU microarchitectures under diverse benchmark workloads.
* Analyzed cache hit/miss ratios, branch predictor accuracy, IPC (Instructions Per Cycle), and memory latency tradeoffs.

---

## 🛠️ Technical Stack

* **Languages:** Python, C, C++, Java, Haskell, SystemVerilog, SQL, Assembly.
* **Backend & Web:** FastAPI, WebSockets, RESTful APIs, SQLAlchemy, PostgreSQL, MongoDB, Firebase / Firestore.
* **Systems & Infra:** Linux (Arch Linux, Hyprland), Docker, Git, CI/CD, Apache Spark, xv6 Kernel, gem5.
* **Engineering Principles:** Clean Architecture, TDD / Automated Testing, Concurrency & Synchronization, Algorithmic Optimization.

---

## 🎯 Looking For
I am currently looking for opportunities as a **Junior Backend Engineer** or **Systems / Software Engineer**, where I can apply strong fundamentals in concurrency, distributed systems, and low-level optimization to real-world infrastructure challenges.

---

## 🌐 Personal Environment & Configurations
* [Hyprland Dotfiles](https://github.com/lautarofamaf/dots-hyprland) — Fully customized Wayland/Hyprland Linux desktop environment.
* [System Configuration](https://github.com/lautarofamaf/config) — Shell and development environment dotfiles.
* [Competitive Programming](https://github.com/lautarofamaf/cpc) — Algorithmic problem solving and data structures in C++.
