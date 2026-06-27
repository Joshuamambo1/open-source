# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **160** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · OpenAI · Anthropic · Gemini · Groq · Z.AI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 64 | [Browse →](./aiml/) |
| 📦 **Misc** | 23 | [Browse →](./misc/) |
| 🎨 **Frontend** | 19 | [Browse →](./frontend/) |
| 📊 **Data** | 10 | [Browse →](./data/) |
| ⚙️ **Backend** | 9 | [Browse →](./backend/) |
| 🧩 **Orchestration** | 8 | [Browse →](./orchestration/) |
| 📱 **Mobile** | 7 | [Browse →](./mobile/) |
| 🏷️ **Automation** | 7 | [Browse →](./automation/) |
| 🏷️ **Mcp** | 4 | [Browse →](./mcp/) |
| 🚀 **DevOps & Infra** | 2 | [Browse →](./devopsinfra/) |
| 🏷️ **Knowledgerag** | 2 | [Browse →](./knowledgerag/) |
| 🔐 **Security** | 1 | [Browse →](./security/) |
| 🔧 **DevTools** | 1 | [Browse →](./devtools/) |
| ✨ **Design** | 1 | [Browse →](./design/) |
| 💳 **Payments** | 1 | [Browse →](./payments/) |
| 📈 **Trading** | 1 | [Browse →](./trading/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [HKUDS/nanobot](./automation/hkuds-nanobot.md) | ⭐ 44.8k | Automation |
| 2 | [jeremylongshore/claude-code-plugins-plus-skills](./orchestration/jeremylongshore-claude-code-plugins-plus-skills.md) | ⭐ 2.4k | Orchestration |
| 3 | [activepieces/activepieces](./mcp/activepieces-activepieces.md) | ⭐ 23k | Mcp |
| 4 | [zhayujie/CowAgent](./orchestration/zhayujie-cowagent.md) | ⭐ 45.6k | Orchestration |
| 5 | [meltano/meltano](./aiml/meltano-meltano.md) | ⭐ 2.5k | AI/ML |
| 6 | [heygen-com/hyperframes](./mcp/heygen-com-hyperframes.md) | ⭐ 31.6k | Mcp |
| 7 | [micro/go-micro](./mcp/micro-go-micro.md) | ⭐ 22.8k | Mcp |
| 8 | [langgenius/dify](./aiml/langgenius-dify.md) | ⭐ 138.6k | AI/ML |
| 9 | [nocobase/nocobase](./automation/nocobase-nocobase.md) | ⭐ 23.1k | Automation |
| 10 | [stablyai/orca](./payments/stablyai-orca.md) | ⭐ 8k | Payments |

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
2. **Score** — weighted: usefulness, quality, integration, production readiness, outlook, adoption
3. **Categorize** — rule-based tagging across product domains, integrations, MCP, RAG, automation and infrastructure
4. **Summarize** — concise RU/EN/ZH summaries via LLM with deterministic fallback
5. **Sync** — markdown committed here, metadata upserted to PostgreSQL

## 🛠️ Self-host

```bash
git clone https://github.com/kirbudilov01/reposearchengine
cp .env.example .env
# Set LLM_PROVIDER, CATALOG_REPO_PATH, DATABASE_URL, ...
npm install && npm start
```

Supports cloud LLM providers (OpenAI · Anthropic · OpenRouter · Gemini · Groq · Z.AI).

## 📦 Data format

- [`index.json`](./index.json) — full catalog sorted by score
- `<category>/README.md` — category index with ranked table
- `<category>/<owner>-<name>.md` — per-repo card with stats, topics, summary

## 📜 License

MIT (metadata). Each linked repository retains its own license.

---

<sub>🤖 Maintained automatically by RepoScout · Built with Claude Code</sub>
