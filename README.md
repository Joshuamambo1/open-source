# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **160** |
| 📁 **Categories** | **15** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · OpenAI · Anthropic · Gemini · Groq · Z.AI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 53 | [Browse →](./aiml/) |
| 📦 **Misc** | 23 | [Browse →](./misc/) |
| 🎨 **Frontend** | 16 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 16 | [Browse →](./orchestration/) |
| 🏷️ **Mcp** | 15 | [Browse →](./mcp/) |
| ⚙️ **Backend** | 11 | [Browse →](./backend/) |
| 📊 **Data** | 9 | [Browse →](./data/) |
| 📱 **Mobile** | 7 | [Browse →](./mobile/) |
| 🚀 **DevOps & Infra** | 2 | [Browse →](./devopsinfra/) |
| 🔧 **DevTools** | 2 | [Browse →](./devtools/) |
| 🏷️ **Automation** | 2 | [Browse →](./automation/) |
| 🔐 **Security** | 1 | [Browse →](./security/) |
| ✨ **Design** | 1 | [Browse →](./design/) |
| ⛓️ **Crypto** | 1 | [Browse →](./crypto/) |
| 🏷️ **Knowledgerag** | 1 | [Browse →](./knowledgerag/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [n8n-io/n8n](./mcp/n8n-io-n8n.md) | ⭐ 194.9k | Mcp |
| 2 | [danny-avila/LibreChat](./orchestration/danny-avila-librechat.md) | ⭐ 40.2k | Orchestration |
| 3 | [can1357/oh-my-pi](./mcp/can1357-oh-my-pi.md) | ⭐ 15.6k | Mcp |
| 4 | [strands-agents/harness-sdk](./orchestration/strands-agents-harness-sdk.md) | ⭐ 6.4k | Orchestration |
| 5 | [microsoft/mcp-for-beginners](./orchestration/microsoft-mcp-for-beginners.md) | ⭐ 16.7k | Orchestration |
| 6 | [IBM/mcp-context-forge](./mcp/ibm-mcp-context-forge.md) | ⭐ 4k | Mcp |
| 7 | [archestra-ai/archestra](./mcp/archestra-ai-archestra.md) | ⭐ 3.9k | Mcp |
| 8 | [FlorianBruniaux/claude-code-ultimate-guide](./orchestration/florianbruniaux-claude-code-ultimate-guide.md) | ⭐ 5.3k | Orchestration |
| 9 | [ruvnet/ruflo](./orchestration/ruvnet-ruflo.md) | ⭐ 62.6k | Orchestration |
| 10 | [MemTensor/MemOS](./orchestration/memtensor-memos.md) | ⭐ 10.1k | Orchestration |

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
