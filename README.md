# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **9059** |
| 📁 **Categories** | **22** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · OpenAI · Anthropic · Gemini · Groq · Z.AI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 3092 | [Browse →](./aiml/) |
| 📦 **Misc** | 1627 | [Browse →](./misc/) |
| 🎨 **Frontend** | 867 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 772 | [Browse →](./orchestration/) |
| 🔧 **DevTools** | 478 | [Browse →](./devtools/) |
| ⚙️ **Backend** | 415 | [Browse →](./backend/) |
| ⛓️ **Crypto** | 321 | [Browse →](./crypto/) |
| 🏷️ **Mcp** | 296 | [Browse →](./mcp/) |
| 📊 **Data** | 205 | [Browse →](./data/) |
| 🏷️ **Automation** | 191 | [Browse →](./automation/) |
| 💳 **Payments** | 146 | [Browse →](./payments/) |
| 🏷️ **Knowledgerag** | 132 | [Browse →](./knowledgerag/) |
| 📈 **Trading** | 107 | [Browse →](./trading/) |
| 📱 **Mobile** | 102 | [Browse →](./mobile/) |
| 🚀 **DevOps & Infra** | 80 | [Browse →](./devopsinfra/) |
| 🏷️ **Database** | 78 | [Browse →](./database/) |
| 🔐 **Security** | 68 | [Browse →](./security/) |
| ✨ **Design** | 30 | [Browse →](./design/) |
| 🏷️ **Observability** | 17 | [Browse →](./observability/) |
| 🎯 **Product** | 16 | [Browse →](./product/) |
| 🏷️ **Marketing** | 11 | [Browse →](./marketing/) |
| 🏷️ **Education** | 8 | [Browse →](./education/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [headroomlabs-ai/headroom](./orchestration/headroomlabs-ai-headroom.md) | ⭐ 46.8k | Orchestration |
| 2 | [diegosouzapw/OmniRoute](./mcp/diegosouzapw-omniroute.md) | ⭐ 6.7k | Mcp |
| 3 | [langgenius/dify](./orchestration/langgenius-dify.md) | ⭐ 146.2k | Orchestration |
| 4 | [OpenAPITools/openapi-generator](./backend/openapitools-openapi-generator.md) | ⭐ 26.2k | Backend |
| 5 | [strands-agents/harness-sdk](./orchestration/strands-agents-harness-sdk.md) | ⭐ 6.2k | Orchestration |
| 6 | [rocketride-org/rocketride-server](./orchestration/rocketride-org-rocketride-server.md) | ⭐ 2.4k | Orchestration |
| 7 | [yusufkaraaslan/Skill_Seekers](./mcp/yusufkaraaslan-skill-seekers.md) | ⭐ 13.5k | Mcp |
| 8 | [MCPJam/inspector](./mcp/mcpjam-inspector.md) | ⭐ 2k | Mcp |
| 9 | [usebruno/bruno](./automation/usebruno-bruno.md) | ⭐ 45.1k | Automation |
| 10 | [NangoHQ/nango](./aiml/nangohq-nango.md) | ⭐ 7.4k | AI/ML |

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
