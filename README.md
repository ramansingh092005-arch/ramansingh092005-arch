<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=venom&height=250&text=UTKARSH%20SINGH&fontSize=65&fontColor=00E5FF&color=0:050816,50:151038,100:001F3F&animation=twinkling&stroke=00D4FF&strokeWidth=1&desc=ECE%20%40%20IIIT%20Nagpur&descSize=20&descColor=ffffff&descAlignY=72"/>

<a href="https://git.io/typing-svg">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=2200&pause=800&color=00D4FF&center=true&vCenter=true&width=780&lines=Software+Engineering+%7C+AI+%2F+ML;Competitive+Programming+%7C+DSA;Backend+Engineering+%7C+System+Design;Hardware+%2B+Software%3A+Verilog+to+Full-Stack;Building+Intelligent+Real-World+Products" />
</a>

<br/>

<a href="mailto:ramansingh092005@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/utkarsh-singh-a07966274/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/ramansingh092005-arch"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/></a>
<a href="https://leetcode.com/u/SINGH_UTKAR0402/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/></a>
<a href="https://codeforces.com/profile/utkarsh0402"><img src="https://img.shields.io/badge/Codeforces-445F9D?style=for-the-badge&logo=codeforces&logoColor=white"/></a>
<a href="https://www.codechef.com/users/mad_coder_09"><img src="https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white"/></a>

<br/><br/>

<img src="https://img.shields.io/badge/STATUS-OPEN%20TO%20INTERNSHIPS-00C853?style=flat-square"/>
<img src="https://komarev.com/ghpvc/?username=ramansingh092005-arch&style=flat-square&color=00D4FF&label=PROFILE+VIEWS"/>
<img src="https://img.shields.io/github/followers/ramansingh092005-arch?style=flat-square&color=00D4FF"/>

<br/><br/>

**I enjoy solving complex problems, engineering reliable systems, and turning ideas into working products.**

<br/>

| 🧠 ALGORITHMS | ⚙️ ENGINEERING | 🤖 INTELLIGENCE | 🔌 HARDWARE |
|:---:|:---:|:---:|:---:|
| DSA & Competitive Programming | Backend & Real-Time Systems | AI / Machine Learning | Verilog, FSMs, Digital Comms |

</div>

---

## ⚡ At a Glance

| | |
|:--|:--|
| 🎓 **Education** | B.Tech, Electronics & Communication Engineering, **IIIT Nagpur** |
| 🧠 **Core strength** | Data Structures, Algorithms, complexity analysis |
| ⚙️ **Builds** | Real-time backend systems, hardware simulators, ML-driven systems, algorithm visualizers |
| 🧭 **Approach** | Understand → Find the invariant → Design → Prove correctness → Optimize → Build |
| 🎯 **Looking for** | SDE / Backend internships, Quantitative Engineering opportunities |
| 📬 **Contact** | [ramansingh092005@gmail.com](mailto:ramansingh092005@gmail.com) |

---

## 🚀 Featured Projects

| # | Project | Domain | Core Idea | Stack |
|:-:|:--|:--|:--|:--|
| 01 | **Aaspaas** | Retail Tech | Operating system for kirana shops | `Node.js` `TypeScript` `PostgreSQL` `MongoDB` `Socket.IO` `Vite` |
| 02 | **Smart Traffic Management** | Hardware / Digital Logic | Adaptive signals with emergency preemption | `Verilog` `Icarus` `Python` `Flask` |
| 03 | **Adaptive OFDM System** | AI + Communication | ML-driven modulation adaptation | `MATLAB` `Simulink` `Python` `Random Forest` |
| 04 | **PathFinder** | Algorithms | Interactive graph algorithm visualizer | `React` `JavaScript` `HTML` `CSS` |

<details open>
<summary><b>01 · Aaspaas: Kirana Shop Operating System</b> &nbsp; <img src="https://img.shields.io/badge/RETAIL-00D4FF?style=flat-square"/></summary>

<br/>

> **Vision:** Digitizing neighbourhood retail through one unified shop management platform.

**Problem:** Local shops manage inventory, billing, purchases and customer credit through disconnected manual processes.

**Solution:** A unified operating system for everyday kirana shop operations.

**Key engineering features**

- Shop and product management
- Inventory and stock workflows
- Billing and sales management
- Customer and supplier ledgers
- Purchase and expense tracking
- Real-time updates using Socket.IO

**High-level architecture**

```mermaid
flowchart LR
    A[Vite Frontend] -->|REST| B[Node.js + TypeScript API]
    A <-->|Socket.IO| B
    B --> C[(PostgreSQL)]
    B --> D[(MongoDB)]
```

**Roadmap (planned, not yet implemented):** demand forecasting, stock recommendations, natural-language business analytics.

**Stack:** `Node.js` `TypeScript` `PostgreSQL` `MongoDB` `Socket.IO` `Vite`

</details>

<details>
<summary><b>02 · Smart Traffic Management System</b> &nbsp; <img src="https://img.shields.io/badge/HARDWARE-8B5CF6?style=flat-square"/></summary>

<br/>

> **Vision:** Adaptive traffic control using hardware-oriented digital logic.

**Problem:** Fixed-time traffic signals cannot adapt to changing traffic density or emergency vehicle requirements.

**Solution:** A Verilog-based traffic controller with adaptive signal timing and deterministic emergency prioritization.

**Key engineering features**

- 10-state Finite State Machine
- Dynamic adaptive green timing
- Deterministic emergency preemption
- Hardware-enforced mutual exclusion (no conflicting greens)
- Python Flask middleware
- Frontend traffic visualization

**Architecture**

```mermaid
flowchart TD
    A[Traffic Inputs] --> B[Verilog Controller]
    B --> C{10-State FSM}
    C --> D[Adaptive Signal Timing]
    C --> E[Emergency Preemption]
    D --> F[Flask Middleware]
    E --> F
    F --> G[Frontend Visualization]
```

**Stack:** `Verilog HDL` `Icarus Verilog` `Python` `Flask`

</details>

<details>
<summary><b>03 · AI-Driven Adaptive OFDM Communication System</b> &nbsp; <img src="https://img.shields.io/badge/AI%20%2F%20ML-00D4FF?style=flat-square"/></summary>

<br/>

> **Vision:** Applying machine learning to adaptive digital communication.

**Problem:** Static modulation strategies may not perform optimally as wireless channel conditions change.

**Solution:** An OFDM communication simulation that explores machine-learning-based modulation adaptation.

**Key engineering features**

| Parameter | Value |
|:--|:--|
| IFFT size | 64-point |
| Active subcarriers | 52 |
| Cyclic prefix | 16 samples |
| Channel models | AWGN, Rayleigh |
| Adaptation model | Random Forest |
| Metrics | BER, SER, EVM, Goodput |

**Signal chain**

```mermaid
flowchart LR
    A[Input Bits] --> B[Modulation]
    B --> C[64-pt IFFT]
    C --> D[Cyclic Prefix]
    D --> E[Wireless Channel]
    E --> F[Receiver]
    F --> G[Performance Evaluation]
    G --> H[Random Forest Adaptation]
    H -.feedback.-> B
```

**Stack:** `MATLAB` `Simulink` `Python` `Random Forest`

</details>

<details>
<summary><b>04 · PathFinder: Graph Algorithm Visualizer</b> &nbsp; <img src="https://img.shields.io/badge/ALGORITHMS-8B5CF6?style=flat-square"/></summary>

<br/>

> **Vision:** Making graph algorithms easier to understand through interactive visualization.

| Algorithm | Type | Complexity |
|:--|:--|:--|
| BFS | Unweighted shortest path | O(V + E) |
| DFS | Traversal | O(V + E) |
| Dijkstra | Weighted shortest path | O((V + E) log V) |
| A* Search | Heuristic search | Depends on heuristic |
| Bellman-Ford | Negative edges | O(V · E) |

**Stack:** `React` `JavaScript` `HTML` `CSS`

</details>

<div align="center">

<a href="https://github.com/ramansingh092005-arch?tab=repositories">
<img src="https://img.shields.io/badge/EXPLORE%20ALL%20REPOSITORIES-00D4FF?style=for-the-badge&logo=github&logoColor=black"/>
</a>

</div>

---

## 🛠️ Tech Stack

<details open>
<summary><b>Explore technologies</b></summary>

<br/>

**Languages**

<p><img src="https://skillicons.dev/icons?i=cpp,c,python,js,ts&theme=dark"/></p>

**Frontend**

<p><img src="https://skillicons.dev/icons?i=html,css,react,vite,tailwind&theme=dark"/></p>

**Backend & Databases**

<p><img src="https://skillicons.dev/icons?i=nodejs,express,flask,postgres,mongodb&theme=dark"/></p>

**AI / Machine Learning**

<p><img src="https://skillicons.dev/icons?i=tensorflow,python&theme=dark"/></p>

Random Forest · ML fundamentals · Model development and evaluation

**Hardware & Simulation**

<p>
<img src="https://img.shields.io/badge/Verilog%20HDL-5C2D91?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Icarus%20Verilog-007C91?style=for-the-badge"/>
<img src="https://img.shields.io/badge/MATLAB-E16737?style=for-the-badge&logo=mathworks&logoColor=white"/>
<img src="https://img.shields.io/badge/Simulink-0076A8?style=for-the-badge"/>
</p>

**Developer Tools**

<p><img src="https://skillicons.dev/icons?i=git,github,vscode,linux,bash,npm&theme=dark"/></p>

</details>

---

## 🧠 Competitive Programming

<div align="center">

<a href="https://leetcode.com/u/SINGH_UTKAR0402/"><img src="https://img.shields.io/badge/LeetCode-SINGH__UTKAR0402-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/></a>
<a href="https://codeforces.com/profile/utkarsh0402"><img src="https://img.shields.io/badge/Codeforces-utkarsh0402-445F9D?style=for-the-badge&logo=codeforces&logoColor=white"/></a>
<a href="https://www.codechef.com/users/mad_coder_09"><img src="https://img.shields.io/badge/CodeChef-mad__coder__09-5B4638?style=for-the-badge&logo=codechef&logoColor=white"/></a>

<br/><br/>

<!-- If this card ever fails to load, simply delete this line. -->
<img src="https://leetcard.jacoder.me/SINGH_UTKAR0402?theme=dark&font=Fira%20Code&ext=heatmap" width="60%"/>

</div>

<details>
<summary><b>Topic roadmap and problem-solving loop</b></summary>

<br/>

| Foundation | Intermediate | Advanced |
|:--|:--|:--|
| Arrays, Strings, Hashing | Trees, Graphs, BFS/DFS | Segment Trees, Fenwick Trees |
| Prefix Sum, Sliding Window | Binary Search on Answer | DSU, Shortest Paths |
| Two Pointers, Sorting | Stack, Monotonic Stack, Heaps | Bitmask DP, DP on Trees |
| Recursion, Backtracking | Dynamic Programming, Greedy | Number Theory, Combinatorics |

```cpp
while (!solved) {
    understand_constraints();
    identify_pattern();
    establish_invariant();
    derive_approach();
    prove_correctness();
    analyze_complexity();
    optimize_if_needed();
}
```

</details>

---

## 📊 GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=ramansingh092005-arch&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true"/>
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ramansingh092005-arch&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"/>

<img src="https://streak-stats.demolab.com?user=ramansingh092005-arch&theme=tokyonight&hide_border=true"/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=ramansingh092005-arch&theme=tokyo-night&hide_border=true&area=true"/>

<img src="https://github-profile-trophy.vercel.app/?username=ramansingh092005-arch&theme=onedark&no-frame=true&no-bg=true&margin-w=8&column=7"/>

</div>

<details>
<summary><b>🐍 Contribution animation</b></summary>

<div align="center">

<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ramansingh092005-arch/ramansingh092005-arch/output/github-contribution-grid-snake-dark.svg"/>
<source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ramansingh092005-arch/ramansingh092005-arch/output/github-contribution-grid-snake.svg"/>
<img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/ramansingh092005-arch/ramansingh092005-arch/output/github-contribution-grid-snake.svg" width="100%"/>
</picture>

</div>

</details>

---

## 🎯 Roadmap

- [x] Build projects across backend, hardware, ML and algorithms
- [ ] Master Data Structures and Algorithms
- [ ] Improve Codeforces and CodeChef rating consistently
- [ ] Build production-ready backend systems
- [ ] Deepen databases, networking and system design
- [ ] Ship Aaspaas to real shop owners
- [ ] Explore AI and quantitative engineering
- [ ] Contribute to meaningful open-source projects

---

## 🤝 Let's Connect

> 💼 Open to **SDE / Backend internships** and **Quantitative Engineering** opportunities.
> 🤝 Happy to collaborate on products, hackathons and open-source.

<div align="center">

<a href="mailto:ramansingh092005@gmail.com"><img src="https://img.shields.io/badge/Email%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/utkarsh-singh-a07966274/"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>

<br/><br/>

*"Think in invariants. Build from first principles. Engineer for impact."*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:050816,50:151038,100:001F3F"/>

</div>
