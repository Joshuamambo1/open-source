# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **6832** |
| 📁 **Categories** | **22** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 2550 | [Browse →](./aiml/) |
| 📦 **Misc** | 1246 | [Browse →](./misc/) |
| 🎨 **Frontend** | 679 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 592 | [Browse →](./orchestration/) |
| 🔧 **DevTools** | 362 | [Browse →](./devtools/) |
| ⚙️ **Backend** | 340 | [Browse →](./backend/) |
| ⛓️ **Crypto** | 235 | [Browse →](./crypto/) |
| 📊 **Data** | 162 | [Browse →](./data/) |
| 💳 **Payments** | 108 | [Browse →](./payments/) |
| 📈 **Trading** | 84 | [Browse →](./trading/) |
| 📱 **Mobile** | 81 | [Browse →](./mobile/) |
| 🏷️ **Mcp** | 78 | [Browse →](./mcp/) |
| 🚀 **DevOps & Infra** | 70 | [Browse →](./devopsinfra/) |
| 🏷️ **Automation** | 63 | [Browse →](./automation/) |
| 🏷️ **Knowledgerag** | 55 | [Browse →](./knowledgerag/) |
| 🔐 **Security** | 48 | [Browse →](./security/) |
| 🏷️ **Database** | 24 | [Browse →](./database/) |
| ✨ **Design** | 21 | [Browse →](./design/) |
| 🎯 **Product** | 14 | [Browse →](./product/) |
| 🏷️ **Marketing** | 9 | [Browse →](./marketing/) |
| 🏷️ **Observability** | 8 | [Browse →](./observability/) |
| 🏷️ **Education** | 3 | [Browse →](./education/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [ohmyzsh/ohmyzsh](./aiml/ohmyzsh-ohmyzsh.md) | ⭐ 186.9k | AI/ML |
| 2 | [google-gemini/gemini-cli](./aiml/google-gemini-gemini-cli.md) | ⭐ 103.3k | AI/ML |
| 3 | [n8n-io/n8n](./aiml/n8n-io-n8n.md) | ⭐ 186.9k | AI/ML |
| 4 | [mcp-use/mcp-use](./aiml/mcp-use-mcp-use.md) | ⭐ 9.9k | AI/ML |
| 5 | [PipedreamHQ/pipedream](./backend/pipedreamhq-pipedream.md) | ⭐ 11.3k | Backend |
| 6 | [teng-lin/notebooklm-py](./aiml/teng-lin-notebooklm-py.md) | ⭐ 12.9k | AI/ML |
| 7 | [subzeroid/instagrapi](./backend/subzeroid-instagrapi.md) | ⭐ 6.2k | Backend |
| 8 | [Klavis-AI/klavis](./aiml/klavis-ai-klavis.md) | ⭐ 5.7k | AI/ML |
| 9 | [davepoon/buildwithclaude](./aiml/davepoon-buildwithclaude.md) | ⭐ 2.9k | AI/ML |
| 10 | [open-webui/open-webui](./aiml/open-webui-open-webui.md) | ⭐ 136.1k | AI/ML |

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

Supports local LLMs (Ollama) and cloud providers (OpenAI · Anthropic · OpenRouter).

## 📦 Data format

- [`index.json`](./index.json) — full catalog sorted by score
- `<category>/README.md` — category index with ranked table
- `<category>/<owner>-<name>.md` — per-repo card with stats, topics, summary

## 📜 License

MIT (metadata). Each linked repository retains its own license.

---

<sub>🤖 Maintained automatically by RepoScout · Built with Claude Code</sub>
