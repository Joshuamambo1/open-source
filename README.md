# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **2019** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 774 | [Browse →](./aiml/) |
| 📦 **Misc** | 344 | [Browse →](./misc/) |
| 🎨 **Frontend** | 202 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 192 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 103 | [Browse →](./backend/) |
| 🔧 **DevTools** | 103 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 87 | [Browse →](./crypto/) |
| 📊 **Data** | 58 | [Browse →](./data/) |
| 💳 **Payments** | 48 | [Browse →](./payments/) |
| 📈 **Trading** | 32 | [Browse →](./trading/) |
| 🚀 **DevOps & Infra** | 28 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 23 | [Browse →](./mobile/) |
| 🔐 **Security** | 13 | [Browse →](./security/) |
| 🎯 **Product** | 6 | [Browse →](./product/) |
| ✨ **Design** | 5 | [Browse →](./design/) |
| 🏷️ **Marketing** | 1 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [cvxpy/cvxpy](./misc/cvxpy-cvxpy.md) | ⭐ 6.2k | Misc |
| 2 | [invoke-ai/InvokeAI](./aiml/invoke-ai-invokeai.md) | ⭐ 27.1k | AI/ML |
| 3 | [astral-sh/ruff](./frontend/astral-sh-ruff.md) | ⭐ 47.4k | Frontend |
| 4 | [bpftrace/bpftrace](./misc/bpftrace-bpftrace.md) | ⭐ 10.1k | Misc |
| 5 | [ArduPilot/ardupilot](./misc/ardupilot-ardupilot.md) | ⭐ 15k | Misc |
| 6 | [giampaolo/psutil](./misc/giampaolo-psutil.md) | ⭐ 11.2k | Misc |
| 7 | [mudler/LocalAI](./aiml/mudler-localai.md) | ⭐ 46.1k | AI/ML |
| 8 | [trinodb/trino](./data/trinodb-trino.md) | ⭐ 12.8k | Data |
| 9 | [DioxusLabs/dioxus](./aiml/dioxuslabs-dioxus.md) | ⭐ 35.9k | AI/ML |
| 10 | [seaweedfs/seaweedfs](./aiml/seaweedfs-seaweedfs.md) | ⭐ 32.1k | AI/ML |

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
