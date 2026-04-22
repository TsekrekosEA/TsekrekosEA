<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    HERO / TYPING HEADER                       -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<h1 align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=4A8FD4&center=true&vCenter=true&width=600&lines=Hi,+I'm+Andrianos!;CS+%26+Telecom+Engineering+%40+EKPA;Systems+%7C+ML+%7C+Full-Stack;" alt="Typing SVG" />
  </a>
</h1>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=TsekrekosEA&label=Profile+views&color=1A2B4A&style=flat" alt="profile views" />
  &nbsp;
  <a href="mailto:egor.andrianos.tsekrekos@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-1A2B4A?style=flat&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
  &nbsp;
  <a href="https://linkedin.com/in/egor-andrianos-tsekrekos">
    <img src="https://img.shields.io/badge/LinkedIn-1A2B4A?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/Athens%2C%20Greece-1A2B4A?style=flat&logo=googlemaps&logoColor=white" alt="Location"/>
</p>

<br/>

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                         ABOUT ME                              -->
<!-- ═══════════════════════════════════════════════════════════════ -->

### About me

- 3rd year **CS & Telecom Engineering** student at **EKPA**, Athens
-  I'm drawn to problems where understanding the fundamentals gives an unfair advantage
-  Currently exploring **agentic AI workflows** — multi-agent systems with sub-agent delegation, automated test validation, and adversarial security agents
-  Speak **Greek** · **English (C2)** · **Russian (C1)** · **French (A1)**
-  Reach me at **egor.andrianos.tsekrekos@gmail.com**
-  Check out my portfolio : https://tsekrekosea-portfolio.vercel.app/
-  Open to **software engineering / ML internships** in Greece

<br clear="right"/>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                         PROJECTS                              -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🛠️ Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔐 [NetWatch](https://github.com/TsekrekosEA/NetWatch)
**Network Anomaly Detection & IDS**

A two-stage intrusion detection system built around real packet capture and 4M flows from CIC-IDS-2018.

- **Stage 1:** Statistical z-score baselining (rolling 1K-flow window)
- **Stage 2:** Isolation Forest + Random Forest — **90.91% accuracy**, **0.96% FPR**
- Live React dashboard over WebSocket, IP threat intel (GeoIP + AbuseIPDB), Prometheus/Grafana observability, 50-test pytest suite

![Python](https://img.shields.io/badge/Python-1A2B4A?style=flat-square&logo=python&logoColor=white)
![Scapy](https://img.shields.io/badge/Scapy-1A2B4A?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1A2B4A?style=flat-square&logo=scikit-learn&logoColor=white)
![React](https://img.shields.io/badge/React-1A2B4A?style=flat-square&logo=react&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-1A2B4A?style=flat-square&logo=docker&logoColor=white)

</td>
<td width="50%" valign="top">

### 📝 [KnowBase](https://github.com/TsekrekosEA/KnowBase)
**Collaborative Knowledge Base with RAG**

Full-stack real-time collaborative editor with CRDT conflict resolution, semantic vector search, and AI Q&A.

- **Yjs CRDTs** — offline-first, deterministic merge without locks
- **pgvector HNSW** — semantic search over local `all-MiniLM-L6-v2` embeddings
- Multi-provider RAG (Anthropic · OpenAI · GitHub Copilot), WikiLinks, graph view, version history
- Built using a **multi-agent AI development workflow** with automated test and security agents

![TypeScript](https://img.shields.io/badge/TypeScript-1A2B4A?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-1A2B4A?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1A2B4A?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-1A2B4A?style=flat-square&logo=react&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-1A2B4A?style=flat-square&logo=docker&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔍 [ANN Vector Search Engine](https://github.com/TsekrekosEA/vector-similarity-search)
**High-Performance ANN from Scratch**

C++17 implementation of four ANN indexing methods, benchmarked on SIFT1M (1M 128-d vectors) and MNIST — no external ANN libraries.

- **LSH · Hypercube · IVF-Flat · IVFPQ** — all built from first principles
- Neural LSH extension with learned hash functions
- Bioinformatics application: ANN vs NCBI BLAST for protein homolog detection

![C++](https://img.shields.io/badge/C++17-1A2B4A?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-1A2B4A?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-1A2B4A?style=flat-square&logo=numpy&logoColor=white)

</td>
<td width="50%" valign="top">

### 🖥️ [Burroughs B1700 Emulator](https://github.com/TsekrekosEA/Burroughs-B1700-Emulator)
**First-Ever Public Implementation**

The first public, fully-documented emulator of the Burroughs B1700 — a 1972 mainframe with a software-defined ISA and hardware-enforced tagged memory.

- No fixed instruction set — the CPU's ISA is loaded from tape at runtime
- Complete toolchain: **assembler · disassembler · tape reader · test suite**
- Reconstructed entirely from primary-source Burroughs hardware manuals
- Anticipates virtual machines, managed runtimes, and capability-based security

![C++](https://img.shields.io/badge/C++-1A2B4A?style=flat-square&logo=cplusplus&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-1A2B4A?style=flat-square&logo=assemblyscript&logoColor=white)

</td>
</tr>
</table>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                       TECH STACK                              -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## ⚙️ Tech Stack

**Languages**

![C](https://img.shields.io/badge/C-1A2B4A?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++17-1A2B4A?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-1A2B4A?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-1A2B4A?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-1A2B4A?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-1A2B4A?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-1A2B4A?style=for-the-badge&logo=gnubash&logoColor=white)
![VHDL](https://img.shields.io/badge/VHDL-1A2B4A?style=for-the-badge&logo=v&logoColor=white)
![Prolog](https://img.shields.io/badge/Prolog-1A2B4A?style=for-the-badge&logo=swi-prolog&logoColor=white)

**Frameworks & Tools**

![React](https://img.shields.io/badge/React-1A2B4A?style=for-the-badge&logo=react&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-1A2B4A?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1A2B4A?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-1A2B4A?style=for-the-badge&logo=docker&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1A2B4A?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-1A2B4A?style=for-the-badge&logo=numpy&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-1A2B4A?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-1A2B4A?style=for-the-badge&logo=grafana&logoColor=white)
![Git](https://img.shields.io/badge/Git-1A2B4A?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-1A2B4A?style=for-the-badge&logo=linux&logoColor=white)

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    GITHUB STATS ROW                           -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 📊 GitHub Stats

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=TsekrekosEA&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=4A8FD4&icon_color=4A8FD4&text_color=C9D1D9&rank_icon=github" alt="GitHub Stats"/>
  &nbsp;&nbsp;
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TsekrekosEA&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=4A8FD4&text_color=C9D1D9&langs_count=8" alt="Top Languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=TsekrekosEA&theme=tokyonight&hide_border=true&background=0D1117&ring=4A8FD4&fire=4A8FD4&currStreakLabel=4A8FD4" alt="GitHub Streak"/>
</p>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                     ACTIVITY GRAPH                            -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 📈 Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=TsekrekosEA&bg_color=0D1117&color=4A8FD4&line=4A8FD4&point=FFFFFF&area=true&hide_border=true" alt="Contribution Graph"/>
</p>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                        FOOTER WAVE                            -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=1A2B4A&height=80&section=footer" alt="footer wave"/>
</p>

<p align="center">
  <i>Open to internship opportunities in Greece · Summer / Fall 2026</i>
</p>
