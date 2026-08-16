<!-- ========================================================= -->

<!--                        HERO                               -->

<!-- ========================================================= -->

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,45:0f2027,75:203a43,100:2c5364&height=240&section=header&text=Sufal%20Bala&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=38"
    width="100%"
  />
</p>

<p align="center">
  <img
    src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=25&duration=2800&pause=700&color=00F7FF&center=true&vCenter=true&width=850&lines=Systems+Engineer;Rust+%7C+Linux+%7C+Backend;Database+Engine+Developer;Networking+%26+Infrastructure;Building+Software+From+First+Principles"
  />
</p>

<p align="center">
  <a href="https://github.com/sufal54">
    <img src="https://komarev.com/ghpvc/?username=sufal54&label=Profile%20Views&color=0e75b6&style=flat" />
  </a>
  <a href="https://github.com/sufal54?tab=followers">
    <img src="https://img.shields.io/github/followers/sufal54?label=Followers&style=flat&logo=github" />
  </a>
  <a href="https://github.com/sufal54?tab=repositories">
    <img src="https://img.shields.io/badge/Repositories-Explore-203a43?style=flat&logo=github" />
  </a>
</p>

---

# `whoami`

```rust
struct Engineer {
    name: &'static str,
    role: &'static str,
    philosophy: &'static str,
    focus: [&'static str; 5],
}

let me = Engineer {
    name: "Sufal Bala",
    role: "Systems Engineer",
    philosophy: "Understand the abstraction before using it.",
    focus: [
        "Database Engines",
        "Backend Infrastructure",
        "Linux Systems",
        "Networking",
        "High Performance Software",
    ],
};
```

> I like understanding what happens **under the abstraction**.

I build software infrastructure from first principles — databases, HTTP servers,
networking systems, concurrency primitives, developer tools and backend infrastructure.

### Current interests

```text
┌────────────────────────────────────────────────────────────┐
│                                                            │
│  🦀 Rust             Systems Programming                   │
│  🐧 Linux            Kernel / OS Concepts                   │
│  📦 Databases        Storage Engines                       │
│  🌐 Networking       TCP / HTTP / DNS                      │
│  ⚡ Performance      Concurrency / I/O                     │
│  🧠 Architecture     Backend Infrastructure                │
│                                                            │
└────────────────────────────────────────────────────────────┘
```

---

# ⚙️ Engineering Philosophy

<details>
<summary><b>🔬 First Principles</b></summary>

I prefer understanding the underlying mechanism instead of hiding everything behind frameworks.

```text
Framework
    ↓
Library
    ↓
Protocol
    ↓
System Call
    ↓
Operating System
    ↓
Hardware
```

</details>

<details>
<summary><b>⚡ Performance</b></summary>

I care about:

* Memory allocations
* Disk I/O
* Network latency
* Lock contention
* CPU utilization
* Serialization overhead
* Concurrency models
* Cache behavior

</details>

<details>
<summary><b>🧩 Architecture</b></summary>

I enjoy designing systems where the individual components are understandable,
testable and replaceable.

```text
Application
     │
     ▼
┌──────────────┐
│   Services   │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│  Core Logic  │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│ Infrastructure│
└──────┬───────┘
       │
       ▼
┌──────────────┐
│ Linux / I/O  │
└──────────────┘
```

</details>

---

# 🚀 Flagship Projects

## 📦 JacksDB

**Embedded database engine built from first principles.**

```text
Application
     │
     ▼
┌─────────────┐
│  Query API  │
└──────┬──────┘
       ▼
┌─────────────┐
│ Query Logic │
└──────┬──────┘
       ▼
┌─────────────┐
│   Storage   │
└──────┬──────┘
       ▼
┌─────────────┐
│ Binary File │
└─────────────┘
```

### Core concepts

* 📁 File-based persistence
* 🧬 Binary storage formats
* 🔎 Query execution
* 🧹 Storage cleanup
* 💾 Disk-oriented architecture
* ⚡ Efficient read/write paths
* 🧠 Memory vs disk tradeoffs
* 🔐 Minimal external dependencies

<details>
<summary><b>🧪 What I'm exploring</b></summary>

```text
Storage Engine
├── Binary Encoding
├── Block Layout
├── Record Management
├── Persistence
├── Query Execution
├── Updates
├── Deletes
└── Garbage Collection
```

</details>

---

## 🌐 Glote

**Lightweight HTTP framework written in Rust.**

> Understanding HTTP servers by building one.

### Architecture

```text
TCP Connection
      │
      ▼
┌──────────────┐
│ HTTP Parser  │
└──────┬───────┘
       ▼
┌──────────────┐
│   Router     │
└──────┬───────┘
       ▼
┌──────────────┐
│ Middleware   │
└──────┬───────┘
       ▼
┌──────────────┐
│  Handler     │
└──────┬───────┘
       ▼
┌──────────────┐
│ HTTP Response│
└──────────────┘
```

### Core features

* 🛣️ Custom routing
* 🧩 Middleware pipeline
* ⚙️ Async request handling
* 🧵 Worker-pool concurrency
* 🔌 TCP/socket-level understanding
* 🪶 Lightweight architecture

---

# 🧠 What I Focus On

<details>
<summary><b>📦 Database Internals</b></summary>

* Binary storage
* File layouts
* Record management
* Indexing
* Query execution
* Persistence
* Garbage collection
* Memory/disk tradeoffs

</details>

<details>
<summary><b>🌐 Networking</b></summary>

* TCP
* HTTP
* DNS
* Socket programming
* Connection handling
* Routing
* Proxy architecture
* Network I/O

</details>

<details>
<summary><b>🐧 Linux Systems</b></summary>

* Processes
* Threads
* File descriptors
* File I/O
* System calls
* Signals
* Networking
* Process scheduling
* Shell tooling

</details>

<details>
<summary><b>⚡ Concurrency</b></summary>

* Worker pools
* Thread pools
* Async execution
* Task scheduling
* Locks
* Synchronization
* Parallel workloads
* Resource management

</details>

---

# 🛠️ Technology Stack

## 🚨 Languages

<p>
  <img src="https://skillicons.dev/icons?i=rust" height="48"/>
  <img src="https://skillicons.dev/icons?i=c" height="48"/>
  <img src="https://skillicons.dev/icons?i=ts" height="48"/>
  <img src="https://skillicons.dev/icons?i=js" height="48"/>
  <img src="https://skillicons.dev/icons?i=python" height="48"/>
</p>

## ⚙️ Backend & Frameworks

<p>
  <img src="https://skillicons.dev/icons?i=nestjs" height="48"/>
  <img src="https://skillicons.dev/icons?i=express" height="48"/>
  <img src="https://skillicons.dev/icons?i=nextjs" height="48"/>
  <img src="https://skillicons.dev/icons?i=react" height="48"/>
  <img src="https://skillicons.dev/icons?i=tailwind" height="48"/>
  <img src="https://skillicons.dev/icons?i=graphql" height="48"/>
</p>

## 🗄️ Databases & Storage

<p>
  <img src="https://skillicons.dev/icons?i=mongodb" height="48"/>
  <img src="https://skillicons.dev/icons?i=mysql" height="48"/>
  <img src="https://skillicons.dev/icons?i=redis" height="48"/>
</p>

## 🧰 Infrastructure

<p>
  <img src="https://skillicons.dev/icons?i=linux" height="48"/>
  <img src="https://skillicons.dev/icons?i=docker" height="48"/>
  <img src="https://skillicons.dev/icons?i=kubernetes" height="48"/>
  <img src="https://skillicons.dev/icons?i=nginx" height="48"/>
  <img src="https://skillicons.dev/icons?i=git" height="48"/>
</p>

---

# 📊 GitHub Analytics

<p align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=sufal54&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github"
    height="180"
  />
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=sufal54&layout=compact&theme=tokyonight&hide_border=true"
    height="180"
  />
</p>

<p align="center">
  <img
    src="https://github-readme-streak-stats.herokuapp.com/?user=sufal54&theme=tokyonight&hide_border=true"
    width="70%"
  />
</p>

---

# 🐍 Contribution Activity

<p align="center">
  <img
    src="https://raw.githubusercontent.com/sufal54/sufal54/output/github-contribution-grid-snake.svg"
    alt="GitHub contribution snake"
  />
</p>

---

# 📈 GitHub Activity

<details>
<summary><b>📅 Contribution Graph</b></summary>

<br>

<p align="center">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=sufal54&theme=tokyo-night&hide_border=true"
    width="100%"
  />
</p>

</details>

---

# 🧪 Currently Building

```text
┌───────────────────────────────────────────────────────┐
│                   CURRENT LAB                         │
├───────────────────────────────────────────────────────┤
│                                                       │
│  🦀 Rust Systems Programming                          │
│  📦 Database Architecture                             │
│  🌐 Networking                                        │
│  ⚡ Concurrency                                       │
│  🐧 Linux Internals                                   │
│  🔬 Performance Engineering                           │
│                                                       │
└───────────────────────────────────────────────────────┘
```

---

# 🧰 Developer Environment

```bash
$ neofetch

OS          → Arch Linux
WM          → Hyprland
Shell       → Bash / Zsh
Editor      → VS Code / Neovim
Primary     → Rust
Backend     → Node.js / Rust
Frontend    → TypeScript
Database    → MongoDB / MySQL
Container   → Docker
```

---

# 🎯 Engineering Goals

```text
[████████████████████] Systems Programming

[██████████████████░░] Database Engineering

[█████████████████░░░] Networking

[████████████████░░░░] Distributed Systems

[███████████████░░░░░] Performance Engineering
```

> Build it. Break it. Understand it. Improve it.

---

# 🔗 Connect With Me

<p align="center">

  <a href="https://github.com/sufal54">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>

  <a href="https://www.linkedin.com/in/sufal-bala-b404242a9">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>

  <a href="mailto:sufalbala29@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>

  <a href="https://www.instagram.com/sufalbala74">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/>
  </a>

</p>

---

<p align="center">

### `sudo make systems`

**Building software that makes the abstraction understandable.**

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer"/>

</p>
