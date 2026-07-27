# Hi, I'm AT0M(0x4154304D) 👋

**Systems & Network Engineer | eBPF / XDP | Linux Networking | Kubernetes**

I work at the intersection of **Linux networking, cloud infrastructure, and performance engineering**. My main interests are understanding how packets, processes, and distributed systems behave under real-world production workloads—and turning difficult low-level problems into reproducible, measurable solutions.

My current focus includes high-performance packet processing, kernel observability, network troubleshooting, and cloud-native infrastructure.

## 🔭 What I'm Working On

* Building and troubleshooting **eBPF, XDP, BCC, and bpftrace** tooling
* Investigating packet loss across **XDP redirect, devmap, bonding, IPIP, and physical NIC paths**
* Analyzing Linux network drivers, RX/TX queues, IRQ distribution, and hardware offload behavior
* Operating and debugging **Kubernetes, containerd, Prometheus, and distributed services**
* Profiling Go applications and identifying CPU, memory, I/O, and garbage-collection bottlenecks
* Strengthening my research foundation in **computer networks and programmable data planes**

## 🧠 Areas of Interest

```text
Linux Networking       eBPF / XDP              Kernel Observability
High-Performance I/O   Network Performance     Cloud Infrastructure
Kubernetes             Distributed Systems     Programmable Networks
```

I am especially interested in problems that cross multiple layers:

```text
Application
    ↓
Container / Kubernetes
    ↓
Linux Network Stack
    ↓
eBPF / XDP
    ↓
NIC Driver and Hardware
```

## 🛠️ Technical Stack

### Languages

* **Go** — systems services, profiling, concurrent programs
* **Python** — automation, testing, infrastructure tooling
* **C** — eBPF/XDP programs and low-level Linux development
* **Shell** — system diagnosis, deployment, and operational automation

### Linux and Networking

* Linux network stack
* TCP/IP, routing, ARP and IPIP
* Bonding, NIC queues, RSS and IRQ affinity
* Network namespaces and virtual interfaces
* `iproute2`, `ethtool`, `tcpdump`, `perf`, `strace`, `lsof`
* Mellanox `mlx5`, Intel `i40e` and `ixgbe` driver troubleshooting

### eBPF Ecosystem

* XDP and TC
* libbpf
* BCC
* bpftrace
* bpftool
* xdp-tools
* BPF maps, devmap, tracepoints, kprobes and CO-RE

### Cloud and Infrastructure

* Kubernetes
* Docker and containerd
* Prometheus
* JMeter
* MySQL
* NFS
* CI/CD and automated testing

## 🔬 How I Approach Engineering Problems

I prefer to diagnose systems from evidence rather than assumptions.

My usual workflow is:

1. Reproduce the problem under controlled conditions.
2. Identify the exact layer where the behavior changes.
3. Collect data from applications, the kernel, drivers, and hardware.
4. Correlate traces, counters, logs, and source code.
5. Build a minimal experiment to validate the suspected cause.
6. Document the result so the investigation can be repeated.

For example, when investigating network packet loss, I may trace the complete path from an application or container through the Linux network stack, XDP redirect logic, NIC queues, driver error codes, and physical interface counters.

## 📚 Current Learning and Research

I am currently deepening my knowledge in:

* High-performance computer networks
* Programmable packet processing
* Linux kernel networking
* eBPF-based observability
* Network measurement and performance evaluation
* Distributed systems reliability

My long-term goal is to combine practical production engineering with rigorous computer-networking research.

## 📌 Featured Projects

### High-Performance Network Diagnostics

Tools and experiments for diagnosing packet loss, XDP redirect failures, queue imbalance, driver errors, and network-stack performance.

### eBPF Observability Toolkit

Reusable eBPF and bpftrace programs for tracing kernel functions, network events, process behavior, and performance bottlenecks.

### Cloud Infrastructure Automation

Automation and testing tools for Kubernetes, Prometheus, Linux hosts, and distributed infrastructure.

## 🤝 Connect

* GitHub: [0x4154304D](https://github.com/0x4154304D)
* Email: `shipf8023@live.com`

---

> Understand the complete system—from application behavior to kernel execution and network hardware.
