# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **12773** |
| 📁 **Categories** | **22** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · OpenAI · Anthropic · Gemini · Groq · Z.AI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 4029 | [Browse →](./aiml/) |
| 📦 **Misc** | 2248 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1198 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 1083 | [Browse →](./orchestration/) |
| 🔧 **DevTools** | 647 | [Browse →](./devtools/) |
| 🏷️ **Mcp** | 640 | [Browse →](./mcp/) |
| ⚙️ **Backend** | 570 | [Browse →](./backend/) |
| ⛓️ **Crypto** | 441 | [Browse →](./crypto/) |
| 🏷️ **Automation** | 403 | [Browse →](./automation/) |
| 📊 **Data** | 273 | [Browse →](./data/) |
| 🏷️ **Knowledgerag** | 262 | [Browse →](./knowledgerag/) |
| 💳 **Payments** | 189 | [Browse →](./payments/) |
| 🏷️ **Database** | 172 | [Browse →](./database/) |
| 📱 **Mobile** | 151 | [Browse →](./mobile/) |
| 📈 **Trading** | 145 | [Browse →](./trading/) |
| 🚀 **DevOps & Infra** | 96 | [Browse →](./devopsinfra/) |
| 🔐 **Security** | 89 | [Browse →](./security/) |
| 🏷️ **Observability** | 37 | [Browse →](./observability/) |
| ✨ **Design** | 36 | [Browse →](./design/) |
| 🏷️ **Education** | 29 | [Browse →](./education/) |
| 🎯 **Product** | 21 | [Browse →](./product/) |
| 🏷️ **Marketing** | 14 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [headroomlabs-ai/headroom](./orchestration/headroomlabs-ai-headroom.md) | ⭐ 46.8k | Orchestration |
| 2 | [xberg-io/xberg](./mcp/xberg-io-xberg.md) | ⭐ 8.5k | Mcp |
| 3 | [xberg-io/kreuzberg](./mcp/xberg-io-kreuzberg.md) | ⭐ 8.5k | Mcp |
| 4 | [diegosouzapw/OmniRoute](./mcp/diegosouzapw-omniroute.md) | ⭐ 6.7k | Mcp |
| 5 | [langgenius/dify](./orchestration/langgenius-dify.md) | ⭐ 146.2k | Orchestration |
| 6 | [hey-api/hey-api](./payments/hey-api-hey-api.md) | ⭐ 5k | Payments |
| 7 | [OpenAPITools/openapi-generator](./backend/openapitools-openapi-generator.md) | ⭐ 26.2k | Backend |
| 8 | [google-antigravity/antigravity-sdk-python](./mcp/google-antigravity-antigravity-sdk-python.md) | ⭐ 2k | Mcp |
| 9 | [assafelovic/gpt-researcher](./mcp/assafelovic-gpt-researcher.md) | ⭐ 27.9k | Mcp |
| 10 | [strands-agents/harness-sdk](./orchestration/strands-agents-harness-sdk.md) | ⭐ 6.2k | Orchestration |

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
