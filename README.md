# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **10662** |
| 📁 **Categories** | **22** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · OpenAI · Anthropic · Gemini · Groq · Z.AI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 3499 | [Browse →](./aiml/) |
| 📦 **Misc** | 1821 | [Browse →](./misc/) |
| 🎨 **Frontend** | 992 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 940 | [Browse →](./orchestration/) |
| 🔧 **DevTools** | 551 | [Browse →](./devtools/) |
| ⚙️ **Backend** | 478 | [Browse →](./backend/) |
| 🏷️ **Mcp** | 478 | [Browse →](./mcp/) |
| ⛓️ **Crypto** | 384 | [Browse →](./crypto/) |
| 🏷️ **Automation** | 301 | [Browse →](./automation/) |
| 📊 **Data** | 234 | [Browse →](./data/) |
| 🏷️ **Knowledgerag** | 193 | [Browse →](./knowledgerag/) |
| 💳 **Payments** | 164 | [Browse →](./payments/) |
| 📈 **Trading** | 126 | [Browse →](./trading/) |
| 📱 **Mobile** | 116 | [Browse →](./mobile/) |
| 🏷️ **Database** | 114 | [Browse →](./database/) |
| 🚀 **DevOps & Infra** | 90 | [Browse →](./devopsinfra/) |
| 🔐 **Security** | 76 | [Browse →](./security/) |
| ✨ **Design** | 32 | [Browse →](./design/) |
| 🏷️ **Observability** | 23 | [Browse →](./observability/) |
| 🎯 **Product** | 19 | [Browse →](./product/) |
| 🏷️ **Education** | 19 | [Browse →](./education/) |
| 🏷️ **Marketing** | 12 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [headroomlabs-ai/headroom](./orchestration/headroomlabs-ai-headroom.md) | ⭐ 46.8k | Orchestration |
| 2 | [xberg-io/kreuzberg](./mcp/xberg-io-kreuzberg.md) | ⭐ 8.5k | Mcp |
| 3 | [diegosouzapw/OmniRoute](./mcp/diegosouzapw-omniroute.md) | ⭐ 6.7k | Mcp |
| 4 | [langgenius/dify](./orchestration/langgenius-dify.md) | ⭐ 146.2k | Orchestration |
| 5 | [hey-api/hey-api](./payments/hey-api-hey-api.md) | ⭐ 5k | Payments |
| 6 | [OpenAPITools/openapi-generator](./backend/openapitools-openapi-generator.md) | ⭐ 26.2k | Backend |
| 7 | [assafelovic/gpt-researcher](./mcp/assafelovic-gpt-researcher.md) | ⭐ 27.9k | Mcp |
| 8 | [strands-agents/harness-sdk](./orchestration/strands-agents-harness-sdk.md) | ⭐ 6.2k | Orchestration |
| 9 | [rocketride-org/rocketride-server](./orchestration/rocketride-org-rocketride-server.md) | ⭐ 2.4k | Orchestration |
| 10 | [yusufkaraaslan/Skill_Seekers](./mcp/yusufkaraaslan-skill-seekers.md) | ⭐ 13.5k | Mcp |

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
