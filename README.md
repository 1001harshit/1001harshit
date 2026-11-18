<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f6feb,100:ffa657&height=200&section=header&text=Harshit%20Kumar&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Backend%20Engineer%20%C2%B7%20Distributed%20Systems%20%C2%B7%20Databases&descSize=18&descAlignY=58&animation=fadeIn" alt="Harshit Kumar" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=900&color=FFA657&center=true&vCenter=true&width=720&lines=Backend+systems+in+Go%2C+TypeScript+and+Python;Storage+engines%3A+LSM+trees%2C+WAL%2C+MVCC;Payments+%26+lending+ledgers+at+Oro;Profiling%2C+benchmarking%2C+performance+tuning;Cloud%3A+AWS+CDK%2C+Docker%2C+GitHub+Actions" alt="Typing intro" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/harshit-kumar-733925251/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <img src="https://komarev.com/ghpvc/?username=1001harshit&style=for-the-badge&color=1f6feb&label=Profile+views" alt="Profile views" />
</p>

---

### 👋 About me

Backend engineer at **Orocorp Technologies**, working on fintech payments and lending ledgers. I like understanding systems all the way down: I built a database storage engine from scratch to learn how they really work. I also research GPU / HPC workloads. **DA-IICT**, class of 2026.

---

### 🧠 Skills

<table>
<tr>
<td width="50%" valign="top">

#### ⚙️ Backend engineering
<img src="https://skillicons.dev/icons?i=go,ts,nodejs,py,fastapi&theme=dark" alt="Go, TypeScript, Node.js, Python, FastAPI" />

- REST APIs with **Fastify** and **FastAPI**
- Concurrency in Go: goroutines, locks, lock-free fast paths
- Network protocols: a full **Redis (RESP)** server, AUTH and TLS
- Fintech: payment flows and ledgers

</td>
<td width="50%" valign="top">

#### 🗄️ Databases & storage internals
<img src="https://skillicons.dev/icons?i=postgres,redis,sqlite&theme=dark" alt="PostgreSQL, Redis, SQLite" />

- **LSM trees**: WAL with group commit, memtables, SSTables, compaction
- **MVCC**, point-in-time reads, crash recovery
- Bloom filters, block caches, on-disk formats
- Data modelling in PostgreSQL, Redis and SQLite

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🚀 Performance & reliability
<img src="https://skillicons.dev/icons?i=go,linux,bash&theme=dark" alt="Go, Linux, Bash" />

- Profiling with **pprof** (CPU, mutex contention)
- Benchmarking against Redis, Kvrocks and Dragonfly
- Tail-latency work (p99 halved in emberkv)
- Differential and crash testing (`kill -9`)

</td>
<td width="50%" valign="top">

#### ☁️ Cloud & DevOps
<img src="https://skillicons.dev/icons?i=aws,docker,githubactions,git&theme=dark" alt="AWS, Docker, GitHub Actions, Git" />

- Infrastructure as code with **AWS CDK**
- Docker images, multi-platform releases
- CI/CD with GitHub Actions, GoReleaser, Homebrew taps
- Secrets handled through AWS Secrets Manager

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🤖 AI & LLM apps
<img src="https://skillicons.dev/icons?i=py,fastapi,redis&theme=dark" alt="Python, FastAPI, Redis" />

- Agent workflows with **LangGraph**
- **RAG** with ChromaDB and local models via Ollama
- Rule-based safety checks around model output

</td>
<td width="50%" valign="top">

#### 🎨 Frontend
<img src="https://skillicons.dev/icons?i=react,nextjs,ts,tailwind&theme=dark" alt="React, Next.js, TypeScript, Tailwind" />

- **React** and **Next.js**
- TypeScript in strict mode, Tailwind CSS
- Server-validated cart and checkout state

</td>
</tr>
</table>

---

### 🛠️ Projects

| Project | What it shows |
|---|---|
| [**emberkv**](https://github.com/1001harshit/emberkv) | A Redis-compatible database in Go with time travel (ASOF, ROLLBACK, BRANCH). Storage internals, concurrency, benchmarking. Matches Redis 8 on 228 of 229 commands, uses 2.3× less memory, loses 0 writes on `kill -9`. |
| [**AeroTriage**](https://github.com/1001harshit/aerotriage) | Offline-first AI medical triage with LangGraph, RAG and a Redis-backed WhatsApp booking flow. |
| [**Lumen**](https://github.com/1001harshit/lumen-store) | Next.js 16 storefront with a deliberately light back end and a server-validated cart. |
| [**MockFlow**](https://github.com/1001harshit/mockflow) | API mocking platform for development teams, in TypeScript. |
| **StayHub** *(private)* | Vacation-rental marketplace: React, Fastify, PostgreSQL, deployed on AWS with CDK. |

<details>
<summary>▶️ See emberkv in action</summary>
<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/1001harshit/emberkv/main/docs/demo.gif" alt="emberkv time-travel demo: FLUSHALL, then ROLLBACK restores the data" width="640" />
</p>
</details>

---

### 📊 GitHub activity

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=1001harshit&theme=github-dark-blue&hide_border=true&background=0d1117&ring=ffa657&fire=ffa657&currStreakLabel=ffa657" alt="Contribution streak" height="170" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=1001harshit&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=ffa657&langs_count=8&exclude_repo=eDisGo,jbbmo-Introduction-to-Git-and-GitHub,gkpbt-css-circle" alt="Top languages" height="170" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=1001harshit&bg_color=0d1117&color=c9d1d9&line=ffa657&point=1f6feb&area=true&area_color=1f6feb&hide_border=true&custom_title=Contributions%20over%20the%20last%2031%20days" alt="Contribution graph" width="100%" />
</p>

<!-- Snake: drawn from the contribution grid by .github/workflows/snake.yml -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/1001harshit/1001harshit/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/1001harshit/1001harshit/output/github-contribution-grid-snake.svg" />
    <img alt="Snake eating the contribution grid" src="https://raw.githubusercontent.com/1001harshit/1001harshit/output/github-contribution-grid-snake-dark.svg" />
  </picture>
</p>

<!-- Footer -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:ffa657,50:1f6feb,100:0d1117&height=120&section=footer" alt="" width="100%" />
</p>
