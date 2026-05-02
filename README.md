# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **14166** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 5345 | [Browse →](./aiml/) |
| 📦 **Misc** | 2848 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1380 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 1062 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 867 | [Browse →](./backend/) |
| 🔧 **DevTools** | 843 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 494 | [Browse →](./crypto/) |
| 📊 **Data** | 323 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 312 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 177 | [Browse →](./mobile/) |
| 💳 **Payments** | 155 | [Browse →](./payments/) |
| 📈 **Trading** | 142 | [Browse →](./trading/) |
| 🔐 **Security** | 118 | [Browse →](./security/) |
| ✨ **Design** | 44 | [Browse →](./design/) |
| 🎯 **Product** | 29 | [Browse →](./product/) |
| 🏷️ **Marketing** | 27 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [pnpm/pnpm](./misc/pnpm-pnpm.md) | ⭐ 34.8k | Misc |
| 2 | [lutzroeder/netron](./aiml/lutzroeder-netron.md) | ⭐ 32.8k | AI/ML |
| 3 | [reflex-dev/reflex](./frontend/reflex-dev-reflex.md) | ⭐ 28.4k | Frontend |
| 4 | [DIYgod/RSSHub](./misc/diygod-rsshub.md) | ⭐ 43.8k | Misc |
| 5 | [foundry-rs/foundry](./crypto/foundry-rs-foundry.md) | ⭐ 10.3k | Crypto |
| 6 | [googleapis/mcp-toolbox](./aiml/googleapis-mcp-toolbox.md) | ⭐ 14.9k | AI/ML |
| 7 | [m1k1o/neko](./frontend/m1k1o-neko.md) | ⭐ 20.7k | Frontend |
| 8 | [glpi-project/glpi](./data/glpi-project-glpi.md) | ⭐ 5.8k | Data |
| 9 | [lsdefine/GenericAgent](./crypto/lsdefine-genericagent.md) | ⭐ 8.6k | Crypto |
| 10 | [argoproj/argo-cd](./devopsinfra/argoproj-argo-cd.md) | ⭐ 22.8k | DevOps & Infra |

## 🚀 How it works

```mermaid
graph LR
  A[GitHub · HN · Reddit · PH] --> B[RepoScout]
  B --> C[Score · Dedupe · Categorize]
  C --> D[LLM Summarize]
  D --> E[Supabase DB]
  D --> F[This Catalog]
```

1. **Discover** — 4 sources pulled in parallel
2. **Score** — weighted: stars, forks, recency, topics, source trust
3. **Categorize** — rule-based + LLM-assisted tagging
4. **Summarize** — concise bilingual (EN/RU) summaries via LLM
5. **Sync** — markdown committed here, metadata upserted to Supabase

## 🛠️ Self-host

```bash
git clone https://github.com/kirbudilov01/reposearchengine
cp .env.example .env
# Set LLM_PROVIDER, CATALOG_REPO_PATH, SUPABASE_URL, ...
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
