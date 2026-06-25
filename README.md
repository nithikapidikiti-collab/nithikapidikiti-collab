<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Nithika%20Pidikiti&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%E2%80%A2%20Systems%20Programming%20%E2%80%A2%20Full%20Stack&descAlignY=58&descSize=18" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3500&pause=1000&color=A78BFA&center=true&vCenter=true&width=600&lines=Building+systems+from+the+ground+up.;C+%7C+Python+%7C+Full+Stack+%7C+AI.;BIT+Co-op+Scholar+%40+UTS.;Incoming+SWE+Intern+%40+Woolworths+Group.)](https://git.io/typing-svg)

<br/>

![UTS](https://img.shields.io/badge/BIT%20Co--op%20Scholar-University%20of%20Technology%20Sydney-6D28D9?style=for-the-badge&logo=graduation-cap&logoColor=white)
![Woolworths](https://img.shields.io/badge/Incoming%20SWE%20Intern-Woolworths%20Group-4C1D95?style=for-the-badge&logo=briefcase&logoColor=white)

<br/>

![Location](https://img.shields.io/badge/Sydney%2C%20Australia-0F172A?style=flat-square&logo=googlemaps&logoColor=A78BFA)
&nbsp;
[![Portfolio](https://img.shields.io/badge/Portfolio-6D28D9?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-nithikapidikiti.vercel.app)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-4C1D95?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/nithika-pidikiti)
&nbsp;
[![Email](https://img.shields.io/badge/Email-1E1B4B?style=flat-square&logo=gmail&logoColor=A78BFA)](mailto:nithikapidikiti@gmail.com)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-0F172A?style=flat-square&logo=github&logoColor=white)](https://github.com/nithika-pidikiti)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=nithika-pidikiti&style=flat-square&color=6D28D9&label=Profile+Views)
&nbsp;
![Followers](https://img.shields.io/github/followers/nithika-pidikiti?style=flat-square&color=4C1D95&label=Followers&logo=github&logoColor=white)
&nbsp;
![Stars](https://img.shields.io/github/stars/nithika-pidikiti?style=flat-square&color=7C3AED&label=Total+Stars&logo=github&logoColor=white)

</div>

---

## ◈ About

<img align="right" width="320" src="https://github-readme-stats.vercel.app/api?username=nithika-pidikiti&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0D0D1A&title_color=A78BFA&icon_color=7C3AED&text_color=C4B5FD&rank_icon=github" />

First-year **Bachelor of Information Technology (Co-op) Scholar** at the University of Technology Sydney, with hands-on experience across the full systems stack — from bare-metal network protocol implementation in C to production AI-integrated web applications.

My engineering practice is grounded in fundamentals. I have built a DNS resolver from wire format, a concurrent HTTP/1.1 server with POSIX sockets, a VPN tunnel with AES-256-GCM encryption, a peer-to-peer file transfer system, and a complete TCP/IP stack — all without third-party libraries. This low-level depth informs how I approach every layer above it.

Incoming **Software Engineering Intern at Woolworths Group** (July 2026), with interest in enterprise architecture, cloud-native systems, and applied AI.

<br/>

**⟡ Open To**
&nbsp;&nbsp;Software Engineering · AI/ML Engineering · Cloud Infrastructure · Full Stack Development · Open Source

<br clear="right"/>

---

## ◈ Tech Stack

<div align="center">

**Languages**

[![Languages](https://skillicons.dev/icons?i=python,java,js,ts,c,html,css,bash,sql&theme=dark)](https://skillicons.dev)

**Frontend**

[![Frontend](https://skillicons.dev/icons?i=react,nextjs,tailwind,figma,framer&theme=dark)](https://skillicons.dev)

**Backend & Databases**

[![Backend](https://skillicons.dev/icons?i=nodejs,flask,fastapi,supabase,postgres,sqlite,mysql&theme=dark)](https://skillicons.dev)

**Cloud, DevOps & Tooling**

[![Cloud](https://skillicons.dev/icons?i=aws,gcp,docker,git,github,vscode,linux&theme=dark)](https://skillicons.dev)

</div>

---

## ◈ AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|:---|:---:|:---|
| Large Language Model Integration | ████████░░ Advanced | Anthropic Claude API, prompt engineering, multi-turn conversation design, structured outputs |
| Agentic Systems | ███████░░░ Proficient | LangChain, tool-use agents, phase-gated AI workflows |
| AI Product Engineering | ████████░░ Advanced | End-to-end AI feature development, LLM-in-the-loop UX, human-AI interaction design |
| Retrieval-Augmented Generation | ██████░░░░ Developing | Embedding pipelines, vector search, contextual retrieval |
| Natural Language Processing | ██████░░░░ Developing | Text classification, semantic similarity, document summarisation |

</div>

---

## ◈ Featured Projects

<details>
<summary><b>⟡ TCP/IP Stack — Full Network Protocol Implementation from Scratch</b></summary>
<br/>

A complete TCP/IP stack implemented in C without any networking libraries. Covers Ethernet framing, ARP resolution, IP routing, TCP three-way handshake, data flow management, and retransmission logic — all running over a macOS TUN virtual network interface.

| Attribute | Detail |
|:---|:---|
| **Stack** | C · POSIX · macOS TUN Interface · Raw Sockets |
| **Scope** | Ethernet · ARP · IP · TCP (full handshake + retransmission) |
| **Performance** | Raw socket throughput with manual buffer management |
| **Complexity** | Wire-level protocol parsing · RFC-accurate TCP state machine |
| **Learning Depth** | TCP congestion window basics · no library abstractions |
| **Repository** | [github.com/nithika-pidikiti/tcp-ip-stack](https://github.com/nithika-pidikiti/tcp-ip-stack) |

Most engineers use TCP without understanding what happens below the socket API. This project closes that gap entirely — every byte of every protocol layer is implemented and visible.

<br/>
</details>

<details>
<summary><b>⟡ TinyVPN — Encrypted VPN Tunnel with AES-256-GCM</b></summary>
<br/>

A lightweight VPN tunnel built from scratch in C. Features AES-256-GCM authenticated encryption, UDP transport for performance, Diffie-Hellman key exchange for forward secrecy, and runs over a macOS TUN virtual network interface. No VPN libraries used.

| Attribute | Detail |
|:---|:---|
| **Stack** | C · OpenSSL · macOS TUN · UDP Sockets |
| **Security** | AES-256-GCM authenticated encryption · Diffie-Hellman key exchange |
| **Transport** | UDP with manual fragmentation and reassembly |
| **Architecture** | Client-server tunnel with encrypted channel establishment |
| **Repository** | [github.com/nithika-pidikiti/tinyvpn](https://github.com/nithika-pidikiti/tinyvpn) |

<br/>
</details>

<details>
<summary><b>⟡ DNS Resolver — Recursive Resolution from Root Servers</b></summary>
<br/>

A fully recursive DNS resolver in C that parses DNS wire format manually, handles pointer compression in response packets, and traces the complete resolution chain from root servers to authoritative nameservers — no resolver libraries used.

| Attribute | Detail |
|:---|:---|
| **Stack** | C · Raw UDP Sockets · DNS Wire Format |
| **Scope** | Recursive resolution · pointer decompression · multi-record type support |
| **Accuracy** | RFC 1035-compliant message parsing |
| **Repository** | [github.com/nithika-pidikiti/dns-resolver](https://github.com/nithika-pidikiti/dns-resolver) |

<br/>
</details>

<details>
<summary><b>⟡ HTTP Server — Concurrent HTTP/1.1 in C</b></summary>
<br/>

A concurrent HTTP/1.1 server built from scratch in C using POSIX sockets and fork-based concurrency. Handles static file serving, request parsing, keep-alive connections, and proper status code responses.

| Attribute | Detail |
|:---|:---|
| **Stack** | C · POSIX Sockets · Fork-based Concurrency |
| **Scope** | HTTP/1.1 request parsing · static file serving · keep-alive |
| **Architecture** | Multi-process server with socket reuse and graceful teardown |
| **Repository** | [github.com/nithika-pidikiti/http-server](https://github.com/nithika-pidikiti/http-server) |

<br/>
</details>

<details>
<summary><b>⟡ P2P File Share — Peer-to-Peer Transfer over Raw TCP</b></summary>
<br/>

Peer-to-peer file transfer built directly on raw TCP sockets with chunked streaming, no third-party libraries. Includes progress tracking and handles large file transfers with manual buffer management.

| Attribute | Detail |
|:---|:---|
| **Stack** | Python · Raw TCP Sockets |
| **Scope** | Chunked streaming · progress tracking · direct socket-to-socket transfer |
| **Repository** | [github.com/nithika-pidikiti/p2p-fileshare](https://github.com/nithika-pidikiti/p2p-fileshare) |

<br/>
</details>

<details>
<summary><b>⟡ Port Scanner — Fast Concurrent TCP Port Scanner</b></summary>
<br/>

A multithreaded TCP port scanner built in Python using thread pooling and raw socket connections. Scans port ranges concurrently and reports open/closed/filtered states with latency metrics.

| Attribute | Detail |
|:---|:---|
| **Stack** | Python · Sockets · Threading |
| **Scope** | Concurrent scanning · thread pool management · TCP handshake probing |
| **Repository** | [github.com/nithika-pidikiti/port-scanner](https://github.com/nithika-pidikiti/port-scanner) |

<br/>
</details>

---

## ◈ Experience

**Software Engineering Intern &nbsp;·&nbsp; Woolworths Group**
`July 2026 — Present` &nbsp;·&nbsp; Bella Vista, Sydney

Joining the technology division of Australia's largest supermarket group as part of the BIT Co-op Scholar program. Engineering at scale within a high-availability retail technology environment.

- Contributing across enterprise architecture, digital platforms, or data engineering domains
- Working within cloud-native infrastructure serving millions of daily customers
- Applying software engineering fundamentals to production systems with direct business impact

![AWS](https://img.shields.io/badge/AWS-1E1B4B?style=flat-square&logo=amazonaws&logoColor=A78BFA)
![Cloud Architecture](https://img.shields.io/badge/Cloud%20Architecture-1E1B4B?style=flat-square&logoColor=A78BFA)
![Enterprise Systems](https://img.shields.io/badge/Enterprise%20Systems-1E1B4B?style=flat-square&logoColor=A78BFA)
![Python](https://img.shields.io/badge/Python-1E1B4B?style=flat-square&logo=python&logoColor=A78BFA)

---

**Tutor (English & Writing) &nbsp;·&nbsp; Independent**
`2025 — Present` &nbsp;·&nbsp; Sydney

Private tutor delivering structured English, analytical essay writing, and selective school exam preparation for Years 5–7 students. Curriculum designed to ICAS and NSW Selective Test standards.

![Curriculum Design](https://img.shields.io/badge/Curriculum%20Design-1E1B4B?style=flat-square&logoColor=A78BFA)
![ICAS](https://img.shields.io/badge/ICAS%20Preparation-1E1B4B?style=flat-square&logoColor=A78BFA)
![NSW Selective](https://img.shields.io/badge/NSW%20Selective%20Test-1E1B4B?style=flat-square&logoColor=A78BFA)

---

## ◈ Achievements

<div align="center">

| Recognition | Details |
|:---:|:---|
| 🏛 BIT Co-op Scholar | Competitive scholarship at UTS — awarded to high-achieving students placed directly into industry internships |
| 🚀 75+ Contributions | Active open-source contribution streak across 11+ repositories in the past year |
| 🔧 6 Systems Projects | Built DNS, HTTP, TCP/IP, VPN, P2P, and port scanner from scratch — no libraries |

</div>

---

## ◈ Certifications

<div align="center">

**AWS**

![AWS Cloud Practitioner](https://img.shields.io/badge/AWS%20Cloud%20Practitioner-232F3E?style=for-the-badge&logo=amazonaws&logoColor=FF9900)

**Cisco**

![Cisco Networking](https://img.shields.io/badge/Cisco%20Networking%20Fundamentals-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)

**Google**

![Google Cloud](https://img.shields.io/badge/Google%20Cloud%20Fundamentals-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

</div>

---

## ◈ Coding Profiles

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/nithika-pidikiti)
&nbsp;&nbsp;
[![HackerRank](https://img.shields.io/badge/HackerRank-00EA64?style=for-the-badge&logo=hackerrank&logoColor=black)](https://hackerrank.com/nithika-pidikiti)
&nbsp;&nbsp;
[![GeeksForGeeks](https://img.shields.io/badge/GeeksforGeeks-0F9D58?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://geeksforgeeks.org/user/nithika-pidikiti)

</div>

---

## ◈ GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=nithika-pidikiti&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0D0D1A&title_color=A78BFA&icon_color=7C3AED&text_color=C4B5FD&rank_icon=github&include_all_commits=true&count_private=true" />
&nbsp;
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nithika-pidikiti&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0D0D1A&title_color=A78BFA&text_color=C4B5FD&langs_count=8" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=nithika-pidikiti&theme=midnight-purple&hide_border=true&background=0D0D1A&ring=7C3AED&fire=A78BFA&currStreakLabel=C4B5FD&sideLabels=C4B5FD&dates=6D28D9&currStreakNum=A78BFA&sideNums=A78BFA" />

</div>

---

## ◈ GitHub Trophies

<div align="center">

[![Trophies](https://github-profile-trophy.vercel.app/?username=nithika-pidikiti&theme=darkhub&no-frame=true&no-bg=true&margin-w=8&column=7&title=Stars,Followers,Commits,Repositories,PullRequest,Issues,MultiLanguage)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## ◈ Contribution Activity

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=nithika-pidikiti&theme=react-dark&bg_color=0D0D1A&color=A78BFA&line=7C3AED&point=C4B5FD&area=true&area_color=4C1D95&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## ◈ Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nithika-pidikiti/nithika-pidikiti/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/nithika-pidikiti/nithika-pidikiti/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/nithika-pidikiti/nithika-pidikiti/output/github-contribution-grid-snake.svg" />
</picture>

</div>

---

## ◈ Current Focus

```yaml
nithika_pidikiti:
  learning:
    - Enterprise cloud architecture (AWS Solutions Architect path)
    - Advanced systems programming in C and Rust
    - Large-scale distributed systems design
  building:
    - Low-level networking tools and protocol implementations
    - AI-integrated full stack applications
    - Open source systems utilities
  exploring:
    - Agentic AI architectures and multi-agent coordination
    - Retrieval-augmented generation at production scale
    - Operating systems internals and kernel concepts
  open_to:
    - Software Engineering internships and graduate roles
    - AI/ML engineering opportunities
    - Open source collaboration on systems or AI projects
    - Research engineering partnerships
```

---

## ◈ Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-nithikapidikiti%40gmail.com-6D28D9?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nithikapidikiti@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-nithika--pidikiti-4C1D95?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/nithika-pidikiti)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-nithika--pidikiti-1E1B4B?style=for-the-badge&logo=github&logoColor=A78BFA)](https://github.com/nithika-pidikiti)
&nbsp;
[![Portfolio](https://img.shields.io/badge/Portfolio-nithikapidikiti.vercel.app-7C3AED?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-nithikapidikiti.vercel.app)

</div>

---

<div align="center">

*"The best engineers understand what happens one level below their abstraction."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer&animation=fadeIn" />

</div>
