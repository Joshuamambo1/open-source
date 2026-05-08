# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **2379** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 920 | [Browse →](./aiml/) |
| 📦 **Misc** | 392 | [Browse →](./misc/) |
| 🎨 **Frontend** | 238 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 225 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 123 | [Browse →](./backend/) |
| 🔧 **DevTools** | 120 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 100 | [Browse →](./crypto/) |
| 📊 **Data** | 64 | [Browse →](./data/) |
| 💳 **Payments** | 60 | [Browse →](./payments/) |
| 📈 **Trading** | 40 | [Browse →](./trading/) |
| 🚀 **DevOps & Infra** | 36 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 27 | [Browse →](./mobile/) |
| 🔐 **Security** | 18 | [Browse →](./security/) |
| 🎯 **Product** | 8 | [Browse →](./product/) |
| ✨ **Design** | 6 | [Browse →](./design/) |
| 🏷️ **Marketing** | 2 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [ludwig-ai/ludwig](./aiml/ludwig-ai-ludwig.md) | ⭐ 11.7k | AI/ML |
| 2 | [karatelabs/karate](./backend/karatelabs-karate.md) | ⭐ 8.9k | Backend |
| 3 | [documenso/documenso](./security/documenso-documenso.md) | ⭐ 12.8k | Security |
| 4 | [f/prompts.chat](./aiml/f-prompts.chat.md) | ⭐ 161.8k | AI/ML |
| 5 | [modelscope/ms-swift](./aiml/modelscope-ms-swift.md) | ⭐ 14k | AI/ML |
| 6 | [micro-editor/micro](./frontend/micro-editor-micro.md) | ⭐ 28.6k | Frontend |
| 7 | [1Panel-dev/MaxKB](./orchestration/1panel-dev-maxkb.md) | ⭐ 20.9k | Orchestration |
| 8 | [zhayujie/CowAgent](./orchestration/zhayujie-cowagent.md) | ⭐ 44.2k | Orchestration |
| 9 | [HKUDS/Vibe-Trading](./trading/hkuds-vibe-trading.md) | ⭐ 5.6k | Trading |
| 10 | [apache/datafusion](./data/apache-datafusion.md) | ⭐ 8.7k | Data |

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
