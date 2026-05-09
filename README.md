# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **4767** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 1933 | [Browse →](./aiml/) |
| 📦 **Misc** | 804 | [Browse →](./misc/) |
| 🎨 **Frontend** | 475 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 456 | [Browse →](./orchestration/) |
| 🔧 **DevTools** | 253 | [Browse →](./devtools/) |
| ⚙️ **Backend** | 236 | [Browse →](./backend/) |
| ⛓️ **Crypto** | 177 | [Browse →](./crypto/) |
| 📊 **Data** | 109 | [Browse →](./data/) |
| 💳 **Payments** | 88 | [Browse →](./payments/) |
| 📈 **Trading** | 60 | [Browse →](./trading/) |
| 📱 **Mobile** | 56 | [Browse →](./mobile/) |
| 🚀 **DevOps & Infra** | 55 | [Browse →](./devopsinfra/) |
| 🔐 **Security** | 37 | [Browse →](./security/) |
| ✨ **Design** | 12 | [Browse →](./design/) |
| 🎯 **Product** | 11 | [Browse →](./product/) |
| 🏷️ **Marketing** | 5 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [santifer/career-ops](./aiml/santifer-career-ops.md) | ⭐ 43.8k | AI/ML |
| 2 | [exelban/stats](./misc/exelban-stats.md) | ⭐ 38.6k | Misc |
| 3 | [navidrome/navidrome](./aiml/navidrome-navidrome.md) | ⭐ 21k | AI/ML |
| 4 | [flybywiresim/aircraft](./aiml/flybywiresim-aircraft.md) | ⭐ 5.4k | AI/ML |
| 5 | [Serial-Studio/Serial-Studio](./frontend/serial-studio-serial-studio.md) | ⭐ 6.9k | Frontend |
| 6 | [apache/groovy](./misc/apache-groovy.md) | ⭐ 5.4k | Misc |
| 7 | [RustPython/RustPython](./misc/rustpython-rustpython.md) | ⭐ 22k | Misc |
| 8 | [TeamNewPipe/NewPipe](./mobile/teamnewpipe-newpipe.md) | ⭐ 38k | Mobile |
| 9 | [ai-collection/ai-collection](./aiml/ai-collection-ai-collection.md) | ⭐ 8.9k | AI/ML |
| 10 | [alibaba/spring-cloud-alibaba](./frontend/alibaba-spring-cloud-alibaba.md) | ⭐ 29.1k | Frontend |

## 🚀 How it works

```mermaid
graph LR
  A[GitHub · HN · Reddit · PH] --> B[RepoScout]
  B --> C[Score · Dedupe · Categorize]
  C --> D[LLM Summarize]
  D --> E[PostgreSQL DB]
  D --> F[This Catalog]
```

1. **Discover** — 4 sources pulled in parallel
2. **Score** — weighted: stars, forks, recency, topics, source trust
3. **Categorize** — rule-based + LLM-assisted tagging
4. **Summarize** — concise bilingual (EN/RU) summaries via LLM
5. **Sync** — markdown committed here, metadata upserted to PostgreSQL

## 🛠️ Self-host

```bash
git clone https://github.com/kirbudilov01/reposearchengine
cp .env.example .env
# Set LLM_PROVIDER, CATALOG_REPO_PATH, DATABASE_URL, ...
npm install && npm start
```

Supports local LLMs (Ollama) and cloud providers (OpenAI · Anthropic · OpenRouter).

## 📦 Data format

- [`index.json`](./index.json) — full catalog sorted by score
- `<category>/README.md` — category index with ranked table
- `<category>/<owner>-<name>.md` — per-repo card with stats, topics, summary

## 📜 License

MIT (metadata). Each linked repository retains its own license.

---

<sub>🤖 Maintained automatically by RepoScout · Built with Claude Code</sub>
