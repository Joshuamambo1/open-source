# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **8815** |
| 📁 **Categories** | **22** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · OpenAI · Anthropic · Gemini · Groq · Z.AI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 3041 | [Browse →](./aiml/) |
| 📦 **Misc** | 1615 | [Browse →](./misc/) |
| 🎨 **Frontend** | 850 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 729 | [Browse →](./orchestration/) |
| 🔧 **DevTools** | 468 | [Browse →](./devtools/) |
| ⚙️ **Backend** | 410 | [Browse →](./backend/) |
| ⛓️ **Crypto** | 304 | [Browse →](./crypto/) |
| 🏷️ **Mcp** | 262 | [Browse →](./mcp/) |
| 📊 **Data** | 201 | [Browse →](./data/) |
| 🏷️ **Automation** | 178 | [Browse →](./automation/) |
| 💳 **Payments** | 139 | [Browse →](./payments/) |
| 🏷️ **Knowledgerag** | 116 | [Browse →](./knowledgerag/) |
| 📱 **Mobile** | 100 | [Browse →](./mobile/) |
| 📈 **Trading** | 98 | [Browse →](./trading/) |
| 🚀 **DevOps & Infra** | 80 | [Browse →](./devopsinfra/) |
| 🏷️ **Database** | 76 | [Browse →](./database/) |
| 🔐 **Security** | 68 | [Browse →](./security/) |
| ✨ **Design** | 30 | [Browse →](./design/) |
| 🎯 **Product** | 16 | [Browse →](./product/) |
| 🏷️ **Observability** | 16 | [Browse →](./observability/) |
| 🏷️ **Marketing** | 11 | [Browse →](./marketing/) |
| 🏷️ **Education** | 7 | [Browse →](./education/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [OpenAPITools/openapi-generator](./backend/openapitools-openapi-generator.md) | ⭐ 26.2k | Backend |
| 2 | [rocketride-org/rocketride-server](./orchestration/rocketride-org-rocketride-server.md) | ⭐ 2.4k | Orchestration |
| 3 | [yusufkaraaslan/Skill_Seekers](./mcp/yusufkaraaslan-skill-seekers.md) | ⭐ 13.5k | Mcp |
| 4 | [NangoHQ/nango](./aiml/nangohq-nango.md) | ⭐ 7.4k | AI/ML |
| 5 | [kubeshark/kubeshark](./mcp/kubeshark-kubeshark.md) | ⭐ 11.9k | Mcp |
| 6 | [GAM-team/GAM](./frontend/gam-team-gam.md) | ⭐ 4.2k | Frontend |
| 7 | [vstorm-co/full-stack-ai-agent-template](./orchestration/vstorm-co-full-stack-ai-agent-template.md) | ⭐ 1.2k | Orchestration |
| 8 | [google-gemini/gemini-cli](./aiml/google-gemini-gemini-cli.md) | ⭐ 103.3k | AI/ML |
| 9 | [ansible/awx](./automation/ansible-awx.md) | ⭐ 15.4k | Automation |
| 10 | [webiny/webiny-js](./mcp/webiny-webiny-js.md) | ⭐ 8k | Mcp |

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
