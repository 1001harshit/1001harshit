<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f6feb,100:ffa657&height=200&section=header&text=Harshit%20Kumar&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Backend%20Engineer%20%C2%B7%20Distributed%20Systems%20%C2%B7%20Databases&descSize=18&descAlignY=58&animation=fadeIn" alt="Harshit Kumar" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/1001harshit/emberkv">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=900&color=FFA657&center=true&vCenter=true&width=720&lines=Backend+engineer+on+payments+%26+lending+ledgers;Built+emberkv%3A+a+Redis-compatible+database;...that+can+travel+back+in+time+%E2%8F%B3;LSM+trees+%C2%B7+MVCC+%C2%B7+WAL+%C2%B7+Go;DA-IICT+'26+%C2%B7+Ahmedabad%2C+India" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/harshit-kumar-733925251/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/1001harshit/emberkv"><img src="https://img.shields.io/badge/emberkv-v0.4.0-ffa657?style=for-the-badge&logo=go&logoColor=white" alt="emberkv" /></a>
  <img src="https://komarev.com/ghpvc/?username=1001harshit&style=for-the-badge&color=1f6feb&label=Profile+views" alt="Profile views" />
</p>

---

### 👋 About me

- 🏦 Backend engineer at **Orocorp Technologies**, working on fintech payments and lending ledgers
- 🗄️ I like building systems from the ground up: storage engines, queues, protocols
- ⚡ Researching GPU / HPC workloads
- 🎓 **DA-IICT**, class of 2026
- 🔭 Next up: replication for emberkv

---

### 🔥 Featured project: [emberkv](https://github.com/1001harshit/emberkv)

**A persistent, Redis-compatible key-value database written from scratch in Go, with built-in time travel.**

<p align="center">
  <a href="https://github.com/1001harshit/emberkv">
    <img src="https://raw.githubusercontent.com/1001harshit/emberkv/main/docs/demo.gif" alt="emberkv time-travel demo: FLUSHALL, then ROLLBACK restores the data" width="720" />
  </a>
</p>

```text
ASOF -10m GET price    → read a value as it was 10 minutes ago
HISTORY user:42        → every version of a key
ROLLBACK -5m           → undo an accidental FLUSHALL
BRANCH CREATE test     → an instant copy of the whole database
```

| Benchmarked against Redis 8, Kvrocks and Dragonfly | Result |
|---|---|
| Redis compatibility | **228 / 229** commands reply byte-for-byte like Redis 8 |
| Memory for the same data | **62 MiB** vs 145 MiB for Redis (2.3× less) |
| Writes lost on `kill -9` | **0** (Redis's default config lost 36,156) |
| vs Apache Kvrocks (closest on-disk design) | **1.2–1.8× faster** |

**Under the hood:** write-ahead log with group commit · skip-list memtable · SSTables with Bloom filters and a block cache · universal compaction · MVCC · blocking queues · AUTH and TLS. No external dependencies.

```bash
brew install 1001harshit/tap/emberkv
```

---

### 🚀 More projects

<p align="center">
  <a href="https://github.com/1001harshit/stayhub"><img src="https://github-readme-stats.vercel.app/api/pin/?username=1001harshit&repo=stayhub&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=ffa657&icon_color=1f6feb" alt="StayHub" /></a>
  <a href="https://github.com/1001harshit/aerotriage"><img src="https://github-readme-stats.vercel.app/api/pin/?username=1001harshit&repo=aerotriage&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=ffa657&icon_color=1f6feb&description=Offline-first%20AI%20medical%20triage%20with%20LangGraph%2C%20RAG%20and%20a%20Redis%20queue" alt="AeroTriage" /></a>
  <a href="https://github.com/1001harshit/lumen-store"><img src="https://github-readme-stats.vercel.app/api/pin/?username=1001harshit&repo=lumen-store&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=ffa657&icon_color=1f6feb" alt="Lumen store" /></a>
  <a href="https://github.com/1001harshit/mockflow"><img src="https://github-readme-stats.vercel.app/api/pin/?username=1001harshit&repo=mockflow&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=ffa657&icon_color=1f6feb&description=An%20API%20mocking%20platform%20for%20development%20teams" alt="MockFlow" /></a>
</p>

| Project | What it is | Stack |
|---|---|---|
| [**StayHub**](https://github.com/1001harshit/stayhub) | Vacation-rental marketplace with guest, host and admin portals | React · Fastify · PostgreSQL · AWS CDK |
| [**AeroTriage**](https://github.com/1001harshit/aerotriage) | Offline-first AI triage and appointment workflow with WhatsApp booking | FastAPI · LangGraph · RAG · Redis |
| [**Lumen**](https://github.com/1001harshit/lumen-store) | Skincare storefront with a server-validated cart | Next.js 16 · React 19 · Tailwind |
| [**MockFlow**](https://github.com/1001harshit/mockflow) | API mocking platform | TypeScript |

---

### 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,ts,js,py,html,css&theme=dark" alt="Languages" /><br/>
  <img src="https://skillicons.dev/icons?i=nodejs,react,nextjs,fastapi,tailwind&theme=dark" alt="Frameworks" /><br/>
  <img src="https://skillicons.dev/icons?i=postgres,redis,sqlite&theme=dark" alt="Databases" /><br/>
  <img src="https://skillicons.dev/icons?i=aws,docker,linux,git,githubactions&theme=dark" alt="Tools" />
</p>

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
