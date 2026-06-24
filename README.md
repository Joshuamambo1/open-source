# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **10247** |
| 📁 **Categories** | **22** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · OpenAI · Anthropic · Gemini · Groq · Z.AI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 3388 | [Browse →](./aiml/) |
| 📦 **Misc** | 1757 | [Browse →](./misc/) |
| 🎨 **Frontend** | 965 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 902 | [Browse →](./orchestration/) |
| 🔧 **DevTools** | 528 | [Browse →](./devtools/) |
| ⚙️ **Backend** | 461 | [Browse →](./backend/) |
| 🏷️ **Mcp** | 439 | [Browse →](./mcp/) |
| ⛓️ **Crypto** | 370 | [Browse →](./crypto/) |
| 🏷️ **Automation** | 274 | [Browse →](./automation/) |
| 📊 **Data** | 224 | [Browse →](./data/) |
| 🏷️ **Knowledgerag** | 181 | [Browse →](./knowledgerag/) |
| 💳 **Payments** | 161 | [Browse →](./payments/) |
| 📈 **Trading** | 123 | [Browse →](./trading/) |
| 📱 **Mobile** | 112 | [Browse →](./mobile/) |
| 🏷️ **Database** | 101 | [Browse →](./database/) |
| 🚀 **DevOps & Infra** | 86 | [Browse →](./devopsinfra/) |
| 🔐 **Security** | 75 | [Browse →](./security/) |
| ✨ **Design** | 31 | [Browse →](./design/) |
| 🏷️ **Observability** | 22 | [Browse →](./observability/) |
| 🎯 **Product** | 18 | [Browse →](./product/) |
| 🏷️ **Education** | 17 | [Browse →](./education/) |
| 🏷️ **Marketing** | 12 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [headroomlabs-ai/headroom](./orchestration/headroomlabs-ai-headroom.md) | ⭐ 46.8k | Orchestration |
| 2 | [diegosouzapw/OmniRoute](./mcp/diegosouzapw-omniroute.md) | ⭐ 6.7k | Mcp |
| 3 | [langgenius/dify](./orchestration/langgenius-dify.md) | ⭐ 146.2k | Orchestration |
| 4 | [hey-api/hey-api](./payments/hey-api-hey-api.md) | ⭐ 5k | Payments |
| 5 | [OpenAPITools/openapi-generator](./backend/openapitools-openapi-generator.md) | ⭐ 26.2k | Backend |
| 6 | [assafelovic/gpt-researcher](./mcp/assafelovic-gpt-researcher.md) | ⭐ 27.9k | Mcp |
| 7 | [strands-agents/harness-sdk](./orchestration/strands-agents-harness-sdk.md) | ⭐ 6.2k | Orchestration |
| 8 | [rocketride-org/rocketride-server](./orchestration/rocketride-org-rocketride-server.md) | ⭐ 2.4k | Orchestration |
| 9 | [yusufkaraaslan/Skill_Seekers](./mcp/yusufkaraaslan-skill-seekers.md) | ⭐ 13.5k | Mcp |
| 10 | [quantumlib/Cirq](./trading/quantumlib-cirq.md) | ⭐ 5k | Trading |

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
